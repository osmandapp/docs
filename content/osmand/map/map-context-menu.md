---
title: "Map Context menu"
intro: "'Map Context menu' provides information of selected object on the map and allows to share, to edit, to move or to navigate to this place."
versions: '*'
---
{% data reusables.general.article-not-complete %}

## Context menu 
In order to open Context menu you should tap on the object or place on the Map. There are two types of action: by short tap, by long tap.

### Select an object (short tap)
Context menu will appear when you **short tap** on the marked object on the Map. In this case context menu provides you with the information of the POI name, icon (how it marked on the map),  address, distance and direction from the current position.

**Note**: This only applies to objects that have [a node](https://wiki.openstreetmap.org/wiki/Node) or [a way](https://wiki.openstreetmap.org/wiki/Way).

![Context menu Android](/assets/images/map/map_context_menu_short_tap_android.png)  ![Context menu iOS](/assets/images/map/map_context_menu_short_tap_ios.png) 

### Select any point (long tap)
Context menu will appear  when you hold  the any point on the Map with **long tap**. In this case context menu provides you with the information of georraphical point address , distance and direction from the current position and as icon is the location mark. 

![Context menu long_tap_Android](/assets/images/map/map_context_menu_long_tap_android.png) ![Context menu long_tap_iOS](/assets/images/map/map_context_menu_long_tap_ios.png)  |

### Hide context menu

To hide the context menu:
- Click on any empty place (to not open menu once again) on the map
- Drag down by the top of menu 

## Details
In order to gain more details about object you need to click on the "Details" button in the Context menu or move this panel up. 

![Context menu](/assets/images/map/Context_menu.png)
 
### Object info
If you press the details button or move the Context menu panel up appears the [Tag info](https://taginfo.openstreetmap.org/) about the object. This info could be copied to the  buffer by tap on it:
- Website
- Working hours
- Height
- Phone number
- Alternative name/ Historical name/ Old name/ Build name
- Fee (if the entrance can be paid)
- Access for the wheelchairs
- Wikipedia article
- Nearby Wikipedia articles
- Nearby POI
- OpenStreetMap link
- Coordinates
- Online photo
- etc.

### Coordinates 
In the Context menu you can find geographical coordinates of an object. In order to see the coordinates you should click on the description for opening coordinates types. To copy it to the buffer, you should tap on it. There are 7 kinds of available coordinates and 1 link. You can select any of it to display or copy:

| | |
|------|------|
|Coordinates|Example|
|• Decimal degrees (DD) <br> • DDD.DDDDD <br> • DDD MM.MMM <br> • DDD MM.MMM <br> • DDD MM.MMM <br> • DDD MM SS.S <br> • UTM Standard <br> • UTM Standard:  <br> • MGRS <br> • OLC <br> • Link|![Coordinates](/assets/images/map/map_context_menu_Coordinates.png)|


### Nearby Wikipedia

[{% data variables.android-values.wiki_around %}](/osmand/plugins/wikipedia) - click the description for opening Wikipedia POIs list and the button '{% data variables.android-values.shared_string_show_on_map %}' for showing another Wikipedia POIs.

**Note**: [{% data variables.android-values.wiki_around %}](/osmand/plugins/wikipedia) will appear only if you previously downloaded Wikipedia articles for the area.
![Nearby Wikipedia articles](/assets/images/map/map_context_menu_Nearby_Wikipedia.png)

### Nearby POIs

[{% data variables.android-values.speak_poi %}](https://wiki.openstreetmap.org/wiki/Points_of_interest) - click the description for opening POIs list and the button {% data variables.android-values.shared_string_show_on_map %} for showing another POIs near chosen point

![Nearby POI](/assets/images/map/context_menu_Nearby_POI.png)

### OSM link

Via OpenStreetMap link you can go to the OpenStreetMap website to find more information about the pbject: https://www.openstreetmap.org/node or https://www.openstreetmap.org/way
![OSM link](/assets/images/map/context_menu_OSM_link.png)

### Online photos 

Photos from [Mappillary](/osmand/plugins/mapillary), [OpenPlaceReviews](/osmand/plugins/openplacereviews), [Wikimedia](https://www.wikimedia.org/) sources. Click to image for opening image resource. 
![Online photo](/assets/images/map/context_menu_Online_photo.png)

## Actions


![Context menu Actions](/assets/images/map/context_menu_Actions.png)

### Add / Edit Favorite

- [{% data variables.android-values.add_edit_favorite %}](/osmand/personal/myplaces)  - adds a selected point to the favorites list.

### Add / Edit Marker

- Restore marker
- Mark marker as passed
- [{% data variables.android-values.shared_string_marker %} / {% data variables.android-values.edit_map_marker %}](/osmand/personal/markers) - put marker on the selected point.

### Share

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

 
