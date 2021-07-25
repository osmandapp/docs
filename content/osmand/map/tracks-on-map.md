---
title: "Tracks and Routes"
intro: "On the map, a user can display GPX-tracks and navigation routes."
versions: '*'
---

{% data reusables.general.article-not-complete %}

## Type of routes

Routes on the map have next type:
- Tracks (GPX) - recorded or planning trip in [GPX-format](https://en.wikipedia.org/wiki/GPS_Exchange_Format).

![Tracks on the map](/assets/images/map/tracks_layer.png)

- Navigation Route - trip from A to B which built by [routing type](/osmand/navigation/route-navigation).

![Route on the map](/assets/images/map/route_layer.png)

- Routes and route networks on the map - [objects which rendering](/osmand/map/vector-maps#routes) on the map from [data OpenStreetMap](https://wiki.openstreetmap.org/wiki/Relation:route).

![Routes on the map](/assets/images/map/routes_layer.png)


## Tracks 

Track is [user data](/osmand/personal/myplaces) that showed [recorded](/osmand/plugins/trip-recording) or [planning trip](/osmand/plan-route). 

OsmAnd app uses [GPX-format](https://en.wikipedia.org/wiki/GPS_Exchange_Format)

![Tracks on the map Android](/assets/images/map/tracks_layer_android.png) ![Tracks on the map iOS](/assets/images/map/tracks_layer_ios.png) 

There are several ways to show or not [GPX-tracks](/osmand/personal/myplaces) on the map:

### {% data variables.android-values.configure_map %} menu

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_map %} → {% data variables.android-values.show_gpx %} → &#8230 → Choosing tracks for displayed from the list and setting of track appearance. Info below "{% data variables.android-values.show_gpx %}" shows number of selected tracks on the map: 

![Tracks note](/assets/images/map/tracks_note.png)

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.configure_map %} → {% data variables.ios-values.tracks %} → Choosing tracks for displayed from the list 

![Tracks menu Android](/assets/images/map/tracks_menu_android.png) ![Tracks menu iOS](/assets/images/map/tracks_menu_ios.png) 

###  {% data variables.android-values.shared_string_my_places %} menu


{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.shared_string_my_places %} → {% data variables.android-values.shared_string_gpx_files %} → &#xe802; → {% data variables.android-values.shared_string_show_on_map %}  or ["Map" button](/osmand/personal/tracks#my-places-android) for choosing multiple tracks. 

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.menu_my_places %} → {% data variables.ios-values.tracks %} → &#8250; → {% data variables.ios-values.map_settings_show %} or ["Layer" button](/osmand/personal/tracks#my-places-ios) for choosing multiple tracks.

![Tracks my places Android](/assets/images/map/tracks_myplaces_android.png) ![Tracks menu iOS](/assets/images/map/tracks_myplaces_ios.png)


### Track Appearance (Android)

You can [short tap](/osmand/map/map-context-menu#select-route-short-tap-for-android) on the track on the map -> {% data variables.android-values.shared_string_overview %} -> click to "eye" button for not showing the track on the map.

![Track menu options Android](/assets/images/map/eye_button_android.png)   

[Short tap](/osmand/map/map-context-menu#select-route-short-tap-for-android) on the track on the map -> {% data variables.android-values.shared_string_overview %} -> click to "palette" button for opening Track appearacne menu:

![Track menu Appearance Android](/assets/images/map/track_appearance_menu_android.png)   

- {% data variables.android-values.gpx_split_interval %} - {% data variables.android-values.gpx_split_interval_descr %}.

![Track menu Appearance Split interval Android](/assets/images/map/track_appearance_menu_split_interval_android.png)   

- {% data variables.android-values.gpx_direction_arrows %} - adding direction info for the track.

![Track menu Appearance direction arrows Android](/assets/images/map/track_appearance_menu_direction_arrows_android.png)   

- {% data variables.android-values.track_show_start_finish_icons %} - showing or not start / finish icons of the track.

![Track menu Appearance start and finish icons Android](/assets/images/map/track_appearance_menu_sf_icons_android.png)  

- {% data variables.android-values.shared_string_color %} -  select color for the track: color by {% data variables.android-values.track_coloring_solid %} (constant color), {% data variables.android-values.map_widget_speed %} (color depends on speed info of the track), {% data variables.android-values.map_widget_altitude %} (color depends on altitude info of the track), {% data variables.android-values.shared_string_slope %} (color depends on slope info of the track). For planning trip, user can choose color of route infor data: 
{% data variables.android-values.routeInfo_roadClass_name %}, {% data variables.android-values.routeInfo_surface_name %}, {% data variables.android-values.routeInfo_smoothness_name %}, {% data variables.android-values.routeInfo_winter_ice_road_name %}, {% data variables.android-values.routeInfo_surface_name %}.

![Track menu Appearance Track color Android](/assets/images/map/track_appearance_menu_track_color_android.png) 

- {% data variables.android-values.select_track_width %} - rendering of thikness for the track: {% data variables.android-values.rendering_value_thin_name %}, {% data variables.android-values.rendering_value_medium_name %}, {% data variables.android-values.rendering_value_bold_name %}, {% data variables.android-values.shared_string_custom %}.

![Track menu Appearance Track Thickness Android](/assets/images/map/track_appearance_menu_track_thickness_android.png) 

## Navigation Route

The route is a line on the map that shows a user's creating trip. In OsmAnd users create a route by [Navigation function](/osmand/navigation).

| Android | iOS |
| :--- | :--- |
| ![Route on the map Android](/assets/images/map/route_layer_android.png) |![Route on the map iOS](/assets/images/map/route_layer_ios.png) |

### Route Appearance (Android)

In OsmAnd for Android, [a user can customize](/osmand/personal/profiles) route line: color and width.

{% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %} → {% data variables.android-values.profile_appearance %} → {% data variables.android-values.customize_route_line %}

![Route Customization Android](/assets/images/map/route_custom_android.png)

## Travel Routes


- Hiking 
- Bicycle
- Node networks

Link to [Vector map style](/osmand/map/vector-maps#routes).


## Analyze Route on Map (Android)

![Track menu analyze on map Android](/assets/images/personal/tracks/track_analyze_on_map_android.png) ![Track menu analize on the map distance Android](/assets/images/personal/tracks/track_analyze_on_map_distance_android.png) 

- Interact with map & graph
- Follow My location 
- Graph: altitude / slope / speed
- Graph: distance / time



## Read more

### [Tracks](/osmand/personal/tracks)
### [Track Context menu](/osmand/map/track-context-menu)
### [Configure map menu](/osmand/map/configure-map-menu)
### [Trip recording](/osmand/plugins/trip-recording)
### [Plan a route](/osmand/plan-route)
### [Navigation by track](/osmand/navigation/gpx-navigation)
