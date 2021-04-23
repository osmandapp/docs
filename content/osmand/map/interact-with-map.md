---
title:  Interact with map
intro: "General introduction information about the map and it’s content. Gestures, map orientation, and compass settings are described"
versions: '*'
---

## Gestures

Gestures are an important part of navigation that helps to facilitate using OsmAnd.

{% data variables.product.android_button_seq %}
* *Moving the map* - tap on the screen and move finger on the map.
* *Double tapping on the map with one finger* - zoom in the map.
* *Double tapping on the map with two fingers* - zoom out the map.
* *Double tapping on the map and then swiping up or down* - zoom in the map by using one finger.
* *Pinching  and zooming with two fingers* - zoom in or zoom out the map.  
* *Two fingers rotation on the map* - rotate the map.

{% data variables.product.ios_button_seq %}
* *Moving the map* - tap on the screen and move finger on the map.
* *Double tapping on the map with one finger* - zoom in the map.
* *Double tapping on the map with two fingers* - zoom out the map.
* *Two fingers on the map and then swiping up or down* - to adjust the slope of the map (2.5D).
* *Pinching  and zooming with two fingers* - zoom in or zoom out the map.  
* *Two fingers rotation on the map* - rotate the map.

## Map orientation

Map orientation is a setting for displaying the map on your device relative to North or your movement. There are 3 different Map orientation modes.

![Compass widget](/assets/images/widgets/compass_widget.png)

Map orientation modes are switched by click on the [Compass widget](/osmand/widgets/map-buttons/#compass).
- **{% data variables.android-values.rotate_map_none_opt %}** - map is not being rotated by any external movements, and it could be rotated only by *2 pointer gesture* (2 double tap & rotate).
- **{% data variables.android-values.rotate_map_bearing_opt %}** - map is being rotated by bearing, i.e. direction of your movement (GPS direction) is synchronized with the map. The map will be oriented, so that head looking view will be strictly above (higher) my location icon on the map. Without movement the map won't be rotated. In this mode the center of the map will be located slightly below the center of the device. It allows seeing more map information ahead of your movement which is usable in navigation mode. It can be disabled by setting:

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.shared_string_settings%} → {% data variables.android-values.shared_string_profiles %} → {% data variables.android-values.general_settings_2 %} → {% data variables.android-values.always_center_position_on_map %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.shared_string_settings %} → {% data variables.ios-values.app_profiles %} → {% data variables.ios-values.general_settings_2 %} → {% data variables.ios-values.always_center_position_on_map %}.

- **{% data variables.android-values.rotate_map_compass_opt %}** - map is being synchornized with device compass orientation. So, [Compass widget](/osmand/widgets/map-buttons/#compass) will point to actual Earth North if device is hold flat. In case compass sensor is not present on device, map orientation won't change.

Map orientation could be changed in Profile settings:

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile%} → {% data variables.android-values.general_settings_2 %}  → {% data variables.android-values.rotate_map_to_bearing %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.shared_string_settings %} → {% data variables.ios-values.app_profiles %} → {% data variables.ios-values.general_settings_2 %} → {% data variables.ios-values.map_settings_appearance %} → {% data variables.ios-values.rotate_map_to_bearing %}

### Extra compass settings (Android)

- ** Use Kalman filter (Android)** - smoothen rotation of the map with a slower rotation animation though it introduces a small delay (< 1 second) till:  

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.shared_string_settings%} → {% data variables.android-values.shared_string_profiles %} → {% data variables.android-values.general_settings_2 %} → {% data variables.android-values.shared_string_other %} → {% data variables.android-values.use_kalman_filter_compass %}

- ** Use Magnetic sensor** - smoothen rotation of the map with a slower rotation animation though it introduces a small delay (< 1 second) till:

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.shared_string_settings%} → {% data variables.android-values.shared_string_profiles %} → {% data variables.android-values.general_settings_2 %} → {% data variables.android-values.shared_string_other %} → {% data variables.android-values.use_magnetic_sensor %}
