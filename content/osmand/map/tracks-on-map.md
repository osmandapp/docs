---
title: "Tracks and Routes"
intro: "OsmAnd has many powerful features to display various routes on the map. Routes could be built as part of Navigation, created via Plan Route, imported as GPX tracks, recorded via Trip Recording plugin or browsed and selected from OpenStreetMap data." 
versions: '*'
---

{% data reusables.general.article-not-complete %}

## Type of routes on the map

OsmAnd can display several different type of routes:

1.  [Tracks (GPX)](#tracks) - recorded or planned trip saved in [GPX-format](https://en.wikipedia.org/wiki/GPS_Exchange_Format). This kind of route could be imported from the external source, created in the application or recorded by user. GPX could contain one of 3 different types of data or all of them:
    - Track as a line - file has ```<trkpt>``` points array, each point has location and optionally time, speed, altitude and other attributes. These tracks are displayed on the map as solid lines.
    - Track as a route -  file has ```<rtept>``` points array, each point describes as an intermediate point of the route. It depends on track how points within a route should be connected either as small route segments or via straight line. These tracks are displayed on the map as dashed lines. 
    - Waypoints - file has ```<wpt>``` points with attributes. Waypoints are displayed as circular points on the map. You could click on them to get additional information.
2. [Navigation Route](#navigation-route) - a route line displayed during [navigation](/osmand/navigation/route-navigation). By default this is a solid transparent blue line, though default appearance depends on [vector map style](/osmand/map/vector-maps#default-map-styles), [day & night mode](/osmand/map/vector-maps#map-mode). It's also possible to fully customize it on Android.
3. [Routes and route networks on the map](#routes-on-the-map) - special [objects](/osmand/map/vector-maps#routes) on the map from [OpenStreetMap](https://wiki.openstreetmap.org/wiki/Relation:route) data and provided with standard vector maps. They typically represent popular local routes and could be displayed in many ways (shields, color, thickness, pattern). To use these types of routes you will need to enable them on the map.

Read more about [GPX Tracks](/osmand/personal/tracks).

## Tracks 

![Tracks on the map Android](/assets/images/map/tracks_layer_android.png) ![Tracks on the map iOS](/assets/images/map/tracks_layer_ios.png) 

There are many ways to display [Tracks](/osmand/personal/myplaces) on the map.

### Display via {% data variables.android-values.configure_map %} menu

{% data reusables.general.android-ios-switcher %}

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_map %} → {% data variables.android-values.show_gpx %} → &#8230 → Choosing tracks for displayed from the list and setting of track appearance.

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.configure_map %} → {% data variables.ios-values.tracks %} → Choosing tracks for displayed from the list 

![Tracks note](/assets/images/map/tracks_note.png)

{% default %}

{% enddefault %}

{% android %}

![Tracks menu Android](/assets/images/map/tracks_menu_android.png)

{% endandroid %}

{% ios %}

![Tracks menu iOS](/assets/images/map/tracks_menu_ios.png) 

{% endios %}

### Display via {% data variables.android-values.shared_string_my_places %} menu

{% data reusables.general.android-ios-switcher %}

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.shared_string_my_places %} → {% data variables.android-values.shared_string_gpx_files %} → &#xe802; → {% data variables.android-values.shared_string_show_on_map %}  or ["Map" button](/osmand/personal/tracks#my-places-android) for choosing multiple tracks. 

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.menu_my_places %} → {% data variables.ios-values.tracks %} → &#8250; → {% data variables.ios-values.map_settings_show %} or ["Layer" button](/osmand/personal/tracks#my-places-ios) for choosing multiple tracks.

{% default %}

{% enddefault %}

{% android %}

![Tracks my places Android](/assets/images/map/tracks_myplaces_android.png)

{% endandroid %}

{% ios %}

![Tracks menu iOS](/assets/images/map/tracks_myplaces_ios.png)

{% endios %}


### Track Appearance

You can [short tap](/osmand/map/map-context-menu#select-route-short-tap-for-android) on the track on the map -`>` {% data variables.android-values.shared_string_overview %} → click to "eye" button for not showing the track on the map.

![Track menu options Android](/assets/images/map/eye_button_android.png)   

[Short tap](/osmand/map/map-context-menu#select-route-short-tap-for-android) on the track on the map -> {% data variables.android-values.shared_string_overview %} → click to "palette" button for opening Track appearance menu:

![Track menu Appearance Android](/assets/images/map/track_appearance_menu_android.png)   

- {% data variables.android-values.gpx_split_interval %} - {% data variables.android-values.gpx_split_interval_descr %}

![Track menu Appearance Split interval Android](/assets/images/map/track_appearance_menu_split_interval_android.png)   

- {% data variables.android-values.gpx_direction_arrows %} - adding direction info for the track.

![Track menu Appearance direction arrows Android](/assets/images/map/track_appearance_menu_direction_arrows_android.png)   

- {% data variables.android-values.track_show_start_finish_icons %} - showing or not start / finish icons of the track.

![Track menu Appearance start and finish icons Android](/assets/images/map/track_appearance_menu_sf_icons_android.png)  

- {% data variables.android-values.shared_string_color %} -  select color for the track: color by {% data variables.android-values.track_coloring_solid %} (constant color), {% data variables.android-values.map_widget_speed %} (color depends on speed info of the track), {% data variables.android-values.map_widget_altitude %} (color depends on altitude info of the track), {% data variables.android-values.shared_string_slope %} (color depends on slope info of the track). For planning trip, user can choose color of route info data: 
{% data variables.android-values.routeInfo_roadClass_name %}, {% data variables.android-values.routeInfo_surface_name %}, {% data variables.android-values.routeInfo_smoothness_name %}, {% data variables.android-values.routeInfo_winter_ice_road_name %}, {% data variables.android-values.routeInfo_surface_name %}.

![Track menu Appearance Track color Android](/assets/images/map/track_appearance_menu_track_color_android.png) 

- {% data variables.android-values.select_track_width %} - rendering of thikness for the track: {% data variables.android-values.rendering_value_thin_name %}, {% data variables.android-values.rendering_value_medium_name %}, {% data variables.android-values.rendering_value_bold_name %}, {% data variables.android-values.shared_string_custom %}.

![Track menu Appearance Track Thickness Android](/assets/images/map/track_appearance_menu_track_thickness_android.png) 

### Analyze Track on Map (Android)

For detailde information of the track on the map you need to use "Analyze on map" option:

Short tap on the track → [{% data variables.android-values.shared_string_options %}](/osmand/map/track-context-menu#options) → {% data variables.android-values.analyze_on_map %}

![Track menu analyze on map Android](/assets/images/personal/tracks/track_analyze_on_map_android.png) ![Track menu analize on the map distance Android](/assets/images/personal/tracks/track_analyze_on_map_distance_android.png) 

- Graph: altitude / slope / speed - data of vertical axis. Here user can choose: Altitude, Slope, Speed, Altitude/Slope, Altitude/Speed data for viewing on Graph.

![Track menu analyze on map 1 Android](/assets/images/personal/tracks/track_analyze_on_map_1_android.png)

- Graph: distance / time - data of horizontal data. User can choose: Distance, Time, Time of day for analyzing data of vertical axis by timing or distance.

![Track menu analyze on map 2 Android](/assets/images/personal/tracks/track_analyze_on_map_2_android.png)

- Interact with map & graph - tap to Graph for showing info about track point and moving finger along Graph shows info about points of the track. User can scale Graph by [two fingers](/osmand/map/interact-with-map#gestures). 

![Track menu analyze on map 3 Android](/assets/images/personal/tracks/track_analyze_on_map_3_android.png) ![Track menu analyze on map 4 Android](/assets/images/personal/tracks/track_analyze_on_map_4_android.png)

- Follow My location - new function for [navigation by track](/osmand/navigation/gpx-navigation).

![Track menu analyze on map 5 Android](/assets/images/personal/tracks/track_analyze_on_map_5_android.png)



## Navigation Route

The route is a line on the map that shows a user's creating trip. In OsmAnd users create a route by [Navigation function](/osmand/navigation/route-navigation).


 ![Route on the map Android](/assets/images/map/route_layer_android.png) ![Route on the map iOS](/assets/images/map/route_layer_ios.png)

### Route Appearance (Android)

In OsmAnd for Android, [a user can customize](/osmand/personal/profiles#cuztomize-route-line-android) route line: color and width.

{% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %} → {% data variables.android-values.profile_appearance %} → {% data variables.android-values.customize_route_line %}

![Route Customization Android](/assets/images/map/route_custom_android.png)

## Routes on the map

![Routes on the map](/assets/images/map/routes_layer.png) ![Configure Map Routes section](/assets/images/map/configure_map_routes_android.png)

In OsmAnd user can highlight routes and hiking symbol overlay for activities. It will very useful for cycling, hiking, etc.:

Android: Menu → Configure map → Map rendering → Routes

iOS: Menu → Map → Map style → Routes

- [Hiking](https://wiki.openstreetmap.org/wiki/Key:sac_scale):

![Map routes - hiking osmc](/assets/images/map/map-routes-hiking-osmc.png)

- Bicycle

![Map routes - cycle-node-networks](/assets/images/map/map-routes-cycle-node-networks.png)

- [Node networks](https://wiki.openstreetmap.org/wiki/Node_Networks)

![Map routes - hiking node networks](/assets/images/map/map-routes-hiking-node-networks.png)

Read more about Travel routes for [Vector map style](/osmand/map/vector-maps#routes).



## Read more

{% link_with_intro /osmand/personal/tracks %}

{% link_with_intro /osmand/map/track-context-menu %}

{% link_with_intro /osmand/map/configure-map-menu %}

{% link_with_intro /osmand/plan-route %}

{% link_with_intro /osmand/plugins/trip-recording %}

{% link_with_intro /osmand/navigation/gpx-navigation %}

