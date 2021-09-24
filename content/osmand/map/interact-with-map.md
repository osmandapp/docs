---
title:  Interact with map
intro: "How to interact with map using buttons and gestures, so you could pan, rotate and zoom in/out the map, how to rotate the map manually or automatically by compass or by bearing and how to change zoom scale."
versions: '*'
---

## Gestures

Gestures are important part of the map navigation.

| Map Action | Gesture |
|:------------|:---------------|
|**Move**| Press on the map with **one** finger and move around |
|**Slide**| Swipe the map with **one** finger |
|**Zoom in**| • Double tap on the map with **one** finger <br> • Double tap on the map with **one** finger and then swipe up <br> • Pinch with **two** fingers |
|**Zoom out**| • Double tap on the map with **two** fingers <br> • Double tap on the map with **one** finger and then swipe down <br> •  Pinch with **two** fingers |
|**Rotate**| Press with **two** fingers on the map and rotate |
|**Tilt** - 3D (only iOS) | Press with **two** fingers on the map and then swipe up or down |

Slide animations could be disabled with special [setting](#disable-all-animations-android).

## My Location & Zoom

![Configure screen menu](/assets/images/widgets/location_zoom_buttons.png)

**My location** is a circle button that shows whether the center of the map is synchronized with "my location" (geolocation of the device). It is also known as "Where am I?". Generally in navigation, the map is synced with device location, and there are no needs to move the map constantly. In this case, the button is hidden and will be activated when the map and 'my location' will go out of sync by user gesture. The app will try to find the device location and show it on the map at the center of the screen when the user clicks on it ( iOS will switch to the 3D mode when the user click twice on it).

**My location** button has following indicative states:
- Full blue icon - location is found but it is not synchronized with map
- White icon - location is found and it is synchronized with map
- Grey icon - location has not found yet
- Arrow icon (iOS) - 3D mode is switched on

**Long tap** on **My location** opens Context menu, so user can share own location.

**Zoom buttons** are always visible next to **My Location** and allow to control map zoom level. Changing zoom level doesn't change map synchronization with location. **Long tap** on **Zoom buttons** opens Map magnifier dialog and allows to change map detailing.

Keep in mind that during navigation zoom can be controlled by **Auto zoom setting**:

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.shared_string_settings %} → {% data variables.android-values.application_profiles%} → {% data variables.android-values.routing_settings_2 %} → {% data variables.android-values.map_during_navigation_info %} → {% data variables.android-values.auto_zoom_map %}  

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.shared_string_settings %} → {% data variables.ios-values.app_profiles %} → {% data variables.ios-values.routing_settings_2 %} → {% data variables.ios-values.map_during_navigation %} → {% data variables.ios-values.auto_zoom_map %}

## Map magnifier
Map magnifier is a special way to magnify the map. Essentially it works as a magnifying glass for paper maps, it allows to see the text bigger for raster maps or to see more or less details for the same scale - [Read more](/osmand/map/vector-maps#map-magnifier).

## Map orientation & Compass

![Compass widget](/assets/images/widgets/compass_widget.png)

Compass widget indicates how map is oriented on the device screen and top arrow / red arrow points where the north of map is located. It also shows the current Map orientation mode. Clicking on the compass will cycle through all Map orientation modes.

### Configure visibility

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.map_widget_config %} → {% data variables.android-values.map_widget_left %} → {% data variables.android-values.map_widget_compass %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.layer_map_appearance %} → {% data variables.ios-values.map_widget_left %} → {% data variables.ios-values.map_widget_compass %}

### Map orientation modes
- **{% data variables.android-values.rotate_map_none_opt %}** - map is not being rotated by any external movements, and it could be rotated only by *2 pointer gesture* (2 double tap & rotate).
- **{% data variables.android-values.rotate_map_bearing_opt %}** - map is being rotated by bearing, i.e. direction of your movement (GPS direction) is synchronized with the map. [Read more](#rotate-map-by-bearing).
- **{% data variables.android-values.rotate_map_compass_opt %}** - map is being synchronized with the device compass orientation. So, [Compass widget](/osmand/widgets/map-buttons/#compass) will point to actual Earth North if device is held flat. In case compass sensor is not present on device, map orientation won't change.

Map orientation could be changed in Profile settings:

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile%} → {% data variables.android-values.general_settings_2 %}  → {% data variables.android-values.rotate_map_to_bearing %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.shared_string_settings %} → {% data variables.ios-values.app_profiles %} → {% data variables.ios-values.general_settings_2 %} → {% data variables.ios-values.map_settings_appearance %} → {% data variables.ios-values.rotate_map_to_bearing %}

### Rotate map by bearing
If rotate map by bearing is enabled, then the map will be oriented, so that head looking view will be strictly above (higher) my location icon on the map. Without movement the map won't be rotated. In this mode the center of the map will be located slightly below the center of the device. It allows seeing more map information ahead of your movement which is usable in the navigation mode. It can be disabled by a setting 

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.shared_string_settings%} → {% data variables.android-values.shared_string_profiles %} → {% data variables.android-values.general_settings_2 %} → {% data variables.android-values.always_center_position_on_map %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.shared_string_settings %} → {% data variables.ios-values.app_profiles %} → {% data variables.ios-values.general_settings_2 %} → {% data variables.ios-values.always_center_position_on_map %}

## Settings

### Disable all animations (Android)

You can disable all map animations during map change (gestures and buttons) in Settings {% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.shared_string_settings%} → {% data variables.android-values.shared_string_profiles %} → {% data variables.android-values.general_settings_2 %} → 
{% data variables.android-values.do_not_use_animations %}.

### Extra compass settings (Android)

- ** Use Kalman filter (Android)** - smoothen rotation of the map with a slower rotation animation though it introduces a small delay (< 1 second) till:  

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.shared_string_settings%} → {% data variables.android-values.shared_string_profiles %} → {% data variables.android-values.general_settings_2 %} → {% data variables.android-values.shared_string_other %} → {% data variables.android-values.use_kalman_filter_compass %}

- ** Use Magnetic sensor** - smoothen rotation of the map with a slower rotation animation though it introduces a small delay (< 1 second) till:

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.shared_string_settings%} → {% data variables.android-values.shared_string_profiles %} → {% data variables.android-values.general_settings_2 %} → {% data variables.android-values.shared_string_other %} → {% data variables.android-values.use_magnetic_sensor %}

## External input device buttons (Android)

Select an external control device, such as a keyboard or WunderLINQ.

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %} → {% data variables.android-values.general_settings_2 %} → {% data variables.android-values.external_input_device %}

| Map Action | Keyboard key |
|:------------|:---------------|
|**Move up**| "W","&#8593;"  |
|**Move down**| "S","&#8595;"  |
|**Move left**| "W","&#8592;"  |
|**Move right**| "W","&#8594;"  |
|**Zoom in**| "&#43;" |
|**Zoom out**| "&#8722;" |

