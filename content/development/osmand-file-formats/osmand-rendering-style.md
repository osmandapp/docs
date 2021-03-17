---
title: Map Rendering style - .render.xml
intro: 'OsmAnd rendering style is a special XML file that describes how vector map features should be displayed on the map. It is typically quite large by lines of code and highly customizable.'
versions: '*'
---

In case you want to modify a default rendering style, take a look at [Github definition](https://github.com/osmandapp/OsmAnd-resources/blob/master/rendering_styles/default.render.xml). [Here](https://github.com/osmandapp/OsmAnd-resources/tree/master/rendering_styles) you can also find all different styles, so in case you want to create your own style, you can find the easiest example.

In case you consider creating your own rendering style, you might need to create [your own maps](/development/map-creation/create-offline-maps-yourself#custom-vector-map-tags) to add custom features display.

## Map style sections 

Map style file consists of several sections.

| Section | Description |
|---------|-------------|
| **Header** | Consists of `name` (style name), `defaultColor` (default map color could be overridden by attribute defaultColor) and `depends` (inherits all properties from parent style). |
| **Parameters** | Defined as `<renderingProperty>` has `attr` which will be used in the style as a parameter name and `name`, `description` will be displayed to user. |
| **Attributes** and **constants** | Defined as `<renderingAttribute>` and as `<renderingConstant>` allows to reuse same blocks of rendering styles for different map objects | 
| **Order** section | Defined as a block [`<order>`](https://github.com/osmandapp/OsmAnd-resources/blob/master/rendering_styles/default.render.xml#L2876). Each map object is searched in the order-section to get whether it will be rendered as point, line or polygon (`objectType`) and in which `order` should be displayed. <br><br> **Search parameters** (input): `tag`, `value`, `zoom`, `point` (true or false), `area` (osm type), `cycle` (start and end point are same). <br><br> **Search result** (output): `objectType` (point = 1, line = 2, polygon = 3), `order` (0-255). Order of rendering is defined as: polygons, line-shadows, lines, points. If `order` is the same for polygons, then polygons are displayed from the largest polygon to the smallest. Note: polygons shouldn't overlap partially otherwise behavior is not defined. |
| **Text** section | Defined as a block [`<text>`](https://github.com/osmandapp/OsmAnd-resources/blob/master/rendering_styles/default.render.xml#L3811). Each displayed map object is searched whether it should display the text and how it should be displayed. <br><br> **Search parameters** (input): `tag`, `value`, `zoom`, `nameTag` (each text tag is checked). <br><br> **Search result** (output): `textOnPath`, `textMinDistance` (margin between same texts i.e. road names, refs ), `textSize`, `textColor`, `textHaloRadius`, `textOrder`, `textDy`, `textBold`, `nameTag2` (extra name in the braces if present), `textShield` (background arond text), `icon` (icon instead of text), `textItalic`, `textWrapWidth`, `intersectionMargin` (extra margin to not overlap text). |
| **Point** section | Defined as a block [`<point>`](https://github.com/osmandapp/OsmAnd-resources/blob/master/rendering_styles/default.render.xml#6467). Each displayed point map object (defined in `order`-section) is searched in this section to determine how it should be displayed. <br><br> **Search parameters** (input): `tag`, `value`, `zoom`, `e`. <br><br> **Search result** (output): `shield` (icon shield), `icon`, `iconVisibleSize` (extra space to not clutter icons), `iconOrder`, `intersectionSizeFactor`. |
| **Polygon** section | Defined as a block [`<polygon>`](https://github.com/osmandapp/OsmAnd-resources/blob/master/rendering_styles/default.render.xml#8580). Each displayed polygon map object (defined in `order`-section) is searched in this section to determine how it should be displayed. <br><br> **Search parameters** (input): `tag`, `value`, `zoom` . <br><br> **Search result** (output): `color` (color to fill the polygon), `shader` (fill polygon with same icon), `color_2, color_N` (color of stroke around polygon), `strokeWidth_2` (stroke width), `pathEffect_2`, `cap_2`. |
| **Line** section | Defined as a block [`<line>`](https://github.com/osmandapp/OsmAnd-resources/blob/master/rendering_styles/default.render.xml#9535). Each displayed line map object (defined in `order`-section) is searched whether in this section to determine how it should be displayed. 1 line object could be rendered as multiple combined lines up to -2 layers below and up to 7 layers on top. <br><br> **Search parameters** (input): `tag`, `value`, `zoom`, `nameTag` (each text tag is checked), . <br><br> **Search result** (output): `color, color_*` (color of stroke around polygon), `strokeWidth, strokeWidth_*` (stroke width), `pathEffect, pathEffect_*` (path effect), `cap, cap_*` (BUTT, ROUND, SQUARE), `pathIcon`, `pathIconStep`, `shadowRadius` (shadow around line). |

## Map feature selectors

To determine which attributes should be retrieved from rendering style, following search procedure is completed:
- Find the most inner `<case>` that corresponds to Search input parameters `tag/value/zoom` i.e. for `highway=primary` - `<case tag="highway" value="primary">` will be found.
- All internals of `<case>` are applied sequentially deep and output parameters are collected
    - `<case><apply output="1"/><apply_if zoom="15" output="2"> <case>` - output will be 2 in case `zoom=15` and output will be 1 otherwise.    
- Checked if `<case>` is part of any `<switch>` and if it is then all `apply` and `apply_if` of that switch will be evaluated as well

Evaluation rules:
- In each  `case`, `apply_if`, `switch`, `apply` input attributes are checked to match (evalute to true), otherwise section is skipped and output attributes are not collected.
- All rules evaluated sequentially and output parameters could be overridden by folowing rules
- `additional=?` is a special input attribute that checks additional tags of the object
- Map style parameters are input search parameters as well next to `tag/value/zoom`
    - Example: `<apply_if nightMode="false" streetLightingNight="false" shield="street_lamp_lit_no_shield"/>`. Input parameters: nightMode, streetLightingNight; output parameters - shield.


## Attributes & Constants

## Map Style Parameters

## Special attributes (altitude / graph)
