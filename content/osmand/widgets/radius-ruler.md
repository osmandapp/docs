---
title: "Radius-ruler and Ruler"
intro: "All ruler tools help to understand [scale of the map](https://en.wikipedia.org/wiki/Scale_(map)). Radius-ruler tool helps to determine the radius around the selected point on the map via displaying distance-circles on the map. Distance by tap tool helps to calculate the distance between selected points to find the shortest distance. "
versions: '*'
---
{% data reusables.general.article-not-complete %}

![Radius-ruler screen](/assets/images/widgets/radius_ruler_screen.png)

## Radius-ruler widget
Radius-ruler widget shows distance between your location and center point of the 'Radius-ruler'. Widget is clickable and changes how the Radius ruler circles are displayed, between the black scale, the grey one and non-visible modes.

![Radius-ruler screen](/assets/images/widgets/radius_ruler_widget.png)

| | |
|------------|------------|
| Enable | {% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.layer_map_appearance %} → {% data variables.android-values.map_widget_right %} → {% data variables.android-values.radius_ruler_item %}   <br>  {% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.layer_map_appearance %} → {% data variables.ios-values.map_widget_right %} → {% data variables.ios-values.map_widget_ruler_control %} |
| Click | Сhanges widget state between the black scale, the grey one and non-visible modes. |
| Distance Units Format | {% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %} → {% data variables.android-values.general_settings_2 %} → {% data variables.android-values.units_and_formats %} → {% data variables.android-values.unit_of_length %} <br> {% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.sett_settings %} → {% data variables.ios-values.app_profiles %} → {% data variables.ios-values.general_settings_2 %} → {% data variables.ios-values.units_and_formats %} → {% data variables.ios-values.unit_of_length %}   |

## Compass ruler for Radius-ruler widget

![Compass ruler](/assets/images/widgets/compass_ruler.png)

By default [Map orientation](https://docs.osmand.net/en/main@latest/osmand/map/interact-with-map#map-orientation--compass) information is displayed on radius-ruler circles. It displays how the Map North is oriented to the Head of device. 
In addition to that, you could see **blue triangle** as a Compass direction. This option requires to have **GPS-compass** present & enabled on your device and keep your device flat, so you could see where head of device is pointing out. Hint: if you rotate your device such as blue and red arrows match, your device head will be pointing to North. If you rotate the map to make the match, then you could see the map properly oriented to the physical landscape.

| | |
|------------|------------|
| Enable | {% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.layer_map_appearance %} → {% data variables.android-values.map_widget_right %} → {% data variables.android-values.radius_ruler_item %} → {% data variables.android-values.shared_string_ellipsis %} → {% data variables.android-values.show_compass_ruler %} / {% data variables.android-values.hide_compass_ruler %}   <br>  {% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.layer_map_appearance %} → {% data variables.ios-values.map_widget_right %} → {% data variables.ios-values.map_widget_ruler_control %} → {% data variables.ios-values.shared_string_ellipsis%} → {% data variables.ios-values.show_compass_ruler %} / {% data variables.android-values.hide_compass_ruler %}  |
| Angular Units Format | {% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %} → {% data variables.android-values.general_settings_2 %} → {% data variables.android-values.units_and_formats %} → {% data variables.android-values.angular_measeurement%} <br> {% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.sett_settings %} → {% data variables.ios-values.app_profiles %} → {% data variables.ios-values.general_settings_2 %} → {% data variables.ios-values.units_and_formats %} → {% data variables.ios-values.angular_units %}   |


## 'Distance by tap' tool

![distance between two random points on the map](/assets/images/widgets/distance_between_two_random_points.png)

**To check the distance from the user's location to a point on the map**: touch a spot on the map. It will allow to see the measurement and the line connecting the two points. The line will stay on screen as long as the user is touching it.

**To check the distance between two random points on the map**: touch simultaneously two spots on the map. It will allow to see the measurement and the line connecting the two points. The line will stay on screen as long as the user is touching it.
The line will fade by itself after 2 seconds.

| | |
|------------|------------|
| Enable | {% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.layer_map_appearance %} → {% data variables.android-values.map_widget_appearance_rem %} → {% data variables.android-values.map_widget_distance_by_tap %}   |
|   | {% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.layer_map_appearance %} → {% data variables.ios-values.map_widget_appearance_rem %} → {% data variables.ios-values.map_widget_distance_by_tap %} |
| Format | {% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %} → {% data variables.android-values.general_settings_2 %} → {% data variables.android-values.units_and_formats %} → {% data variables.android-values.unit_of_length %} |
|   | {% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.sett_settings %} → {% data variables.ios-values.app_profiles %} → {% data variables.ios-values.general_settings_2 %} → {% data variables.ios-values.units_and_formats %} → {% data variables.ios-values.unit_of_length %}   |

## Ruler

The Ruler tool displays map scale and shows the number of meters/kilometers (other units of measure) in a segment. Can be seen at the bottom of the screen.

![Ruler tool](/assets/images/widgets/ruler_tool_map.png)

The Ruler gives a visual estimate of the objects on the map and distance between them. The Ruler will change the display value during map zooming.

| | |
|------------|------------|
| Format | {% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %} → {% data variables.android-values.general_settings_2 %} → {% data variables.android-values.units_and_formats %} → {% data variables.android-values.unit_of_length %} |
|   | {% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.sett_settings %} → {% data variables.ios-values.app_profiles %} → {% data variables.ios-values.general_settings_2 %} → {% data variables.ios-values.units_and_formats %} → {% data variables.ios-values.unit_of_length %}   |

