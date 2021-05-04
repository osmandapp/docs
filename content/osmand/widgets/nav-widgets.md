---
title: "Navigational widgets"
intro: "Navigational widgets are enabled during navigation to display information such as distance, arrival or left time, next turns, bearing, current street name, lanes information, max speed, approaching alerts, POIs, waypoints."
versions: '*'
---
{% data reusables.general.article-not-complete %}

![Navigational widgets all](/assets/images/widgets/navigational_widgets_all.png)

## Relative / magnetic bearing

The widget shows relative or magnetic bearing in angular unit ({% data variables.android-values.shared_string_degrees %} 180, {% data variables.android-values.shared_string_degrees %} 360, {% data variables.android-values.shared_string_milliradians %}).

[Relative bearing](https://en.wikipedia.org/wiki/Bearing_(angle)#Relative) refers to the angle between the craft's forward direction and the location of another object. For example, an object relative bearing of 0 degrees would be dead ahead; an object relative bearing 180 degrees would be behind.

[Magnetic bearing](https://en.wikipedia.org/wiki/Bearing_(angle)#Absolute) is measured in relation to magnetic north, using the direction toward the magnetic north pole (in northeastern Canada) as a reference point.

![Relative Magnetic bearing widget](/assets/images/widgets/relative_magnetic_bearing_widget.png)

| | |
|------------|------------|
| Enable | {% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.map_widget_config %} → {% data variables.android-values.map_widget_right %} → {% data variables.android-values.map_widget_bearing %} or {% data variables.android-values.map_widget_magnetic_bearing %}  |
|  | {% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.layer_map_appearance %} → {% data variables.ios-values.map_widget_right %} → {% data variables.ios-values.map_widget_magnetic_bearing %} or {% data variables.ios-values.map_widget_bearing %}|
| Format | {% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %} → {% data variables.android-values.general_settings_2 %} → {% data variables.android-values.units_and_formats %} → {% data variables.android-values.angular_measeurement %} |
|        | {% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.sett_settings %} → {% data variables.ios-values.app_profiles %} → {% data variables.ios-values.general_settings_2 %} → {% data variables.ios-values.units_and_formats %} → {% data variables.ios-values.angular_units %} |
| Click | Changes between  Relative bearing or Magnetic bearing (with "M"). |    

## Destination

The widget shows current distance to the navigation finish point.

![Destination widget](/assets/images/widgets/destination_widget.png)

| | |
|------------|------------|
| Enable | {% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.map_widget_config %} → {% data variables.android-values.map_widget_right %} →  {% data variables.android-values.route_descr_destination %} |
|  | {% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.layer_map_appearance %} → {% data variables.ios-values.map_widget_right %} → {% data variables.ios-values.map_widget_distance%}|
| Click | Moving the map to a finish point. |    

## Intermediate destination

The widget shows current distance to the nearest intermediate navigation point.

![Intermediate destination widget](/assets/images/widgets/intermediate_destination_widget.png)

| | |
|------------|------------|
| Enable | {% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.map_widget_config %} → {% data variables.android-values.map_widget_right %} →  {% data variables.android-values.map_widget_intermediate_distance %} |
|  | {% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.layer_map_appearance %} → {% data variables.ios-values.map_widget_right %} → {% data variables.ios-values.map_widget_intermediate_distance %}|
| Click | If the user has one intermediate point, the map will move to the intermediate point. |
|       | If the user has more than two intermediate points, the Destination list with all points will open. |

## Arrival time or Time to go

The widget shows navigation {% data variables.android-values.access_arrival_time %} or {% data variables.android-values.map_widget_time %}.

![Arrival time Time to go widget](/assets/images/widgets/arrival_time_time_to_go_widget.png)

| | |
|------------|------------|
| Enable | {% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.map_widget_config %} → {% data variables.android-values.map_widget_right %} →  {% data variables.android-values.access_arrival_time %} or {% data variables.android-values.map_widget_time %}   |
|  | {% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.layer_map_appearance %} → {% data variables.ios-values.map_widget_right %} → {% data variables.ios-values.access_arrival_time %} or {% data variables.ios-values.map_widget_time %}|
| Click | Changes between "Arrival time" to "Time to go" and vice versa. |  

## Intermediate arrival time or Intermediate time

The widget shows {% data variables.android-values.access_intermediate_arrival_time %} or {% data variables.android-values.map_widget_intermediate_time %} of navigation to the intermediate point.

![Intermediate Arrival time Time widget](/assets/images/widgets/intermediate_arrival_time_and_time_widget.png)

| | |
|------------|------------|
| Enable | {% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.map_widget_config %} → {% data variables.android-values.map_widget_right %} →  {% data variables.android-values.access_intermediate_arrival_time %} or {% data variables.android-values.map_widget_intermediate_time %}   |
|  | {% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.layer_map_appearance %} → {% data variables.ios-values.map_widget_right %} → {% data variables.ios-values.access_intermediate_arrival_time %} or {% data variables.ios-values.map_widget_intermediate_time %}|
| Click | Changes between "Intermediate arrival time" to "Intermediate time" and vice versa. |  

## Speed limit

The widget shows a speed limit for a current road.

Speed limit data from [OpenStreetMap project](http://openstreetmap.org/).

![Speed limit widget](/assets/images/widgets/speed_limit_widget.png)

| |
|------------|------------|
| Enable | {% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.map_widget_config %} → {% data variables.android-values.map_widget_right %} →  {% data variables.android-values.map_widget_max_speed %}  |
|  | {% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.layer_map_appearance %} → {% data variables.ios-values.map_widget_right %} → {% data variables.ios-values.map_widget_max_speed %}|

## Lanes

The widget shows the lanes you have to drive during a navigation with [distance to a maneuver](/development/algorithms/voice-prompt-triggering).

![Lanes widgets](/assets/images/widgets/lanes_widget.png)

| | |
|------------|------------|
| Enable | {% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.map_widget_config %} → {% data variables.android-values.map_widget_appearance_rem %} →  {% data variables.android-values.show_lanes  %} |
|  | {% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.layer_map_appearance %} → {% data variables.ios-values.map_widget_appearance_rem %} → {% data variables.ios-values.show_lanes %} |

## Alert information

The widget shows alerts on the screen during navigation

Warnings are displayed in the lower left corner during navigation.

![Alert information widgets](/assets/images/widgets/alert_information_widget.png)

There is an option to turn on and turn off the alerts such as: {% data variables.android-values.show_traffic_warnings %}, {% data variables.android-values.show_pedestrian_warnings %}, {% data variables.android-values.show_cameras %}, {% data variables.android-values.show_tunnels %}. Other alerts are always active by default.

| | |
|------------|------------|
| Enable | {% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %} → {% data variables.android-values.routing_settings_2 %} →  {% data variables.android-values.screen_alerts  %} |
|  | {% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.sett_settings %} → {% data variables.ios-values.app_profiles %} → {% data variables.ios-values.routing_settings_2 %} → {% data variables.ios-values.screen_alerts %} |
| Distance of showing | {% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %} → {% data variables.android-values.routing_settings_2 %} →  {% data variables.android-values.voice_announces %} →  {% data variables.android-values.announcement_time_title %}|
|  | {% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.sett_settings %} → {% data variables.ios-values.app_profiles %} → {% data variables.ios-values.routing_settings_2 %} → {% data variables.ios-values.voice_announces %} → {% data variables.ios-values.arrival_distance %} |

**List with all Alerts in OsmAnd.**

| | |    |
|------------|------------|------------|
|Name|Description|Icon|
|{% data variables.android-values.show_traffic_warnings %}| [Traffic calming](https://en.wikipedia.org/wiki/Traffic_calming) uses physical design and other measures to improve safety for motorists, pedestrians and cyclists. | ![Alert traffic calming widgets](/assets/images/widgets/warnings_traffic_calming.png)  ![Alert traffic calming us widgets](/assets/images/widgets/warnings_traffic_calming_us.png)|
|{% data variables.android-values.show_pedestrian_warnings %}| [A pedestrian crossing](https://en.wikipedia.org/wiki/Pedestrian_crossing) (primarily British English) or crosswalk is a place designated for pedestrians to cross a road, street, or avenue. OsmAnd shows the alert of uncontrolled pedestrian crossing.  | ![Alert traffic calming widgets](/assets/images/widgets/warnings_pedestrian.png)  ![Alert traffic calming us widgets](/assets/images/widgets/warnings_pedestrian_us.png) |
|{% data variables.android-values.traffic_warning_speed_limit %}| In most countries the [Road speed limits](https://en.wikipedia.org/wiki/Speed_limit) are used to set the legal maximum, middle or minimum speed at which road vehicles may travel on a given stretch of road. In OsmAnd the alert is shown when you exceed the speed. You can set parameters of speed exceeding (0, 5, 10.. km/h). {% data variables.android-values.speed_cameras_alert %} You need to make a choice depending on the law of your country. Select Keep active and you will receive alerts and warnings about speed cameras. Select Uninstall. All data related to speed cameras: alerts, notifications, POIs will be deleted until OsmAnd is completely reinstalled. ![Alert ex_speed widgets](/assets/images/widgets/ex_warning_speed.png)  | ![Alert speed_limit widgets](/assets/images/widgets/warnings_limit.png) ![Alert speed_limit_ca widgets](/assets/images/widgets/warnings_speed_limit_ca.png) ![Alert speed_limit_us widgets](/assets/images/widgets/warnings_speed_limit_us.png)|
|{% data variables.android-values.show_tunnels %}| A tunnel is an underground passageway, esp cars that pass under a mountain, river, or a congested urban area. In OsmAnd the alert "Tunnels" has information about tunnel length. If you are in a tunnel it shows distance to the end of the tunnel.   ![Alert ex_tunnel widgets](/assets/images/widgets/ex_warning_tunnel.png)  | ![Alert warnings_tunnel widgets](/assets/images/widgets/warnings_tunnel.png)  ![Alert warnings_tunnel_us widgets](/assets/images/widgets/warnings_tunnel_us.png) |
|{% data variables.android-values.show_cameras %}| [A traffic enforcement camera](https://en.wikipedia.org/wiki/Traffic_enforcement_camera) is a camera that may be mounted beside or over a road or installed in an enforcement vehicle to detect motoring offenses, including speeding, vehicles going through a red traffic light, vehicles going through a toll booth without paying, unauthorized use of a bus lane, or for recording vehicles inside a congestion charge area.     **NOTE:** {% data variables.android-values.speed_cameras_alert %} For uninstalling speed cameras from OsmAnd: {% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.shared_string_settings %} → {% data variables.android-values.osmand_settings %} → {% data variables.android-values.uninstall_speed_cameras %}, {% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.sett_settings %} → {% data variables.ios-values.app_profiles %} → {% data variables.ios-values.routing_settings_2 %} → {% data variables.ios-values.screen_alerts %} → {% data variables.ios-values.show_cameras %}   | ![Alert traffic calming widgets](/assets/images/widgets/warnings_speed_camera.png)   |
|{% data variables.android-values.traffic_warning_stop %}| [A stop sign](https://en.wikipedia.org/wiki/Stop_sign) is a traffic sign designed to notify drivers that they must come to a complete stop and make sure the intersection is safely clear of vehicles and pedestrians before continuing past the sign.  | ![Alert stop widgets](/assets/images/widgets/warnings_stop.png) |
|{% data variables.android-values.show_railway_warnings %}|This warning means that there is a [railway crossing](https://en.wikipedia.org/wiki/Crossbuck) ahead. | ![Alert warnings_railways widgets](/assets/images/widgets/warnings_railways.png) ![Alert warnings_railways_ca widgets](/assets/images/widgets/warnings_railways_ca.png)  ![Alert warnings_railways_us widgets](/assets/images/widgets/warnings_railways_us.png)  |
|{% data variables.android-values.traffic_warning_border_control %}|This warning indicates that border control is ahead.| ![Alert border control widgets](/assets/images/widgets/warnings_border_control.png)  |
|{% data variables.android-values.traffic_warning_border_control %}| [Hazard symbols or warning symbols](https://en.wikipedia.org/wiki/Hazard_symbol) are recognisable symbols designed to warn about hazardous or dangerous materials, locations, or objects, including electric currents, poisons, and radioactivity. | ![Alert warnings_hazard widgets](/assets/images/widgets/warnings_hazard.png)  ![Alert warnings_hazard_us widgets](/assets/images/widgets/warnings_hazard_us.png) |
|{% data variables.android-values.traffic_warning_payment %}| This warning indicates that a toll booth for a toll road is ahead.   ![Alert toll_booth widgets](/assets/images/widgets/ex_toll_booth.png) | ![Alert speed_limit widgets](/assets/images/widgets/warnings_limit.png) |

## Next turns

The widget shows warnings about your maneuvers with a picture of maneuver and [distance](/development/algorithms/voice-prompt-triggering) to it.

![Next turns widget](/assets/images/widgets/next_turns_widget.png)

| | |
|------------|------------|
| Enable | {% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.map_widget_config %} → {% data variables.android-values.map_widget_left %} → {% data variables.android-values.map_widget_next_turn %}, {% data variables.android-values.map_widget_next_turn_small %}, {% data variables.android-values.map_widget_next_next_turn %}|
|  | {% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.layer_map_appearance %} → {% data variables.ios-values.map_widget_left %} → {% data variables.ios-values.map_widget_next_turn %}, {% data variables.ios-values.map_widget_next_turn_small %}, {% data variables.ios-values.map_widget_next_next_turn %} |

## Street name

The widget shows street names or roads (highway shield), as well as a scheme of the maneuver during navigation.

When driving along a street or highway, the widget shows the name or designation of the current street (road) with a blue arrow.

![Street name POIs widget_2](/assets/images/widgets/street_name_widget_2.png)

When maneuvering, the widget shows the scheme of the maneuver and the name (designation) of the street (road) where to turn.

![Street name POIs widget](/assets/images/widgets/street_name_widget.png)

| |
|------------|------------|
| Enable  |{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.map_widget_config %} → {% data variables.android-values.map_widget_appearance_rem %} →  {% data variables.android-values.map_widget_top_text %} |
|  |For {% data variables.product.ios_button_seq %} always showed |

## POIs/Favorites

The widget shows (Points of interest) POI and Favorites along the route.

There are two distances information near POI/Favorite icon. Top info is the distance to the nearest point on your route, down info is the distance from the nearest route point to POI/Favorite.

Android:

![Street name POIs widget_android](/assets/images/widgets/street_name_poi_widget_android.png)

iOS: in addition to the distance from the nearest route point, the side of the route where POI/Favorite is located is also shown. 

![Street name POIs widget_ios](/assets/images/widgets/street_name_poi_widget_ios.png)

| |
|------------|------------|
| Enable  |{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.get_directions %} → {% data variables.android-values.shared_string_settings %} →  {% data variables.android-values.show_along_the_route %} →  {% data variables.android-values.points_of_interests %}, {% data variables.android-values.shared_string_my_favorites %}, {% data variables.android-values.way_alarms %} |
| Enable  | {% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → Start navigation with one or more intermediate destination → pencil button |

## Read Next

{% link_with_intro /markers %}
