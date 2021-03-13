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
| **Text** section | Defined as a block [`<text>`](https://github.com/osmandapp/OsmAnd-resources/blob/master/rendering_styles/default.render.xml#L3811). Each displayed map object is searched whether it should display the text and how it should be displayed. <br><br> **Search parameters** (input): `tag`, `value`, `zoom`, `nameTag` (each text tag is checked), . <br><br> **Search result** (output): `textOnPath`, `textMinDistance`, `textSize`, `textColor`, `textHaloRadius`, `textOrder`, `textDy`, `textBold`, `nameTag2`, `textShield`, `icon`, `textItalic`, `textWrapWidth`, `intersectionMargin`. |
| **Point** section | Defined as a block [`<point>`](https://github.com/osmandapp/OsmAnd-resources/blob/master/rendering_styles/default.render.xml#6467). Each displayed point map object (defined in `order`-section) is searched in this section to determine how it should be displayed. <br><br> **Search parameters** (input): `tag`, `value`, `zoom`, `nameTag` (each text tag is checked), . <br><br> **Search result** (output): `textOnPath`, `textMinDistance`, `textSize`, `textColor`, `textHaloRadius`, `textOrder`, `textDy`, `textBold`, `nameTag2`, `textShield`, `icon`, `textItalic`, `textWrapWidth`, `intersectionMargin`. |
| **Polygon** section | Defined as a block [`<polygon>`](https://github.com/osmandapp/OsmAnd-resources/blob/master/rendering_styles/default.render.xml#8580). Each displayed polygon map object (defined in `order`-section) is searched in this section to determine how it should be displayed. <br><br> **Search parameters** (input): `tag`, `value`, `zoom`, `nameTag` (each text tag is checked), . <br><br> **Search result** (output): `textOnPath`, `textMinDistance`, `textSize`, `textColor`, `textHaloRadius`, `textOrder`, `textDy`, `textBold`, `nameTag2`, `textShield`, `icon`, `textItalic`, `textWrapWidth`, `intersectionMargin`. |
| **Line** section | Defined as a block [`<line>`](https://github.com/osmandapp/OsmAnd-resources/blob/master/rendering_styles/default.render.xml#9535). Each displayed line map object (defined in `order`-section) is searched whether in this section to determine how it should be displayed. <br><br> **Search parameters** (input): `tag`, `value`, `zoom`, `nameTag` (each text tag is checked), . <br><br> **Search result** (output): `textOnPath`, `textMinDistance`, `textSize`, `textColor`, `textHaloRadius`, `textOrder`, `textDy`, `textBold`, `nameTag2`, `textShield`, `icon`, `textItalic`, `textWrapWidth`, `intersectionMargin`. |

## Map feature selectors
- `additional`
- Map Style Parameters
- Search Parameters

## Attributes & Constants

## Map Style Parameters

## Special attributes (altitude / graph)
