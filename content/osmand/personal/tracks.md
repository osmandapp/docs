---
title: "Tracks"
intro: "Short information about tracks and how to use them"
versions: '*'
---

{% data reusables.general.article-not-complete %}

## Track

Track on the map is user recorded trip or plan route with makred points on it or not. OsmAnd track file has gpx-format.

You can add tracks to OsmAnd in these ways: 
- Import from the external source.
- Create in the application using [Plan route](/osmand/plan-route) tool.
- Record in the application using [Trip recording](/osmand/plugins/trip-recording) plugin. 

All tracks in the application are stored in the [{% data variables.android-values.shared_string_menu %}](/osmand/start-with/main-menu) → [{% data variables.android-values.shared_string_my_places %}](/osmand/personal/myplaces) → [{% data variables.android-values.shared_string_gpx_tracks%}](/osmand/personal/tracks).

Abilities to manage tracks in OsmAnd:
- Enable and disable tracks on the map.
- Configure track appearance, edit and analyze.
- Use for navigation.

OsmAnd has no limit on the number of tracks to store and display.

There are two options to display [Tracks](/osmand/personal/tracks) on the map: via [Configure map](/osmand/map/tracks-on-map#display-via-configure-map-menu) menu or [My places](/osmand/map/tracks-on-map#display-via-my-places-menu) menu


![Track on the map](/assets/images/personal/tracks/track_on_map_android.png) ![Track on the map iOS](/assets/images/personal/tracks/track_on_map_ios.png)


- Formats: OsmAnd uses [GPX](https://en.wikipedia.org/wiki/GPS_Exchange_Format) format for tracks and points.
- Import: the app can import [GPX](https://en.wikipedia.org/wiki/GPS_Exchange_Format), [KML](https://en.wikipedia.org/wiki/Keyhole_Markup_Language), [KMZ](https://en.wikipedia.org/wiki/Keyhole_Markup_Language) formats of tracks and points.

## Create / Edit Track

### Coordinate input (Android)

- [By Coordinate input](/osmand/plan-route/coordinate-input) 

### Record track

- [Link to Recording Plugin](/osmand/plugins/trip-recording)

### Add waypoint

- [Context menu](/osmand/map/map-context-menu#-add--edit--track-waypoint)

### Edit mode (iOS)

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.menu_my_places %} → {% data variables.ios-values.tracks %} → {% data variables.ios-values.create_new_trip %}

![Edit mode ios](/assets/images/personal/tracks/edit_mode_ios.png) 

- Add points - click to {% data variables.ios-values.add_waypoint %} or {% data variables.ios-values.select_wpt_on_map %}.

![Edit mode adding point ios](/assets/images/personal/tracks/edit_mode_add_point_ios.png) 

- Edit / delete - clicking to "Pencil" button open menu with "Edit" and "Delete" buttons. 

![Edit mode edit point ios](/assets/images/personal/tracks/edit_mode_edit_point_ios.png)  ![Edit mode edit point ios](/assets/images/personal/tracks/edit_mode_edit_point_1_ios.png)

- Change order - long tap to "&#9776;" button and change the order of chosen point by moving up or down.

![Edit mode moving point ios](/assets/images/personal/tracks/edit_mode_moving_point_ios.png) 


### Edit via Plan Route

- [Edit track](/osmand/plan-route/create-route) via Plan route tool.

## Manage Tracks 

### My Places

{% android %}

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.shared_string_my_places%} → {% data variables.android-values.shared_string_tracks %}

At the bottom of the screen are four Actions buttons.

![My places tracks Android](/assets/images/personal/tracks/my_places_tracks_android.png) 

- "+" button  - allows to import GPX track from device storage.
- "earth" button - opens [Add point menu](/osmand/plan-route/coordinate-input) for adding points by inputting coordinates.
- "map" button - allows to choose tracks for showing its on the map.
- "&#x1F5D1;" button - allows to choose tracks for deleting.
- "&#10227;" button - allows to refresh tracks list.
- "OSM editing" button - allows [to upload chosen track to OSM](/osmand/plugins/osm-editing).

{% endandroid %}

### Search / Sort

Clicking to "&#x1F50D;" button on the top of the device screen opens the searching function of the tracks list.

![My places tracks seaching function Android](/assets/images/personal/tracks/my_places_tracks_seaching_android.png) 

Clicking to "sort" button on the top of the device screen opens choosing sort menu for tracks on the list.

![My places tracks sort function Android](/assets/images/personal/tracks/my_places_tracks_sort_android.png) ![My places tracks sort 1 function Android](/assets/images/personal/tracks/my_places_tracks_sort_1_android.png) 

Sort menu: 

- {% data variables.android-values.sort_last_modified %} - sorting tracks in the list by last modified.
- {% data variables.android-values.sort_name_ascending %} - sorting tracks in the list by name A → Z.
- {% data variables.android-values.sort_name_descending %} - sorting tracks in the list by name Z → A.

### My Places (iOS)

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.menu_my_places %} → {% data variables.ios-values.tracks %}

![My places tracks iOS](/assets/images/personal/tracks/my_places_tracks_ios.png)


### Actions

**Actions on Folder list**

![My places tracks Actions iOS](/assets/images/personal/tracks/my_places_tracks_actions_ios.png)

- "layers" button on the top of the device screen - allows to choose and show tracks on the map from tracks list.
- "{% data variables.ios-values.gpx_import_title %}" on bottom part of the device screen - open tab "{% data variables.ios-values.import_from_docs %}" and next description "{% data variables.ios-values.gpx_import_desc %}".
- "{% data variables.ios-values.create_new_trip %}" on bottom part of the device screen - opens ["Edit mode"](/osmand/personal/tracks#edit-mode-ios) for creating new track.

**Actions on Track menu**

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.menu_my_places %} → {% data variables.ios-values.tracks %} → tap to the needed track

![My places tracks file Actions iOS](/assets/images/personal/tracks/my_places_track_file_actions_ios.png)

- {% data variables.ios-values.fav_rename %} - allows to rename the chosen track.
- {% data variables.ios-values.shared_string_remove %} - allows to delete the chosen track.
- {% data variables.ios-values.shared_string_export %} - allows to delete the chosen track.
- {% data variables.ios-values.gpx_edit_mode %} - allows [to edit / create track](/osmand/personal/tracks#edit-mode-ios).
- {% data variables.ios-values.product_title_trip_planning %} - to be deleted.
- {% data variables.ios-values.plan_route_change_folder %} - allows to change a folder for the chosen track.


## Import/Export track

- Link to Import / Export functionality
- Storage

## Read more

### [Show track on Map](/osmand/map/tracks-on-map)
### [Analyze on Map](/osmand/map/tracks-on-map)
### [Track Context menu](/osmand/map/track-context-menu)
### [Navigation by track](/osmand/navigation/gpx-navigation)
### [Trip recording](/osmand/plugins/trip-recording)
