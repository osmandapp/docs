---
title: "Download maps"
intro: "Download maps is a nessecarily action for further using map and navigation in offline mode. Maps can be downloaded both through the list in the main menu and by clicking on the needed territory on the map."
versions: '*'
---
{% data reusables.general.article-not-complete %}

Application is not properly functional without offline maps which are not distributed within application. Even though application supports [Vector maps](osmand/map/vector-maps) and  [Raster map](/osmand/map/raster-maps), it is highly recommend to start with Offline Vector Maps to get all features properly functioning such as [! Search !](/osmand/todo), [! Navigation!](/osmand/todo),  [! Context menu !](/osmand/todo). 

## Download - First Screen

When the app is launched for the first time, it suggests to download the map based on your internet location. It could be not correctly detected in case you are using VPN and it's possible to select another map region.

**Note** - World map. Old versions of OsmAnd (< 3.8) suggest to download World map, so you could browse the map on the planet level zoom. In new OsmAnd versions: small "Mini world overview map" is packaged inside. There is a bigger "World overview map" available to download which contains more details for the World-level map.

![Download map](/assets/images/settings/download_map.png)

## Download - Main menu
In order to download new maps or see already downloaded you need to open Download map list:

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.welmode_download_maps %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.res_mapsres %}

Download map menu includes:
- Name of the page - 'Map' (Android) / 'Map and resourses' (iOS)
- Refresh the page button - refresh the page
- Search button - by pressing on it you can enter the name of the region or city that you would like to download
- Map counter (Only in free version) - display how many map downloads left
- Device memory - show the how much memory left
- All downloads / Worldwide - is a menu with all available to download files:
- Local / Installed - Display already downloaded files
- Updates / OsmAnd Live - Display the map that could be updated

![Download maps regions ](/assets/images/settings/download_maps_regions.png)

## Download - Select on World map

The one of the option to download map is tap on the map and hold. In the bottom part of the screen will appear an banner with suggestion to download map of this area.

![Tap on the map download region](/assets/images/settings/tap_on_the_map_download_region.png)

## Download - Map Zoom in (Android)
It is available to download a map of a certain area using zoom in the World map. The notification "Download detailed map, to view the area" will appear at the top bar. Press the button to download and the map will automatically appear in {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.welmode_download_maps %}

![Zoom in download map Android ](/assets/images/settings/zoom_in_download_map_android.png)

**Note**: This dialog can be turned off  in {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.shared_string_settings %} → {% data variables.android-values.osmand_settings %} → {% data variables.android-values.dialogs_and_notifications_title %}

## Download - own map (Advanced)

There is a possibility to download created by yourself (in OsmAnd Map Creator) map. [Read more](/development/map-creation/create-offline-maps-yourself)

