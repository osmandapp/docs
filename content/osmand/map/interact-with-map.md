---
title:  Interact with map
intro: "Map interaction is certain actions that help users to better navigate the map. Gestures as zoom in and zoom out, map buttons, help you to faster move on the main interface."
versions: '*'
---

## Gestures

Gestures are an important part of navigation that helps to facilitate using OsmAnd.

|Process |Actions|
|:------------|:---------------|
|**Moving the map**|Tap on the screen and move finger on the map|
|**Zoom in the map**|Double tapping on the map with one finger / Double tapping on the map and then swiping up / Moving two fingers backwards from each other| 
|**Zoom out the map**|Double tapping on the map with two fingers / Double tapping on the map and then swiping down / Moving two fingers towards each other|
|**Rotate the map**|Tap two fingers on the map and rotate|
|**3D view** (available only for iOS)|Two fingers on the map and then swiping up or down|
---

## Map buttons

Map buttons such as Zoom buttons, Search, Direction, Compass, My Location and Menu represent main controls on the map.

### My Location & Zoom

![Configure screen menu](/assets/images/widgets/location_zoom_buttons.png)

**My location** is a circle button that shows whether the center of the map is synchronized with "my location" (geolocation of the device). It is also known as "Where am I?". Generally in navigation, the map is synced with device location, and there are no needs to move the map constantly. In this case, the button is hidden and will be activated when the map and 'my location' will go out of sync by user gesture. The app will try to find the device location and show it on the map at the center of the screen when the user clicks on it ( iOS will switch to the 3D mode when the user clicks twice on it).

**My location** button has following indicative states:
- Full blue icon - location is found but it is not synchronized with map
- White icon - location is found and it is synchronized with map
- Grey icon - location has not found yet
- Arrow icon (iOS) - 3D mode is switched on

**Long tap** on **My location** opens the Context menu, so user can share own location.

**Zoom buttons** are always visible next to **My Location** and allow to control map zoom level. Changing zoom level doesn't change map synchronization with location. **Long tap** on **Zoom buttons** opens Map magnifier dialog and allows to change map detailing.

Keep in mind that during navigation zoom can be controlled by **Auto zoom setting**:

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.shared_string_settings %} → {% data variables.android-values.application_profiles%} → {% data variables.android-values.routing_settings_2 %} → {% data variables.map_during_navigation_info %} → {% data variables.android-values.auto_zoom_map %}  

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.shared_string_settings %} → {% data variables.ios-values.app_profiles %} → {% data variables.ios-values.routing_settings_2 %} → {% data variables.ios-values.map_behavior %} → {% data variables.ios-values.auto_zoom_map %}

### Directions

![Directions button allows](/assets/images/widgets/directions_button_allows.png)

**Directions** button allows to [chart a route](/osmand/navigation) and [start navigation](/osmand/navigation). In navigation mode this button is not visible by default and it appears after a short tap on the map.

**Directions** button has 3 different indicative states:
- Default grey icon - the route has not been built yet. A dialog to build a new route will appear by click.
- Default blue icon - the route is built, but navigation has not started yet. A dialog with route information will appear by click.
- Blue arrow icon - the route is built and navigation has started. A dialog with route information will appear by click.

### Configure Map

![Configure Map](/assets/images/widgets/configure_map.png)

**Configure Map** button allows to access to [Configure Map menu](/osmand/map/configure-map-menu). Icon on it indicates [Current app profile](/osmand/start-with/profiles).

### Main menu

![Main menu button](/assets/images/widgets/main_menu_button.png)

**Main menu** button allows to access to [all features](/osmand/main-menu) of the application. In navigation mode this button is not visible by default. It appears after a short tap on the map.

### Search

![Search button](/assets/images/widgets/search_button.png)

Search button buttons provides quick access from the map to [search capabilities](/osmand/search/).

### Compass

![Compass widget](/assets/images/widgets/compass_widget.png)

Compass widget indicates how map is oriented on the device screen and top arrow / red arrow points where the north of map is located. It also shows the current **[Map orientation mode](/osmand/map/interact-with-map#map-orientation)**. Clicking on the compass will cycle through all Map orientation modes.

**Configure visibility**

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.map_widget_config %} → {% data variables.android-values.map_widget_left %} → {% data variables.android-values.map_widget_compass %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.layer_map_appearance %} → {% data variables.ios-values.map_widget_left %} → {% data variables.ios-values.map_widget_compass %}

- **{% data variables.android-values.rotate_map_none_opt %}** - map is not being rotated by any external movements, and it could be rotated only by *2 pointer gesture* (2 double tap & rotate).
- **{% data variables.android-values.rotate_map_bearing_opt %}** - map is being rotated by bearing, i.e. direction of your movement (GPS direction) is synchronized with the map. The map will be oriented, so that head looking view will be strictly above (higher) my location icon on the map. Without movement the map won't be rotated. In this mode the center of the map will be located slightly below the center of the device. It allows seeing more map information ahead of your movement which is usable in navigation mode. It can be disabled by setting:

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.shared_string_settings%} → {% data variables.android-values.shared_string_profiles %} → {% data variables.android-values.general_settings_2 %} → {% data variables.android-values.always_center_position_on_map %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.shared_string_settings %} → {% data variables.ios-values.app_profiles %} → {% data variables.ios-values.general_settings_2 %} → {% data variables.ios-values.always_center_position_on_map %}.

- **{% data variables.android-values.rotate_map_compass_opt %}** - map is being synchronized with the device compass orientation. So, [Compass widget](/osmand/widgets/map-buttons/#compass) will point to actual Earth North if device is held flat. In case compass sensor is not present on device, map orientation won't change.

Map orientation could be changed in Profile settings:

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile%} → {% data variables.android-values.general_settings_2 %}  → {% data variables.android-values.rotate_map_to_bearing %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.shared_string_settings %} → {% data variables.ios-values.app_profiles %} → {% data variables.ios-values.general_settings_2 %} → {% data variables.ios-values.map_settings_appearance %} → {% data variables.ios-values.rotate_map_to_bearing %}

### Extra compass settings (Android)

- ** Use Kalman filter (Android)** - smoothen rotation of the map with a slower rotation animation though it introduces a small delay (< 1 second) till:  

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.shared_string_settings%} → {% data variables.android-values.shared_string_profiles %} → {% data variables.android-values.general_settings_2 %} → {% data variables.android-values.shared_string_other %} → {% data variables.android-values.use_kalman_filter_compass %}

- ** Use Magnetic sensor** - smoothen rotation of the map with a slower rotation animation though it introduces a small delay (< 1 second) till:

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.shared_string_settings%} → {% data variables.android-values.shared_string_profiles %} → {% data variables.android-values.general_settings_2 %} → {% data variables.android-values.shared_string_other %} → {% data variables.android-values.use_magnetic_sensor %}
