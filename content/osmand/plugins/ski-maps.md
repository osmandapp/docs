---
title: Ski-maps
intro: "Full map of ski pistes, ski lift markers and even colored lines indicating the complexity of each track."
versions: '*'
---


{% data reusables.general.article-not-complete %}


OsmAnd Ski Maps is a plugin allowing you to navigate at winter sports locations. It provides you with a full map of ski pistes, ski lift markers and even colored lines indicating the complexity of each track.

This plugin for OsmAnd puts at your fingertips details of global downhill ski slopes, cross country ski runs, Alpine ski routes, cable cars and ski lifts. Routes and pistes are shown color-coded by difficulty, and depicted in a special 'Winter' map style which assimilates a snow-colored winter landscape.

Activating this view changes [the map style to 'Winter and ski'](/osmand/map/vector-maps#winter-and-ski), showing all landscape features under wintry conditions. This view can be reverted by either de-activating it again here, or by changing the ['Map style'](/osmand/map/vector-maps#default-map-styles) under ['Configure map'](/osmand/map/configure-map-menu) as desired.


## Enable / Disable plugin

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.plugins_menu_group: %} → {% data variables.android-values.plugin_ski_name %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.plugins %} → {% data variables.ios-values.product_title_skimap %}

![Ski maps plugin Android](/assets/images/plugins/ski-maps/plugin_ski_maps_android.png) ![Ski maps plugin iOS](/assets/images/plugins/ski-maps/plugin_ski_maps_ios.png)

## Ski maps

Data from [OpenStreetMap project](http://openstreetmap.org/).

OsmAnd [Rendering.xml](https://github.com/osmandapp/OsmAnd-resources/blob/master/rendering_styles/skimap.render.xml) file.

[Rendering documentation](/development/osmand-file-formats/osmand-rendering-style) for Winter and ski map.

First, you need to go to Plugins menu - Ski map view and select Enable.  Then use the 'Configure map - Map style' menu to switch the winter and ski style on. After that, you can find your desired area on the map and enjoy the info about the ski tracks including their complexity, location and infrastructure around.

For switch on [Winter and ski map style](/osmand/map/vector-maps#winter-and-ski).

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_map %} → {% data variables.android-values.map_widget_map_rendering %} → {% data variables.android-values.map_widget_renderer %} → {% data variables.android-values.winter_and_ski_renderer %} 

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.configure_map %} → {% data variables.ios-values.map_settings_offline %} → {% data variables.android-values.winter_and_ski_renderer %}

![Ski maps plugin map style Android](/assets/images/plugins/ski-maps/plugin_ski_maps_style_android.png) ![Ski maps plugin map style iOS](/assets/images/plugins/ski-maps/plugin_ski_maps_style_ios.png)


For [Winter and ski map style](/osmand/map/vector-maps#winter-and-ski) user can switch on [Ski slopes](/osmand/map/vector-maps#routes) routes.

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_map %} → {% data variables.android-values.rendering_attr_pisteRoutes_name %} 

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.configure_map %} → {% data variables.ios-values.rendering_category_routes %} → {% data variables.ios-values.rendering_attr_pisteRoutes_name %}

![Map routes - ski slopes](/assets/images/map/map-routes-ski-slopes.png)

### Map legend

of Ski map you can find  [_here_](https://osmand.net/help-online/map-legend#nautical).

## Ski navigation

You need [to enable Ski-maps plugin](/osmand/plugins/ski-maps#enable--disable-plugin) and to choose Ski profile for routing by ski slopes.

[Navigation link](/osmand/navigation/route-navigation)




