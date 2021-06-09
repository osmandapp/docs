---
title: "Map Context menu"
intro: "'Map Context menu' provides information of selected object on the map and allows to share, to edit, to move or to navigate to this place."
versions: '*'
---
{% data reusables.general.article-not-complete %}

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

![Actions menus](/assets/images/map/actions_menus_android.png) ![Video list](/assets/images/map/actions_menus_ios.png)


### Add / Edit Favorite

![Add Edit favorite action Android](/assets/images/map/add_favorite_android.png) ![Add Edit favorite action iOS](/assets/images/map/add_favorite_ios.png)

In the context menu there are options to **add** or to **edit** the selected point / object to the [favorites list](/osmand/personal/myplaces). 
- In order to **add**, you need to select a point / object, click on the 'Star' icon (with signature Add) and enter all the necessary information. 
- In order to **edit** information about favorite point you need to turn on 'Show on the map' (Menu → Me places → Favorites) then press on it and in the Context menu instead of 'Star' icon will appear 'Pancil icon' (with signature Edit).

- [{% data variables.android-values.add_edit_favorite %}](/osmand/personal/myplaces)  - adds a selected point to the favorites list.

### Add / Edit Marker

![Add Edit marker action Android](/assets/images/map/add_marker_android.png) ![Add Edit marker action iOS](/assets/images/map/add_marker_ios.png)

It is possible to mark a point or an object in order to make it easier to plan navigation. You just need to click on the 'flag' icon in the menu (Android), 'arrow' (iOS) - displays direction and distance to the selected point from your current location.

Actions:
- [{% data variables.android-values.shared_string_marker %} / {% data variables.android-values.edit_map_marker %}](/osmand/personal/markers) - puts a new marker on the selected point.
- 'Mark passed' (Android) / Dismiss (iOS) - deactivates marker and puts it to the History.
- 'Make active' (Android) - moves marker to the top position (on the top panel).
- 'Restore marker' (Android) - moves marker from History to active list.

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

It is possible to create navigation To/From chosen point on the map using next Actions of Map Context menu.

- [{% data variables.android-values.get_directions %}](/osmand/widgets/map-buttons#directions) - allows you to plan route from your location to the selected point (or reverse) by clicking the 'Direction' button.
- {% data variables.android-values.context_menu_item_directions_from %} - makes the chosen point as departure point for navigation.

### Search nearby

![Search action Android](/assets/images/map/action_search_android.png) ![Search action iOS](/assets/images/map/action_search_ios.png)

For [starting search](/osmand/search) near chosen point you need to use next Action. 

- {% data variables.android-values.context_menu_item_search %} - opens seach menu and searches near the chosen point.

### Avoid road

![Avoid action Android](/assets/images/map/action_avoid_android.png)

This action adds a point on the road which would be avoided during routing. The routing algorithm of OsmAnd won't build a route through this point.

- {% data variables.android-values.avoid_road %} - allows to mark place that you would like to avoid for [navigation](/osmand/navigation/route-navigation).

### Change objects position

![Action Change position Android](/assets/images/map/action_change_position_android.png) ![Action Change position iOS](/assets/images/map/action_change_position_ios.png)

This action allows you to change the location for your points (Marker, Favorite, Created POI, Audio/Video Note or Track Waypoint). Click to this action for choose point and move your screen for new location.

- {% data variables.android-values.change_markers_position %} - moves selected Marker, Favorite, Created POI, Audio/Video Note or Track Waypoint  to another location.

### Plan a route

![Action Plan a route Android](/assets/images/map/action_plan_route_android.png)

Opens ['Plan a route'](/osmand/plan-route/create-route) tool with the selected point as the first point.

- {% data variables.android-values.plan_a_route %} - opens ["Plan a route"](/osmand/plan-route/create-route) tool and select chosen point as the beginning of a route.

### Update / Download Online Maps

![Action Download online map Android](/assets/images/map/action_download_online_map_android.png) ![Action Download online map iOS](/assets/images/map/action_download_online_map_ios.png)

Action is for download and update online maps (tiles). Full instruction about it read [here](/osmand/map/raster-maps#download--update-tiles). 

- {% data variables.android-values.shared_string_download_map %} - allows downloading online map (tiles) in the buffer for using in offline.
- {% data variables.android-values.update_tile %} - allows udating online map (tiles).

### Update / Download Vector Maps

![Action Download vector map Android](/assets/images/map/action_download_vector_map_android.png) ![Action Download vector map iOS](/assets/images/map/action_download_vector_map_ios.png)

Action allows [updating or downloading OsmAnd maps (vector and terrain)](/osmand/start-with/download-maps) by clicking to the map  using special buttons on Map Context menu. 

For **Android** clicking on the map for Zoom 3-7. There is next information in the Map Context menu: name, type and size of a choosing map data.:

- {% data variables.android-values.shared_string_download %} - allows to download a map of selected region.
- {% data variables.android-values.shared_string_update %} - allows to update a map of selected region.
- {% data variables.android-values.live_update %} - starts to update [a live map](osmand/personal) of selected region.
- {% data variables.android-values.download_select_map_types %} - opens the dialogue for choosing any data like [terrain maps](/osmand/plugins/contour-lines#terrain-settings), [contour lines](/osmand/plugins/contour-lines#contour-lines-settings), [wikipedia](/osmand/plugins/wikipedia) of selected region for download.

Clicking to '{% data variables.android-values.rendering_category_details %}' button opens additional information about a map and a region of download: type and size of a map, link to a countre (region) wikipedia page, creating day of a map, population of a country.


For **iOS**, there is button for downloading a map of region in Map context menu. By clicking to this button start to download a map.


### * Add Parking

![Action Parking Android](/assets/images/map/action_parking_android.png) ![Action Parking iOS](/assets/images/map/action_parking_ios.png)

To designate the selected point as [a parking position](/osmand/plugins/parking).

- [{% data variables.android-values.context_menu_item_add_parking_point %}](/osmand/plugins/parking) - makes or edits the chosen point as parking position.

### * Add Track waypoint

![Action Waypoint Android](/assets/images/map/action_waypoint_android.png) ![Action Waypoint iOS](/assets/images/map/action_waypoint_ios.png)

In order to make chosen point like a waypoint for [a track from a visible tracks list](/osmand/map/tracks-on-map#tracks-on-the-map-layers).

- {% data variables.android-values.context_menu_item_add_waypoint %} - makes selected point to a track as a waypoint.

### * Create / Modify POI

![Action POI Android](/assets/images/map/action_poi_android.png) ![Action POI iOS](/assets/images/map/action_poi_ios.png)

In OsmAnd user can create POI in the chosen place and modify chosen POI. For this user need to enable ['OpenStreetMap editing' plugin](/osmand/plugins/osm-editing). All modified or creating data keep saved on [OpenStreetMap](https://www.openstreetmap.org/).

{% data variables.android-values.context_menu_item_create_poi %} - allows [to create POI](/osmand/plugins/osm-editing#how-to-add-poi) in a chosen point.

{% data variables.android-values.poi_context_menu_modify %} - allows [to modify chosen POI](/osmand/plugins/osm-editing#how-to-modify-poi).

### * Open OSM Note

![Action Note Android](/assets/images/map/action_note_android.png) ![Action Note iOS](/assets/images/map/action_note_ios.png)

An user can report about the mistakes on the map to [OpenStreetMap](https://www.openstreetmap.org/). For adding [OSM Note](/osmand/plugins/osm-editing#how-to-report-a-mistake) in a chosen point, an user need to enable ['OpenStreetMap editing' plugin](/osmand/plugins/osm-editing). 

- [{% data variables.android-values.context_menu_item_open_note %}](/osmand/plugins/osm-editing) - adds [OSM note](https://wiki.openstreetmap.org/wiki/Notes) for to [OpenStreetMap](https://www.openstreetmap.org/).


### * Audio-Video (Android)

![Action Audio-Video Android](/assets/images/map/action_av_note_android.png)

Assign selected point as audio/video/photo point.

- {% data variables.android-values.recording_context_menu_arecord %} - makes a [audio note](/osmand/map/point-layers-on-map#audio--video-notes-on-the-map) on selected point (creates new point on the overlay with audio icon).
- {% data variables.android-values.recording_context_menu_vrecord%} - makes a [video note](/osmand/map/point-layers-on-map#audio--video-notes-on-the-map) on selected point (creates new point on the overlay with video icon).
- {% data variables.android-values.recording_context_menu_precord %} - makes a [photo point](/osmand/map/point-layers-on-map#audio--video-notes-on-the-map) on the map.



## Customize (Android advanced)

It is a menu where the user can reorder or hide items from the 'Context menu actions', to see hidden items from the menu, copy the list of items from the another profile and reset to default settings. 

Android users can reset to default configuration of the Context menu or copy configuration of the Context menu from another profile.

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %} → {% data variables.android-values.ui_customization %} → {% data variables.android-values.context_menu_actions %}

![Context menu actions items ](/assets/images/map/customize_actions_menu.png)

 
