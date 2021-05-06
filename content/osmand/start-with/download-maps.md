---
title: "Download maps"
intro: "Download maps is a nessecarily action for further using map and navigation in offline mode. Maps can be downloaded both through the list in the main menu and by clicking on the needed territory on the map."
versions: '*'
---
{% data reusables.general.article-not-complete %}

## First steps in map downloading

When the app is launching for the first time,  appears a suggestion  to download the map. This allows OsmAnd to determine location of the device  and will offer you to download the current region map. It is possible to select another region or skip downloading by clicking 'Skip' in the top-right corner.

**Note**: The "Mini world overview map"  will be downloaded by default. We recommend downloading the "World overview map". This is a basic map that allows you to view all regions and countries.

![Download map](/assets/images/settings/download_map.png)

There are two main map types you can use: vector and raster.
- [Vector maps](/osmand/start-with/download-maps#how-to-download-vector-maps) is a database of points, lines and polygons which collectively make up all the features on the map. This map format is relatively small in size and easy to download and convenient for offline use.
- [Raster map](/osmand/map/online-raster-maps) is a  electronic map image made up of a set number of pixels. This type of maps is more voluminous, requires a longer download and cannot always be used offline. 

In order to use navigation conveniently and quickly in offline mode, we recommend downloading vector maps.
## How to download vector maps
All "vector" maps in OsmAnd have native format. They are compact and allows  easily zooming without losing detail or resolution. 
### Download map via Main menu
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

### Download map via Zoom in the World map (Android)
It is available to download a map of a certain area using zoom in the World map. The notification "Download detailed map, to view the area" will appear at the top bar. Press the button to download and the map will automatically appear in {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.welmode_download_maps %}

![Zoom in download map Android ](/assets/images/settings/zoom_in_download_map_android.png)

**Note**: This dialog can be turned off  in {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.shared_string_settings %} → {% data variables.android-values.osmand_settings %} → {% data variables.android-values.dialogs_and_notifications_title %}

### Download actual region map by Clicking on the World map  

The one of the option to download map is tap on the map and hold. In the bottom part of the screen will appear an banner with suggestion to download map of this area.

![Tap on the map download region](/assets/images/settings/tap_on_the_map_download_region.png)

## Download created by yourself map

There is a possibility to download created by yourself (in OsmAnd Map Creator) map. [Read more](/development/map-creation/create-offline-maps-yourself)

