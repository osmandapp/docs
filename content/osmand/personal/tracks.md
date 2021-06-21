---
title: "Tracks"
intro: "Tracks"
versions: '*'
---

{% data reusables.general.article-not-complete %}

Track on the map is user recorded trip or plan route with makred points on it or not. OsmAnd track file has gpx-format.

{% default %}

![Track on the map](/assets/images/personal/track_on_map_android.png) ![Track on the map iOS](/assets/images/personal/track_on_map_ios.png)

{% enddefault %}

{% android %}

![Track on the map](/assets/images/personal/track_on_map_android.png)

{% endandroid %}

{% ios %}

![Track on the map iOS](/assets/images/personal/track_on_map_ios.png)

{% endios %}

## 'My Places' menu

{% default %}

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.shared_string_my_places%} → {% data variables.android-values.shared_string_tracks %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.menu_my_places %} → {% data variables.ios-values.tracks %}

![My places tracks Android](/assets/images/personal/my_places_tracks_android.png) ![My places tracks iOS](/assets/images/personal/my_places_tracks_ios.png)

{% enddefault %}

{% android %}

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.shared_string_my_places%} → {% data variables.android-values.shared_string_tracks %}

![My places tracks Android](/assets/images/personal/my_places_tracks_android.png)

{% endandroid %}

{% ios %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.menu_my_places %} → {% data variables.ios-values.tracks %}

![My places tracks iOS](/assets/images/personal/my_places_tracks_ios.png)

{% endios %}

### Actions (menu)

{% default %}

**For Android**:

![My places tracks Actions Android](/assets/images/personal/my_places_tracks_actions_android.png)

- Search - find track by name.
- Sort tracks - sort tracks by last modified, A-Z, Z-A.
- Record/Stop/Save - for current track.
- '&#43;' - import track from storage of your device.
- Add points - adding points by coordinates and saving as gpx-track.
- Show on the map.
- Delete.
- Reset.
- Upload to OSM.


**For iOS**

![My places tracks Actions iOS](/assets/images/personal/my_places_tracks_actions_ios.png)

- Show on the map.
- Record/Stop/Save - for current track.
- {% data variables.ios-values.gpx_import_title %} - import track from storage of your device.
- {% data variables.ios-values.create_new_trip %} track - adding waypoints and save GPX-file.

{% enddefault %}

{% android %}

![My places tracks Actions Android](/assets/images/personal/my_places_tracks_actions_android.png)

- Search - find track by name.
- Sort tracks - sort tracks by last modified, A-Z, Z-A.
- Record/Stop/Save - for current track.
- '&#43;' - import track from storage of your device.
- Add points - adding points by coordinates and saving as gpx-track.
- Show on the map.
- Delete.
- Reset.
- Upload to OSM.

{% endandroid %}

{% ios %}

![My places tracks Actions iOS](/assets/images/personal/my_places_tracks_actions_ios.png)

- Show on the map.
- Record/Stop/Save - for current track.
- {% data variables.ios-values.gpx_import_title %} - import track from storage of your device.
- {% data variables.ios-values.create_new_trip %} track - adding waypoints and save GPX-file.

{% endios %}

### Track menu(actions)?

{% default %}

**For Android**:

Clicking to track folder '&#8744;'. Next, choose needed track and click to '&#8285;'


![My places tracks Actions Android](/assets/images/personal/my_places_tracks_actions_android.png)

- {% data variables.android-values.shared_string_show_on_map %} - show chosen track on the map.
- {% data variables.android-values.analyze_on_map %} - open 'Analyze on map' function for chosen track.
- {% data variables.android-values.shared_string_move %} - moving a chosen track to any track folders.
- {% data variables.android-values.shared_string_rename %} - rename a chosen track.
- {% data variables.android-values.shared_string_share %} - share a chosen track.
- {% data variables.android-values.shared_string_export %} - export a chosen track.
- {% data variables.android-values.shared_string_delete %} - delete a chosen track.

**For iOS**

Clicking to track folder '&#8250;'. Next, choose needed track and click to '&#8250;' and '&#8230;' in up of the screen.

![My places tracks Actions iOS](/assets/images/personal/my_places_tracks_actions_ios.png)

- {% data variables.ios-values.fav_rename %} - rename a chosen track.
- {% data variables.ios-values.shared_string_remove %} - delete a chosen track.
- {% data variables.ios-values.shared_string_export %} - export a chosen track.
- {% data variables.ios-values.gpx_edit_mode %} - open 'Edit mode' function for chosen track.
- {% data variables.ios-values.product_title_trip_planning %} -  open 'Trip planning' function for chosen track.
- {% data variables.ios-values.plan_route_change_folder %} - moving a chosen track to any track folders.


{% enddefault %}

{% android %}

Clicking to track folder '&#8744;'. Next, choose needed track and click to '&#8285;'


![My places tracks Actions Android](/assets/images/personal/my_places_tracks_actions_android.png)

- {% data variables.android-values.shared_string_show_on_map %} - show chosen track on the map.
- {% data variables.android-values.analyze_on_map %} - open 'Analyze on map' function for chosen track.
- {% data variables.android-values.shared_string_move %} - moving a chosen track to any track folders.
- {% data variables.android-values.shared_string_rename %} - rename a chosen track.
- {% data variables.android-values.shared_string_share %} - share a chosen track.
- {% data variables.android-values.shared_string_export %} - export a chosen track.
- {% data variables.android-values.shared_string_delete %} - delete a chosen track.

{% endandroid %}

{% ios %}

Clicking to track folder '&#8896;'. Next, choose needed track and click to '&#8250;' and '&#8230;' in up of the screen.

![My places tracks Actions iOS](/assets/images/personal/my_places_tracks_actions_ios.png)

- {% data variables.ios-values.fav_rename %} - rename a chosen track.
- {% data variables.ios-values.shared_string_remove %} - delete a chosen track.
- {% data variables.ios-values.shared_string_export %} - export a chosen track.
- {% data variables.ios-values.gpx_edit_mode %} - open 'Edit mode' function for chosen track.
- {% data variables.ios-values.product_title_trip_planning %} -  open 'Trip planning' function for chosen track.
- {% data variables.ios-values.plan_route_change_folder %} - moving a chosen track to any track folders.

{% endios %}



## Add waypoint

Waypoints or track points are points that are a part of track (GPX) file.These points displayed automatically if track is displayed on the map. They look & could be configured similar to Favorites - icon, names, color, shape.

### By Map Context menu

[Add track waypoint](/osmand/map/map-context-menu#-add-track-waypoint)

### By Manage track menu

**For Android**

Add Waypoint

**For iOS**

Add Waypoint to track

## Manage tracks 

## Record track

## Import/Export track



