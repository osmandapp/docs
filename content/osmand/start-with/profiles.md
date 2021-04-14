---
title: "Application profiles"
intro: "Application profiles"
versions: '*'
---
## Profile types

There are few profile types set by default in OsmAnd.

|   Profile type |  OS |
| :------------- | :------------- |
| {% data variables.android-values.rendering_value_browse_map_name %} | Android/iOS |
|{% data variables.android-values.routing_engine_vehicle_type_driving  %}   | Android/iOS   |  
|{% data variables.android-values.activity_type_cycling_name  %}   | Android/iOS   |   
| {% data variables.android-values.routing_engine_vehicle_type_walking  %}  |   Android/iOS |  
|{% data variables.android-values.app_mode_public_transport  %}   |  Android/iOS |  
| {% data variables.android-values.routing_engine_vehicle_type_truck  %}  | Android  |   
|  {% data variables.android-values.app_mode_motorcycle  %}  |  Android  |   
|  {% data variables.android-values.app_mode_boat %}  | Android/iOS  |   
| {% data variables.android-values.app_mode_aircraft %}  |  Android/iOS |  
| {% data variables.android-values.app_mode_skiing %}   |  Android/iOS |   

## Profile settings

All  profiles can be configure.

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.rendering_value_browse_map_name %} or any other profile that has been set before → {% data variables.android-values.configure_profile %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.sett_settings %} → {% data variables.ios-values.app_profiles %} → {% data variables.ios-values.rapp_mode_default %} or any other profile that has been set before  → {% data variables.ios-values.configure_profile %} → {% data variables.ios-values.shared_string_enabled%} turn on or off

>**Note**: For Android the profile can be changed in 'Configure profile' by tapping the relevant icon at the top right corner

<!--
|   | settings  | OS| profile |
| :------------- | :------------- | :------------- | :------------- |
| Profile settings | {% data variables.android-values.general_settings_2 %} | Android/iOS | all  |
|   | {% data variables.android-values.routing_settings_2 %}   |  Android/iOS | all, except {% data variables.android-values.rendering_value_browse_map_name %}  |
|   |  {% data variables.android-values.configure_map %}  |  Android/iOS  |  all |
|   |  {% data variables.android-values.layer_map_appearance %} |  Android/iOS  |  all |
|   | {% data variables.android-values.profile_appearance %}  | Android/iOS  |  all |
|   | {% data variables.android-values.ui_customization %}   |  Android  | all  |
|  Plugin settings |  {% data variables.android-values.shared_string_trip_recording %} | Android/iOS  | all  |
|   | {% data variables.android-values.audionotes_plugin_name %}  | Android  |  all |
|   |  {% data variables.android-values.osm_settings %}  |  Android |  all |
|   | {% data variables.android-values.open_place_reviews%}   | Android  |  all |
|   |  {% data variables.android-values.shared_string_accessibility%} | Android  | all  |
|   |  {% data variables.android-values.debugging_and_development%}  |  Android |  all |
|  Actions  | {% data variables.android-values.export_profile%}  | Android/iOS  | all  |
|   | {% data variables.android-values.copy_from_other_profile%}  |  Android/iOS |  all |
|   | {% data variables.android-values.reset_to_default%}   |  Android/iOS |  all |
|   | {% data variables.android-values.profile_alert_delete_title%}  |  Android | all  |

-->
|   | settings  | OS| profile |
| :------------- | :------------- | :------------- | :------------- |
| Profile settings | [General settings](#general-settings) | Android/iOS | all  |
|   | [Navigation settings](#navigation-settings)	  |  Android/iOS | all, except {% data variables.android-values.rendering_value_browse_map_name %}  |
|   |  [Configure map](#configure-map)	 |  Android/iOS  |  all |
|   |  [Configure screen](#configure-screen)	 |  Android/iOS  |  all |
|   | 	[Profile appearance](#profile-appearance)  | Android/iOS  |  all |
|   | 	[UI Customization](#ui-customization)  |  Android  | all  |

## Creating new navigation profiles (custom profiles)

Users can create new navigation profiles based on default app profiles. It defines basic setup like widgets' visibility, speed and distance units. Other parameters can be configured.

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.rendering_value_browse_map_name %} or any other profile that has been set before → {% data variables.android-values.new_profile %} → choose the profile from the list → add {% data variables.android-values.profile_name_hint%} → {% data variables.android-values.select_color%} → {% data variables.android-values.select_icon_profile_dialog_title %} → {% data variables.android-values.select_color%} → select {% data variables.android-values.select_map_icon %} → select {% data variables.android-values.select_navigation_icon %} → press {% data variables.android-values.shared_string_save  %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %}→ {% data variables.ios-values.sett_settings %} → {% data variables.ios-values.app_profiles %} → {% data variables.ios-values.new_profile %} → choose the profile from the list → {% data variables.ios-values.enter_profile_name %} → select {% data variables.ios-values.profile_appearance%} → {% data variables.ios-values.select_icon %} → {% data variables.ios-values.appearance_on_map %} → select {% data variables.ios-values.position_icon_at_rest %} → select {% data variables.ios-values.position_icon_while_moving %} → press {% data variables.ios-values.shared_string_save%} at the top right corner.

## General settings

|  | settings  |configurations | OS |
| :------------- | :------------- | :------------- | :------------- |
| {% data variables.android-values.shared_string_appearance %} | {% data variables.android-values.choose_osmand_theme %} | {% data variables.android-values.dark_theme %}/{% data variables.android-values.light_theme %} | Android  |
|   | {% data variables.android-values.rotate_map_to_bearing %}  |  {% data variables.android-values.rotate_map_none_opt %}/ {% data variables.android-values.rotate_map_bearing_opt %}/ {% data variables.android-values.rotate_map_compass_opt %} |  Android/iOS  |
|   |  {% data variables.android-values.always_center_position_on_map %}  | turn on/off and {% data variables.android-values.apply_to_all_profiles %}/ Apply only to selected profile/ {% data variables.android-values.discard_changes %}  | Android/iOS   |
|   |  {% data variables.android-values.map_screen_orientation %}  | {% data variables.android-values.map_orientation_portrait %}/ {% data variables.android-values.map_orientation_landscape %}/ {% data variables.android-values.map_orientation_default %}  |  Android |
|   | {% data variables.android-values.screen_control %}   | {% data variables.android-values.screen_timeout %}/ {% data variables.android-values.turn_screen_on %}  |  Android |
|   |   {% data variables.ios-values.allow_3D_view %} | turn on or off  |  iOS |
| {% data variables.android-values.units_and_formats %}  |  {% data variables.android-values.driving_region %}   |  {% data variables.android-values.driving_region_automatic %}/ [list of regions](#list-of-regions)|  Android/iOS    |
|   |  {% data variables.android-values.coords_format %}  | [list of coordinate format](#list-of-coordinate-format)  |  Android/iOS |
|   |   {% data variables.android-values.angular_measeurement %} | {% data variables.android-values.shared_string_degrees %} 180/ {% data variables.android-values.shared_string_degrees %} 360/ {% data variables.android-values.shared_string_milliradians %}    |Android/iOS   |
|   |   {% data variables.android-values.default_speed_system %} |  [list of unit speed ](#list-of-unit-speed ) |Android/iOS     |
| {% data variables.android-values.shared_string_other%}  |  {% data variables.android-values.use_volume_buttons_as_zoom %}  |  turn on or off ability to control the map zoom level using the volume buttons on the device  | Android  |
|   |   {% data variables.android-values.use_kalman_filter_compass%}  | turn on/off an ability to reduce noise in compass reading  (adds inertia)  | Android  |
|   |   {% data variables.android-values.use_magnetic_sensor %}   |  turn/or off (highly recommended to use it for compass reading) | Android  |
|   |  {% data variables.android-values.tap_on_map_to_hide_interface %}   |  turn on/off (a tap on the toggles the control buttons and widgets) |  Android |
|   |  {% data variables.android-values.do_not_use_animations %}  |  turn on/off and {% data variables.android-values.apply_to_all_profiles %}/ Apply only to selected profile/ {% data variables.android-values.discard_changes %}   |  Android |
|   | {% data variables.android-values.do_not_use_animations %}  | {% data variables.android-values.sett_generic_ext_input %}/ {% data variables.android-values.sett_wunderlinq_ext_input %}/ {% data variables.android-values.sett_parrot_ext_input %}(Android only)   | Android/iOS   |

### list of regions

|Region | {% data variables.android-values.right_side_navigation %} |{% data variables.android-values.left_side_navigation%} |
| :------------- | :------------- | :------------- |
| {% data variables.android-values.driving_region_europe_asia %} | {% data variables.android-values.si_km_m %} | - |
|  {% data variables.android-values.driving_region_us %} | {% data variables.android-values.si_mi_feet %}  |  - |  
|  {% data variables.android-values.driving_region_canada %} |  {% data variables.android-values.si_km_m %}  | -  |
|  {% data variables.android-values.driving_region_uk %} |  - | {% data variables.android-values.si_mi_meter %} |  
| {% data variables.android-values.driving_region_japan %}  | -   | {% data variables.android-values.si_km_m %} |  
|  {% data variables.android-values.driving_region_australia %} |   - | {% data variables.android-values.si_km_m %} |  

### list of coordinate format

| Type | {% data variables.android-values.shared_string_examplen %} | Note |
| :------------- | :------------- | :------------- |
| {% data variables.android-values.navigate_point_format_D %} | 49.41869° N, 8.67339° E | - |
|  {% data variables.android-values.navigate_point_format_DM %} | 49°25.121'N, 08°40.403' E |  - |  
|  {% data variables.android-values.navigate_point_format_DMS %} |  49°25'07.3"N, 08°40'24.2" E  | -  |
|  {% data variables.android-values.navigate_point_format_utm %} |  32N 476311 5474052  | OsmAnd uses the UTM Standart, which is similar but not identical to the UTM NATO format. [Read more ](#https://en.m.wikipedia.org/wiki/Universal_Transverse_Mercator_coordinate_system )|  
| {% data variables.android-values.navigate_point_format_mgrs %}  | 32U MV 76311 74052  |OsmAnd uses the MGRS, which is similar to the UTM NATO format. [Read more ](#https://en.m.wikipedia.org/wiki/Military_Grid_Reference_System) |  
|  {% data variables.android-values.navigate_point_format_olc %} | 8FXCCM9F+F9 | -|  

### list of unit speed

* {% data variables.android-values.si_kmh %}
* {% data variables.android-values.si_mph %}
* {% data variables.android-values.si_m_s %}
* {% data variables.android-values.si_min_m %}
* {% data variables.android-values.si_min_km %}
* {% data variables.android-values.si_nm_h %}


## Navigation settings

In Navigation settings user can configure navigation parameters for profile.

>**Note**:  parameters change for different  Navigation types.

<!--
|  | settings  |configurations | OS |
| :------------- | :------------- | :------------- | :------------- |
| Navigation | {% data variables.android-values.nav_type_title %} |  | Android/iOS   |
|   | {% data variables.android-values.route_parameters %}  |   |  Android/iOS  |
|   |  {% data variables.android-values.screen_alerts %}  |   | Android/iOS   |
|   |  {% data variables.android-values.voice_announces %}  |  |  Android/iOS   |
|   | {% data variables.android-values.vehicle_parameters %}   | |  Android/iOS |
| {% data variables.android-values.help_other_header %}| {% data variables.android-values.map_during_navigation_info %}  |  |   Android/iOS |
|  |  {% data variables.android-values.animate_my_location %}   |  |  Android   |
-->
|  | settings  |configurations | OS |
| :------------- | :------------- | :------------- | :------------- |
| Navigation | {% data variables.android-values.nav_type_hint %}| defines how the routes will be calculated. Choose [default navigation types](default-navigation-types) or import a modified routing file [routing.xml ](https://github.com/osmandapp/OsmAnd-resources/blob/master/routing/routing.xml)(only for Android). | Android/iOS   |
|   | {% data variables.android-values.route_parameters %}  |  gives a set of settings to [configure routing for selected profile](configure-routing-for-selected-profile )  |  Android/iOS  |
|   |  {% data variables.android-values.screen_alerts %}  |   | Android/iOS   |
|   |  {% data variables.android-values.voice_announces %}  |  |  Android/iOS   |
|   | {% data variables.android-values.vehicle_parameters %}   | |  Android/iOS |
| {% data variables.android-values.shared_string_other %}| {% data variables.android-values.map_during_navigation_info %}  |  |   Android/iOS |
|  |  {% data variables.android-values.animate_my_location %}   |  |  Android   |

### default navigation types

|   Navigation type |  Description |
| :------------- | :------------- |
| {% data variables.android-values.rendering_value_bicycle_name %} | Prefers cycling paths, tracks, cycle routes and footways.|
|{% data variables.android-values.app_mode_boat  %}   |  Prefers waterways, rivers and water canals|  
|{% data variables.android-values.rendering_value_car_name %}   |  Prefers motorways, highways and unpaved roads  |   
| {% data variables.android-values.routing_profile_direct_to  %}  |  Draws the straight line between start and finish points. User can see a point projection that represents the distance to the end point on the line. The point on the line is a virtual point to show the distance (it is not a projection on the line) but a point that has the same distance as current location to the finish point  |  
|{% data variables.android-values.rendering_value_pedestrian_name  %}   |  Prefers hiking routes, footways |  
| {% data variables.android-values.app_mode_public_transport  %}  | Prefers car routes  |   
|  {% data variables.android-values.routing_profile_ski  %}  |  Prefers hills, slopes, ski trails  |   
|  {% data variables.android-values.routing_profile_straightline %}  |  Draws the straight line between start and finish points and redraw the strait line when users position changes. In case user deviate from the route during the navigation, this setting builds the shortest path from your current position to the calculated route with the maximum angle. |   

<!-- ### configure route parameters

|  general| settings  |configurations | OS |
| :------------- | :------------- | :------------- | :------------- |
| Navigation | {% data variables.android-values.nav_type_title %} |  | Android/iOS   |
|   | {% data variables.android-values.route_parameters %}  |   |  Android/iOS  |
|   |  {% data variables.android-values.screen_alerts %}  |   | Android/iOS   |
|   |  {% data variables.android-values.voice_announces %}  |  |  Android/iOS   |
|   | {% data variables.android-values.vehicle_parameters %}   | |  Android/iOS |
| {% data variables.android-values.help_other_header %}| {% data variables.android-values.map_during_navigation_info %}  |  |   Android/iOS |
|  |  {% data variables.android-values.animate_my_location %}   |  |  Android   |
-->

### configure routing for selected profile
<!--
|  | Car  |Bicycle | On foot |
| :------------- | :-------------: | :-------------: | :------------- |
| Avoid roads (and road types)| turn on/off ({% data variables.android-values.routing_attr_avoid_toll_name %}/ {% data variables.android-values.routing_attr_avoid_unpaved_name %}/ {% data variables.android-values.routing_attr_avoid_ferries_name %}/ {% data variables.android-values.routing_attr_avoid_shuttle_train_name %}/ {% data variables.android-values.routing_attr_avoid_motorway_name%}/ {% data variables.android-values.routing_attr_avoid_borders_name %}/ {% data variables.android-values.routing_attr_avoid_ice_roads_fords_name %} ) | turn on/off ({% data variables.android-values.routing_attr_avoid_unpaved_name%}/ {% data variables.android-values.routing_attr_avoid_unpaved_name%}|  |

-->

| Route parameters | Car  |Bicycle | On foot | OS |
| :------------- | :-------------: | :-------------: | :-------------: | :------------- |
| **Avoid roads (and road types)**|**turn on/off**|Android/iOS |
|{% data variables.android-values.routing_attr_avoid_toll_name %}| ✔ | - | - | |  
|{% data variables.android-values.routing_attr_avoid_unpaved_name %}| ✔ | ✔ | ✔ | |
|{% data variables.android-values.routing_attr_avoid_ferries_name %}  | ✔  | ✔  | ✔  |  |
|{% data variables.android-values.routing_attr_avoid_shuttle_train_name %}|  ✔ |  - | -  | |   
|{% data variables.android-values.routing_attr_avoid_motorway_name %} | ✔ | -  |  ✔ |  |
|{% data variables.android-values.routing_attr_avoid_borders_name %}|  ✔  |  ✔  |  - | |
|{% data variables.android-values.routing_attr_avoid_ice_roads_fords_name %}| ✔ | - | - | |   
|{% data variables.android-values.routing_attr_avoid_stairs_name %}| - | ✔ | ✔  |  |
|{% data variables.android-values.routing_attr_avoid_footways_name %}| - |  ✔ | - | |  
|{% data variables.android-values.routing_attr_avoid_sett_name %}| - | ✔ | - |  |
| **Prefer...**| **turn on/off**| Android/iOS  |
|{% data variables.android-values.routing_attr_driving_style_prefer_unpaved_name %}|  ✔  |  - | - | |  
|{% data variables.android-values.routing_attr_prefer_hiking_routes_name %}| - |  ✔  | - |  |
| **{% data variables.android-values.routing_attr_short_way_name %}** (optimized shorter route for energy saving)| **turn on/off** | Android/iOS |
|**{% data variables.android-values.routing_attr_allow_private_name %}** (allow access to private areas) | **turn on/off** |Android/iOS |
|   |✔   |✔ |✔ ||
|**{% data variables.android-values.routing_attr_height_obstacles_name %}** (routing could avoid strong uphills)| **turn on/off**     |Android/iOS|
|   |  | ✔|||
|**{% data variables.android-values.temporary_conditional_routing %}** (use road restrictions that are active now on the map)|**turn on/off**|Android/iOS|
|   |  ✔ ||||
|**{% data variables.android-values.fast_route_mode% }** (enable to calculate fastest route or for fuel-saving route)|**turn on/off**||
|   |   |✔|||
| **{% data variables.android-values.routing_attr_driving_style_name %}** | - |{% data variables.android-values.routing_attr_driving_style_prefer_unpaved_name %}/  {% data variables.android-values.routing_attr_driving_style_safety_name %}/ {% data variables.android-values.routing_attr_driving_style_balance_name %}/  {% data variables.android-values.routing_attr_driving_style_speed_name %}| -  ||
| **{% data variables.android-values.routing_attr_allow_motorway_name %}** | - | ✔ | - ||
| **{% data variables.android-values.recalculate_route_in_deviation %}** (the route will be recalculated if the distance from the route to the current location is more then selected value)| **turn on/off**| Android/iOS |   
|   | select the distance after witch the route will be recalculated   |   |   ||
|**{% data variables.android-values.in_case_of_reverse_direction %}**|**enabled/disabled**| Android/iOS |
|   | ✔   |   |   ||  
|**{% data variables.ios-values.road_speeds %}** | set the min and max travel speed for roads on the route | iOS |
|   | ✔  |   |   |   |   
|**{% data variables.android-values.use_live_routing %}** (enable navigation for OsmAnd Live changes)   |**enabled/disabled**|   Android     |
|   |  ✔ |   |   |   |  
|**{% data variables.android-values.use_two_phase_routing %}**|**enabled/disabled**| Android |
|   | ✔  |   |   |   |   
| **{% data variables.android-values.use_fast_recalculation %}** (recalculates only the initial part of the route, useful for long trips)|**enabled/disabled**| Android |
|   |  ✔   |   |   |   |   
-->
