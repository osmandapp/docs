---
title: "{% data variables.android-values.plugin_nautical_name %}"
intro: "Nautical chart as a detailed graphical representation of oceans, seas, coastal areas and rivers helps to identify what obstacles can show up in your waterway and plot an optimal course to your destination."
versions: '*'
---


{% data reusables.general.article-not-complete %}

To view the Nautical map on the screen, the following configuration is needed: 

1. Purchase Nautical services.

2. Enable the plugin. 

3. Download the Nautical maps.

4. Consider the following settings:

    - **Nautical** is selected for the Map Style, 
    - enable the Boat profile, and/or the Boat navigation,
    - if needed, show, or hide the depth contours,
    - if needed, display full details for the symbols on the map. 



## What is Nautical Chart?

Nautical Chart is a typographic map with high level of detail to help skippers to drive a boat along the selected course on the water. It is like a road map for everybody on a vehicle. The map, often called *'Chart'* due to historical reasons, provides a detailed graphical representation of oceans, seas, coastal areas and rivers.

Nautical Charts are important for professional sailors as well as amateurs easily renting a boat to make a tour over the city canals. The charts provide them with various information like sailing routes, navigation lights, dangerous areas, areas where it's allowed or not allowed to sail or dock, etc.

All professional sailors are obliged to have official nautical charts on their ships. These charts are published by authorized agencies and cost quite some money. Agencies are investing a lot in keeping the charts up to date. They release updates for the charts on regular basis, but, because of the fact that reviewing the information and processing the updates take time, the nautical charts are never completely up-to-date.

![Nautical maps](/assets/images/plugins/nautical-charts/nautical_maps.png)


## What is the data source?

Nautical charts of OsmAnd are based on the data from  [OpenSeaMap](http://www.openseamap.org/) project. The idea of the project is to build a detailed map by people who actually use it. Every user of the map can contribute by adding changes to it and thus, making it more detailed and more accurate.



## Purchase Nautical service

{% data reusables.general.android-ios-switcher %}

{% default %}

To use the Nautical Chart, the service needs to be purchased. Depending on the app version whether it is an iOS app, or an Android one, the purchase is made differently. For more details, visit [Purchases](/osmand/purchases). 

{% enddefault %}

{% ios%}

Nautical Charts require purchase. For purchases on **iOS**, refer to [in-app purchases, or a subscription](/osmand/purchases/ios#in-app-purchases). To view the already made purchases, go to: {% data variables.ios-values.menu %} → {% data variables.ios-values.sett_settings %} → {% data variables.ios-values.purchases %} 

{% endios%}

{% android%}

Nautical Charts require purchase. For purchases on **Android**, refer to [in-app purchases, a subscription, or the full version of the app](/osmand/purchases/android#free-and-paid-features). To view the already made purchases, go to: {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.shared_string_settings %} → {% data variables.android-values.purchases %}

{% endandroid%}


## Enable Nautical plugin

{% data reusables.general.android-ios-switcher %}

{% default %}

With the purchase of Nautical service completed, the Nautical plugin can be enabled. The plugin is an autonomous functionality, which if enabled, provides more maps for 
download, adds the Boat profile, and enables the Boat navigation. 

![Nautical maps plugin Android](/assets/images/plugins/nautical-charts/plugin_nautical_android.png) ![Nautical maps plugin iOS](/assets/images/plugins/nautical-charts/plugin_nautical_ios.png)


{% enddefault %}

{% ios%}

With the purchase of Nautical service made in the **iOS** version, to start using Nautical Charts, the Nautical plugin should be enabled, as follows: 

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.plugins %} → {% data variables.ios-values.product_title_nautical %}

After enabling the Nautical plugin, you can download Nautical maps, add the Boat profile, and use Boat navigation.

![Nautical maps plugin iOS](/assets/images/plugins/nautical-charts/plugin_nautical_ios.png)

{% endios%}

{% android%}

With the purchase of Nautical service made in the **Android** version, to start using Nautical Charts, the Nautical plugin should be enabled, as follows:

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.plugins_menu_group: %} → {% data variables.android-values.plugin_nautical_name %}

After enabling the Nautical plugin, you can download Nautical maps, add the Boat profile, and use Boat navigation.

![Nautical maps plugin Android](/assets/images/plugins/nautical-charts/plugin_nautical_android.png)

{% endandroid%}




  
## Download Nautical maps

{% data reusables.general.android-ios-switcher %}

{% default %}

If a map is downloaded, it is visible, assuming that the Map Style is established as **Nautical** in the Boat profile (see the guidance below). And vice versa, if a map is not downloaded, it is not visible and cannot be used. 

There are some categories of Nautical [maps available for download](/osmand/start-with/download-maps#type-of-maps):

- sea marks and symbols,
- depth points,
- depth contours. 

Marks and symbols are downloaded once for the entire World. Depth points are available per hemisphere, and for some regions. Depth contours can be downloaded for specific areas and then turned off, if not needed. 

Depth points show numbers on the water to indicate the lowest depth at that spot. Contours show equal depths. Both points and contours are intended to visualize how the relief might change underneath the water surface. 

Marks and symbols provide all nautical navigation signs, for inland as well as for nearshore navigation. Knowing this symbols helps to predict the location of rocks, obstacles, anchorages, the move of the current, deep and shallow water, the side of a channel regardless of the direction of your movement, etc. 

![Nautical plugin maps view Android](/assets/images/plugins/nautical-charts/plugin_nautical_view_android.png) ![Nautical plugin maps view iOS](/assets/images/plugins/nautical-charts/plugin_nautical_view_ios.png)

{% enddefault %}

{% ios%}

In the **iOS** version, all nautical maps are available for download in the following area:

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.res_mapsres %}} → {% data variables.ios-values.region_nautical %}

For an optimal representation, it is possible to select maps up to your current needs: marks and symbols can be added with depth points, and if required, with contours. On the other hand, standard maps with inland, onshore and nearshore information can be a good addition to the waterway information of the Nautical map.  

![Nautical plugin maps view iOS](/assets/images/plugins/nautical-charts/plugin_nautical_view_ios.png)

{% endios%}

{% android%}

In the **Android** version, all nautical maps are available for download in the following area:

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.welmode_download_maps %} → {% data variables.android-values.nautical_maps %}

For an optimal representation, it is possible to select maps up to your current needs: marks and symbols can be added with depth points, and if required, with contours. On the other hand, standard maps with inland, onshore and nearshore information can be a good addition to the waterway information of the Nautical map.  

![Nautical plugin maps view Android](/assets/images/plugins/nautical-charts/plugin_nautical_view_android.png)

{% endandroid%}

> **NOTE**: All numbers on the Nautical Charts are presented in meters. 






## Map legend for any reference

For any reference on what a symbol identifies on the Nautical map, use the **Map legend**. It provides explanation of symbolic elements on all maps, and specifically the [Nautical map](https://osmand.net/help-online/map-legend#nautical), so that to guide you if any doubts on the type of harbor, landmarks, wreck kind, bridge and building differences, etc.  




## Nautical settings

{% data reusables.general.android-ios-switcher %}

{% default %}

With the Nautical plugin enabled, the following settings become available regardless of what map is downloaded:
     
    - add, configure, and use the Boat profile, 
    - select the [Boat navigation](/osmand/navigation/boat-navigation) in any profile,
    - show, or hide the depth contours, if the respective map has been downloaded,
    - display full [details](/osmand/map/vector-maps#details) for the symbols on the map.

Additionally, the [Nautical option](/osmand/map/vector-maps#nautical) in the Map Style, if established, adds marine style to the way of how a map is currently represented in any of available profiles, and especially in the Boat profile. 



{% enddefault %}

{% ios%}

In the **iOS** version, with the Nautical plugin enabled, you can:

- add the Boat profile in:

- select the [Boat navigation](/osmand/navigation/boat-navigation) in:

- show/hide depth contours in: 

- select the display of symbol [details](/osmand/map/vector-maps#details) in: 

{% endios%}

{% android%}

In the **Android** version, with the Nautical plugin enabled, you can:

- add the Boat profile in:

- select the [Boat navigation](/osmand/navigation/boat-navigation) in:

- show/hide depth contours in: 

- select the display of symbol [details](/osmand/map/vector-maps#details) in:


{% endandroid%}




## Return to conventional maps

{% data reusables.general.android-ios-switcher %}

{% default %}

To return to one of OsmAnd's conventional map styles, do any of the following:

- disable the Nautical plugin, 
- change the 'Map style' to anything else then 'Nautical'. 

{% enddefault %}

{% ios%}

{% endios%}

{% android%}


{% endandroid%}


