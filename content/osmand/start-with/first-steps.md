---
title: "First steps"
intro: "This section is helping you to begin with OsmAnd. It includes information about  app installation, necessarily downloading and permission"
versions: '*'
---

{% data reusables.general.article-not-complete %}

{% default %}

![First screen Android](/assets/images/settings/first_screen_android.png) ![Download map Android](/assets/images/settings/download_map_android.png)

{% enddefault %}

{% android %}

![Android](/assets/images/settings/download_map_android.png)

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

Our goal is to create fully functional Map-oriented application that could be used offline in various purposes. The application is full of features, so you don't need to switch between different apps and have everything at your fingertips:
- Browse Worldwide Map with lots of details displayed with [many map styles](/osmand/map/vector-maps).
- Display, search and save various [Points of interests](/osmand/map/point-layers-on-map).
- [Plan a route](/osmand/plan-route/create-route) by car, bicycle, foot and combine it.
- Start [voice guided navigation](/osmand/navigation/route-navigation) with screen on and off.
- Make your tourist trip rich with offline [Wikipedia](/osmand/plugins/wikipedia) and [Wikivoyage](/osmand/plan-route/travel-guides).
- Fully customize how [the map displayed](/osmand/map/configure-map-menu) and what [widgets](/osmand/widgets) are displayed on it.
- Navigate [by boat](/osmand/navigation/boat-navigation), [by a given track](/osmand/navigation/gpx-navigation), [by public transport](/osmand/navigation/public-transport-navigation) and [offroad](/osmand/navigation/markers-navigation).
- Everything works in **Offline Mode**!
- And don't forget to contribute to [OpenStreetMap](https://www.openstreetmap.org/) with [OSM Editing Plugin](/osmand/plugins/osm-editing).

## Actions Guide

### How to download maps

{% data reusables.general.android-ios-switcher %}

OsmAnd is an offline map application, so after '{% data variables.android-values.get_started %}' screen, you will be proposed to [download map](/osmand/start-with/download-maps#download---first-screen) of your region. You can select another region or skip this step and download map later. 

{% android %}

![First screen](/assets/images/settings/first_screen_android.png) ![Download map Android](/assets/images/settings/download_map_android.png)

{% endandroid %}

**Note**: Application is not properly functional without offline maps which are not distributed within application. Even though application supports [Vector maps](/osmand/map/vector-maps) and  [Raster maps](/osmand/map/raster-maps), it is highly recommend to start with Offline Vector Maps to get all features properly functioning such as [Search](/osmand/search), [Navigation](//osmand/navigation),  [Context menu](/osmand/map/map-context-menu). 

[Read more](/osmand/start-with/download-maps) about download map options.

### How to manage your settings

For convenient use of the application, the user is advised to select the desired profiles and configure the basic parameters of the app.  In the [Main menu](/osmand/start-with/main-menu) when you press Settings button you enter the [Global settings](/osmand/personal/global-settings) menu and [Profile configuration](/osmand/personal/profiles) menu.

![Settings Android](/assets/images/settings/settings_android.png) ![Configure profile Android](/assets/images/settings/configure_profile_android.png)

### How to configure plugins

[Plugins](/osmand/plugins) is an additional settings that provides you with advanced functions of the application. You can customize what plugin should be switched on according to your current needs. 

![Plugins main menu Android](/assets/images/plugins/plugins_main_menu_android.png)

Enable / disable plugins:

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.plugin_settings %} →  &#65049; → Enable

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.plugins %} → &#10003; .

[Read more](/osmand/plugins) about OsmAnd plugins.

### How to configure map
[Map interactions](/osmand/map/interact-with-map) are gestures and actions that help you better navigate the map. In order to choose which map style you would like to use and customize map mode and which icons should be displayed on the map, you need to go to the [Configure map](/osmand/map/configure-map-menu) menu. 

![Configure map](/assets/images/map/configure_map_menu_android.png)

### How to сonfigure screen

[Configure screen](/osmand/widgets/configure-screen) allows you to enable [Informational](/osmand/widgets/info-widgets) & [Navigation](/osmand/widgets/nav-widgets) widgets, [Quick action](/osmand/widgets/quick-action), and other elements that will be displayed on the Map.

![Configure screen Android](/assets/images/widgets/configure_screen_android.png)

### How to add personal data to maps

OsmAnd allows you to make a different mark on the Map for your personal use. It could be [Favorite](/osmand/personal/favorites) points, [Markers](/osmand/personal/markers), [Audio/Video notes](/osmand/plugins/audio-video-notes) (Android only), [track recording](/osmand/plugins/trip-recording).

![Add personal data](/assets/images/settings/personal_data_android.png)

[Read more](/osmand/map/point-layers-on-map) about points on the map.

### How to browse & find point of interest

[Points of interest (POI)](https://wiki.openstreetmap.org/wiki/Map_features#Amenity) are specific points highlighted with an icon on the map. They represent interesting or useful places & objects and they are part of [Vector Maps](/osmand/map/vector-maps). You can use them to display, [navigate](/osmand/navigation) and [search](/osmand/search/search-poi) the points of interest on the Map.

![Multiple POI Selection](/assets/images/map/multiple_selection_android.png) ![Search and display POI Android](/assets/images/map/search_display_poi_android.png)

### How to plan a route

[Plan route](/osmand/plan-route/create-route) is an additional tool that helps you to measure distance on the map, plan your trip and save it as a gpx file,  and edit exists track. 

![Plan route](/assets/images/settings/plan_route_android.png)

### How to search by address

In the OsmAnd you can find any address, place and object that has been marked on the [OpenStreetMap](https://www.openstreetmap.org/). You can [search](/osmand/search/search-address) by the name of the city, postcode and coordinates. 

![Address search Android](/assets/images/settings/address_search_android.png)

**Note:** You need to download the map before searching for an address there. Also, if your current location is too far from your searching address you might need to increase the searching radius. 

### How to start navigation

The [navigation](/osmand/navigation) functionality guides you to your destinations, by displaying routes, offering turn-by-turn instructions, and optional voice guidance.

![Navigation Android](/assets/images/settings/navigation_android.png)

### How to record you trip

[Trip recording](/osmand/plugins/trip-recording) is a tool that allows to record all movements into track using phone's GPS.

![Trip recording Android](/assets/images/settings/trip_recording_android.png)

### How to edit maps

[Screenshots]().


## Privacy

It is an [open source](https://github.com/osmandapp/osmand), ads-free / tracker-free privacy focused application. In order to preserve maximum privacy, OsmAnd offers Offline maps as a first place, so no interaction, geo information is leaked from your device. We are very attentive to what data is collected and what data is transferred by network, you can read more in our [Privacy policy](https://osmand.net/help-online/privacy-policy). 

## Permissions

OsmAnd doesn't have any required permissions on iOS / Android version. 

**Essential**:
- **Internet** - initial download / update offline maps. Also could be needed to access online features such as [Street Level Imagery](/osmand/map/point-layers-on-map#-street-level-imagery), [Online photos](/osmand/map/map-context-menu#online-photos) or [Online maps](/osmand/map/raster-maps).
- **GPS** / **GSM Network** - determine your location, follow you in a navigation mode, record your trip (optional). This permission is asked when you click [my location button](/osmand/widgets/map-buttons#my-location--zoom) or when you [start navigation](/osmand/navigation/route-navigation).

**Optional**:
- **Camera/voice recording** (Android) - only used by [the Audio/Video notes](/osmand/plugins/audio-video-notes). This feature is packaged as plugin and by default disabled. It allows to quickly create location-related audio/video notes during a trip.

### Troubleshooting

If you have a specific question, please check [Troubleshooting](/osmand/troubleshooting) to have it answered.


