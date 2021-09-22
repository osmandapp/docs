---
title: "Boat navigation"
intro: "Boat navigation"
versions: '*'
---

{% data reusables.general.article-not-complete %}


Boat mode for navigation can be enabled together with [the Nautical plugin](/osmand/plugins/nautical-charts). You can build your trip on rivers or waterway fairway. You can read more about navigation profiles [here](/osmand/personal/profiles).

![Boat Navigation screen Android](/assets/images/navigation/boat/boat_navigation_android.png) ![Boat Navigation screen iOS](/assets/images/navigation/boat/boat_navigation_ios.png)
  
## How to use

Navigation type for Boat navigation is [Boat](/osmand/navigation/boat-navigation#boat) by default. This type uses rivers or waterway fairways for building your route. 
For starting naviation user need to click [navigation button](/osmand/widgets/map-buttons#directions) on the screen or choose ["Navigation" in the main menu](/osmand/start-with/main-menu#features):

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.shared_string_navigation %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.routing_settings %}

User need to choose start-finish points on a river, for example. 

![Boat Navigation screen points Android](/assets/images/navigation/boat/boat_navigation_points_android.png) ![Boat Navigation screen points iOS](/assets/images/navigation/boat/boat_navigation_points_ios.png)

### Details

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.shared_string_navigation %} → {% data variables.android-values.rendering_category_details %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.routing_settings %} → {% data variables.ios-values.res_details %}

![Boat Navigation screen details Android](/assets/images/navigation/boat/boat_navigation_details_android.png) ![Boat Navigation screen details iOS](/assets/images/navigation/boat/boat_navigation_details_ios.png)

buttons:
- &#128438; (Android) - allows to save and print your route like data table.
- {% data variables.android-values.save_as_new_track %} (Android) - allows...
- {% data variables.ios-values.shared_string_export %} or share - allows...

Graph with altitude info.

Button [Analyse on map](/osmand/navigation/route-navigation#details)

{% data variables.ios-values.routeInfo_steepness_name %} info.

{% data variables.android-values.step_by_step %} instructions (Android)


### Options

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.shared_string_navigation %} → {% data variables.android-values.shared_string_options %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.routing_settings %} → {% data variables.ios-values.shared_string_options %}

![Boat Navigation screen options Android](/assets/images/navigation/boat/boat_navigation_options_android.png) ![Boat Navigation screen options iOS](/assets/images/navigation/boat/boat_navigation_options_ios.png)

- {% data variables.android-values.shared_string_sound %} - allows to switch off/on voice prompts and to open [voice prompts settings menu](/osmand/personal/profiles#navigation-settings).
- {% data variables.android-values.impassable_road %} - allows to select a road you want to avoid during navigation.
- {% data variables.android-values.show_along_the_route %} (Android) - link
- {% data variables.android-values.follow_track %} - link
- {% data variables.android-values.temporary_conditional_routing %} - link
- {% data variables.android-values.routing_settings_2 %} - opens [Navigation settings menu](/osmand/personal/profiles#navigation-settings) of your app profile.
- {% data variables.android-values.customize_route_line %} (Android) - [link](/osmand/map/tracks-on-map#route-appearance-android).
- {% data variables.android-values.simulate_navigation %} - allows to simulate your navigation trip.


## Navigation types

In OsmAnd users can choose boat navigation types. It's a need for different use cases. 
[Boat navigation type](/osmand/navigation/boat-navigation#boat) is by default for Boat profile. Advanced users can choose additional two navigation types for boat navigation: [Direct-to-point](/navigation/boat-navigation#direct-to-point) and [Straight-line](/osmand/navigation/boat-navigation#straight-line).

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %}({% data variables.android-values.app_mode_boat %}) → {% data variables.android-values.routing_settings_2 %} → {% data variables.android-values.nav_type_hint %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.sett_settings %} → {% data variables.ios-values.app_profiles %} ({% data variables.ios-values.app_mode_boat %}) → {% data variables.ios-values.sett_settings %} → {% data variables.ios-values.routing_settings_2 %} → {% data variables.ios-values.nav_type_title %}

### Boat

Boat navigation type (by default for Boat app profiles) uses rivers, waterway fairway for routing. 
User can calculate distance for koyak trip, for example.

![Boat Navigation type Android](/assets/images/navigation/boat/boat_navigation_type_android.png) ![Boat Navigation type iOS](/assets/images/navigation/boat/boat_navigation_type_ios.png)


### Direct-to-point

Next version of navigation type for boat:  **Direct-to-point**. Direct-to-point navigation is a critical and frequently used feature for marine users.

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %}({% data variables.android-values.app_mode_boat %}) → {% data variables.android-values.routing_settings_2 %} → {% data variables.android-values.nav_type_hint %} → {% data variables.android-values.routing_profile_direct_to %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.sett_settings %} → {% data variables.ios-values.app_profiles %} ({% data variables.ios-values.app_mode_boat %}) → {% data variables.ios-values.sett_settings %} → {% data variables.ios-values.routing_settings_2 %} → {% data variables.ios-values.nav_type_title %} → {% data variables.ios-values.nav_type_direct_to %}

How to make your navigation profile with your parameters read [here](/osmand/personal/profiles).

It is possible to specify the recalculation distance (by default it is OFF for this routing profile). The route will be recalculated if the distance from the route to the current location is more than selected value.
Next, in case if you deviate from the route during the navigation, this setting builds the shortest path from your current position to the calculated route with the maximum angle. In other words, if the angle is higher than the one set by the user, OsmAnd calculates the next point of the route to build an additional route segment, so the angle will be valid.

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %}({% data variables.android-values.app_mode_boat %}) → {% data variables.android-values.routing_settings_2 %} → {% data variables.android-values.route_parameters %} → {% data variables.android-values.route_recalculation_dist_title %} and {% data variables.android-values.recalc_angle_dialog_title %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.sett_settings %} → {% data variables.ios-values.app_profiles %} ({% data variables.ios-values.app_mode_boat %}) → {% data variables.ios-values.sett_settings %} → {% data variables.ios-values.routing_settings_2 %} → {% data variables.ios-values.route_parameters %} → {% data variables.ios-values.recalculate_route %} and {% data variables.android-values.recalc_angle_dialog_title %}

Also, you can see a point projection that represents the distance to the end point on the line. The point on the line is a virtual point to show the distance (it is not a projection on the line) but a point that has the same distance as current location to the finish point. So it is easy to measure the progress and it is possible to use measurements tool to get correct distance.

![Direct-to-point Navigation type Android](/assets/images/navigation/boat/direct_navigation_type_android.png)

### Straight line

The next navigation type:  **Straight line**.

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %}({% data variables.android-values.app_mode_boat %}) → {% data variables.android-values.routing_settings_2 %} → {% data variables.android-values.nav_type_hint %} → {% data variables.android-values.routing_profile_straightline %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.sett_settings %} → {% data variables.ios-values.app_profiles %} ({% data variables.ios-values.app_mode_boat %}) → {% data variables.ios-values.sett_settings %} → {% data variables.ios-values.routing_settings_2 %} → {% data variables.ios-values.nav_type_title %} → {% data variables.ios-values.nav_type_straight_line %}

There is also a new setting to specify at which distance of user's location from route to start recalculation.
The route will be recalculated if the distance from the route to the current location is more than selected value:

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %}({% data variables.android-values.app_mode_boat %}) → {% data variables.android-values.routing_settings_2 %} → {% data variables.android-values.route_parameters %} → {% data variables.android-values.route_recalculation_dist_title %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.sett_settings %} → {% data variables.ios-values.app_profiles %} ({% data variables.ios-values.app_mode_boat %}) → {% data variables.ios-values.sett_settings %} → {% data variables.ios-values.routing_settings_2 %} → {% data variables.ios-values.route_parameters %} → {% data variables.ios-values.recalculate_route %}

![Streaight-line Navigation type Android](/assets/images/navigation/boat/straight_navigation_type_android.png)

Professional sailors are required to have official maps, as well, but this extension can be of great help to you in a small voyage or be a supplement to the official nautical charts.
