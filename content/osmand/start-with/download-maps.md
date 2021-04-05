---
title: "Download maps"
intro: "Download maps"
versions: '*'
---
When the app is launching for the first time, the User can see the suggestion to download the map. That lets the OsmAnd determine the user's location and suggests downloading the current region map. It is possible to select another region or skip downloading by clicking 'Skip' in the top-right corner.

> NOTE: The "Mini world overview map"  will be downloaded by default. We recommend downloading the "World overview map". This basic map allows user to view regions and countries.

![Download map](/assets/images/settings/download_map.png)

> NOTE: For offline use, you need to preload necessary maps. OsmAnd uses .obf file format for the maps.

<!-- There are two main map types you can download. -->
## Vector maps (preferred solution)

All "vector" maps in OsmAnd have native format. They are 10%  compacter than tiles and allows zooming without losing detail or resolution. For slow devices zooming out to "overview" levels takes more time and CPU.

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.welmode_download_maps %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.res_mapsres %}

The list of maps to download will appear. User can use the search (magnifying glass) at the left top corner to find necessary region.

![Download maps regions ](/assets/images/settings/download_maps_regions.png)

### Zoom in the World map to download the map (Android)

To download a map of a certain area user can zoom in the World map. The notification "Download detailed map, to view the area" will appear at the top bar. Press the button to download and the map will automatically appear in {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.welmode_download_maps %}

![Zoom in download map Android ](/assets/images/settings/zoom_in_download_map_android.png)

> NOTE: This dialog can be turned on or off  in {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.shared_string_settings %} → {% data variables.android-values.osmand_settings %} → {% data variables.android-values.dialogs_and_notifications_title %}

### Click on the World map to download the actual region

The map of a certain area can be downloaded by tapping on the map. OsmAnd will offer to download the map of the chosen area. At the bottom of the screen, the button with the name of the area on it will be shown.

![Tap on the map download region](/assets/images/settings/tap_on_the_map_download_region.png)

<!-- ## Prepared maps

Users can make their own maps using **OsmAnd Map Creator**.  Prepare the maps on your PC and transfer them to the "OsmAnd" folder on your device. You might need to restart the app afterward.-->
