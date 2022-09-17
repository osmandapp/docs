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

- "Show / hide"  - track on the map
- "Appearance" - opens [Appearance](/osmand/map/tracks-on-map#track-appearance) menu of the track.
- "Edit track" - opens the track in ["Plan route" tool](/osmand/plan-route/create-route).
- "Directions" - opens the track for ["Follow track"](/osmand/navigation/gpx-navigation) option in Navigation.

{% endandroid %}

{% ios %}

![quick actions for track iOS](/assets/images/personal/tracks/quick_actions_track_ios.png)

- "Show / hide"  - allows to show or not a track on the map.
- "Appearance" - opens [Appearance](/osmand/map/tracks-on-map#track-appearance) menu of the track.
- "Export" - allows to export a track.
- "Directions" - opens the track for ["Follow track"](/osmand/navigation/gpx-navigation) option in Navigation.

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

- {% data variables.ios-values.shared_string_distance %} 
- {% data variables.ios-values.shared_string_time_span %} 
- {% data variables.ios-values.shared_string_start_time %} 
- {% data variables.ios-values.shared_string_end_time %} 


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

- {% data variables.ios-values.gpx_avg_altitude%} 
- {% data variables.ios-values.gpx_alt_range %} 
- {% data variables.ios-values.gpx_ascent %} 
- {% data variables.ios-values.gpx_descent %} 

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

- {% data variables.ios-values.gpx_average_speed %} 
- {% data variables.ios-values.gpx_max_speed %} 
- {% data variables.ios-values.shared_string_time_moving %} 
- {% data variables.ios-values.distance_moving %} 

{% endios %}

## Points / Waypoints

### Add / Delete

Points / Waypoins menu in Context track menu opens list of track / folders waypoints.

{% data reusables.general.android-ios-switcher %}

{% default %}

![Track menu points Android](/assets/images/personal/tracks/track_menu_points_android.png) ![Statistics screen track iOS](/assets/images/personal/tracks/waypoints_track_list_ios.png)

{% enddefault %}

{% android %}

![Track menu points Android](/assets/images/personal/tracks/track_menu_points_android.png)

{% endandroid %}

{% ios %}

![Statistics screen track iOS](/assets/images/personal/tracks/waypoints_track_list_ios.png)

{% endios %}

### Waypoints folder 

Manipulation with waypoints folder: change name and color, delete..

{% data reusables.general.android-ios-switcher %}

{% default %}

"&#8285;" button opens waypoint Group menu.

![Track menu Group menu Android](/assets/images/personal/tracks/track_menu_group_menu_android.png) ![Track menu Group menu iOS](/assets/images/personal/tracks/track_menu_group_menu_ios.png) 

{% enddefault %}

{% android %}

"&#8285;" button opens waypoint Group menu.

![Track menu Group menu Android](/assets/images/personal/tracks/track_menu_group_menu_android.png) 

Actions:
- {% data variables.android-values.shared_string_show_on_map %} - allows to show or not group waypoints on the map.
- {% data variables.android-values.shared_string_rename %} - allows to change Group name.
- {% data variables.android-values.change_color %} - allows to change color for group waypoints.
- {% data variables.android-values.copy_to_map_markers %} - allows to move group waypoints to [Map markers](/osmand/personal/markers).
- {% data variables.android-values.copy_to_map_favorites %} - allows to move group waypoints to [Favorites](/osmand/personal/favorites).
- {% data variables.android-values.shared_string_delete %} - allows to delete group waypoints.

{% endandroid %}

{% ios %}

"&#8230;" button opens waypoint Group menu.

![Track menu Group menu iOS](/assets/images/personal/tracks/track_menu_group_menu_ios.png) 

Actions:
- {% data variables.ios-values.map_settings_show %} - allows to show or not group waypoints on the map.
- {% data variables.ios-values.fav_rename %} - allows to change Group name.
- {% data variables.ios-values.change_color %} - allows to change color for group waypoints.
- {% data variables.ios-values.shared_string_delete %} - allows to delete group waypoints.

{% endios %}

## Options

Menu "Options" allows to make manipulation with the chosen track, to opens it in other tools.

{% data reusables.general.android-ios-switcher %}

{% default %}

![Track menu options Android](/assets/images/personal/tracks/track_menu_options_android.png)  ![Track menu options iOS](/assets/images/personal/tracks/track_menu_options_ios.png)  

{% enddefault %}

{% android %}

![Track menu options Android](/assets/images/personal/tracks/track_menu_options_android.png)  

- {% data variables.android-values.shared_string_show_on_map %} - shows or not the track on the map.
- {% data variables.android-values.shared_string_appearance %} - opens [Appearance menu](/osmand/map/tracks-on-map#track-appearance-android) for the track.
- {% data variables.android-values.shared_string_navigation %} - starts navigation by [Follow track option](/osmand/navigation/gpx-navigation).
- {% data variables.android-values.join_segments %} - allows to join gaps of the track.
- {% data variables.android-values.analyze_on_map %} - opens [Analyze on map function](/osmand/map/tracks-on-map#analyze-track-on-map-android).
- {% data variables.android-values.analyze_by_intervals %} - [analyze the track by time or distance intervals](/osmand/map/track-context-menu#split-interval).
- {% data variables.android-values.shared_string_share %} - export the chosen track.
- {% data variables.android-values.upload_to_openstreetmap %} - [upload the chose track to OpenStreetMap](/osmand/plugins/osm-editing#how-to-upload-gpx-track).
- {% data variables.android-values.edit_track %} - open the chosen track in [Plan route tool](/osmand/plan-route/create-route).
- {% data variables.android-values.rename_track %} - change track name.
- {% data variables.android-values.change_folder %} - select folder and add new one for the chosen track.
- {% data variables.android-values.shared_string_gps_filter %} - allows [to filter points of the track](/osmand/map/track-context-menu#gps-filter). 
- {% data variables.android-values.shared_string_delete %} - delete the track.

{% endandroid %}

{% ios %}

 ![Track menu options Android](/assets/images/personal/tracks/track_menu_options_ios.png)  

- {% data variables.ios-values.map_settings_show %} - shows or not the track on the map.
- {% data variables.ios-values.map_settings_appearance %} - opens [Appearance menu](/osmand/map/tracks-on-map#track-appearance-android) for the track.
- {% data variables.ios-values.shared_string_navigation%} - starts navigation by [Follow track option](/osmand/navigation/gpx-navigation).
- {% data variables.ios-values.analyze_on_map %} - opens [Analyze on map function](/osmand/map/tracks-on-map#analyze-track-on-map-android).
- {% data variables.ios-values.shared_string_export %} - export the chosen track.
- {% data variables.ios-values.edit_track %} - open the chosen track in [Plan route tool](/osmand/plan-route/create-route).
- Dublicate track - allows to make and save a copy of the track.
- {% data variables.ios-values.gpx_rename_q %} - change track name.
- {% data variables.ios-values.plan_route_change_folder %} - select folder and add new one for the chosen track.
- {% data variables.ios-values.shared_string_delete %} - delete the track.


{% endios %}


### Split interval

A user can divide a track by intervals (distance or time) and analyze it.

{% data reusables.general.android-ios-switcher %}

{% default %}

![Track split interval screen Android](/assets/images/personal/tracks/track_split_interval_android.png) ![Track split interval screen time Android](/assets/images/personal/tracks/track_split_interval_time_android.png)

{% enddefault %}

{% android %}

{% data variables.android-values.shared_string_options %} → {% data variables.android-values.analyze_by_intervals %}

- Split the track  by distance or time interval

![Track split interval screen Android](/assets/images/personal/tracks/track_split_interval_android.png) ![Track split interval screen time Android](/assets/images/personal/tracks/track_split_interval_time_android.png)

{% endandroid %}

{% ios %}

{% note %}
This feature doesn't exist for iOS version of OsmAnd.
{% endnote %}

{% endios %}

### GPS filter

A user can filter points of a GPX track by Smoothing, Speed, Altitude, Min GPS Precision for saving new track without excluded points.

{% data reusables.general.android-ios-switcher %}

{% default %}

{% enddefault %}

{% android %}

![GPS filter screen Android](/assets/images/personal/tracks/gps_filter_android.png)

In the screen you see the map (with [zoom buttons](/osmand/map/interact-with-map#my-location--zoom), [my location button](/osmand/map/interact-with-map#my-location--zoom), my track location button), buttons "Reset" and "&#8285;"(Actions), part with two menus: **Filter** and **Statistics**.

- "&#8285;"(Actions) button opens "Actions" part of "Filter" or "Statistics" menu.
- "&#8634;" button allows to reset the track to original.
- "My track location" button allows to move the map to your track.

**Filter** Menu

Here you can change any filter parameters for your track. The menu two parts: Points and Actions.

| **_Points_** | 
|:------------|
|Numbers points after filtration / all points of the track.| 
|![GPS filter screen points numbers Android](/assets/images/personal/tracks/gps_filter_points_numbers_android.png) | 
|*Smoothing*: Set the threshold distance between points. Track points not at least this distance away from the last visible point will be hidden. Be aware that high thresholds may oversimplify the track geometry.| 
|![GPS filter smoothing numbers Android](/assets/images/personal/tracks/gps_filter_smoothing_android.png) |
|*Speed*: Only track points matching the set interval will appear on the chart and map, the rest will be hidden.| 
|![GPS filter speed numbers Android](/assets/images/personal/tracks/gps_filter_speed_android.png) | 
|*Altitude*: Only track points matching the set interval will appear on the chart and map, the rest will be hidden.| 
|![GPS filter altitude numbers Android](/assets/images/personal/tracks/gps_filter_altitude_android.png) | 
|*GPS precision*: Set the maximum accepted value for HDOP. Points with higher value will be hidden.| 
|![GPS filter precision numbers Android](/assets/images/personal/tracks/gps_filter_precision_android.png) | 


**_Actions_**

OsmAnd will apply the changes to the track without updating the file. You can save changes manually.

- {% data variables.android-values.reset_to_original %} - allows to reset parameters to original.
- {% data variables.android-values.save_as_copy %} - allows to save the track as new.
- {% data variables.android-values.save_changes_into_file %} - allows to rewrite the track with new parameters.

**Statistics** Menu

This menu has two parts: Graph and Actions. Actions part is similar like Filter menu.

The Graph part has three graph parametes: Overview, Altitude, Speed. This functional is a copy of [track Graph](/osmand/map/track-context-menu#altitude--speed-graphs).

![GPS filter graph Android](/assets/images/personal/tracks/gps_filter_graph_android.png)


{% endandroid %}

{% ios %}

{% note %}
This feature doesn't exist for iOS version of OsmAnd.
{% endnote %}

{% endios %}


## Read more

{% link_with_intro /osmand/personal/tracks %}

{% link_with_intro /osmand/map/tracks-on-map %}

{% link_with_intro /osmand/plan-route %}

{% link_with_intro /osmand/plugins/trip-recording %}

[Analyze on Map](/osmand/map/tracks-on-map)
