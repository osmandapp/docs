---
title: "Tracks Context menu"
intro: "Tracks Context menu is menu with actions and data of GPX-track."
versions: '*'
---

{% data reusables.general.article-not-complete %}

For openng Track Context menu:

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.shared_string_my_places %} → {% data variables.android-values.shared_string_gpx_files %} → click to choosing track or just tap to choosing track on the map.

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.menu_my_places %} → {% data variables.ios-values.tracks %} → click to choosing track.

## Overview

In Overview user can find track data info and make some actions.

![Track menu overview Android](/assets/images/personal/tracks/track_menu_overview_android.png) ![Statistics screen track iOS](/assets/images/personal/tracks/statistics_track_ios.png)

### iOS info panel

"&#8230;" button - actions which you can make with the track.

![My places tracks file Actions iOS](/assets/images/personal/tracks/my_places_track_file_actions_ios.png)

- {% data variables.ios-values.fav_rename %} - allows to rename the track.
- {% data variables.ios-values.shared_string_remove %} - allows to remove chosen track.
- {% data variables.ios-values.shared_string_export %} - allows to export chosen track.
- {% data variables.ios-values.gpx_edit_mode %} - opens [Edit mode menu](/osmand/personal/tracks#edit-mode-ios) for waypoints.
- {% data variables.ios-values.product_title_trip_planning %} - opens [Trip planning tool](/osmand/personal/tracks#edit-via-plan-route) for chosen track.
- {% data variables.ios-values.plan_route_change_folder %} - allows to move chosen track to another track folder or new folder.


Info panel has name and short info of the track:

![Info for track iOS](/assets/images/personal/tracks/info_track_ios.png)

Quick actions:
- {% data variables.ios-values.map_settings_show %} - show a track on the map.
- {% data variables.ios-values.fav_color %} - change color track.

![Actions for track iOS](/assets/images/personal/tracks/actions_track_ios.png)

Info:
- {% data variables.ios-values.gpx_speed %} - average speed, max speed.
- {% data variables.ios-values.gpx_route_time %} - start time, finish time, total time, moving time.
- {% data variables.ios-values.gpx_uphldownhl %} - average elevation, elevation range, up/down, uphills total.

![Full info for track iOS](/assets/images/personal/tracks/full_info_track_ios.png)

### Info panel (Android)

Info panel for Android has track name and short description, track info.

![Full info for track Android](/assets/images/personal/tracks/full_info_track_android.png)

Next track info:
- Name of the track.
- Short description of the track.
- Direction and distance to the point on the track.
- {% data variables.android-values.distance %} - showing track distnace.
- {% data variables.android-values.altitude_ascent %} / {% data variables.android-values.altitude_descent %}.
- {% data variables.android-values.altitude_range %} - showing max and min altitude.
- {% data variables.android-values.average_speed %}.
- {% data variables.android-values.max_speed %}.
- {% data variables.android-values.shared_string_time_span %} - recorded time of the track.
- {% data variables.android-values.shared_string_time_moving %} - sum of time during motion.

### Quick actions

![quick actions for track Android](/assets/images/personal/tracks/quick_actions_track_android.png)

- Show / hide  - track on the map
- Appearance - open [Appearance](/osmand/map/tracks-on-map#track-appearance-android) menu of the track.
- Edit track - open the track in ["Plan route" tool](/osmand/plan-route/create-route).
- Directions - open the track for ["Follow track"](/osmand/navigation/gpx-navigation) option in Navigation.

### Description

![Description for track Android](/assets/images/personal/tracks/description_track_android.png)

- Image   <!--how to add any images to descriptions?}-->
- {% data variables.android-values.add_description %} - for creating description of the track.
- {% data variables.android-values.shared_string_edit %} - for editing descritpion of the track.
- {% data variables.android-values.context_menu_read_full %} - for opening and reading full description.

## Altitude / Speed Graphs 

Click to the "{% data variables.android-values.shared_string_gpx_track %}" button opens Graph of Track Context menu. Here there are name of track, three tabs ([{% data variables.android-values.shared_string_overview %}](/osmand/map/track-context-menu#overview-1), [{% data variables.android-values.altitude %}](/osmand/map/track-context-menu#altitude), [{% data variables.android-values.map_widget_speed %}](/osmand/map/track-context-menu#speed)), Graph with additional info and [{% data variables.android-values.analyze_on_map %}](/osmand/map/tracks-on-map#analyze-route-on-map-android), {% data variables.android-values.shared_string_options %} buttons.

**{% data variables.android-values.analyze_on_map %}** button opens [Analyze track menu](/osmand/map/tracks-on-map#analyze-route-on-map-android) for the track.

**{% data variables.android-values.shared_string_options %}** button opens menu with: "Edit" opens the track in [Plan route tool](/osmand/plan-route), "Delete" allows to delete chosen track item, "Split interval" opens [Split interval function](/osmand/map/track-context-menu#split-interval) for the track.

![Track menu track Android](/assets/images/personal/tracks/track_menu_track_android.png) ![Track menu Options track Android](/assets/images/personal/tracks/track_menu-options_track_android.png)

### Overview

This tab opens a graph with speed / altitude info on distance, additional track data: 
- {% data variables.android-values.distance %}
- {% data variables.android-values.shared_string_time_span %}
- {% data variables.android-values.shared_string_start_time %}
- {% data variables.android-values.shared_string_end_time %}

![Track graph overview Android](/assets/images/personal/tracks/track_graph_overview_android.png) 

### Altitude

This tab opens a graph with altitude / slope info on distance, additional track data:
- {% data variables.android-values.average_altitude %}
- {% data variables.android-values.altitude_range %}
- {% data variables.android-values.altitude_ascent %}
- {% data variables.android-values.altitude_descent %}

![Track graph altitude Android](/assets/images/personal/tracks/track_graph_altitude_android.png) 

### Speed

This tab opens a with speed info on distance, additional track data:
 - {% data variables.android-values.average_speed %}
 - {% data variables.android-values.max_speed %}
 - {% data variables.android-values.moving_time %}
 - {% data variables.android-values.distance_moving %} 

![Track graph Speed Android](/assets/images/personal/tracks/track_graph_speed_android.png) 

## Points / Waypoints

Points / Waypoins menu in Context track menu opens list of track / folders waypoints.

![Track menu points Android](/assets/images/personal/tracks/track_menu_points_android.png) ![Statistics screen track iOS](/assets/images/personal/tracks/waypoints_track_list_ios.png)

### iOS Waypoints

Buttons on top of the screen:

- Folders <-> Points list - the button changes order in waypoints list.

![Track menu Waypoins order iOS](/assets/images/personal/tracks/track_menu_waypoints_order_ios.png) ![Track menu Waypoins order iOS](/assets/images/personal/tracks/track_menu_waypoints_order_1_ios.png) 

- Editing waypoints ("pencil" button) - the button opens "Actions" panel for waypoints.

![Track menu Waypoins action panel iOS](/assets/images/personal/tracks/track_menu_waypoints_actions_panel_ios.png)

Actions:
- 'Import loader' - allows to share/import chosen waypoints.
- 'Folder' - allows to move waypoints to others folders or to new creating folder.
- 'Palette of colors' - allows to change colors for waypoints.
- 'BIN' - allows to delete chosen waypoints.

[For adding new waypoint](/osmand/personal/tracks#add-waypoint) you need to tap on the map. [Map Context menu](/osmand/map/map-context-menu#-add--edit--track-waypoint) opens where you can choose "Add waypoint".

![Track menu Waypoint add iOS](/assets/images/personal/tracks/track_menu_waypoint_add_ios.png) ![Track menu Waypoint add 1 iOS](/assets/images/personal/tracks/track_menu_waypoint_add_1_ios.png)

### Android Group menu

"&#8285;" button opens waypoint Group menu.

![Track menu Group menu Android](/assets/images/personal/tracks/track_menu_group_menu_android.png) 

Actions:
- {% data variables.android-values.shared_string_show_on_map %} - allows to show or not group waypoints on the map.
- {% data variables.android-values.shared_string_rename %} - allows to change Group name.
- {% data variables.android-values.change_color %} - allows to change color for group waypoints.
- {% data variables.android-values.copy_to_map_markers %} - allows to move group waypoints to [Map markers](/osmand/personal/markers).
- {% data variables.android-values.copy_to_map_favorites %} - allows to move group waypoints to [Favorites](/osmand/personal/favorites).
- {% data variables.android-values.shared_string_delete %} - allows to delete group waypoints.

## Options

![Track menu options Android](/assets/images/personal/tracks/track_menu_options_android.png)  

- {% data variables.android-values.shared_string_show_on_map %} - shows or not the track on the map.
- {% data variables.android-values.shared_string_appearance %} - opens [Appearance menu](/osmand/map/tracks-on-map#track-appearance-android) for the track.
- {% data variables.android-values.shared_string_navigation %} - starts navigation by [Follow track option](/osmand/navigation/gpx-navigation).
- {% data variables.android-values.analyze_on_map %} - opens [Analyze on map function](/osmand/map/tracks-on-map#analyze-track-on-map-android).
- {% data variables.android-values.analyze_by_intervals %} - [analyze the track by time or distance intervals](/osmand/map/track-context-menu#split-interval).
- {% data variables.android-values.shared_string_share %} - export the chosen track.
- {% data variables.android-values.upload_to_openstreetmap %} - [upload the chose track to OpenStreetMap](/osmand/plugins/osm-editing#how-to-upload-gpx-track).
- {% data variables.android-values.edit_track %} - open the chosen track in [Plan route tool](/osmand/plan-route/create-route).
- {% data variables.android-values.rename_track %} - change track name.
- {% data variables.android-values.change_folder %} - select folder and add new one for the chosen track.
- {% data variables.android-values.shared_string_delete %} - delete the track.


### Split interval

{% data variables.android-values.shared_string_options %} → {% data variables.android-values.analyze_by_intervals %}

- Split the track  by distance or time interval

![Track split interval screen Android](/assets/images/personal/tracks/track_split_interval_android.png) ![Track split interval screen Android](/assets/images/personal/tracks/track_split_interval_time_android.png)


## Read more

{% link_with_intro /osmand/personal/tracks %}

{% link_with_intro /osmand/map/tracks-on-map %}

{% link_with_intro /osmand/plan-route %}

{% link_with_intro /osmand/plugins/trip-recording %}

[Analyze on Map](/osmand/map/tracks-on-map)
