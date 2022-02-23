---
title: "{% data variables.android-values.plugin_ski_name %}"
intro: "Ski map view shows winter colors and pistes - ski paths down a mountain or cross-country - as well as cableways, chairlifts, amenities and services nearby, which are useful in navigating through the destinations like recreational areas, ski resorts, and terrain parks."
versions: '*'
---


{% data reusables.general.article-not-complete %}


## Overview

To illustrate skiing location and amenities, most resorts and parks provide their piste map/trail map. OsmAnd Ski Map shows officially approved ski areas and piste maps of most ski resorts on the northern and southern hemispheres, in Europe, Scandinavia, central Asia, Japan, North America, and other. 

The [Piste Maps](https://wiki.openstreetmap.org/wiki/Piste_Maps) of [OpenStreetMap](https://www.openstreetmap.org/#map=16/51.5110/0.0550) is the source of data for Osm Ski Map. Combined with the default vector maps, the Ski Map of OsmAnd preserves its accuracy and benefits from a variety of contributors, like: ski resorts, lift operators, instructors, eager mountaineers, winter sports enthusiasts, etc.

The Ski map view is delivered as part of the default vector maps, and does not require any extra downloading. However, it is disabled by default. The plugin allows you quickly and easily to enable the Ski map view and use it. The Ski map view is one of the OsmAnd [Map Styles](/osmand/map/vector-maps) that provide extra capabilities by highlighting some objects, while making other less viable. 

With the profiles configured individually, it is possible to configure and prepare one specifically for skiing by highlighting an assorted amount of winter and ski related information on the map. 

&nbsp;&nbsp;&nbsp;&nbsp;

## Setup

### Enable plugin

{% data reusables.general.android-ios-switcher %}

{% default %}

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.plugins_menu_group: %} → {% data variables.android-values.plugin_ski_name %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.plugins %} → {% data variables.ios-values.product_title_skimap %}

![Ski maps plugin Android](/assets/images/plugins/ski-maps/plugin_ski_maps_android.png) ![Ski maps plugin iOS](/assets/images/plugins/ski-maps/plugin_ski_maps_ios.png)

{% enddefault %}

{% ios%}

![Ski maps plugin iOS](/assets/images/plugins/ski-maps/plugin_ski_maps_ios.png)

{% endios%}

{% android%}

![Ski maps plugin Android](/assets/images/plugins/ski-maps/plugin_ski_maps_android.png)

{% endandroid%}


&nbsp;&nbsp;&nbsp;&nbsp;

### Set Winter and Ski map style

{% data reusables.general.android-ios-switcher %}

{% default %}

First, you need to go to Plugins menu - Ski map view and select Enable.  Then use the 'Configure map - Map style' menu to switch the winter and ski style on. After that, you can find your desired area on the map and enjoy the info about the ski tracks including their complexity, location and infrastructure around.

For switch on [Winter and ski map style](/osmand/map/vector-maps#winter-and-ski).

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_map %} → {% data variables.android-values.map_widget_map_rendering %} → {% data variables.android-values.map_widget_renderer %} → {% data variables.android-values.winter_and_ski_renderer %} 

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.configure_map %} → {% data variables.ios-values.map_settings_offline %} → {% data variables.android-values.winter_and_ski_renderer %}

![Ski maps plugin map style Android](/assets/images/plugins/ski-maps/plugin_ski_maps_style_android.png) ![Ski maps plugin map style iOS](/assets/images/plugins/ski-maps/plugin_ski_maps_style_ios.png)

{% enddefault %}

{% ios%}

![Ski maps plugin map style iOS](/assets/images/plugins/ski-maps/plugin_ski_maps_style_ios.png)

{% endios%}

{% android%}

![Ski maps plugin map style Android](/assets/images/plugins/ski-maps/plugin_ski_maps_style_android.png)

{% endandroid%}



&nbsp;&nbsp;&nbsp;&nbsp;

### Combine with contours and/or hillshade



&nbsp;&nbsp;&nbsp;&nbsp;

## Ski map options


&nbsp;&nbsp;&nbsp;&nbsp;

### Piste type and complexity



&nbsp;&nbsp;&nbsp;&nbsp;

### Piste grooming



&nbsp;&nbsp;&nbsp;&nbsp;

### Ski slope routes

For [Winter and ski map style](/osmand/map/vector-maps#winter-and-ski) user can switch on [Ski slopes](/osmand/map/vector-maps#routes) routes.

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_map %} → {% data variables.android-values.rendering_category_routes %} → {% data variables.android-values.rendering_attr_pisteRoutes_name %} 

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.configure_map %} → {% data variables.ios-values.map_settings_style %} → {% data variables.ios-values.rendering_category_routes %} → {% data variables.ios-values.rendering_attr_pisteRoutes_name %}

![Map routes - ski slopes](/assets/images/map/map-routes-ski-slopes.png)


&nbsp;&nbsp;&nbsp;&nbsp;

### Night skiing 



&nbsp;&nbsp;&nbsp;&nbsp;

### Street lightening 


&nbsp;&nbsp;&nbsp;&nbsp;

### Map legend

Map legend of Ski map you can find  [here](https://osmand.net/help-online/map-legend#nautical).



&nbsp;&nbsp;&nbsp;&nbsp;

### Remove Ski





&nbsp;&nbsp;&nbsp;&nbsp;

## Ski navigation

You need [to enable Ski-maps plugin](/osmand/plugins/ski-maps#enable--disable-plugin) and to choose Ski profile for routing by ski slopes.

[Navigation link](/osmand/navigation/route-navigation)




&nbsp;&nbsp;&nbsp;&nbsp;

## Ski Map data details

OsmAnd [Rendering.xml](https://github.com/osmandapp/OsmAnd-resources/blob/master/rendering_styles/skimap.render.xml) file.

[Rendering documentation](/development/osmand-file-formats/osmand-rendering-style) for Winter and ski map.

