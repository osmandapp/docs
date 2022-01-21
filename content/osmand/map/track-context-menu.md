---
title: "Tracks Context menu"
intro: "Tracks Context menu is menu with actions and data of GPX-track."
versions: '*'
---

{% data reusables.general.article-not-complete %}

For openng Track Context menu:

{% data variables.android-values.shared_string_menu %} → {% data variables.android-values.shared_string_my_places %} → {% data variables.android-values.shared_string_gpx_files %} → click to choosing track or just tap to choosing track on the map.

There are the next tabs of Track Context menu:

 - [Overview](/osmand/map/track-context-menu#overview)
 - [Altitude / Speed Graphs](/osmand/map/track-context-menu#altitude--speed-graphs) 
 - [Points / Waypoints](/osmand/map/track-context-menu#points--waypoints)
 - [Options](/osmand/map/track-context-menu#options)

{% default %}

![Track menu Android](/assets/images/personal/tracks/menu_track_android.png) ![Track menu iOS](/assets/images/personal/tracks/menu_track_ios.png)

{% enddefault %}

{% android %}

![Track menu Android](/assets/images/personal/tracks/menu_track_android.png)

{% endandroid %}

{% ios %}

![Statistics screen track iOS](/assets/images/personal/tracks/menu_track_ios.png)

{% endios %}

## Overview

In Overview user can find track data info and make actions with viewing of the chosen track:

- [Info panel](/osmand/map/track-context-menu#info-panel) - shows track info: distance, speed, ascent/descent...
- [Quick actions](/osmand/map/track-context-menu#quick-actions) - action buttons for the chosen track.
- [Description and info](/osmand/map/track-context-menu#description-and-info) - track file info and track description.

You can [short tap](/osmand/map/map-context-menu#select-route-short-tap-for-android) on the track on the map → {% data variables.android-values.shared_string_overview %} → click to "eye" button for not showing the track on the map.

{% data reusables.general.android-ios-switcher %}

{% default %}

![Track menu overview Android](/assets/images/personal/tracks/track_menu_overview_android.png) ![Statistics screen track iOS](/assets/images/personal/tracks/statistics_track_ios.png)

{% enddefault %}

{% android %}

![Track menu overview Android](/assets/images/personal/tracks/track_menu_overview_android.png)

{% endandroid %}

{% ios %}

 ![Statistics screen track iOS](/assets/images/personal/tracks/statistics_track_ios.png)

{% endios %}

### Info panel

Info panel shows the track name, info about trip data, distance and direction to chosen track point from your position.

{% data reusables.general.android-ios-switcher %}

{% default %}

![Full info for track Android](/assets/images/personal/tracks/full_info_track_android.png) ![Full info for track Android](/assets/images/personal/tracks/full_info_track_ios.png)

{% enddefault %}

{% android %}

![Full info for track Android](/assets/images/personal/tracks/full_info_track_android.png)

Next track info:
- The track name - you can change it in [Options menu](/osmand/map/track-context-menu#options).
- Short description of the track - short part from [full description](/osmand/map/track-context-menu#description).
- Direction and distance to the point on the track - blue arrow with distance.
- Info panel of data trip:

 {% data variables.android-values.distance %} - showing track distance.

 {% data variables.android-values.altitude_ascent %} / {% data variables.android-values.altitude_descent %} - sums of ascents and descents of a trip.

 {% data variables.android-values.altitude_range %} - showing min and max altitude of a trip.

 {% data variables.android-values.average_speed %} - average speed of a trip.

 {% data variables.android-values.max_speed %} - max speed of a trip.

 {% data variables.android-values.shared_string_time_span %} - recorded time of a trip.

 {% data variables.android-values.shared_string_time_moving %} - sum of time during motion of a trip.

{% endandroid %}

{% ios %}

![Full info for track Android](/assets/images/personal/tracks/full_info_track_ios.png)

Next track info:
- The track name - you can change it in [Options menu](/osmand/map/track-context-menu#options).
- Direction and distance to the point on the track - blue arrow with distance.
- Info panel of data trip:

 {% data variables.ios-values.shared_string_distance %} - showing track distance.

 {% data variables.ios-values.gpx_ascent %} / {% data variables.ios-values.gpx_descent %} - sums of ascents and descents of a trip.

 {% data variables.ios-values.gpx_alt_range %} - showing min and max altitude of a trip.

 {% data variables.ios-values.gpx_average_speed %} - average speed of a trip.

 {% data variables.ios-values.gpx_max_speed %} - max speed of a trip.

 {% data variables.ios-values.total_time %} - recorded time of a trip.

 {% data variables.ios-values.moving_time %} - sum of time during motion of a trip.

{% endios %}

### Quick actions

Buttons panel with the next action: Show/Hide a track on the map, opening [Appearance](/osmand/map/tracks-on-map#track-appearance) menu of a track, Export / [Plan route](/osmand/plan-route/create-route), [Navigation](/osmand/navigation/gpx-navigation).

{% data reusables.general.android-ios-switcher %}

{% default %}

![quick actions for track Android](/assets/images/personal/tracks/quick_actions_track_android.png) ![quick actions for track iOS](/assets/images/personal/tracks/quick_actions_track_ios.png)

{% enddefault %}

{% android %}

![quick actions for track Android](/assets/images/personal/tracks/quick_actions_track_android.png)

- Show / hide  - track on the map
- Appearance - open [Appearance](/osmand/map/tracks-on-map#track-appearance) menu of the track.
- Edit track - open the track in ["Plan route" tool](/osmand/plan-route/create-route).
- Directions - open the track for ["Follow track"](/osmand/navigation/gpx-navigation) option in Navigation.

{% endandroid %}

{% ios %}

![quick actions for track iOS](/assets/images/personal/tracks/quick_actions_track_ios.png)

- Show / hide  - allow to show or not a track on the map.
- Appearance - open [Appearance](/osmand/map/tracks-on-map#track-appearance) menu of the track.
- Export - allows to export a track.
- Directions - open the track for ["Follow track"](/osmand/navigation/gpx-navigation) option in Navigation.

{% endios %}

### Description and info

This part contains info about GPX file and description of a GPX track.

{% data reusables.general.android-ios-switcher %}

{% default %}

![Description for track Android](/assets/images/personal/tracks/description_track_android.png) ![Description for track iOS](/assets/images/personal/tracks/description_track_ios.png)

{% enddefault %}

{% android %}

![Description for track Android](/assets/images/personal/tracks/description_track_1_android.png) ![Description for track Android](/assets/images/personal/tracks/description_track_android.png)

- Image??   <!--how to add any images to descriptions?}-->
- {% data variables.android-values.add_description %} - for creating description of the track.
- {% data variables.android-values.shared_string_edit %} - for editing description of the track.
- {% data variables.android-values.context_menu_read_full %} - for opening and reading full description.
- {% data variables.android-values.info_button %} - contains info about file size, location folder, date of creation.

{% endandroid %}

{% ios %}

![Description for track iOS](/assets/images/personal/tracks/description_track_ios.png)

- {% data variables.ios-values.shared_string_info %} - contains info about file size, location folder

{% endios %}



## Altitude / Speed Graphs 

Click to the "{% data variables.android-values.shared_string_gpx_track %}" button opens Graph of Track Context menu. Here there are name of track, three tabs:
- [{% data variables.android-values.shared_string_overview %}](/osmand/map/track-context-menu#overview-1)
- [{% data variables.android-values.altitude %}](/osmand/map/track-context-menu#altitude)
- [{% data variables.android-values.map_widget_speed %}](/osmand/map/track-context-menu#speed)

Graph with additional info and [{% data variables.android-values.analyze_on_map %}](/osmand/map/tracks-on-map#analyze-route-on-map-android), {% data variables.android-values.shared_string_options %} buttons.

**{% data variables.android-values.analyze_on_map %}** button opens [Analyze track menu](/osmand/map/tracks-on-map#analyze-route-on-map-android) for the track.

**{% data variables.android-values.shared_string_options %}** button opens menu with: "Edit" opens the track in [Plan route tool](/osmand/plan-route), "Delete" allows to delete chosen track item, "Split interval" opens [Split interval function](/osmand/map/track-context-menu#split-interval) for the track.

{% data reusables.general.android-ios-switcher %}

{% default %}

![Context track menu Graphs Android](/assets/images/personal/tracks/track_menu_graph_android.png) ![Context track menu Graphs iOS](/assets/images/personal/tracks/track_menu_graph_ios.png)

{% enddefault %}


{% android %}

![Context track menu Graphs Android](/assets/images/personal/tracks/track_menu_graph_android.png)

{% endandroid %}


{% ios %}

![Context track menu Graphs iOS](/assets/images/personal/tracks/track_menu_graph_ios.png)

{% endios %}


### Overview

This tab opens a graph with speed / altitude info on distance, additional track data.

{% data reusables.general.android-ios-switcher %}

{% default %}

![Track graph overview Android](/assets/images/personal/tracks/track_graph_overview_android.png) ![Track graph overview iOS](/assets/images/personal/tracks/track_graph_overview_ios.png) 

{% enddefault %}


{% android %}

![Track graph overview Android](/assets/images/personal/tracks/track_graph_overview_android.png) 

- {% data variables.android-values.distance %}
- {% data variables.android-values.shared_string_time_span %}
- {% data variables.android-values.shared_string_start_time %}
- {% data variables.android-values.shared_string_end_time %}

{% endandroid %}


{% ios %}

![Track graph overview iOS](/assets/images/personal/tracks/track_graph_overview_ios.png) 


{% endios %}





### Altitude

This tab opens a graph with altitude / slope info on distance, additional track data.

{% data reusables.general.android-ios-switcher %}

{% default %}

![Track graph altitude Android](/assets/images/personal/tracks/track_graph_altitude_android.png) ![Track graph altitude iOS](/assets/images/personal/tracks/track_graph_altitude_ios.png) 

{% enddefault %}


{% android %}


![Track graph altitude Android](/assets/images/personal/tracks/track_graph_altitude_android.png) 

- {% data variables.android-values.average_altitude %}
- {% data variables.android-values.altitude_range %}
- {% data variables.android-values.altitude_ascent %}
- {% data variables.android-values.altitude_descent %}

{% endandroid %}


{% ios %}

![Track graph altitude iOS](/assets/images/personal/tracks/track_graph_altitude_ios.png) 

{% endios %}



### Speed

This tab opens a with speed info on distance, additional track data.

{% data reusables.general.android-ios-switcher %}

{% default %}

![Track graph Speed Android](/assets/images/personal/tracks/track_graph_speed_android.png) ![Track graph Speed iOS](/assets/images/personal/tracks/track_graph_speed_ios.png) 

{% enddefault %}


{% android %}

![Track graph Speed Android](/assets/images/personal/tracks/track_graph_speed_android.png) 

 - {% data variables.android-values.average_speed %}
 - {% data variables.android-values.max_speed %}
 - {% data variables.android-values.moving_time %}
 - {% data variables.android-values.distance_moving %} 

{% endandroid %}


{% ios %}

![Track graph Speed iOS](/assets/images/personal/tracks/track_graph_speed_ios.png) 

{% endios %}



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


- {% data variables.ios-values.fav_rename %} - allows to rename the track.
- {% data variables.ios-values.shared_string_remove %} - allows to remove chosen track.
- {% data variables.ios-values.shared_string_export %} - allows to export chosen track.
- {% data variables.ios-values.gpx_edit_mode %} - opens [Edit mode menu](/osmand/personal/tracks#edit-mode-ios) for waypoints.
- {% data variables.ios-values.product_title_trip_planning %} - opens [Trip planning tool](/osmand/personal/tracks#edit-via-plan-route) for chosen track.
- {% data variables.ios-values.plan_route_change_folder %} - allows to move chosen track to another track folder or new folder.



### Split interval

{% data variables.android-values.shared_string_options %} → {% data variables.android-values.analyze_by_intervals %}

- Split the track  by distance or time interval

![Track split interval screen Android](/assets/images/personal/tracks/track_split_interval_android.png) ![Track split interval screen time Android](/assets/images/personal/tracks/track_split_interval_time_android.png)


## Read more

{% link_with_intro /osmand/personal/tracks %}

{% link_with_intro /osmand/map/tracks-on-map %}

{% link_with_intro /osmand/plan-route %}

{% link_with_intro /osmand/plugins/trip-recording %}

[Analyze on Map](/osmand/map/tracks-on-map)
