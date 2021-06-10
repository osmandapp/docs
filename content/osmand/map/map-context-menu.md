---
title: "Map Context menu"
intro: "'Map Context menu' provides information of selected object on the map and allows to share, to edit, to move or to navigate to this place."
versions: '*'
---

## Context menu 
In order to open Context menu you should tap on the object on the Map. There are two types of map contet menu: selecting an object - by short tap, selecting any precise point on the map - by long tap.

### Select an object (short tap)
Context menu will appear when you **short tap** on the marked object on the Map. In this case context menu provides you the information of the object name & icon (how it is marked on the map),  address, distance and direction from your current position. By this method you can select POI, Favorite, Transport stop, Marker or Map Object.

**Note**: Selectable map objects are OpenStreetMap [node](https://wiki.openstreetmap.org/wiki/Node) or [way](https://wiki.openstreetmap.org/wiki/Way).

![Context menu Android](/assets/images/map/map_context_menu_short_tap_android.png) ![Context menu iOS](/assets/images/map/map_context_menu_short_tap_ios.png) 

### Select any point (long tap)
Context menu will appear when you hold at any point on the Map with **long tap**. In this case context menu provides you the information of geographical point address, distance and direction from your current position. 

![Context menu long_tap_Android](/assets/images/map/map_context_menu_long_tap_android.png) ![Context menu long_tap_iOS](/assets/images/map/map_context_menu_long_tap_ios.png)

### Select route (short tap for Android)

Short tap to a GPX-track on the map  opens [Context track menu](/osmand/map/tracks-on-map#context-track-menu-android).

![Context track menu Android](/assets/images/map/context_track_menu_Android.png)

### Hide context menu

To hide the context menu:
- Click on any empty place (to not open menu once again) on the map
- Drag down by the top of menu 

## Details
In order to gain more details about object you need to click on the "Details" button in the Context menu or move the panel up. 

![Context menu Android](/assets/images/map/context_menu_android.png) ![Context menu iOS](/assets/images/map/context_menu_ios.png)
 
### Object info

 This panel includes additional information about the object. This info could be copied to the buffer by tap on it. Additional information about object includes:

- [Coordinates](/osmand/map/map-context-menu#coordinates)
- [Nearby Wikipedia articles](/osmand/map/map-context-menu#nearby-pois-wikipedia)
- [Nearby POI](/osmand/map/map-context-menu#nearby-pois-wikipedia)
- [Public Transport routes (on transport stops)](/osmand/map/map-context-menu#public-transport-routes)
- [Favorites / Track Points from the same group](/osmand/map/map-context-menu#favorites--track-points-from-the-group)
- [OpenStreetMap link](/osmand/map/map-context-menu#openstreetmap-link)
- [Article image / description](/osmand/map/map-context-menu#article-image--description)
- [Online photos](/osmand/map/map-context-menu#online-photos)
- [OpenStreetMap Details](https://wiki.openstreetmap.org/wiki/Map_features)
    - [Alternative names](https://wiki.openstreetmap.org/wiki/Names)
    - [Website](https://wiki.openstreetmap.org/wiki/Key:website)
    - [Phone number](https://wiki.openstreetmap.org/wiki/Key:contact)
    - [Working hours](https://wiki.openstreetmap.org/wiki/Key:opening_hours)
    - [Fee](https://wiki.openstreetmap.org/wiki/Key:fee)
    - [Accessibility](https://wiki.openstreetmap.org/wiki/Key:wheelchair)
    - [Width](https://wiki.openstreetmap.org/wiki/Key:width) / [Height](https://wiki.openstreetmap.org/wiki/Key:height)
    - etc.

### Coordinates 
In the Context menu you can find geographical coordinates of an object. If you expand this section, you will see location in various geo formats and shareable OsmAnd Link. If you click on any item it will be automatically copied to the clipboard. 

|Coordinates format||
|:------|:------|
|• DDD.DDDDD (Plain Decimal Degress) <br> • DDD.DDDDD (N/S, E/W comma) <br> • DDD MM.MMM <br> • DDD MM SS.S <br> • [UTM Standard](https://en.wikipedia.org/wiki/Universal_Transverse_Mercator_coordinate_system)  <br> • [MGRS](https://en.wikipedia.org/wiki/Military_Grid_Reference_System) <br> • [Open Location Code](https://en.wikipedia.org/wiki/Open_Location_Code) <br> • [OsmAnd Web Link](https://osmand.net/go.html) |![Coordinates](/assets/images/map/map_context_menu_Coordinates.png)|

With OsmAnd Web Link you can send location to any device and it will be automatically recognized by OsmAnd (for example: https://osmand.net/go?lat=-49.306051764139475&lon=69.13371469678623&z=10).

### Nearby POIs/ Wikipedia

These sections displays nearby [Wikipedia articles](/osmand/plugins/wikipedia) or [Points of Interest](/osmand/map/point-layers-on-map#points-of-interest-pois-on-the-map) with '{% data variables.android-values.shared_string_show_on_map %}' and '{% data variables.android-values.search_more %}' to display and [search](/osmand/search/search-poi) all other POI & Wikipedia articles.

Clicking to 'Nearby POIs/ Wikipedia articles' opens a points list (Wikipedia and POIs). A tap to one of these points from a point list moves the map to this point (POI or Wikipedia) with the opening point Map Context menu.

**Note**: [{% data variables.android-values.wiki_around %}](/osmand/plugins/wikipedia) will appear only if you previously downloaded special maps with [Wikipedia articles for this area](/osmand/plugins/wikipedia#download-wikipedia).

![Nearby Wikipedia articles](/assets/images/map/map_context_menu_nearby_wikipedia.png) ![Nearby Wikipedia articles](/assets/images/map/map_context_menu_nearby_wikipedia_1.png)

### Public Transport Routes

Shown info about Public transport routes for chosen Transport stop. Information about Public transport Context menu and actions with it read [here](/osmand/map/public-transport#transport-routes-context-menu).

![Public transport Routes Android](/assets/images/map/pt_routes_android.png) ![Public transport Routes iOS](/assets/images/map/pt_routes_ios.png) 

### Favorites / Track Points from the group

This is a list of all points in one group for a [Favorite](/osmand/map/point-layers-on-map#favorites-on-the-map) or Waypoint. By clicking, the entire list of points of one group expands, when clicking on a point from the list, the map moves to the selected point.

![Favorite list](/assets/images/map/favorite_list_android.png) ![Favorite list full](/assets/images/map/favorite_list_full_android.png) 

### Article description

This part contains a part of the description from [Wikipedia article](/osmand/plugins/wikipedia), [Favorite](/osmand/personal/favorites) or Waypoint description, by clicking you can open full description.

![Description list](/assets/images/map/description_list_android.png) ![Description list](/assets/images/map/description_list_ios.png)

### OpenStreetMap link

OpenStreetMap link provides direct link to the OpenStreetMap object where you can find complete information about it (https://www.openstreetmap.org/node or https://www.openstreetmap.org/way).

![OSM link](/assets/images/map/context_menu_osm_link.png) ![OSM link](/assets/images/map/context_menu_osm_link_1.png)

### Online photos 

In this section, you can view photos of the object from different sources web sources. Such as [Mapillary](/osmand/plugins/mapillary) - takes the best and the closest photos from Street-Level view, [OpenPlaceReviews](/osmand/plugins/openplacereviews) - takes photos associated with this object, [Wikimedia](https://www.wikimedia.org/) - takes urls from OpenStreetMap tags **image**, **wikimedia**. Click on the image to open in full size or [browse](/osmand/map/point-layers-on-map#street-level-imagery) street level photos.

![Online photos context menu](/assets/images/map/context_menu_online_photo.png) ![Online photo wikimedia](/assets/images/map/context_menu_online_photo_1.png)

### * Audio/Video Note (Android)

[Audio / Video notes](/osmand/plugins/audio-video-notes) have additional information on Details Menu and buttons (Delete, Play, Show) in Context menu. 

For Image notes in the Details Menu an image is displayed; when you click on the image it opens in the editor. There is information about the date and the time when note was made. In the Context menu, there are 'Show' and 'Delete' buttons to open an image in the editor or delete it.
 
![Image list](/assets/images/map/image_list_android.png) ![Video list](/assets/images/map/video_list_android.png)

## Actions

It is a set of specific manipulations that can be performed on a point or object. This menu is split into two parts: visible section consists of maximum 3 actions and other actions are accessible by 'Actions' button. You can customize (Android) the order of actions in [General settings](#customize-android-advanced).

![Actions menu Android](/assets/images/map/actions_menu_android.png) ![Actions menu iOS](/assets/images/map/actions_menu_ios.png)
![Actions additional menu Android](/assets/images/map/actions_additional_menu_android.png) ![Actions additional menu iOS](/assets/images/map/actions_additional_menu_ios.png)


### Add / Edit Favorite

![Add Edit favorite action Android](/assets/images/map/add_favorite_android.png) ![Add Edit favorite action iOS](/assets/images/map/add_favorite_ios.png)

In the context menu there are options to **add** or to **edit** the selected point / object to the [favorites list](/osmand/personal/myplaces). 
- In order to **add**, you need to select a point / object, click on the 'Star' icon (with signature Add) and enter all the necessary information. 
- In order to **edit** information about favorite point you need to turn on 'Show on the map' (Menu → Me places → Favorites) then press on it and in the Context menu instead of 'Star' icon will appear 'Pancil icon' (with signature Edit).

- [{% data variables.android-values.add_edit_favorite %}](/osmand/personal/myplaces)  - adds a selected point to the favorites list.

### Add / Edit Marker

![Add Edit marker action Android](/assets/images/map/add_marker_android.png) ![Add Edit marker action iOS](/assets/images/map/add_marker_ios.png)

![Pass marker action Android](/assets/images/map/action_pass_marker_android.png) ![Restore marker action Android](/assets/images/map/action_restore_marker_android.png)

It is possible to mark a point or an object in order to make it easier to plan navigation. You just need to click on the 'flag' icon in the menu (Android), 'arrow' (iOS) - displays direction and distance to the selected point from your current location.

Actions:
- [{% data variables.android-values.shared_string_marker %} / {% data variables.android-values.edit_map_marker %}](/osmand/personal/markers) - puts a new marker on the selected point.
- 'Mark passed' (Android) / Dismiss (iOS) - deactivates marker and puts it to the History.
- 'Make active' (Android) - moves marker to the top position (on the top panel).
- 'Restore marker' (Android) - moves marker from History to active list.

Read more about [markers](/osmand/personal/markers).

### Share

![Share action Android](/assets/images/map/action_share_android.png) ![Share action iOS](/assets/images/map/action_share_ios.png)

The app provides the opportunity to **{% data variables.android-values.shared_string_share %}** location in a variety of ways. You can also share your location by selecting 'your location' icon on the map.

All options to share your location: 
- Send - sends a message via messengers (name, address, coordinates and link) 
- Copy - copies a message into clipboard (name, address, coordinates and link) 
- Copy address (Android) - copies a message into clipboard (only address) 
- Copy location/POI name (Android) - copies a message into clipboard (only name and coordinates) 
- Copy coordinates (Android) - copies a message into clipboard (only coordinates) 
- geo (Android) - opens local installed apps that support [geo url](https://developers.google.com/maps/documentation/urls/android-intents) 
- QR-code (Android) - generates location in QR-code (link with your location)
- Save Image (iOS) - saves a screenshot with map and selected point in the image gallery.
- Assign to Contact (iOS) - makes an icon for chosen contact from the map screenshot.
- Print (iOS) - opens Printer Options for printing the map screenshot.
- Save to files (iOS) - saves the map screenshot in iCloud Drive or storage of your device.

### Directions To / From 

![Directions Android](/assets/images/map/action_directions_android.png) ![Directions iOS](/assets/images/map/action_directions_ios.png)

![Multiple Directions Android](/assets/images/map/action_multiple_directions_android.png)

In order to start navigation or route planning, you need to select destination first with [{% data variables.android-values.get_directions %}](/osmand/widgets/map-buttons#directions). In case you already have a destination point, the menu will suggest you to replace the destnation point or to insert as another intermediate or start point. 

It is also possible to select 'From' Destination first via Map context menu ({% data variables.android-values.context_menu_item_directions_from %}).

**Note**: if you click "Start navigation" - 'From' point will be discarded as application enters in Navigation mode. In order to preserve a route, don't click "Start navigation" and [swipe down](#hide-context-menu)  "Route preparation" menu.

Read more about [navigation](/osmand/navigation/route-navigation).

### Search nearby

![Search action Android](/assets/images/map/action_search_android.png) ![Search action iOS](/assets/images/map/action_search_ios.png)

Via this context menu action it is possible to search around specific location on the map. 

Read more about [search](/osmand/search) functionality.

### Avoid road

![Avoid action Android](/assets/images/map/action_avoid_android.png) ![Avoid roads map](/assets/images/map/action_avoid_roads_list_android.png)

It is possible to add avoid roads at specific location, so selected roads will be avoided during the route planning. 

![Avoid delete action Android](/assets/images/map/context_menu_avoid_roads.png) ![Avoid roads list Android](/assets/images/map/action_avoid_delete_android.png) 

**Note**: avoid roads are global and used for all navigation profiles (except online routing). 

Read more about [navigation](/osmand/navigation/route-navigation).

### Change object position

![Action Change position Android](/assets/images/map/action_change_position_android.png) ![Action Change position iOS](/assets/images/map/action_change_position_ios.png)

![Action Change position UI Android](/assets/images/map/action_change_position_ui_android.png) ![Action Change position UI iOS](/assets/images/map/action_change_position_ui_iOS.png) 

Almost every created object by user is moveable i.e. Marker, Favorite, Created POI, Audio/Video Note or Track Waypoint. First select an object on the map and then use '{% data variables.android-values.change_markers_position %}' menu to move it to a new location.

### Plan a route

![Action Plan a route Android](/assets/images/map/action_plan_route_android.png)

You can start a route planning from a selected point via object context menu.

Read more about ['Plan a route'](/osmand/plan-route/create-route) tool.

### Update / Download Online Maps

![Action Download online map Android](/assets/images/map/action_download_online_map_android.png) ![Action Download online map iOS](/assets/images/map/action_download_online_map_ios.png)

To update or download online maps (tiles) at specific location, you can use object context menu: {% data variables.android-values.shared_string_download_map %} and {% data variables.android-values.update_tile %}. Please refer to [full instruction](/osmand/map/raster-maps#download--update-tiles). 

### Update / Download Vector Maps

![Action Download vector map Android](/assets/images/map/action_download_vector_map_android.png) ![Action Download vector map iOS](/assets/images/map/action_download_vector_map_ios.png)

![Select vector map worldwide on Android](/assets/images/map/download_region_map_via_worldmap.png)

In case there is no offline map present at selected location, for example map object menu was opened via Search or via specific Favorite, then the smallest possible offline map will be suggested to [download](/osmand/start-with/download-maps#download---map-context-menu).  

**Android**: If you already have [downloaded](/osmand/start-with/download-maps) OsmAnd maps (vector or terrain), it is possible to updated them via context 
menu. You will need to select the region on the map first - click on any location on worldwide zoom 3-7. 

**Note**: if you have opened context menu for map region (region is higlighted), you will be able to see '{% data variables.android-values.rendering_category_details %}' about it: type and size of a available map, link to a wikipedia page, language, population and other.

### * Add / Delete Parking point

![Action Parking Android](/assets/images/map/action_parking_android.png) ![Action Parking iOS](/assets/images/map/action_parking_ios.png)

![Action Delete Parking Android](/assets/images/map/context_menu_limited_parking.png) ![Action Delete Parking iOS](/assets/images/map/context_menu_limited_parking_ios.png) 

Any selected location on the map could be marked as [a parking position](/osmand/plugins/parking). In order to delete parking position, you can open context menu associated with parking location.

Requires [Parking position plugin](/osmand/plugins/parking).

### * Add Track waypoint

![Action Waypoint Android](/assets/images/map/action_waypoint_android.png) ![Action Waypoint iOS](/assets/images/map/action_waypoint_ios.png)

![Select Track to add Waypoint Android](/assets/images/map/action_select_track_to_add_waypoint_android.png) ![Select Track to add Waypoint iOS](/assets/images/map/action_select_track_to_add_waypoint_ios.png) 

It is possible to [add waypoints](/osmand/personal/tracks#add-waypoint) to any track at selected location via Map Context menu - {% data variables.android-values.context_menu_item_add_waypoint %} . By default waypoint is added to [currently recording track](/osmand/plugins/trip-recording#from-widget). Though if there are many [visible tracks](/osmand/map/tracks-on-map#tracks-on-the-map-layers) on the map, it will be suggested to select the track waypoint will be added to.

Requires [Trip recording plugin](/osmand/plugins/trip-recording).

### * Create / Modify POI

![Action POI Android](/assets/images/map/action_poi_android.png) ![Action POI iOS](/assets/images/map/action_poi_ios.png)

With OSM Editing plugin, you can create and modify most of the POIs present on [OpenStreetMap](https://www.openstreetmap.org/).

{% data variables.android-values.context_menu_item_create_poi %} - [creates a new POI](/osmand/plugins/osm-editing#how-to-add-poi) at selected location.

{% data variables.android-values.poi_context_menu_modify %} - [modifies selected POI](/osmand/plugins/osm-editing#how-to-modify-poi).

Requires [OSM Editing plugin](/osmand/plugins/osm-editing).

### * Open OSM Note

![Action Note Android](/assets/images/map/action_note_android.png) ![Action Note iOS](/assets/images/map/action_note_ios.png)

![Action Add Note Android](/assets/images/map/action_add_osm_note_ui_android.png) ![Action Add Note iOS](/assets/images/map/action_add_osm_note_ui_ios.png)

You can [report](/osmand/plugins/osm-editing#how-to-report-a-mistake) map data errors at specific location to [OpenStreetMap community](https://wiki.openstreetmap.org/wiki/Join_the_community). Please follow [guidelines](https://wiki.openstreetmap.org/wiki/Notes#Adding_notes) and add proper comments to an issue.

Requires [OSM Editing plugin](/osmand/plugins/osm-editing).

### * Comment / Close OSM Note

![Comment OSM Note Android](/assets/images/map/action_comment_note_android.png) ![Reopen OSM Note Android](/assets/images/map/action_reopen_note_android.png)

You can [comment](https://wiki.openstreetmap.org/wiki/Notes#Adding_notes), [resolve](https://wiki.openstreetmap.org/wiki/Notes#Resolving_notes) and reopen
OpenStreetMap Notes via objects context menu.

Requires [OSM Editing plugin](/osmand/plugins/osm-editing).

### * Upload POI / OSM Note

![Upload POI Android](/assets/images/map/action_poi_upload_android.png) ![Upload OSM Note Android](/assets/images/map/action_note_upload_android.png)

In case you use 'Offline mode' to add / edit POI or OSM Note, you will need to upload the changes to OpenStreetMap. By default 'Offline mode' is on to avoid accidental changes of public database. You can upload or delete change via created object context menu.

Requires [OSM Editing plugin](/osmand/plugins/osm-editing).

### * Record AV Note (Android)

![Action Audio-Video Android](/assets/images/map/action_av_note_android.png)

Records or takes a media note at selected point on the map.

- {% data variables.android-values.recording_context_menu_arecord %} - makes a [audio note](/osmand/map/point-layers-on-map#audio--video-notes-on-the-map) on selected point (creates new point on the overlay with audio icon).
- {% data variables.android-values.recording_context_menu_vrecord%} - makes a [video note](/osmand/map/point-layers-on-map#audio--video-notes-on-the-map) on selected point (creates new point on the overlay with video icon).
- {% data variables.android-values.recording_context_menu_precord %} - makes a [photo point](/osmand/map/point-layers-on-map#audio--video-notes-on-the-map) on the map.

Requires [Audio / Video note plugin](/osmand/plugins/audio-video-notes).

### * View / Delete AV Note (Android)

{% data reusables.general.article-not-complete %}

Requires [Audio / Video note plugin](/osmand/plugins/audio-video-notes).

## Customize (Android advanced)

It is possible to reorder or hide items from the '{% data variables.android-values.context_menu_actions %}'. You can move the most useful actions to the top 3 actions and setup whole menu independently for each profile. It is also possible to reset to default settings after all.


{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %} → {% data variables.android-values.ui_customization %} → {% data variables.android-values.context_menu_actions %}

![Context menu actions items ](/assets/images/map/customize_actions_menu.png)

 
