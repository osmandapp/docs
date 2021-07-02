---
title: "First steps"
intro: "This section is helping you to begin with OsmAnd. It includes information about  app installation, necessarily downloading and permission"
versions: '*'
---

{% data reusables.general.article-not-complete %}

{% default %}

![First screen Android](/assets/images/settings/first_screen_android.png) ![Map Android](/assets/images/settings/first_screen_map_android.png) 

{% enddefault %}

{% android %}

![OsmAnd navigation Android](/assets/images/settings/osmand_navigation_android.png) 

{% endandroid %}

{% ios %}

![iOS](/assets/images/map/description_list_ios.png)

{% endios %}

## Install OsmAnd
OsmAnd is a mobile application for Maps and Navigation available for **Android** and **iOS**. You can download it on most popular Markets.

**Android markets**: [Google play store](https://play.google.com/store/apps/details?id=net.osmand&hl=en&gl=US), [Huawei AppGallery](https://appgallery.huawei.com/#/app/C101486545), [Amazon](https://www.amazon.com/OsmAnd-Maps-Navigation/dp/B00D0SA8I8/ref=sr_1_3?dchild=1&keywords=osmand&qid=1616685559&sr=8-3). 

**iOS**: [App store](https://apps.apple.com/us/app/osmand-maps-travel-navigate/id934850257).

[Read more](/osmand/purchases) about OsmAnd versions and Purchases.  

## Welcome to OsmAnd!

Our goal is to create a fully functional map-oriented application that could be used offline & online for various purposes. The application is full of features, so you don't need to switch between different apps and have everything at your fingertips:
- Browse Worldwide Map with lots of details displayed with [many map styles](/osmand/map/vector-maps).
- Display, search and save various [Points of interests](/osmand/map/point-layers-on-map).
- [Plan a route](/osmand/plan-route/create-route) by car, bicycle, foot and combine into multi modal routes.
- Start [voice guided navigation](/osmand/navigation/route-navigation) with screen on and off.
- Make your tourist trip rich with offline [Wikipedia](/osmand/plugins/wikipedia) and [Wikivoyage](/osmand/plan-route/travel-guides).
- Fully customize how [the map displayed](/osmand/map/configure-map-menu) and what [widgets](/osmand/widgets) are displayed on it.
- Navigate [by boat](/osmand/navigation/boat-navigation), [by a given track](/osmand/navigation/gpx-navigation), [by public transport](/osmand/navigation/public-transport-navigation) and [offroad](/osmand/navigation/markers-navigation).
- Everything works in **Offline Mode**!
- And don't forget to contribute to [OpenStreetMap](https://www.openstreetmap.org/) with [OSM Editing Plugin](/osmand/plugins/osm-editing).

## Actions Guide

### How to download maps

{% data reusables.general.android-ios-switcher %}

OsmAnd is an offline map application, so after '{% data variables.android-values.get_started %}' screen, you will be proposed to [download map](/osmand/start-with/download-maps#download---first-screen) of your region. You can select another region or skip this step and download maps later. 

{% android %}

![Show on the map](/assets/images/settings/download_map1_android.png)

{% endandroid %}

{% ios %}

![ios](screenshot)

{% endios %}

**Note**: Application is not properly functional without offline maps which are not distributed within application. Even though application supports [Vector maps](/osmand/map/vector-maps) and  [Raster maps](/osmand/map/raster-maps), it is highly recommend to start with Offline Vector Maps to get all features properly functioning such as [Search](/osmand/search), [Navigation](//osmand/navigation),  [Context menu](/osmand/map/map-context-menu). 

[Read more](/osmand/start-with/download-maps) about download map options.

### How to manage your settings

{% data reusables.general.android-ios-switcher %}

You could manage application settings as [Global settings](/osmand/personal/global-settings) or as [Profile configuration](/osmand/personal/profiles) via [Main menu](/osmand/start-with/main-menu). Application comes with predefined list of profiles which could be modified later. Each profile could be considered as a special customized map application, though by default profiles are used as special navigation modes.

{% android %}

![Manage profile Android](/assets/images/settings/manage_profile_android.png) ![Configure profile Android](/assets/images/settings/configure_profile_android.png)

{% endandroid %}

{% ios %}

![Settings iOS](screenshot)

{% endios %}

[Read more](/osmand/personal/global-settings) about Global settings.
[Read more](/osmand/personal/profiles) about Profile settings.

### How to configure plugins

{% data reusables.general.android-ios-switcher %}

[Plugins](/osmand/plugins) allow greatly to extend application functionality. Plugins could be internal (provided inside OsmAnd) or external (separate installed applications). 3rd party plugins work via [OsmAnd API](/development/build-osmand/osmand-api) and get access to OsmAnd information, you could always review / enable / disable plugins via [Main menu](/osmand/start-with/main-menu) → Plugins. Each plugin could have own [Map Actions](/osmand/map/map-context-menu), [Map Layers](/osmand/map/configure-map-menu), [Map Downloads](/osmand/start-with/download-maps) and Settings.

{% android %}

![Enable plugins Android](/assets/images/settings/plugins_enable_android.png)

{% endandroid %}

{% ios %}

![Enable plugins iOS](/assets/images/settings/plugins_enable_ios.png)

{% endios %}

Enable / disable plugins:

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.plugin_settings %} →  &#65049; → Enable

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.plugins %} → &#10003; .

[Read more](/osmand/plugins) about OsmAnd plugins.

### How to configure map

{% data reusables.general.android-ios-switcher %}

[Map interactions](/osmand/map/interact-with-map) are gestures and actions that help you better navigate the map. In order to choose map style, mode, and enable information that will be displayed on the map you need to go to the  [Main menu](/osmand/start-with/main-menu) then [Configure map](/osmand/map/configure-map-menu). Or on the Map screen you can press on the circle in the left top corner with [navigation type](/osmand/personal/profiles#profile-types) and you will enter to the [Configure map](/osmand/map/configure-map-menu) menu. 

{% android %}

![Configure map](/assets/images/settings/configure_map_menu_android.png) 

{% endandroid %}

{% ios %}

![Settings iOS](screenshot)

{% endios %}

[Read more](osmand/map/configure-map-menu) about map configuration.

### How to сonfigure screen

{% data reusables.general.android-ios-switcher %}

[Configure screen](/osmand/widgets/configure-screen) allows you to enable [Informational](/osmand/widgets/info-widgets) (altitude, speed, current time, etc.) & [Navigation](/osmand/widgets/nav-widgets)  (distanation, bearing, arrival time, etc.) widgets, [Quick action](/osmand/widgets/quick-action), and other elements that will be displayed on the Map.

{% android %}

![Configure screen Android](/assets/images/widgets/configure_screen_android.png)

{% endandroid %}

{% ios %}

![Settings iOS](screenshot)

{% endios %}

[Read more](/osmand/widgets/configure-screen) about Screen configuration.

### How to add personal data to maps

{% data reusables.general.android-ios-switcher %}

OsmAnd allows you to make a different mark on the Map for your personal use. It could be [Favorite](/osmand/personal/favorites) points, [Markers](/osmand/personal/markers), [Audio/Video notes](/osmand/plugins/audio-video-notes) (Android only), [track recording](/osmand/plugins/trip-recording).

{% android %}

![Add personal data](/assets/images/settings/personal_data_android.png)

{% endandroid %}

{% ios %}

![Settings iOS](screenshot)

{% endios %}

[Read more](/osmand/map/point-layers-on-map) about points on the map.

### How to browse & find point of interest

{% data reusables.general.android-ios-switcher %}

[Points of interest (POI)](https://wiki.openstreetmap.org/wiki/Map_features#Amenity) are specific points highlighted with an icon on the map. They represent interesting or useful places & objects and they are part of [Vector Maps](/osmand/map/vector-maps). You can use them to display, [navigate](/osmand/navigation) and [search](/osmand/search/search-poi) the points of interest on the Map.

{% android %}

![Multiple POI Selection](/assets/images/map/multiple_selection_android.png) ![Search and display POI Android](/assets/images/map/search_display_poi_android.png)

{% endandroid %}

{% ios %}

![Multiple POI Selection](/assets/images/settings/multiple_selection_iOS.png) ![Search and display POI iOS](/assets/images/settings/search_display_poi_iOS.png)

{% endios %}

[Read more](/osmand/search/search-poi) about POI search.

### How to plan a route

{% data reusables.general.android-ios-switcher %}

[Plan route](/osmand/plan-route/create-route) is an additional tool that helps you to measure distance on the map, plan your trip and save it as a gpx file,  and edit exists track. 

{% android %}

![Plan route](/assets/images/settings/plan_route_android.png) ![Plan route graph Android](/assets/images/settings/plan_route_graph_android.png)

{% endandroid %}

{% ios %}

![Settings iOS](screenshot)

{% endios %}

[Read more](/osmand/plan-route/create-route) about plan route feature.

### How to search by address

{% data reusables.general.android-ios-switcher %}

In the OsmAnd you can find any address, place and object that has been marked on the [OpenStreetMap](https://www.openstreetmap.org/). You can [search](/osmand/search/search-address) by the name of the city, postcode and coordinates. 

{% android %}

![Address search Android](/assets/images/settings/address_search_android.png)

{% endandroid %}

{% ios %}

![Settings iOS](screenshot)

{% endios %}

**Note:** You need to download the map before searching for an address there. Also, if your current location is too far from your searching address you might need to increase the searching radius. 

[Read more](/osmand/search/search-address) about address search.

### How to start navigation

{% data reusables.general.android-ios-switcher %}

The [navigation](/osmand/navigation) functionality guides you to your destinations, by displaying routes, offering turn-by-turn instructions, and optional voice guidance.

{% android %}

![Navigation Android](/assets/images/settings/navigation_android.png)

{% endandroid %}

{% ios %}

![Settings iOS](screenshot)

{% endios %}

[Read more](/osmand/navigation) about navigation.

### How to record you trip

{% data reusables.general.android-ios-switcher %}

[Trip recording](/osmand/plugins/trip-recording) is a tool that allows to record all movements into track using phone's GPS.

{% android %}

![Trip recording Android](/assets/images/settings/trip_recording_android.png) ![Overview track](/assets/images/settings/overview_track_android.png)

{% endandroid %}

{% ios %}

![Settings iOS](screenshot)

{% endios %}

[Read more](/osmand/plugins/trip-recording) about trip recording.

### How to edit maps

{% data reusables.general.android-ios-switcher %}

OsmAnd powered by OpenStreetMap data. The maps are created by volunteer contributors, so they can have more or fewer details depending on how much work has been done at a certain part of the map. Anyone can register as a contributor and add or edit OSM maps. OsmAnd provide with editing plugin that helps to impove the OpenStreetMap. 

{% android %}

![OSM note Android](/assets/images/settings/osm_note_android.png)

{% endandroid %}

{% ios %}

![Settings iOS](screenshot)

{% endios %}

[Read more](/osmand/plugins/osm-editing) about OSM editing. 

## Privacy

It is an [open source](https://github.com/osmandapp/osmand), ads-free / tracker-free privacy focused application. In order to preserve maximum privacy, OsmAnd offers Offline maps as a first place, so no interaction, geo information is leaked from your device. We are very attentive to what data is collected and what data is transferred by network, you can read more in our [Privacy policy](https://osmand.net/help-online/privacy-policy). 

## Permissions

OsmAnd doesn't have any required permissions on iOS / Android version. 

**Essential**:
- **Internet** - initial download / update offline maps. Also could be needed to access online features such as [Street Level Imagery](/osmand/map/point-layers-on-map#-street-level-imagery), [Online photos](/osmand/map/map-context-menu#online-photos) or [Online maps](/osmand/map/raster-maps).
- **GPS** / **GSM Network** - determine your location, follow you in a navigation mode, record your trip (optional). This permission is asked when you click [my location button](/osmand/widgets/map-buttons#my-location--zoom) or when you [start navigation](/osmand/navigation/route-navigation).

**Optional**:
- **Camera/voice recording** (Android) - only used by [the Audio/Video notes](/osmand/plugins/audio-video-notes). This feature is packaged as plugin and by default disabled. It allows to quickly create location-related audio/video notes during a trip.

## Troubleshooting

If you have a specific question, please check [Troubleshooting](/osmand/troubleshooting) to have it answered.


