---
title: "{% data variables.android-values.plugin_nautical_name %}"
intro: "Nautical map provides detailed graphical representation of oceans, seas, coastal areas and rivers to help you navigate on the water, and be aware of popular traffic routes, obstacles in your waterway, the nearest harbors, anchorages, and other essential reference.  "
versions: '*'
---

{% data reusables.general.article-not-complete %}

To view the Nautical map on the screen, the following configuration is needed: 

1. Purchase Nautical services.

2. Enable the plugin. 

3. Download the Nautical maps.

4. Consider other settings, such as:

    - Nautical map style, 
    - Boat profile, and/or the Boat navigation,
    - depth contours,
    - seabed details. 



## What is Nautical Chart?

Nautical Chart is a typographic map with high level of detail to help skippers drive a boat along the selected course on the water. It is like a road map for everybody on a vehicle. The map, often called as *'Chart'* due to historical reasons, provides a detailed graphical representation of oceans, seas, coastal areas and rivers.

Nautical Charts are important for professional sailors as well as amateurs easily renting a boat to make a tour over the city canals. The charts provide them with various information like sailing routes, navigation lights, dangerous areas, areas where it's allowed or not allowed to sail or dock, etc.

All professional sailors are obliged to have official nautical charts on their ships. These charts are published by authorized agencies and cost quite some money. Agencies are investing a lot in keeping the charts up to date. They release updates for the charts on regular basis, but, because of the fact that reviewing the information and processing the updates take time, the nautical charts are never completely up-to-date.

![Nautical maps](/assets/images/plugins/nautical-charts/nautical_maps.png)


## What is the data source?

Nautical charts of OsmAnd are based on the data from [OpenSeaMap](http://www.openseamap.org/). It cannot replace the official nautical charts. However, it is versatile. Being compiled from data prepared by amateur cartographers as well as organizations, OpenSeaMap goes beyond the costline and provides details on the inland waterways, wildwater, infrastructure of ports, restricted areas, facilities, etc.    

As a project, OpenSeaMap was built on the idea of creating a detailed map by people who actually use it. Every user of the map can contribute to it by adding information they view being important and useful to them, thus, making the map more detailed and accurate, ideal for orientation or route planning.



## Purchase Nautical

{% data reusables.general.android-ios-switcher %}

{% default %}

Nautical Chart is a paid service. Depending on the app version whether it is an iOS app, or an Android one, there are different options of obtaining the map. For more details, visit [Purchases](/osmand/purchases). 

{% enddefault %}

{% ios%}

For a Nautical Chart purchase on **iOS**, refer to [in-app purchases, or a subscription](/osmand/purchases/ios#in-app-purchases). 

It is also possible to view the already made purchases, by opening the following section in settings: 

{% data variables.ios-values.menu %} → {% data variables.ios-values.sett_settings %} → {% data variables.ios-values.purchases %} 

{% endios%}

{% android%}

For a Nautical Chart purchase on **Android**, refer to [in-app purchases, a subscription, or the full version of the app](/osmand/purchases/android#free-and-paid-features). 

It is also possible to view the already made purchases, by opening the following section in settings: 

{% data variables.android-values.shared_string_menu %} → {% data variables.android-values.shared_string_settings %} → {% data variables.android-values.purchases %}

{% endandroid%}


## Enable plugin

{% data reusables.general.android-ios-switcher %}

{% default %}

After the purchase of Nautical service, the Nautical plugin can be enabled. The plugin unlocks more functional capabilities, such as: 

- download nautical maps, 
- enable the Nautical map style for any of the profiles,
- view depth contours and seabed information. 

![Nautical maps plugin Android](/assets/images/plugins/nautical-charts/plugin_nautical_android.png) ![Nautical maps plugin iOS](/assets/images/plugins/nautical-charts/plugin_nautical_ios.png)


{% enddefault %}

{% ios%}

With the purchase of Nautical service made in the **iOS** version, to start using Nautical Charts, the Nautical plugin should be enabled, as follows: 

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.plugins %} → {% data variables.ios-values.product_title_nautical %}

After enabling the Nautical plugin, you can download Nautical maps, select the Nautical map type per profile, guide yourself with more nautical details during navigation.

![Nautical maps plugin iOS](/assets/images/plugins/nautical-charts/plugin_nautical_ios.png)

{% endios%}

{% android%}

With the purchase of Nautical service made in the **Android** version, to start using Nautical Charts, the Nautical plugin should be enabled, as follows:

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.plugins_menu_group: %} → {% data variables.android-values.plugin_nautical_name %}

After enabling the Nautical plugin, you can download Nautical maps, select the Nautical map style per profile, guide yourself with more nautical details during navigation.

![Nautical maps plugin Android](/assets/images/plugins/nautical-charts/plugin_nautical_android.png)

{% endandroid%}




  
## Download Nautical maps

{% data reusables.general.android-ios-switcher %}

{% default %}

With the [download](/osmand/start-with/download-maps) of a nautical map, more details specific to the Boat navigation show up on the map. There are some types of a [nautical map](/osmand/start-with/download-maps#type-of-maps) providing such details as:

- sea marks and symbols,
- depth points,
- depth contours. 

Marks and symbols are downloaded once for the entire World. Depth points are available per hemisphere, and for some regions. Depth contours can be downloaded for specific areas and then turned off, if not needed. If a nautical package is downloaded, its data is displayed on the map, according to the nautical settings described below. 

Nautical data from the depth points packages is represented with the numbers displayed on the water to indicate the lowest depth at a specific spot. The depth contours packages allow you to identify areas of equal depth. Both points and contours are intended to visualize how the relief might change underneath the water surface. 

Marks and symbols provide all nautical navigation signs, for inland as well as for nearshore navigation. Knowing these symbols helps to predict the location of rocks, obstacles, anchorages, the move of the current, areas of deep and shallow water, the side of a channel regardless of the direction of your movement, etc. 

![Nautical plugin maps view Android](/assets/images/plugins/nautical-charts/plugin_nautical_view_android.png) ![Nautical plugin maps view iOS](/assets/images/plugins/nautical-charts/plugin_nautical_view_ios.png)

{% enddefault %}

{% ios%}

In the **iOS** version, all nautical packages are available for [download](/osmand/start-with/download-maps) in the following area:

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.res_mapsres %} → {% data variables.ios-values.region_nautical %}

![Nautical plugin maps view iOS](/assets/images/plugins/nautical-charts/plugin_nautical_view_ios.png)

{% endios%}

{% android%}

In the **Android** version, all nautical maps are available for [download](/osmand/start-with/download-maps) in the following area:

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.welmode_download_maps %} → {% data variables.android-values.nautical_maps %}

![Nautical plugin maps view Android](/assets/images/plugins/nautical-charts/plugin_nautical_view_android.png)

{% endandroid%}

For an optimal representation, it is possible to select maps up to your current needs: marks and symbols can be added with depth points, and if required, with contours. On the other hand, standard maps with inland, onshore and nearshore information for a specific region can be a good addition to the waterway information of the Nautical map. 

> **NOTE**: All numbers on the Nautical Charts are presented in meters. 




## Map legend 

[Map legend](https://osmand.net/help-online/map-legend#nautical) helps everybody who wants to read the map. It provides explanation of symbolic elements on the Nautical map, and serves as a reference to guide yourself with in case of doubts. The Map Legend shows the following visual elements you can find on the map:

- Anchorage and berth,
- Navigation lines and areas,
- Buoys and beacons, 
- Electronic position-fixing systems, fog signals,
- Lights,
- Ports, moorings,
- Offshore platforms,
- Landmarks,
- Buildings, 
- Wrecks and rocks,
- Bridges, lockgates,
- Small craft facilities, 
- Marine farm, fishing,
- Seabed area,
- Cables and pipelines,
- Obstruction,
- and other signs of prohibition, information, regulation, recommendation, etc.




## Nautical settings

{% data reusables.general.android-ios-switcher %}

{% default %}

With the Nautical plugin enabled and a Nautical map downloaded, you can adjust what you see on the map by:
     
- changing the map rendering to the [Nautical](/osmand/map/vector-maps#nautical) type/style;
- showing or hiding the depth contours;
- specifying the detail level for the seabed information. 

The nautical settings can be used for any profile. However, the most value it makes to use them within the [Boat profile](/osmand/personal/profiles) and especially with the [Boat navigation](/osmand/navigation/boat-navigation). 

![Boat profile in iOS](/assets/images/plugins/nautical-charts/ios_boat_profile1.png) ![Boat navigation in iOS](/assets/images/plugins/nautical-charts/ios_boat_navigation2.png) 

{% enddefault %}

{% ios%}

In the **iOS** version, with the Nautical plugin enabled and a Nautical map downloaded, for every specific profile you can change the map type, and the visibility of the depth contour.

#### [NAUTICAL MAP TYPE](/osmand/map/vector-maps#nautical)

To change the map type to **Nautical** and thus, reveal more nautical-specific colors and visualization on the map, go to:

&nbsp;&nbsp;&nbsp;&nbsp;{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.configure_map %} → {% data variables.ios-values.map_settings_type %}

![Nautical Map Type in iOS](/assets/images/plugins/nautical-charts/ios_nautical_map_type1.png)

#### DEPTH CONTOUR

To show or hide the depth contours, and thus, adjust the visual representation of the map to your needs, use the [Configure map](/osmand/map/configure-map-menu) menu and the respective option, as follows: 

&nbsp;&nbsp;&nbsp;&nbsp;{% data variables.ios-values.menu %} → {% data variables.ios-values.configure_map %} → {% data variables.ios-values.map_settings_style %} → {% data variables.ios-values.res_details %}  
        
![Depth contours in iOS](/assets/images/plugins/nautical-charts/ios_depth_contours1.png)

{% endios%}

{% android%}

In the **Android** version, with the Nautical plugin enabled and a Nautical map downloaded, for every specific profile you can change the map type, the visibility of the depth contour, and select the level of details for the seabed to be displayed with. 

#### [NAUTICAL MAP TYPE](/osmand/map/vector-maps#nautical)

To change the map type to **Nautical** and thus, reveal more nautical-specific colors and visualization on the map, go to: 

&nbsp;&nbsp;&nbsp;&nbsp;{% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_map %} → {% data variables.android-values.map_widget_map_rendering %} → {% data variables.android-values.map_widget_renderer %}

![Nautical Map Type in Android](/assets/images/plugins/nautical-charts/and_map_style1.png)

#### DEPTH CONTOUR

To show or hide the depth contours, and thus, adjust the visual representation of the map to your needs, use the [Configure map](/osmand/map/configure-map-menu) menu and the respective option, as follows: 

&nbsp;&nbsp;&nbsp;&nbsp;{% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_map %} → {% data variables.android-values.shared_string_show %} → {% data variables.android-values.rendering_attr_depthContours_name %}

![Nautical depth contours in Android](/assets/images/plugins/nautical-charts/and_nautical_depth_contours2.png)


#### SEABED DETAILS

Seabed details provide information about the vegetation and general material the surface is composed of, such as: rocky, shells, gravel, coral, mud, etc. Due to the international classification of the seabed data, there are options of how to display such details on the map: *simple*, *category*, *all*, or *omit*. To select one of the seabed details options, go to:

&nbsp;&nbsp;&nbsp;&nbsp;{% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_map %} → {% data variables.android-values.map_widget_map_rendering %} → {% data variables.android-values.rendering_attr_seabedDetail_name %}

![Seabed details in Android](/assets/images/plugins/nautical-charts/and_seabed_details1.png)

| Parameter and Description |
| --- | 
| **Omit** - shows no seabed details. |
| **Simple** - shows the seamark symbols in accordance with INT-1 Ref, indicating the nature of the seabed surface. |
| ![Seabed simple](/assets/images/plugins/nautical-charts/seabed_simple1.png) |
| **Category** - in addition to the seamark symbol, also shows the respective seamark tag, indicating the natural material, or the seaweed/seagrass category. | 
| ![Seabed category](/assets/images/plugins/nautical-charts/seabed_category1.png) |
| **All** - in addition to the seamark symbol, tag or category, also shows qualification, like: fine, sticky, coarse, etc.; or for seagrass/seaweed, shows data marked with the *taxon* and *genus* tags.|
| ![Seabed all](/assets/images/plugins/nautical-charts/seabed_all1.png) | 

>**NOTE**: For more details on the classification of the surface details and the rendering options, refer to [OSM's seamark wiki](https://wiki.openstreetmap.org/wiki/Seamarks/INT-1_Section_J).

{% endandroid%}



## Return to conventional maps

To return to one of OsmAnd's conventional map styles, do any of the following:

- disable the Nautical plugin, 
- change the 'Map style' to anything else then 'Nautical'. 

>**NOTE**: By disabling the Nautical plugin, the downloaded nautical maps are not removed, so even if the rendering method is changed from nautical to anything else, when the nautical data is downloaded, it remains visible on the map. 

