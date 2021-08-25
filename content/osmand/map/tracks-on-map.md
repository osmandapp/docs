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
    - Track as a route -  file has ```<rtept>``` points array, each point described as an intermediate point of the route. It depends on how points within a route should be connected either as small route segments or via straight line. These tracks are displayed on the map as dashed lines. 
    - Waypoints - file has ```<wpt>``` points with attributes. Waypoints are displayed as circular points on the map. You could click on them to get additional information.
2. [Navigation Route](#navigation-route) - a route line displayed during [navigation](/osmand/navigation/route-navigation). By default this is a solid transparent blue line, though default appearance depends on [vector map style](/osmand/map/vector-maps#default-map-styles), [day & night mode](/osmand/map/vector-maps#map-mode). It's also possible to fully customize it on Android.
3. [Routes and route networks on the map](#routes-on-the-map) - special [objects](/osmand/map/vector-maps#routes) on the map from [OpenStreetMap](https://wiki.openstreetmap.org/wiki/Relation:route) data and provided with standard vector maps. They typically represent popular local routes and could be displayed in many ways (shields, color, thickness, pattern). To use these types of routes you will need to enable them on the map.

Read more about [GPX Tracks](/osmand/personal/tracks#track).

## Tracks 

There are two options to display [Tracks](/osmand/personal/tracks) on the map: via [{% data variables.android-values.configure_map %}](/osmand/map/tracks-on-map#display-via-configure-map-menu) menu or [{% data variables.android-values.shared_string_my_places %}](/osmand/map/tracks-on-map#display-via-my-places-menu) menu

![Tracks on the map Android](/assets/images/map/tracks_layer_android.png) ![Tracks on the map iOS](/assets/images/map/tracks_layer_ios.png) 

### Display via {% data variables.android-values.configure_map %} menu

{% data reusables.general.android-ios-switcher %}

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_map %} → {% data variables.android-values.show_gpx %} → &#8230 → Choosing tracks for display from the list and setting track appearance.

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.configure_map %} → {% data variables.ios-values.tracks %} → Choosing tracks for displayed from the list 

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

{% data reusables.general.android-ios-switcher %}

In OsmAnd you can change the color, the thickness of the track, display arrows and icons of the starting and ending points.

To get to the track Appearance menu, you need to display track on the map, then in the [track Context menu](https://docs.osmand.net/en/main@latest/osmand/map/track-context-menu#overview) in the {% data variables.android-values.shared_string_overview %} section, [shortly](/osmand/map/map-context-menu#select-route-short-tap-for-android) click on the "palette" icon. 

{% default %}

{% enddefault %}

{% android %}

![Track menu options Android](/assets/images/map/eye_button_android.png) ![Track menu Appearance Android](/assets/images/map/track_appearance_menu_android.png) 

{% endandroid %}

{% ios %}

![Track menu iOS](/assets/images/map/eye_button_ios.png) ![Configure color iOS](/assets/images/map/track_appearance_menu_ios.png) 

{% endios %}

|**Parameter and Description**|   
|------------|--------|
|**{% data variables.android-values.gpx_split_interval %}** - splits track into intervals by distance or time.|
|![Track menu Appearance Split interval Android](/assets/images/map/track_appearance_menu_split_interval_android.png)| 
|**{% data variables.android-values.gpx_direction_arrows %}** - adds direction info for the track.|
|![Track menu Appearance direction arrows Android](/assets/images/map/track_appearance_menu_direction_arrows_android.png)|  
|**{% data variables.android-values.track_show_start_finish_icons %}** - shows or hides start/finish icons of the track.|
|![Track menu Appearance start and finish icons Android](/assets/images/map/track_appearance_menu_sf_icons_android.png)|  
|**{% data variables.android-values.shared_string_color %}** -  you can change the color of the track with solid fill and gradient. To make the track solid, select the Solid fill and color. When choosing to color by speed, height, slope, etc., the track will have a gradient fill according to the track data.|
|![Track menu Appearance Track color Android](/assets/images/map/track_appearance_menu_track_color_android.png)|
|**{% data variables.android-values.select_track_width %}** - allows configuring thickness for the track: {% data variables.android-values.rendering_value_thin_name %}, {% data variables.android-values.rendering_value_medium_name %}, {% data variables.android-values.rendering_value_bold_name %}, {% data variables.android-values.shared_string_custom %}.|
|![Track menu Appearance Track Thickness Android](/assets/images/map/track_appearance_menu_track_thickness_android.png)|

### Analyze Track on Map (Android)

This option allows you to review track information on the map. To get access to this menu shortly tap on the track → [{% data variables.android-values.shared_string_options %}](/osmand/map/track-context-menu#options) → {% data variables.android-values.analyze_on_map %}

![Track menu analyze on map Android](/assets/images/personal/tracks/track_analyze_on_map_android.png) ![Track menu analize on the map distance Android](/assets/images/personal/tracks/track_analyze_on_map_distance_android.png) 

- Graph: altitude / slope / speed - data of vertical axis. Here users can choose: Altitude, Slope, Speed, Altitude/Slope, Altitude/Speed data for viewing on Graph.

![Track menu analyze on map 1 Android](/assets/images/personal/tracks/track_analyze_on_map_1_android.png) ![Track menu analyze on map 1.1 Android](/assets/images/personal/tracks/track_analyze_on_map_1.1_android.png)

- Graph: distance / time - data of horizontal data. Users can choose: Distance, Time, Time of day for analyzing data of vertical axis by timing or distance.

![Track menu analyze on map 2 Android](/assets/images/personal/tracks/track_analyze_on_map_2_android.png) ![Track menu analyze on map 2.1 Android](/assets/images/personal/tracks/track_analyze_on_map_2.1_android.png)


- Interact with map & graph - tap to Graph for showing info about track point and moving finger along Graph shows info about points of the track. User can scale Graph by [two fingers](/osmand/map/interact-with-map#gestures). 

![Track menu analyze on map 3 Android](/assets/images/personal/tracks/track_analyze_on_map_3_android.png) ![Track menu analyze on map 4 Android](/assets/images/personal/tracks/track_analyze_on_map_4_android.png)

- Follow My location - new function for [navigation by track](/osmand/navigation/gpx-navigation).

![Track menu analyze on map 5 Android](/assets/images/personal/tracks/track_analyze_on_map_5_android.png)



## Navigation Route

Navigation route is a line between user-defined points. In OsmAnd, the user builds a route taking into account the navigation parameters.

 ![Route on the map Android](/assets/images/map/route_layer_android.png) ![Route on the map iOS](/assets/images/map/route_layer_ios.png)

### Route Appearance (Android)

You can customize the route line's appearance for any navigation profile. It is available to select the color and width of the line.

{% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %} → {% data variables.android-values.profile_appearance %} → {% data variables.android-values.customize_route_line %}

![Route Customization Android](/assets/images/map/route_custom_android.png)

## Routes on the map

{% data reusables.general.android-ios-switcher %}

One kind of route is node-based cycling, hiking or other routes from the OpenStreetMap. You can enable them in OsmAnd as an additional layer. 

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_map %} → {% data variables.android-values.map_widget_map_rendering %} → {% data variables.android-values.rendering_category_routes %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.configure_map %} → {% data variables.ios-values.map_settings_style %} → {% data variables.ios-values.rendering_category_routes %}

{% default %}

{% enddefault %}

{% android %}

![Configure Map Routes section](/assets/images/map/configure_map_routes_android.png) 

{% endandroid %}

{% ios %}

![Track menu iOS](/assets/images/map/configure_map_routes_ios.png) 

{% endios %}


![Map routes - hiking osmc](/assets/images/map/map-routes-hiking-osmc.png)![Map routes - cycle-node-networks](/assets/images/map/map-routes-cycle-node-networks.png)

Read more about Travel routes for [Vector map style](/osmand/map/vector-maps#routes).

## Read more

{% link_with_intro /osmand/personal/tracks %}

{% link_with_intro /osmand/map/track-context-menu %}

{% link_with_intro /osmand/map/configure-map-menu %}

{% link_with_intro /osmand/plan-route %}

{% link_with_intro /osmand/plugins/trip-recording %}

{% link_with_intro /osmand/navigation/gpx-navigation %}

