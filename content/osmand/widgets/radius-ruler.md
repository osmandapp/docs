---
title: "Radius-ruler and Ruler"
intro: "Radius-ruler tool helps to determine the radius around the selected point on the map via displaying distance-circles on the map. The Ruler tool displays scale. "
versions: '*'
---
"Radius-ruler tool helps to determine the radius around the selected point on the map via displaying distance-circles on the map.
Distance by tap tool helps to calculate the distance between selected points to find the shortest distance. The Ruler tool displays scale. "

![Radius-ruler screen](/assets/images/widgets/radius_ruler_screen.png)

## Radius-ruler widget
Radius-ruler widget shows distance between users location and inner point of the 'Radius-ruler' tool distance-circles on the map. Widget is clickable and changes its state between the black scale, the grey one and no scale modes.

| | |
|------------|------------|
| Enable | {% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.layer_map_appearance %} → {% data variables.android-values.map_widget_right %} → {% data variables.android-values.radius_ruler_item %}   |
|  | {% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.layer_map_appearance %}   → {% data variables.ios-values.map_widget_right %} → {% data variables.ios-values.map_widget_radius_ruler %} |
| Click | Сhanges widget state between the black scale, the grey one and no scale (only ruler) modes. |
| Format | {% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %} → {% data variables.android-values.general_settings_2 %} → {% data variables.android-values.units_and_formats %} → {% data variables.android-values.unit_of_length %} |
|   | {% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.sett_settings %} → {% data variables.ios-values.app_profiles %} → {% data variables.ios-values.general_settings_2 %} → {% data variables.ios-values.units_and_formats %} → {% data variables.ios-values.unit_of_length %}   |

## Compass ruler for Radius-ruler widget

![Compass ruler](/assets/images/widgets/compass_ruler.png)

The compass circle shows the North, the East, the South and the West directions. By default Compass is enable.
As an addition option, it gives the user the Azimuth direction. It is marked as an arrow of a different color. The angle between North, measured clockwise around the observer's horizon, and a celestial body will be displayed over the North arrow.

| | |
|------------|------------|
| Enable | {% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.layer_map_appearance %} → {% data variables.android-values.shared_string_ellipsis %} → {% data variables.android-values.show_compass_ruler %}   |
|  | {% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.layer_map_appearance %}   → {% data variables.ios-values.shared_string_ellipsis%} → {% data variables.ios-values.show_compass_ruler %} |
| Disable  |  {% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.layer_map_appearance %} → {% data variables.android-values.shared_string_ellipsis %} → {% data variables.android-values.hide_compass_ruler %}  |
|   | {% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.layer_map_appearance %}   → {% data variables.ios-values.shared_string_ellipsis%} → {% data variables.ios-values.hide_compass_ruler %}  |
| Click | Сhanges widget state between the black scale, the grey one and no scale (only ruler) modes. |
| Format | {% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %} → {% data variables.android-values.general_settings_2 %} → {% data variables.android-values.units_and_formats %} → {% data variables.android-values.angular_measeurement%} |
|   | {% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.sett_settings %} → {% data variables.ios-values.app_profiles %} → {% data variables.ios-values.general_settings_2 %} → {% data variables.ios-values.units_and_formats %} → {% data variables.ios-values.angular_units %}   |
| Note   |  It is important to have the inner compass functions on your device. |


## 'Distance by tap' tool

![distance between two random points on the map](/assets/images/widgets/distance_between_two_random_points.png)

**To check the distance from the user's location to a point on the map**: touch a spot on the map. It will allow to see the measurement and the line connecting the two points. The line will stay on screen as long as the user is touching it.

**To check the distance between two random points on the map**: touch simultaneously two spots on the map. It will allow to see the measurement and the line connecting the two points. The line will stay on screen as long as the user is touching it.
The line will fade by itself after 2 seconds.

| | |
|------------|------------|
| Enable | {% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.layer_map_appearance %} → {% data variables.android-values.map_widget_appearance_rem %} → {% data variables.android-values.map_widget_distance_by_tap %}   |
| Format | {% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %} → {% data variables.android-values.general_settings_2 %} → {% data variables.android-values.units_and_formats %} → {% data variables.android-values.unit_of_length %} |
|   | {% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.sett_settings %} → {% data variables.ios-values.app_profiles %} → {% data variables.ios-values.general_settings_2 %} → {% data variables.ios-values.units_and_formats %} → {% data variables.ios-values.unit_of_length %}   |

For iOS 'Distance by tap' tool is available as a part of Radius-ruler tool. User have to enable [Radius-ruler widget](https://docs.osmand.net/en/main@latest/osmand/widgets/radius-ruler#radius-ruler-widget) to use the feature.

## Ruler

![Ruler tool](/assets/images/widgets/ruler_tool_map.png)

The Ruler tool displays map scale and shows the number of meters/kilometers (other units of measure) in a segment. Can be seen at the bottom of the screen.


The Ruler gives a visual estimate of the objects on the map and distance between them. The Ruler will change the display value during map zooming.

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %} → {% data variables.android-values.general_settings_2 %} → {% data variables.android-values.units_and_formats %} → {% data variables.android-values.unit_of_length %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.sett_settings %} → {% data variables.ios-values.app_profiles %} → {% data variables.ios-values.general_settings_2 %} → {% data variables.ios-values.units_and_formats %} → {% data variables.ios-values.unit_of_length %}

<!--| | |
|------------|------------|
| Enable | {% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.layer_map_appearance %} → {% data variables.android-values.map_widget_right %} → {% data variables.android-values.radius_ruler_item %}   |
|  | {% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.layer_map_appearance %} → {% data variables.ios-values.map_widget_radius_ruler %} |
| Format | {% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %} → {% data variables.android-values.general_settings_2 %} → {% data variables.android-values.units_and_formats %} → {% data variables.android-values.unit_of_length %} |
|   |  {% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.sett_settings %} → {% data variables.ios-values.app_profiles %} → {% data variables.ios-values.general_settings_2 %} → {% data variables.ios-values.units_and_formats %} → {% data variables.ios-values.unit_of_length %} |-->
