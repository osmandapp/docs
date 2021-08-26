---
title: "Maps"
intro: "Downloading and editing maps data for offline using."
versions: '*'
---

{% data reusables.general.article-not-complete %}


In OsmAnd you can use [Vector maps](/osmand/map/vector-maps) and  [Raster maps](/osmand/map/raster-maps). All maps are store in one place and users can easily download, manage and update the maps. 

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.welmode_download_maps %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.res_mapsres %}

{% default %}

{% enddefault %}

{% android %}

![Maps menu Android](/assets/images/personal/maps/maps_menu_android.png) ![Download maps menu Android](/assets/images/personal/maps/download_map_android.png) 

{% endandroid %}

{% ios %}

![Maps menu iOS](/assets/images/personal/maps/maps_menu_ios.png) ![Download maps menu iOS](/assets/images/personal/maps/download_map_ios.png)

{% endios %}

Buttons on top of the screen:
- Refresh &#10227; map data (new maps for updating)
- Search  button for findind needed map.


## Type of maps


In order to download the region or country map you can enter the name of the country or big city in the search area or from the Menu step by step go into the needed map.
When you enter the country map menu you will see all map types available for download:
-  Standard - contains all of the available information from [OpenStreetMap](https://www.openstreetmap.org/) source. 
-  Roads-only (Android) - contains only information about the roads. Perfectly suited for users with small device memory or for the area where you do not need the details information.
-  [Coutour lines](/osmand/map/vector-maps#contour-lines) - contains information about the elevation lines and terrain.
-  [Hillshades](/osmand/map/raster-maps#hillshade--slope)
-  [Slopes](/osmand/map/raster-maps#hillshade--slope)
-  [Wikipedia](/osmand/plugins/wikipedia) - contains files with the Wikipedia articles that you can read offline.
- Travel guides / Wikivoyage
- Nautical maps
- Voice packages
- Map fonts
- Altitude correction (Android)
- Other maps

**Note**: In the Android version is available to use bulk map downloads. You could easily recognize when this option is available by double arrows next to the map type.

![Download map menu Android](/assets/images/settings/download_map_menu_android.png) ![Regionwide maps Android](/assets/images/settings/regionwide_maps_menu.png)


## Download maps (Maps)

Find and download map data for offline using.

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.welmode_download_maps %} → {% data variables.android-values.download_tab_downloads %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.res_mapsres %}

Search button for findind needed map.

Tool bar of Device memory (how much is free)

Here available:
- {% data variables.android-values.extra_maps_menu_group %} - maps menu group of [Custom plugin](https://osmand.net/features/custom-package).
- {% data variables.android-values.regions %} / {% data variables.ios-values.res_worldwide %} - maps menu group for downloading [vector maps](/osmand/map/vector-maps), [vector maps](/osmand/map/vector-maps), [Contour lines maps and Terrain](/osmand/plugins/contour-lines), [Wikipedia offline data](/osmand/plugins/wikipedia) .
- {% data variables.android-values.world_maps %} - {% data variables.android-values.index_item_world_basemap %}
- {% data variables.android-values.nautical_maps %} - nautical maps of [Nautical plugin](/osmand/plugins/nautical-charts).
- {% data variables.android-values.wikivoyage_travel_guide %} (Android) - file of [Wikivoyage data](/osmand/plan-route/travel-guides).
- {% data variables.android-values.other_location %} (Android) - Voice prompts (TTS, recorded), Map fonts.

![Maps menu download Android](/assets/images/personal/maps/maps_menu_download_android.png) ![Maps menu download iOS](/assets/images/personal/maps/maps_menu_download_ios.png)

## Local maps

Folder with saved map data (Vector and Raster) on your device.

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.welmode_download_maps %} → {% data variables.android-values.download_tab_local %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.res_mapsres %} → {% data variables.ios-values.download_tab_local %}

Android (top of the screen):
- &#10227; button - refresh all data
- Delete button  - delete chosen map.
- &#8285; - {% data variables.android-values.local_index_mi_backup %} or {% data variables.android-values.local_index_mi_restore %} chosen maps.

### Vector data

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.welmode_download_maps %} → {% data variables.android-values.download_tab_local %} → {% data variables.android-values.local_indexes_cat_map %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.res_mapsres %} → {% data variables.ios-values.download_tab_local %} → {% data variables.ios-values.res_mapsres %} and {% data variables.ios-values.res_world_map %}

![Maps menu Local vector Android](/assets/images/personal/maps/maps_menu_local_vector_android.png) ![Maps menu Local vector iOS](/assets/images/personal/maps/maps_menu_local_vector_ios.png)

Info: name of map, size of map, type of map (for iOS: raster data here like Hillshades, Slopes), date of creating map (Android)

Actions with map data:
- Green color of map icon (Android) - fresh map data.
- Orange color of map icon (Android) - needed to update map.
- &#8285; button (Android) - {% data variables.android-values.local_index_mi_backup %}, {% data variables.android-values.shared_string_rename %}, {% data variables.android-values.shared_string_delete %} chosen map.
- icon &#8560; (iOS) - fresh map data.
- icon 'Update' (iOS) - needed to update map.
- &#8250; button (iOS) - open Details menu with next info: type of map, size of map, data creation of map. And action button - Delete map.


### {% data variables.android-values.local_indexes_cat_tile %}

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.welmode_download_maps %} → {% data variables.android-values.download_tab_local %} → {% data variables.android-values.local_indexes_cat_tile %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.res_mapsres %} → {% data variables.ios-values.download_tab_local %} → {% data variables.ios-values.online_raster_maps %}

![Maps menu Local raster Android](/assets/images/personal/maps/maps_menu_local_raster_android.png) ![Maps menu Local raster iOS](/assets/images/personal/maps/maps_menu_local_raster_ios.png)

Info: name of maps, type of raster map (Android), size of map.

Actions with map data:
- &#8285; button (Android) - {% data variables.android-values.local_index_mi_backup %}, {% data variables.android-values.shared_string_rename %}, {% data variables.android-values.shared_string_delete %} chosen map.
- &#8250; button (iOS) - open Details menu with info (type of map, size of map, data creation of map) and 'Actions' buttons - [Clear cache](/osmand/map/raster-maps#clear-raster-map-cache), [Edit map](/osmand/map/raster-maps#change-raster-map-parameters), Delete map.

### Contour lines, Wikipedia, Travel guides (Android)

Data of [Contour lines plugin](/osmand/plugins/contour-lines), [Wikipedia](/osmand/plugins/wikipedia), [Travel guides](/osmand/plan-route/travel-guides)

{% data variables.android-values.shared_string_menu %} → {% data variables.android-values.welmode_download_maps %} → {% data variables.android-values.download_tab_local %} → {% data variables.android-values.local_indexes_cat_tts %}, {% data variables.android-values.local_indexes_cat_voice %}

![Maps menu Local folders Android](/assets/images/personal/maps/maps_menu_local_folders_android.png)

Info: name of map, size of map, size of folder.

Action with map data:
- &#8285; button - {% data variables.android-values.shared_string_rename %}, {% data variables.android-values.shared_string_delete %} chosen map.

### Voice prompts (Android)

Data of [Voice prompts during navigation](/osmand/navigation).

{% data variables.android-values.shared_string_menu %} → {% data variables.android-values.welmode_download_maps %} → {% data variables.android-values.download_tab_local %} → {% data variables.android-values.download_srtm_maps %}, {% data variables.android-values.download_wikipedia_maps %}, {% data variables.android-values.download_maps_travel %}

![Maps menu Local voice prompts Android](/assets/images/personal/maps/maps_menu_local_voice_prompts_android.png)

Info: name of map, size of map.

Action with map data:
- &#8285; button - {% data variables.android-values.shared_string_rename %}, {% data variables.android-values.shared_string_delete %} chosen map.

### Deactivated (Android)

Here all maps, that were moved to deactivate.

![Maps menu Local Deactivate Android](/assets/images/personal/maps/maps_menu_local_deactivate_android.png)

Info: name of map, size of map, date of creation map.

Action with map data:
- &#8285; button - {% data variables.android-values.local_index_mi_restore %}, {% data variables.android-values.shared_string_rename %}, {% data variables.android-values.shared_string_delete %} chosen map.

## Update maps

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.welmode_download_maps %} → {% data variables.android-values.download_tab_updates %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.res_mapsres %} → {% data variables.ios-values.res_updates %}

![Maps menu Update maps Android](/assets/images/personal/maps/maps_menu_update_android.png) ![Maps menu Update maps  iOS](/assets/images/personal/maps/maps_menu_update_ios.png)

Click refresh &#10227; button for update info.

Info: name of map, size of map, date of creation map (Android).

Actions:
- {% data variables.ios-values.res_update_all %} button - update all maps.
- 'Update' button - update chosen map.

## OsmAnd Live

OsmAnd live data - hourly update maps ([paid OsmAnd feature](/osmand/purchases)).

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.welmode_download_maps %} → {% data variables.android-values.download_tab_updates %} → {% data variables.android-values.live_updates %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.res_mapsres %} → {% data variables.ios-values.osmand_live_title %}

**Menu of Live Update**

![Maps menu OsmAnd live Android](/assets/images/personal/maps/maps_menu_osmand_live_android.png) ![Maps menu OsmAnd live  iOS](/assets/images/personal/maps/maps_menu_osmand_live_ios.png)

Button of Enabled or not Live Updates

Click to:
- Blue switcher (Android) - adding chosen map for live update.
- &#8230; (Android) - Parameters menu for Live update.
- '&#43;' (iOS) - adding chosen map for live update.
- &#8250; (iOS) - Parameters menu for Live update.

**Parameters for Live Update**

![Maps menu OsmAnd live edit Android](/assets/images/personal/maps/maps_menu_osmand_live_edit_android.png) ![Maps menu OsmAnd live edit iOS](/assets/images/personal/maps/maps_menu_osmand_live_edit_ios.png)

Info: name of map, last updated (Android), last time checked (Android).

Actions:
- Enabled or not
- {% data variables.android-values.update_frequency %} - Hourly, Daily, Weekly.
- {% data variables.android-values.only_download_over_wifi %} - updating only with wi-fi connection.
- {% data variables.android-values.updates_size %} - info about downloaded map cache. Delete (Android) button downloading data of OsmAnd live.
- {% data variables.android-values.update_now %} - update now chosen map.


## Purchases (iOS)

Link to [Purchases iOS](/osmand/purchases/ios)

![Maps menu Purchases iOS](/assets/images/personal/maps/maps_menu_purchases_ios.png)

Plugins Part - bought plugins.

Maps Part- bought maps.

Button - Restore all purchases
