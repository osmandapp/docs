---
title: "Configure Screen"
intro: "Configure screen is a menu that allows to configure what widgets will be displayed over the map. It allows you to enable and configure Quick action, Navigation widgets,  and remaining elements."
versions: '*'
---

![Configure screen menu](/assets/images/widgets/configure_screen_menu.png)

In order to customize widgets visibility you need to access Configure screen menu.

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.layer_map_appearance %} 

{% data variables.product.ios_button_seq %} {% data variables.ios-values.shared_string_menu %} → {% data variables.ios-values.layer_map_appearance %} 

Most of the widgets could be configured as:
* Show – widget is visible on the map screen
* Hide – widget is hidden from the map screen
* Collapse – creates a group of "collapsible" widgets and a button to quickly expand / collapse them on the maps screen.

![Collapsible widget states](/assets/images/widgets/collapsible_widget_states.png)

**Note**: all widgets are [profile dependent](/osmand/personal/profiles), so in case you change the order, visibility or state for 1 profile, it won't be applied to other profiles. Each profile has its own predefined list of widgets based on the design of the navigation screen. It can be customized and used with or without navigation.

## Configure screen menu

### Quick action
- [Quick action](/osmand/widgets/quick-action) - is a button that gives quick access to frequently used actions.

### Right panel widgets
 - [Intermediate destination](/osmand/widgets/nav-widgets#intermediate-destination) - shows current distance to the nearest intermediate navigation point.
 - [Destination](/osmand/widgets/nav-widgets#destination) - shows current distance to the finish point.
 - [Intermediate arrival time](/osmand/widgets/nav-widgets#intermediate-arrival-time-or-intermediate-time) - shows Intermediate arrival time or Intermediate time of navigation to the intermediate point.
 - [Arrival time](/osmand/widgets/nav-widgets#arrival-time-or-time-to-go) - shows the time when you will approach the destination or if you switch to the time to go it will display the total time left.
 - [Relative bearing](/osmand/widgets/nav-widgets#relative--magnetic-bearing) - shows relative or magnetic bearing.
 - [Speed](/osmand/widgets/info-widgets#speed) - shows your current speed detected by GPS-sensor.
 - [Speed limit](/osmand/widgets/nav-widgets#speed-limit) - shows a speed limit for a current road.
 - [Altitude](/osmand/widgets/info-widgets#altitude) - shows the height above sea level of current geolocation. 
 - [GPS info](/osmand/widgets/info-widgets#gps-info-android) (Android) - shows a number of satellites that a device detects and uses at that moment.
 - [Current time](/osmand/widgets/info-widgets#current-time) - shows current time from your device.
 - [Battery level](/osmand/widgets/info-widgets#battery-level) - shows battery level of your device.
 - [Radius ruler](/osmand/widgets/radius-ruler) - shows distance between users location and inner point of the 'Radius-ruler' tool distance-circles on the map. 
 - [Parking](/osmand/widgets/info-widgets#-parking-widget) - shows distance from the current position to the parking place.
 - [Trip recording](/osmand/widgets/info-widgets#-trip-recording-widget) - provides quick access to start / stop track recording.
 - [Mapillary](/osmand/widgets/info-widgets#-mapillary-widget) - provides quick access to Mapillary app to add Street-Level-Imagery.
 - [FPS debug info](/osmand/widgets/info-widgets#-fps-info-android) (Android) - investigate how fast map & map elements are showed & refreshed.

### Left panel widgets
 - [Next turns](/osmand/widgets/nav-widgets#next-turns) - shows info about next maneuvers and distance to it.
 - [Alert info](/osmand/widgets/nav-widgets#alert-information) - shows traffic alerts during navigation.
 - [Compass](/osmand/widgets/map-buttons#compass) - indicates how the map is oriented on the device screen.

### Remaining elements
- [Street name](/osmand/widgets/nav-widgets#street-name) combined with [Approach POI](/osmand/widgets/nav-widgets#poisfavorites) -
- [Coordinates widget](/osmand/widgets/info-widgets#coordinates-widget) -  shows the geographic coordinates of current geolocation (appears on the top bar).
- [Distance by tap](/osmand/widgets/radius-ruler#distance-by-tap-tool)- an option to measure the distance from your position to the selected point.
- [Map markers](/osmand/widgets/markers) - shows a directional line from your position to the active marker locations (could be on the top bar or on the right widget panel).
- Transparent widgets - makes transparent the background of the navigation and information widgets.  
- [Lanes](/osmand/widgets/nav-widgets#lanes) - shows the lanes you have to drive during a navigation with distance to a maneuver.

## Read more
  [Read more information about each widget individually](/osmand/widgets).
