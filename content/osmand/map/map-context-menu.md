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

### Hide context menu

To hide the context menu:
- Click on any empty place (to not open menu once again) on the map
- Drag down by the top of menu 

## Details
In order to gain more details about object you need to click on the "Details" button in the Context menu or move the panel up. 

![Context menu Android](/assets/images/map/context_menu_Android.png) ![Context menu iOS](/assets/images/map/context_menu_iOS.png)
 
### Object info
 This panel includes additional information about the object. This info could be copied to the buffer by tap on it. Additional information about object includes:

- Coordinates
- Nearby Wikipedia articles
- Nearby POI
- Public Transport routes (on transport stops)
- Favorites / Track Points from the same group
- OpenStreetMap link
- Article image / description
- Online photos
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
|------|------|
|• DDD.DDDDD (Plain Decimal Degress) <br> • DDD.DDDDD (N/S, E/W comma) <br> • DDD MM.MMM <br> • DDD MM SS.S <br> • [UTM Standard](https://en.wikipedia.org/wiki/Universal_Transverse_Mercator_coordinate_system)  <br> • [MGRS](https://en.wikipedia.org/wiki/Military_Grid_Reference_System) <br> • [Open Location Code](https://en.wikipedia.org/wiki/Open_Location_Code) <br> • [OsmAnd Web Link](https://osmand.net/go.html) |![Coordinates](/assets/images/map/map_context_menu_Coordinates.png)|

With OsmAnd Web Link you can send location to any device and it will be automatically recognized by OsmAnd.

### Nearby POIs/ Wikipedia

These sections displays nearby Wikipedia articles or Points of Interest with '{% data variables.android-values.shared_string_show_on_map %}' and '{% data variables.android-values.search_more %}' to display and search all other POI & wikipedia articles.

**Note**: [{% data variables.android-values.wiki_around %}](/osmand/plugins/wikipedia) will appear only if you previously downloaded special maps with Wikipedia articles for this area.

*** Update screenshot ***

![Nearby Wikipedia articles](/assets/images/map/map_context_menu_Nearby_Wikipedia.png)

### Public Transport Routes

{% data reusables.general.article-not-complete %}

### Favorites / Track Points from the group

{% data reusables.general.article-not-complete %}

### Article image / description

{% data reusables.general.article-not-complete %}

![Nearby Wikipedia articles](/assets/images/map/map_context_menu_Nearby_Wikipedia.png)


### OpenStreetMap link

OpenStreetMap link provides direct link to the OpenStreetMap object where you can find complete information about it (https://www.openstreetmap.org/node or https://www.openstreetmap.org/way).

*** Split screenshot ***

![OSM link](/assets/images/map/context_menu_OSM_link.png)

### Online photos 

In this section, you can view photos of the object from different sources web sources. Such as [Mapillary](/osmand/plugins/mapillary) - takes the best and the closest photos from Street-Level view, [OpenPlaceReviews](/osmand/plugins/openplacereviews) - takes photos associated with this object, [Wikimedia](https://www.wikimedia.org/) - takes urls from OpenStreetMap tags **image**, **wikimedia**. Click on the image to open in full size.

![Online photo](/assets/images/map/context_menu_Online_photo.png)

## Actions

It is a set of specific manipulations that can be performed on a point or object. This menu is split into two parts: visible section consists of maximum 3 actions and other actions are accessible by 'Actions' button. You can customize the order of actions in [General settings](#customize-android-advanced).

*** Update screenshot ***


### Add / Edit Favorite

In the context menu there are options to **add** or **edit** the selected point / object to the [favorites list](/osmand/personal/myplaces). 
- In order to **add**, you need to select a point / object, click on the 'Star' icon (with signature Add) and enter all the necessary information. 
- In order to **edit** information about favorite point you need to turn on 'Show on the map' (Menu → Me places → Favorites) then press on it and in the Context menu instead of 'Star' icon will appear 'Pensil icon' (with signature Edit).

- [{% data variables.android-values.add_edit_favorite %}](/osmand/personal/myplaces)  - adds a selected point to the favorites list.

### Add / Edit Marker

It is possible to mark a point or object in order to make it easier to plan navigation using the marked point. To do this, you just need to click on the point and put flag on this place. The context menu will display the name of the marker, the distance from your current position and the "marker passed" and "make active" buttons.
- 'Mark passed' is deactivate marker from the map and relocate it to the History.
- 'Make active' is turned this marker to the active status and makes visible (on the top panel) information about the name of the marker and distance from your current position.
- Restore marker - is an additional option in the Map marker menu to return passed marker from the history list to the active Marker list.

- [{% data variables.android-values.shared_string_marker %} / {% data variables.android-values.edit_map_marker %}](/osmand/personal/markers) - put marker on the selected point.

### Share

The app provides the opportunity to share your location in a variety of ways. To see all options to share location you need to select point then on the Context menu press share and select the best way for it. 
All options to share your location: 
- Send - you can send it like a message via any messenger or cloud service.
- Copy - all information about the location (name of the street, coordinates and link) will be copied to the clipboard 
- Copy address - only address will copy to the clipboard (name of the street, house number if it marked and city name)
- Copy location/POI name - if you press on the POI icon the name of the POI will be copied, if you press on any other point of the map address will be copied to the clipboard.
- Copy coordinates - allows copying only coordinates of the selected point  to the clipboard
- geo- give you an opportunity to open a location via any Map app
- QR-code - allows generating your location in QR-code, you can scan it or share  another user
- **{% data variables.android-values.shared_string_share %}** - shares a selected point with another user

### Directions To / From 

- [{% data variables.android-values.get_directions %}](/osmand/widgets/map-buttons#directions) - allows you to plan route from your location to the selected point (or reverse) by clicking the 'Direction' button
- {% data variables.android-values.context_menu_item_directions_from %} - makes the chosen point as departure point for navigation.

### Plan a route
- {% data variables.android-values.plan_a_route %} (Android ?) - opens ["Plan a route"](/osmand/plan-route/create-route) tool and select chosen point as the beginning of the route.

### Avoid road
- {% data variables.android-values.avoid_road %} (Android ?) - allows to mark place that you would like to avoid for [navigation](/osmand/navigation/route-navigation).

### Add track waypoint

- {% data variables.android-values.context_menu_item_add_waypoint %} - makes selected point to a track as a waypoint.

### Search

- {% data variables.android-values.context_menu_item_search %} - opens seach menu and searches near the chosen point.

### Change position (Move)
- {% data variables.android-values.change_markers_position %} - moves selected Marker, Favorite, Created POI, Audio/Video Note or Track Waypoint  to another location.

### Update / Download Online Maps

- Update map
- Download map

### Update / Download Vector Maps

- Download map vector
- Update map vector

### * Audio-Video (Android)
- {% data variables.android-values.recording_context_menu_arecord %} - makes a [audio note](/osmand/map/point-layers-on-map#audio--video-notes-on-the-map) on selected point (creates new point on the overlay with audio icon).
- {% data variables.android-values.recording_context_menu_vrecord%} - makes a [video note](/osmand/map/point-layers-on-map#audio--video-notes-on-the-map) on selected point (creates new point on the overlay with video icon).
- {% data variables.android-values.recording_context_menu_precord %} - makes a [photo point](/osmand/map/point-layers-on-map#audio--video-notes-on-the-map) on the map.

### * OSM Editing (Android)
- [{% data variables.android-values.poi_context_menu_modify %}](/osmand/plugins/osm-editing)  - edits information of POI.
- [{% data variables.android-values.poi_context_menu_delete %}](/osmand/plugins/osm-editing)  - deletes OpenStreetMap POI.
- [{% data variables.android-values.context_menu_item_open_note %}](/osmand/plugins/osm-editing) - adds [OSM note](https://wiki.openstreetmap.org/wiki/Notes) for to OpenStreetMap.

### * Parking point
- [{% data variables.android-values.context_menu_item_add_parking_point %}](/osmand/plugins/parking) - makes or edits the chosen point as parking position.


## Customize (Android advanced)

It is a menu where the user can reorder or hide items from the 'Context menu actions', to see hidden items from the menu, copy the list of items from the another profile and reset to default settings. 

Android users can reset to default configuration of the Context menu or copy configuration of the Context menu from another profile.

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %} → {% data variables.android-values.ui_customization %} → {% data variables.android-values.context_menu_actions %}

![Context menu actions items ](/assets/images/map/customize_actions_menu.png)

 
