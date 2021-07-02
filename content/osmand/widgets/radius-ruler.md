---
title: "Radius-ruler and Ruler"
intro: "All ruler tools help to understand [scale of the map](https://en.wikipedia.org/wiki/Scale_(map)) and measure distances. Radius-ruler tool helps to determine the radius around the selected point on the map via displaying distance-circles on the map. Distance by tap tool helps to calculate the distance between selected points or to find the distance to a specific point. "
versions: '*'
---

![Radius-ruler screen](/assets/images/widgets/radius_ruler_screen.png)

## Ruler

The Ruler displays a map scale and shows the number of meters / feet (other units of measure) in a segment. It can be seen at the bottom of the screen. On average map scale is a round number that could fit a size of thumb. 

The Ruler gives a visual estimate of the objects on the map and distance between them and it will change the displayed value during map zooming.

![Ruler tool](/assets/images/widgets/ruler_tool_map.png)


| | |
|------------|------------|
| Units Format | {% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %} → {% data variables.android-values.general_settings_2 %} → {% data variables.android-values.units_and_formats %} → {% data variables.android-values.unit_of_length %} <br> {% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.sett_settings %} → {% data variables.ios-values.app_profiles %} → {% data variables.ios-values.general_settings_2 %} → {% data variables.ios-values.units_and_formats %} → {% data variables.ios-values.unit_of_length %}   |


## Radius-ruler widget
Radius-ruler widget shows distance between your location and center point of the 'Radius-ruler'. Radius of the first circle is equal to [the map scale](#ruler).

![Radius-ruler screen](/assets/images/widgets/radius_ruler_widget.png)

| | |
|------------|------------|
| Enable | {% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.layer_map_appearance %} → {% data variables.android-values.map_widget_right %} → {% data variables.android-values.radius_ruler_item %}   <br>  {% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.layer_map_appearance %} → {% data variables.ios-values.map_widget_right %} → {% data variables.ios-values.map_widget_ruler_control %} |
| Click | Сhanges widget state between the black scale, the grey one and non-visible modes. |
| Units Format | {% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %} → {% data variables.android-values.general_settings_2 %} → {% data variables.android-values.units_and_formats %} → {% data variables.android-values.unit_of_length %} <br> {% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.sett_settings %} → {% data variables.ios-values.app_profiles %} → {% data variables.ios-values.general_settings_2 %} → {% data variables.ios-values.units_and_formats %} → {% data variables.ios-values.unit_of_length %}   |

## Compass ruler for Radius-ruler widget

![Compass ruler](/assets/images/widgets/compass_ruler.png)

By default [Map orientation](https://docs.osmand.net/en/main@latest/osmand/map/interact-with-map#map-orientation--compass) information is displayed on radius-ruler circles. It displays how the Map North is oriented to the Head of device. 

In addition to that, you could see **blue triangle** as a Compass direction. This option requires to have **GPS-compass** present & enabled on your device. Keep your device flat, so you could see where head of device is pointing out. 

**Hint**: if you rotate your device such as blue and red arrow pointing up, your device head will be pointing to North. If you rotate the map or device to match blue and red arrows, then you could see the map properly oriented to the physical landscape.

| | |
|------------|------------|
| Enable | {% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.layer_map_appearance %} → {% data variables.android-values.map_widget_right %} → {% data variables.android-values.radius_ruler_item %} → {% data variables.android-values.shared_string_ellipsis %} → {% data variables.android-values.show_compass_ruler %} / {% data variables.android-values.hide_compass_ruler %}   <br>  {% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.layer_map_appearance %} → {% data variables.ios-values.map_widget_right %} → {% data variables.ios-values.map_widget_ruler_control %} → {% data variables.ios-values.shared_string_ellipsis%} → {% data variables.ios-values.show_compass_ruler %} / {% data variables.android-values.hide_compass_ruler %}  |
| Units Format | {% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %} → {% data variables.android-values.general_settings_2 %} → {% data variables.android-values.units_and_formats %} → {% data variables.android-values.angular_measeurement%} <br> {% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.sett_settings %} → {% data variables.ios-values.app_profiles %} → {% data variables.ios-values.general_settings_2 %} → {% data variables.ios-values.units_and_formats %} → {% data variables.ios-values.angular_units %}   |

The {% data variables.android-values.radius_ruler_item %} can be placed both in the center of the screen or shifted downward, which allows you to measure the distance from the current location to a more distant point.
In order to move {% data variables.android-values.radius_ruler_item %} downard you need to turn off  {% data variables.android-values.always_center_position_on_map %}.

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %} → {% data variables.android-values.general_settings_2 %} → {% data variables.android-values.always_center_position_on_map %} →  <br> {% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.sett_settings %} → select profile → {% data variables.ios-values.general_settings_2 %} → {% data variables.ios-values.always_center_position_on_map %}

Video guide how to use Radius ruller for **Android**
[![Video guide how to use Radius ruller for {% data variables.product.android %}](/assets/images/widgets/radius_ruler_video_android.png)](https://www.youtube.com/watch?v=MWT20dVtkDc)

Video guide how to use Radius ruller for **iOS**
[![Video guide how to use Radius ruller for {% data variables.product.ios %}](/assets/images/widgets/radius_ruler_video_ios.png)](https://www.youtube.com/watch?v=C9QLQ52ndiA&t=10s)

## 'Distance by tap' tool

![Distance between two random points on the map](/assets/images/widgets/distance_between_two_random_points.png)

**Distance from your location to a point on the map**: after single tap on the map, the line from your current location and distance will be displayed. The line will be active during long touch on the screen as well.

**Distance between 2 points on the map**: touch simultaneously two spots on the map, the line between points and the distance will be displayed.

| | |
|------------|------------|
| Enable | {% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.layer_map_appearance %} → {% data variables.android-values.map_widget_appearance_rem %} → {% data variables.android-values.map_widget_distance_by_tap %}   <br> {% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.layer_map_appearance %} → {% data variables.ios-values.map_widget_appearance_rem %} → {% data variables.ios-values.map_widget_distance_by_tap %} |
| Units Format | {% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %} → {% data variables.android-values.general_settings_2 %} → {% data variables.android-values.units_and_formats %} → {% data variables.android-values.unit_of_length %} <br> {% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.sett_settings %} → {% data variables.ios-values.app_profiles %} → {% data variables.ios-values.general_settings_2 %} → {% data variables.ios-values.units_and_formats %} → {% data variables.ios-values.unit_of_length %}   |
