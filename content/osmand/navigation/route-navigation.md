---
title: "Navigation by route"
intro: "Navigation by route"
versions: '*'
---
{% data reusables.general.article-not-complete %}

The navigation function allows you to reach your destination easily using voice guidance (optional).

![Navigation screen Android](/assets/images/navigation/route/navigation_android.png) ![Navigation screen iOS](/assets/images/navigation/route/navigation_ios.png)

## How to use

To start the navigation, you need to use [the navigation button](/osmand/widgets/map-buttons#directions) on the map screen. Or choose navigation option in the main menu:

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.shared_string_navigation %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.routing_settings %}


Next, you'll need to set the starting point and the destination. As for the starting point, you can choose your current location, [Favorite location](/osmand/map/point-layers-on-map#favorites), select a point on the map or use [an address](/osmand/search). You can also set a starting point by long tapping on the map and choosing ['Directions from'](/osmand/map/map-context-menu#directions-to--from) in [Map Context menu](/osmand/map/map-context-menu). To navigate to a point, just press the navigation button in its context menu.

![Navigation screen select point Android](/assets/images/navigation/route/navigation_points_android.png) ![Navigation screen iOS](/assets/images/navigation/route/navigation_points_ios.png)

Tap to {% data variables.android-values.route_from %} (your current position by default) or {% data variables.android-values.route_from %} for select Start-Finish points of your navigation:
- {% data variables.android-values.search_button %} - opens [the search menu](/osmand/search) for choosing point.
- {% data variables.android-values.shared_string_address %} - opens address search menu for choosing point.
- {% data variables.android-values.shared_string_my_location %} - allows to choose Your position for point.
- {% data variables.android-values.shared_string_select_on_map %} - opens the map for choosing point by tapping on the map.
- {% data variables.android-values.shared_string_favorites %} - allows to choose [Favorite](/osmand/personal/favorites) for point.
- {% data variables.android-values.shared_string_markers %} - allows to choose [Map marker](/osmand/personal/markers) for point.
- Swap Starting point and Destination - allows to change Start <-> Finish points.


"Swap Starting point and Destination" and "&#43;" buttons:
- "Swap Starting point and Destination" - allows to change Start <-> Finish points.
- "&#43;" - allows to add [intermediate points](/osmand/widgets/nav-widgets#intermediate-destination) for navigation.


 As soon as your points are selected, the app will create a route and will start guiding you after you tap "Start" button.


![Navigation screen start Android](/assets/images/navigation/route/navigation_start_android.png) ![Navigation screen iOS](/assets/images/navigation/route/navigation_start_ios.png)

When the navigation is running, you can press the home button. You will get the message 'OsmAnd is running in the background'. This means that even if you turn the screen off or exit the active app window, you'll still get voice prompts. For Android versions other than 3.3, we have added the “Turn on screen” option. This allows you to show the map on the lock screen during navigation. Now, this function does not request any permissions for the correct operation. You can use it to save phone power. The function is configured separately for each profile. To configure, you need to select a profile that supports navigation and go to Profile settings - General settings - Screen control and enable the Screen timeout option (move the slider to the ON state - should turn blue).

### Navigation options

- {% data variables.android-values.shared_string_sound %} - allows to switch on/off navigation prompts and to open [Voice prompts](/osmand/navigation/voice-navigation) menu.
- {% data variables.android-values.routing_attr_driving_style_name %} (bicycle..) - allows to choose driving style for bicycle navigation type: {% data variables.android-values.routing_attr_prefer_unpaved_name %}, {% data variables.android-values.routing_attr_driving_style_safety_name %}, {% data variables.android-values.routing_attr_driving_style_balance_name %}, {% data variables.android-values.routing_attr_driving_style_speed_name %}.
- {% data variables.android-values.routing_attr_height_obstacles_name %} (bicycle..) - allows to avoid strong uphills: {% data variables.android-values.routing_attr_relief_smoothness_factor_more_plains_name %}, {% data variables.android-values.routing_attr_relief_smoothness_factor_plains_name %}, {% data variables.android-values.routing_attr_relief_smoothness_factor_more_plains_name %}.
- {% data variables.android-values.routing_attr_allow_motorway_name %} (bicycle..) - 
- {% data variables.android-values.impassable_road %} - allows to select a road you want to avoid during navigation, either on the map.
- {% data variables.android-values.show_along_the_route %} - allows to shows [POI, My Favourites](/osmand/widgets/nav-widgets#approach-poisfavorites), [Traffic warnings](/osmand/widgets/nav-widgets#alert-widget) along the route.
- {% data variables.android-values.follow_track %} - allows to choose a track for [navigation by it](/osmand/navigation/gpx-navigation).
- {% data variables.android-values.routing_attr_allow_private_name %} - allows to navigate to private zone.
- {% data variables.android-values.routing_attr_short_way_name %} - calculates navigation by fuel-efficient algorithm.
- {% data variables.android-values.temporary_conditional_routing %} - allows to consider temporary limitations.
- {% data variables.android-values.routing_settings_2 %} - opens [Navigation settings]() of app profile.
- {% data variables.android-values.customize_route_line %} - opens [menu of Route line]().
- {% data variables.android-values.simulate_navigation %} - allows to simulate your navigation.


### Home - Work points

[Special points](/osmand/personal/favorites#special-favorites-personal) of Favorites in Navigation menu for quickly access.

### Previous route

Last route which you built for navigation.

### Displayed tracks

List of shown track on the map. Clicking by one of it opens [Follow track](/osmand/navigation/gpx-navigation) menu function.

### History

Tracks list.

## Navigation route

![Navigation route Android](/assets/images/navigation/route/navigation_route_android.png) ![Navigation route iOS](/assets/images/navigation/route/navigation_route_ios.png)

### Details

![Navigation route Android](/assets/images/navigation/route/navigation_route_details_android.png) ![Navigation route iOS](/assets/images/navigation/route/navigation_route_details_ios.png)

![Navigation route Android](/assets/images/navigation/route/navigation_route_details_1_android.png) ![Navigation route iOS](/assets/images/navigation/route/navigation_route_details_1_ios.png)

![Navigation route Android](/assets/images/navigation/route/navigation_route_details_2_android.png) ![Navigation route iOS](/assets/images/navigation/route/navigation_route_details_2_ios.png)

## Type of navigation

Link to [Navigation profiles](/osmand/personal/profiles)

## Custom routing

Link to Tech Documentation

## Background navigation

Navigation instruction in the background mode.

### Sound

Voice prompts in backgroun during navigation. [Voice navigation](/osmand/navigation/voice-navigation).

### Notification (Android)

Notification info: Turn-by-turn instructions; arrows; arrival time and time to go, current speed.

![Navigation route Notification Android](/assets/images/navigation/route/navigation_notifications_android.png) 

Buttons:
- {% data variables.android-values.stop_navigation_service %} - allows to stop your navigation.
- {% data variables.android-values.shared_string_pause %} - allows to pause your navigation.
- {% data variables.android-values.shared_string_resume %} - allows to resume your navigation.

### Turn on screen (Android)

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %} → {% data variables.android-values.general_settings_2 %} → {% data variables.android-values.screen_control %} 

{% data variables.android-values.screen_timeout %}:
- {% data variables.android-values.system_screen_timeout %} -
- {% data variables.android-values.wake_time %} - 

{% data variables.android-values.turn_screen_on %}. Select screen wake-up options (make sure OsmAnd is in the foreground when the device is being locked):
- {% data variables.android-values.turn_screen_on_proximity_sensor %} - waving your hand across the screen will turn it on.
- {% data variables.android-values.turn_screen_on_navigation_instructions %} - each navigation instruction will turn the screen on.
- {% data variables.android-values.turn_screen_on_power_button %} - pressing the device power button will turn the screen on with OsmAnd on top of the lock screen.
