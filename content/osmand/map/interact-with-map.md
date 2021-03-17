---
title: "Interact with map"
intro: "Interact with map"
versions: '*'
---
Introduction about the map and what it includes. Explanation about coordinates, text size and zoom magnifier.
Special words about my location / radius of my location. Shortly about map interaction pan, zoom, click.


## Gestures

* Zoom in and out map on the main screen by using two fingers.
* There is an additional option for iOS to adjust the slope of the map. User have to put two fingers on the map and swipe down the screen to change the slope and swipe up to change to default state.
* Clicking with two fingers on the map will zoom out the map.
* Set from and to navigation directions in {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.get_directions %}. The elevation chart will appear at the bottom of the screen. User can zoom in and zoom out the elevation chart that will change chart borders accordingly by using two fingers.

There are three wake-up options that user can find in {% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.shared_string_settings%} → {% data variables.android-values.shared_string_profiles %} → {% data variables.android-values.general_settings_2 %} → {% data variables.android-values.shared_string_other %} → {% data variables.android-values.screen_control %} → {% data variables.android-values.turn_screen_on%}.

Note: The OsmAnd should be in the foreground when the device is locked.


## Map orientation

![Compass widget](/assets/images/widgets/compass_widget.png)

There are 3 different **Map orientation** modes which are switched by click on the [Compass widget](/osmand/widgets/map-buttons/#compass).
- **{% data variables.android-values.rotate_map_none_opt %}** - map is not being rotated by any external movements, and it could be rotated only by **2 pointer gesture** (2 double tap & rotate).
- **{% data variables.android-values.rotate_map_bearing_opt %}** - map is being rotated by bearing, i.e. direction of your movement (GPS direction) is synchronized with the map. The map will be oriented, so that head looking view will be strictly above (higher) my location icon on the map. Without movement the map won't be rotated. In this mode the center of the map will be located slightly below the center of the device. It allows seeing more map information ahead of your movement which is usable in navigation mode. It can be disabled by setting
{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.shared_string_settings%} → {% data variables.android-values.shared_string_profiles %} → {% data variables.android-values.general_settings_2 %} → {% data variables.android-values.always_center_position_on_map %};
{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.shared_string_settings %} → {% data variables.ios-values.m_style_overview %} → {% data variables.ios-values.general_settings_2 %} → {% data variables.ios-values.always_center_position_on_map %}.
- **{% data variables.android-values.rotate_map_compass_opt %}** - map is being synchornized with device compass orientation. So, [Compass widget](/osmand/widgets/map-buttons/#compass) will point to actual Earth North if device is hold flat. In case compass sensor is not present on device, map orientation won't change.

Extra compass settings (Android):
- ** Use Kalman filter (Android)** - smoothen rotation of the map with a slower rotation animation though it introduces a small delay (< 1 second) till.  
{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.shared_string_settings%} → {% data variables.android-values.shared_string_profiles %} → {% data variables.android-values.general_settings_2 %} → {% data variables.android-values.shared_string_other %} → {% data variables.android-values.use_kalman_filter_compass %}
- ** Use Magnetic sensor** - smoothen rotation of the map with a slower rotation animation though it introduces a small delay (< 1 second) till.
{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.shared_string_settings%} → {% data variables.android-values.shared_string_profiles %} → {% data variables.android-values.general_settings_2 %} → {% data variables.android-values.shared_string_other %} → {% data variables.android-values.use_magnetic_sensor %}

**Map orientation** could also be changed in Profile settings.

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile%} → {% data variables.android-values.general_settings_2 %}  → {% data variables.android-values.shared_string_appearance %}→ {% data variables.android-values.always_center_position_on_map %};
{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.shared_string_settings %} → {% data variables.ios-values.m_style_overview %} → {% data variables.ios-values.general_settings_2 %} → {% data variables.ios-values.map_settings_appearance %} → {% data variables.ios-values.always_center_position_on_map %}.
