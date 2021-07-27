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

### iOS info

"&#8230;" button - [actions](/osmand/personal/tracks#actions) which you can make with the track.

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

Points / Waypoins menu in Context track menu opens list of track waypoints with point folders.

![Track menu points Android](/assets/images/personal/tracks/track_menu_points_android.png) ![Statistics screen track iOS](/assets/images/personal/tracks/waypoints_track_list_ios.png)


- Route points vs waypoitns
- Search
- Add waypoint
- Open waypoint menu (link to favorites)
- Point filters (bubbles)


## iOS info

- Folders <-> Points list
- edit point - Actions with waypoints

Actions:
- 'Import loader' - allows to share/import waypoints.
- 'Folder' - allows to move waypoints to others folders or to new creating folder.
- 'Palette of colors' - allows to change colors for waypoints.
- 'BIN' - allows to delete chosen waypoints.


### Group menu

![Track menu Group menu Android](/assets/images/personal/tracks/track_menu_group_menu_android.png) 

- Rename (group)
- Show on map
- Change color
- Add / remove map markers
- Copy to favorites
- Delete

## Options

![Track menu options Android](/assets/images/personal/tracks/track_menu_options_android.png)  

- Show on map
- Appearance
- Directions
- Analyze on map
- Analyze split intervals
- Share
- Upload to OSM
- Edit
- Rename / Change folder
- Delete


### Split interval

![Track split interval screen Android](/assets/images/personal/tracks/track_split_interval_android.png) 

- Split interval by distnace / time


## Read more

{% link_with_intro /osmand/personal/tracks %}

{% link_with_intro /osmand/map/tracks-on-map %}

{% link_with_intro /osmand/plan-route %}

{% link_with_intro /osmand/plugins/trip-recording %}

[Analyze on Map](/osmand/map/tracks-on-map)
