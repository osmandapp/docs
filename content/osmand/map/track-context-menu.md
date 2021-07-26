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

- Image   <!--how to add?}-->
- {% data variables.android-values.add_description %} - for creating description of the track.
- {% data variables.android-values.shared_string_edit %} - for editing descritpion of the track.
- {% data variables.android-values.context_menu_read_full %} - for opening and reading full description.

## Altitude / Speed Graphs 

![Track menu track Android](/assets/images/personal/tracks/track_menu_track_android.png) 

Tabs:
- Overview
- Altitude
- Speed

![Track menu track sub Android](/assets/images/personal/tracks/track_menu_track_sub_android.png) 

### Overview

- Distance (Overview)
- Start / end time (Overview)
- Time span (Overview)

### Altitude

- Ascent / Descent (Altitude)
- Altitude range (Altitude)
- Average altitude (Altitude)

### Speed
- Average speed (Speed)
- Max speed
- Time in Motion

## Waypoints

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
