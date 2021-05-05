---
title: "Configure Screen"
intro: "Configure screen button gives an opportunity to customize items visibility on the map screen. This menu allows you to enable Quick action, turn on the widgets on the right and left panels, set up the remaining elements."
versions: '*'
---

- Make similar description of Main menu to [Configure map menu](/osmand/map/configure-map-menu)
{% data reusables.general.article-not-complete %}

All widgets are [profile dependent](/osmand/personal/profiles), so in case you change the order, visibility or state for 1 profile, it won't be applied to other profiles. Each profile has its own predefined list of widgets based on the design of the navigation screen. It can be customized and used with or without navigation.

![Configure screen menu](/assets/images/widgets/configure_screen_menu.png)

In order to customize widgets visibility you need to open Configure screen menu.

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.layer_map_appearance %} 

{% data variables.product.ios_button_seq %} {% data variables.ios-values.shared_string_menu %} → {% data variables.ios-values.layer_map_appearance %} 


Most of the widgets could be configured as:
* Show – widget is visible on the map screen
* Hide – widget is hidden from the map screen
* Collapse – creates a group of "collapsible" widgets and a button to quickly expand / collapse them on the maps screen.

![Collapsible widget states](/assets/images/widgets/collapsible_widget_states.png)

## Quick action
- [Quick action](/osmand/widgets/quick-action) - is a button that gives quick access to frequently used actions.
## Widgets on the right panel
 - [Parking](/osmand/widgets/info-widgets#-parking-widget) - shows distance from the current position to the parking place.
 - [Intermediate destination](/osmand/widgets/nav-widgets#intermediate-destination) - shows current distance to the nearest intermediate navigation point.
 - [Destination](/osmand/widgets/nav-widgets#destination) - shows current distance to the finish point.
 - [Arrival time](/osmand/widgets/nav-widgets#arrival-time-or-time-to-go) - shows the time when you will approach the destination or if you switch to the time to go it will display the total time left.
 - [Relative bearing](/osmand/widgets/nav-widgets#relative--magnetic-bearing) - shows relative or magnetic bearing.
 - [Mapillary](/osmand/widgets/info-widgets#-mapillary-widget) - provides quick access to Mapillary app to add Street-Level-Imagery.
 - [Speed](/osmand/widgets/info-widgets#speed) - shows your current speed detected by GPS-sensor.
 - [Speed limit](/osmand/widgets/nav-widgets#speed-limit) - shows a speed limit for a current road.
 - [Altitude](/osmand/widgets/info-widgets#altitude) - shows the height above sea level of current geolocation. 
 - [GPS info](/osmand/widgets/info-widgets#gps-info-android) - shows a number of satellites that a device detects and uses at that moment (Android).
 - [Trip recording](/osmand/widgets/info-widgets#-trip-recording-widget) - provides quick access to start / stop track recording.
 - [Current time](/osmand/widgets/info-widgets#current-time) - shows current time from a device.
 - [Battery level](/osmand/widgets/info-widgets#battery-level) - shows battery level of the device.
 - [Radius ruller](/osmand/widgets/radius-ruler) - shows distance between users location and inner point of the 'Radius-ruler' tool distance-circles on the map. 
 - [FPS debug info](/osmand/widgets/info-widgets#-fps-info-android) - investigate how fast map & map elements are showed & refreshed (Android).

## Widget on the left panel
 - [Compass](/osmand/widgets/map-buttons#compass) -  indicates how map is oriented on the device screen.

## Remaining elements
- [Coordinates widget](/osmand/widgets/info-widgets#coordinates-widget) -  shows the geographic coordinates of current geolocation (appears on the top bar).
- Distance by tap - an option to measure the distance from your position to the selected point.
- [Map markers](/osmand/widgets/markers) - shows a directional line from your position to the active marker locations (could be on the top bar or on the right widget panel).
- Transparent widgets 
- [Lanes](/osmand/widgets/nav-widgets#lanes) - shows the lanes you have to drive during a navigation with distance to a maneuver.

[Read more information about each widget individually.](/osmand/widgets)
