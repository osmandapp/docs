---
title: "Maps"
intro: "Maps screen allows you to do basic operations over online and offline maps used in OsmAnd such as downloading, removing, renaming, clearing the cache for online maps, updating and checking maps size."
versions: '*'
---

{% data reusables.general.article-not-complete %}


OsmAnd deals with 2 type of maps: [Vector maps](/osmand/map/vector-maps) and  [Raster maps](/osmand/map/raster-maps). All maps are stored in one place of the [Storage](/osmand/personal/storage) and it is accessible with external tools. 

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.welmode_download_maps %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.res_mapsres %}

{% default %}

![Maps menu Android](/assets/images/personal/maps/maps_menu_android.png) ![Download maps menu iOS](/assets/images/personal/maps/download_map_ios.png) 

{% enddefault %}

{% android %}

![Maps menu Android](/assets/images/personal/maps/maps_menu_android.png) ![Download maps menu Android](/assets/images/personal/maps/download_map_android.png) 

{% endandroid %}

{% ios %}

![Maps menu iOS](/assets/images/personal/maps/maps_menu_ios.png) ![Download maps menu iOS](/assets/images/personal/maps/download_map_ios.png)

{% endios %}

## Map types

There are several map types available to download and manage:
- Standard - a fully packaged OsmAnd map based on [OpenStreetMap](https://www.openstreetmap.org/) source, they provide map, routing, address, POI, public transport information, . 
- Roads-only (Android) - a smaller by size map comparing to Standard due to removed map details such as buildings & points on the map.
- [Coutour lines](/osmand/map/vector-maps#contour-lines) - a map that contains the elevation contour lines.
- [Hillshades](/osmand/map/raster-maps#hillshade--slope) - a raster map with hillshade information.
- [Slopes](/osmand/map/raster-maps#hillshade--slope) - a raster map with slopes information. 
- [Online and cached tile maps](/osmand/map/raster-maps) - a custom map source for online maps, could be installed as 3rd party map or as OsmAnd Tiles. 
- [Wikipedia](/osmand/plugins/wikipedia) - a vector map that provides Geo located Articles as POIs from [Wikipedia](https://wikipedia.org/).
- [Travel guides / Wikivoyage](/osmand/plan-route/travel-guides) - a vector map that has a collection of Articles (Text as HTML + GPX file) for example [Wikivoyage](https://www.wikivoyage.org/).
- [Nautical maps](/osmand/plugins/nautical-charts) - a vector map that provide sea depth elevation as points or as lines.
- [Voice packages](/osmand/navigation/voice-navigation) - a voice package that provides sounds and configuration how to guide you in the navigation mode.
- [Map fonts (Android)](/osmand/map/vector-maps#map-fonts-android) - additional fonts files used to render text on the map.
- [Altitude correction (Android)](/osmand/widgets/info-widgets#altitude) - a special map file that provides correction for geoid on Android devices (optional).
- Other maps - maps that couldn't be attached to current maps hierarchy, typically represents deprecated and not supported maps or maps that will be available next release.

**Note**: For regions like Germany consisted of many maps, you can use bulk map downloads, it is depicted as double download arrows next to the map type.

![Download map menu Android](/assets/images/settings/download_map_menu_android.png) ![Regionwide maps Android](/assets/images/settings/regionwide_maps_menu.png)


## Download maps (Maps)

{% data reusables.general.android-ios-switcher %}

Download maps screen allows you to download maps from OsmAnd servers, you will need an active internet connection to do that.

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.welmode_download_maps %} → {% data variables.android-values.download_tab_downloads %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.res_mapsres %}

{% default %}

![Download map menu general iOS](/assets/images/personal/maps/download_map_menu_ios.png) ![Download map menu general Android](/assets/images/personal/maps/download_map_menu_1_android.png) 

{% enddefault %}

{% android %}

![Download map menu general Android](/assets/images/personal/maps/download_map_menu_android.png) ![Download map menu general Android](/assets/images/personal/maps/download_map_menu_1_android.png) 

{% endandroid %}

{% ios %}

![Download map menu general iOS](/assets/images/personal/maps/download_map_menu_ios.png) ![Download map menu general iOS](/assets/images/personal/maps/download_map_menu_1_ios.png)

{% endios %}

**Actions**:
- Refresh &#10227; - redownloads list of available maps from OsmAnd Server.
- Search -  allows you to search maps by **Country**, **Province** or by a large **City**. 
- Toolbar indicates how much memory is available to download and how much maps is available to download for free.

**Hint**: a small Worldwide map is builtin inside OsmAnd, you don't need to download a large Worldwide map if you plan to have detailed maps for region. In case you want to have map that covers full planet including major cities, roads & rivers, you can download **_Detailed worldwide map_**.

## Local maps

{% data reusables.general.android-ios-switcher %}

Local maps represents all downloaded maps on device grouped by [Types](#map-types)

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.welmode_download_maps %} → {% data variables.android-values.download_tab_local %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.res_mapsres %} → {% data variables.ios-values.download_tab_local %}

{% default %}

![Maps menu Local vector Android](/assets/images/personal/maps/maps_menu_local_vector_android.png) ![Maps menu Local vector iOS](/assets/images/personal/maps/maps_menu_local_vector_ios.png)

{% enddefault %}

{% android %}

![Maps menu Local vector Android](/assets/images/personal/maps/maps_menu_local_vector_android.png) 

{% endandroid %}

{% ios %}

![Maps menu Local vector iOS](/assets/images/personal/maps/maps_menu_local_vector_ios.png)

{% endios %}

**Multifile Actions**.
- &#10227; button - scans & refreshes list of available maps on storage.
- Delete button  - Multiselection to delete maps.
- &#8285; - {% data variables.android-values.local_index_mi_backup %} or {% data variables.android-values.local_index_mi_restore %} - multiselection to deactivate and activate [maps](#deactivate-maps-android).

Each map displays its name, size, creation date  within a certain category and highligted by a **color**.
- Green - map is up to date.
- Orange - there is an update available for the map.
- Grey / Italic - map is deactivated 

For each **map specific actions** are available by clicking 3 dots or long tap on the row.
- Rename - changes name of the file and map
- Update - updates map to the latest available version
- Delete - deletes map
- Edit (Online maps) - edits online map configuration
- Clear all tiles cache (Online maps) - clear all the tiles cached by online map.

### Deactivate Maps (Android)

It's possible to deactivate vector maps, so they will be present on the device but will not be used for map display, search and routing. It's optimal to have large storage of maps and use them when they are needed without slowing down OsmAnd functionality.

![Maps menu Local Deactivate Android](/assets/images/personal/maps/maps_menu_local_deactivate_android.png) ![Maps menu Local Deactivate Android](/assets/images/personal/maps/maps_menu_local_deactivate_1_android.png)

Local action available for the map: **{% data variables.android-values.local_index_mi_restore %}** / **{% data variables.android-values.local_index_mi_backup %}**.

## Update maps

{% data reusables.general.android-ios-switcher %}

Every month you will be able to update OsmAnd Maps on Updates screen. Here it's possible to update all maps with one click. Standard and road-only maps are avalaible every month typically with 2 weeks delay. In case you would like to get access to Hourly updates, please check [OsmAnd Live](#osmand-live).

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.welmode_download_maps %} → {% data variables.android-values.download_tab_updates %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.res_mapsres %} → {% data variables.ios-values.res_updates %}

{% default %}

![Maps menu Update maps Android](/assets/images/personal/maps/maps_menu_update_android.png)  ![Maps menu Update maps iOS](/assets/images/personal/maps/maps_menu_update_ios.png)

{% enddefault %}

{% android %}

![Maps menu Update maps Android](/assets/images/personal/maps/maps_menu_update_android.png) 

{% endandroid %}

{% ios %}

![Maps menu Update maps iOS](/assets/images/personal/maps/maps_menu_update_ios.png)

 {% endios %}

## OsmAnd Live

OsmAnd Live is a special ([available by subscription](/osmand/purchases)) feature that provides additional small map updates on top of the large complete monthly maps. It is roughly estimated that map updates for 1 month takes only 2-4% of complete map size. These updates are generated approximately every 15 minutes on OsmAnd Servers and could be downloaded hourly / daily or weekly. On Android they could be downloaded in the background though it doesn't work correctly on all devices. The app restart always checks if there are pending updates and downloads them. 

Each map has independent collection  of tiny map updates, please be aware if you have overlapping map regions. In case you want to revert to initial state you can switch off updates and 'Clear cache'.

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.welmode_download_maps %} → {% data variables.android-values.download_tab_updates %} → {% data variables.android-values.live_updates %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.res_mapsres %} → {% data variables.ios-values.osmand_live_title %}

{% data reusables.general.android-ios-switcher %}

{% default %}

![Maps menu OsmAnd live Android](/assets/images/personal/maps/maps_menu_osmand_live_android.png) ![Maps menu OsmAnd live edit Android](/assets/images/personal/maps/maps_menu_osmand_live_edit_android.png)

{% enddefault %}

{% android %}

![Maps menu OsmAnd live Android](/assets/images/personal/maps/maps_menu_osmand_live_android.png) ![Maps menu OsmAnd live edit Android](/assets/images/personal/maps/maps_menu_osmand_live_edit_android.png)

{% endandroid %}

{% ios %}

![Maps menu OsmAnd live  iOS](/assets/images/personal/maps/maps_menu_osmand_live_ios.png) ![Maps menu OsmAnd live edit iOS](/assets/images/personal/maps/maps_menu_osmand_live_edit_ios.png)

{% endios %}

**Understanding timestamps**.
- ```Latest OpenStreetMap update available``` XX-XX-XXXX XX:XX - represents the latest timestamp of OpenStreetMap changes processed on OsmAnd Servers and available to be downloaded.
- ```Andorra Updated```: Today XX:XX - represents the timestamp of the latest changes inside the local. It's always earlier than ```Latest OpenStreetMap update available``` (but not always equal) and represents specific timestamp for  ```Andorra``` region. If ```Updated timestamp``` is not changed after ```{% data variables.android-values.update_now %}``` then it is the latest timestamp when ```Andorra``` region was modified and processed on OsmAnd servers.
- ```Andorra Last time checked```: Today XX:XX - represents the latest timestamp that local device checked if new updates are available. It's always ahead of updated timestamps and displays both successful and unsuccessful attempts to download maps.


**OsmAnd Live restrictions**.
- Address changes on the map & in the search are not supported yet. Address information could be updated with regular monthly updates.
- Updated roads don't have altitude information thus the slope graphics could be affected.
- Modified and deleted route relations are not handled correctly which could lead to display of no longer existing public transport lanes and hiking routes.
