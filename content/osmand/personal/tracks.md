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

### My Places (Android)

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.shared_string_my_places%} → {% data variables.android-values.shared_string_tracks %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.menu_my_places %} → {% data variables.ios-values.tracks %}

![My places tracks Android](/assets/images/personal/tracks/my_places_tracks_android.png) ![My places tracks iOS](/assets/images/personal/tracks/my_places_tracks_ios.png)

### Search / Sort (Android)

Sort: 

- Last modified
- A -> Z
- Z -> A

### My Places (iOS)

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.menu_my_places %} → {% data variables.ios-values.tracks %} → choose a track

### Actions

![My places tracks Actions Android](/assets/images/personal/tracks/my_places_tracks_actions_android.png) ![My places tracks Actions iOS](/assets/images/personal/tracks/my_places_tracks_actions_ios.png)

![My places tracks file Actions iOS](/assets/images/personal/tracks/my_places_track_file_actions_ios.png)

- Record track / Save (Android / iOS)
- Import track (Android / iOS)
- Coordinate input - create track (Android)
- Edit Mode - edit / create track (iOS) 
- {% data variables.android-values.shared_string_show_on_map %} (Android / iOS)
- {% data variables.android-values.shared_string_move %} /  {% data variables.android-values.shared_string_rename %}  (Android / iOS)
- {% data variables.android-values.shared_string_delete %} (Android / iOS)
- {% data variables.android-values.shared_string_share %}  (Android / iOS)
- {% data variables.android-values.analyze_on_map %} (Android) - open 'Analyze on map' function for chosen track.
- Refresh (Android) - reloads track data from SD card.
- Export to OpenStreetMap (Android)
- Trip Planning (iOS) - to be deleted


## Import/Export track

- Link to Import / Export functionality
- Storage

## Read more

### [Show track on Map](/osmand/map/tracks-on-map)
### [Analyze on Map](/osmand/map/tracks-on-map)
### [Track Context menu](/osmand/map/track-context-menu)
### [Navigation by track](/osmand/navigation/gpx-navigation)
### [Trip recording](/osmand/plugins/trip-recording)
