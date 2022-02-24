---
title: "{% data variables.android-values.plugin_ski_name %}"
intro: "Ski map view shows winter colors and pistes - ski paths down a mountain or cross-country - as well as cableways, chairlifts, amenities and services nearby, which are useful in navigating through the destinations like recreational areas, ski resorts, and terrain parks."
versions: '*'
---


{% data reusables.general.article-not-complete %}


## Overview

To illustrate skiing location and amenities, most resorts and parks provide their piste map/trail map. OsmAnd Ski Map shows known/popular ski touring trails, officially approved ski areas and piste maps of most ski resorts on the northern and southern hemispheres, in Europe, Scandinavia, central Asia, Japan, North America, and other. 

The [Piste Maps](https://wiki.openstreetmap.org/wiki/Piste_Maps) of [OpenStreetMap](https://www.openstreetmap.org/#map=16/51.5110/0.0550) is the source of data for OsmAnd Ski Map. Combined with the default vector maps, the Ski Map of OsmAnd preserves its accuracy and benefits from a variety of contributors, like: ski resorts, lift operators, instructors, eager mountaineers, winter sports enthusiasts, etc.

OsmAnd Ski Map is delivered as part of the default vector maps, and does not require any extra downloading. However, it is disabled by default. The plugin allows you quickly to enable OsmAnd Ski Map and start to use it. OsmAnd Ski Map is one of the [Map Styles](/osmand/map/vector-maps) that provide extra capabilities by highlighting some objects, while making other less viable. 

With the profiles configured individually, it is possible to prepare a Skiing profile specifically for skiing. It will highlight an assorted amount of winter and ski related information on the map. Below are two profiles: the left-hand one is for skiing, the other one is for driving. And the profile for skiing highlights pistes, aerial ways, winter colors, etc. - the map objects useful when navigating through the ski area.

{% data reusables.general.android-ios-switcher %}

{% default %}

![Ski maps in iOS](/assets/images/plugins/ski-maps/ios_yes_ski.png) ![No Ski maps in iOS](/assets/images/plugins/ski-maps/ios_no_ski.png)

{% enddefault %}

{% ios%}

![Ski maps in iOS](/assets/images/plugins/ski-maps/ios_yes_ski.png) ![No Ski maps in iOS](/assets/images/plugins/ski-maps/ios_no_ski.png)

{% endios%}

{% android%}

![Ski maps in Android](/assets/images/plugins/ski-maps/and_yes_ski.png) ![No Ski maps in Android](/assets/images/plugins/ski-maps/and_no_ski.png)

{% endandroid%}





&nbsp;&nbsp;&nbsp;&nbsp;

## Setup

The following setup makes OsmAnd Ski Map show up on the screen:

1. Enable the plugin.

2. Set the Winter and Ski map style.

3. If needed, combine maps. 


### Enable plugin

{% data reusables.general.android-ios-switcher %}

{% default %}

Enabling the Ski map plugin is a quick way to setup OsmAnd Ski Map. The plugin can add the default profile for skiing. If it has not been used yet, the default Skiing profile has the Ski navigation and the [Winter and ski map style](/osmand/map/vector-maps#winter-and-ski) already established for it. Otherwise, the profile would remember the settings of the latest use. 

To enable the Ski Map plugin, do the following:

1. Open the list of plugins in the menu.

2. Find the Ski map plugin, and tap it. 

3. If needed, leave the Ski profile option toggled-on in the opened popup window, so that together with the plugin to enable the Skiing profile. 

![Ski maps plugin Android](/assets/images/plugins/ski-maps/plugin_ski_maps_android.png) ![Ski maps plugin iOS](/assets/images/plugins/ski-maps/plugin_ski_maps_ios.png)

{% enddefault %}

{% ios%}

The **{% data variables.ios-values.product_title_skimap %}** plugin can  be enabled together with the **{% data variables.ios-values.app_mode_skiing %}** profile, which on the first use, has the Ski navigation and the [Winter and ski map style](/osmand/map/vector-maps#winter-and-ski) established for it. 

To enable the **{% data variables.ios-values.product_title_skimap %}** plugin, tap it in the list of plugins opened, as follows: 

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.plugins %} → {% data variables.ios-values.product_title_skimap %}

![Ski maps plugin iOS](/assets/images/plugins/ski-maps/plugin_ski_maps_ios.png)

If the **{% data variables.ios-values.app_mode_skiing %}** profile is needed, leave the respective option toggled on in the opened popup window and tap **OK**. Otherwise, tap Turn off, and the plugin will be enabled without adding the profile. 

![Enabling Ski profile with plugin in iOS](/assets/images/plugins/ski-maps/ios_profile_in_ski_plugin.png)

{% endios%}

{% android%}

The **{% data variables.android-values.plugin_ski_name %}** plugin can  be enabled together with the **{% data variables.android-values.app_mode_skiing %}** profile, which on the first use, has the Ski navigation and the [Winter and ski map style](/osmand/map/vector-maps#winter-and-ski) established for it. 

To enable the **{% data variables.android-values.plugin_ski_name %}** plugin, tap it in the list of plugins opened, as follows:

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.plugins_menu_group: %} → {% data variables.android-values.plugin_ski_name %}

![Ski maps plugin Android](/assets/images/plugins/ski-maps/plugin_ski_maps_android.png) 

 If the **{% data variables.android-values.app_mode_skiing %}** profile is needed, leave the respective option toggled on in the opened popup window and tap **OK**. Otherwise, tap Turn off, and the plugin will be enabled without adding the profile. 

![Enabling Ski profile with plugin in Android](/assets/images/plugins/ski-maps/and_profile_in_ski_plugin.png)

{% endandroid%}


&nbsp;&nbsp;&nbsp;&nbsp;

### Set Winter style

{% data reusables.general.android-ios-switcher %}

{% default %}

The **Winter and Ski** style highlights pistes, ski touring trails, sled paths, etc. - the winter and ski related information. Whenever needed, just enable it for the required profile, as follows: 

1. Select the required [profile](/osmand/personal/profiles). 

2. Open [Configure map](/osmand/map/configure-map-menu).

3. Scroll down up to [Map style](/osmand/map/vector-maps), open it and check the Winter and Ski style. 


![Enable Winter style in iOS](/assets/images/plugins/ski-maps/ios_map_style_winter.png) ![Enable Winter style in Android](/assets/images/plugins/ski-maps/and_map_styles.png)

{% enddefault %}

{% ios%}

To verify what style is currently established for the profile, and\or to establish the **Winter and ski** style, select the respective option in the list of styles opened, as follows:

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.configure_map %} → {% data variables.ios-values.map_settings_offline %} → {% data variables.android-values.winter_and_ski_renderer %}

![Enable Winter style in iOS](/assets/images/plugins/ski-maps/ios_map_style_winter.png) ![Ski maps plugin map style iOS](/assets/images/plugins/ski-maps/plugin_ski_maps_style_ios.png)

{% endios%}

{% android%}

To verify what style is currently established for the profile, and\or to establish the **Winter and ski** style, select the respective option in the list of styles opened, as follows:

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_map %} → {% data variables.android-values.map_widget_map_rendering %} → {% data variables.android-values.map_widget_renderer %} → {% data variables.android-values.winter_and_ski_renderer %} 

![Enable Winter style in Android](/assets/images/plugins/ski-maps/and_map_styles.png) ![Ski maps plugin map style Android](/assets/images/plugins/ski-maps/plugin_ski_maps_style_android.png)

{% endandroid%}

>**NOTE**: The Skiing profile is initially created to be used together with the Winter and Ski style, as by default the Skiing profile is expected to have the Ski navigation established, which is intended for navigating along the pistes. However, what navigation type to use for every specific profile can be changed, and established individually, and thus, the final configuration of the profile, the map style and the navigation is fully governed by the settings made by the user.


&nbsp;&nbsp;&nbsp;&nbsp;

### Combine maps

The default [vector map](/osmand/map/vector-maps) with the enabled [Winter and Ski map style](/osmand/map/vector-maps#winter-and-ski) can be added with the [Contour lines](/osmand/plugins/contour-lines#show-contour-linesterrain) and\or [Hillshade](/osmand/plugins/contour-lines#hillshade-map) maps. Below are two examples. The left-hand figure shows pistes on the default vector map, while the one on the right shows pistes on the default vector map combined with the contour lines and the hillshade rastor map. In the second case, the map unveils more geolocation insights and elevation data to assess the complexity, risks, distance, etc. 

{% data reusables.general.android-ios-switcher %}

{% default %}

![No map combination in Android](/assets/images/plugins/ski-maps/and_no_contour_hillshade.png) ![With map combination in Android](/assets/images/plugins/ski-maps/and_yes_contour_hillshade.png)

{% enddefault %}

{% ios%}

![No map combination in iOS](/assets/images/plugins/ski-maps/ios_no_contours_hillshade.png) ![With map combination in iOS](/assets/images/plugins/ski-maps/ios_yes_contours_hillshade.png)

{% endios%}

{% android%}

![No map combination in Android](/assets/images/plugins/ski-maps/and_no_contour_hillshade.png) ![With map combination in Android](/assets/images/plugins/ski-maps/and_yes_contour_hillshade.png)

{% endandroid%}


&nbsp;&nbsp;&nbsp;&nbsp;

## Ski map options


&nbsp;&nbsp;&nbsp;&nbsp;

### Piste complexity



&nbsp;&nbsp;&nbsp;&nbsp;

### Piste type 



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

