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

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.get_directions %}


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

- {% data variables.android-values.shared_string_sound %} - 
- {% data variables.android-values.impassable_road %}
- {% data variables.android-values.show_along_the_route %} - 
- {% data variables.android-values.follow_track %} - 
- {% data variables.android-values.routing_attr_allow_private_name %} - 
- {% data variables.android-values.routing_attr_short_way_name %} - 
- {% data variables.android-values.temporary_conditional_routing %} - 
- {% data variables.android-values.routing_settings_2 %} - 
- {% data variables.android-values.customize_route_line %} - 
- {% data variables.android-values.simulate_navigation %} - 


### Home - Work points

### Previous route

### Displayed tracks

### History

## Type of navigation

Link to Navigation profiles

## Custom routing

Link to Tech Documentation


