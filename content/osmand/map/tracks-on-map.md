---
title: "Tracks and Routes"
intro: "On the map, a user can display GPX-tracks and navigation routes."
versions: '*'
---

{% data reusables.general.article-not-complete %}

## Tracks on the map (Layers)

Track is [user data](/osmand/personal/myplaces) that showed [recorded](/osmand/plugins/trip-recording) or [planning trip](/osmand/plan-route). 

| Android | iOS |
| :--- | :--- |
| ![Tracks on the map Android](/assets/images/map/tracks_layer_android.png) |![Tracks on the map iOS](/assets/images/map/tracks_layer_ios.png) |

For showing or not [GPX-tracks](/osmand/personal/myplaces) on the map.

**1. {% data variables.android-values.configure_map %} menu**

| Android | iOS |
| :--- | :--- |
|{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_map %} → {% data variables.android-values.show_gpx %} → &#8230 → Choosing tracks for displayed from the list and setting of track appearance | {% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.map_settings_map %} → {% data variables.ios-values.tracks %} → Choosing tracks for displayed from the list |
|  Info below {% data variables.android-values.show_gpx %} shows number of selected tracks on the map ![Tracks note](/assets/images/map/tracks_note.png) |  |
|   ![Tracks menu Android](/assets/images/map/tracks_menu_android.png) | ![Tracks menu iOS](/assets/images/map/tracks_menu_ios.png) |

**2. {% data variables.android-values.shared_string_my_places %} menu**

| Android | iOS |
| :--- | :--- |
|   {% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.shared_string_my_places %} → {% data variables.android-values.shared_string_gpx_files %} → &#xe802; → {% data variables.android-values.shared_string_show_on_map %}  or "Map" button for choosing multiple tracks  | {% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.menu_my_places %} → {% data variables.ios-values.tracks %} → &#8250; → {% data variables.ios-values.map_settings_show %} or "Layer" button for choosing multiple tracks  |
|   ![Tracks my places Android](/assets/images/map/tracks_myplaces_android.png) | ![Tracks menu iOS](/assets/images/map/tracks_myplaces_ios.png) |

## Context Track menu (Android)

| Android | iOS |
| :--- | :--- |
| Click to a track on the map → Tap on the "Eye" button  or {% data variables.android-values.shared_string_menu %}  → {% data variables.android-values.shared_string_show_on_map %} |  |
|   ![Eye button Android](/assets/images/map/eye_button_android.png) |  |

## Track Appearance (Android)

![Track menu options Android](/assets/images/personal/tracks/track_appearance_speed_android.png)  ![Track menu split interval Android](/assets/images/personal/tracks/track_appearance_split_android.png) 


- Split interval
- Direction arrows
- Show start / finish
- Solid color
- Color by speed
- Color by altitude
- Color by slope
- Thickness

## Analyze on Map (Android)

![Track menu analyze on map Android](/assets/images/personal/tracks/track_analyze_on_map_android.png) ![Track menu analize on the map distance Android](/assets/images/personal/tracks/track_analyze_on_map_distance_android.png) 

- Interact with map & graph
- Follow My location 
- Graph: altitude / slope / speed
- Graph: distance / time


## Routes on the map

The route is a line on the map that shows a user's creating trip. In OsmAnd users create a route by [Navigation function](/osmand/navigation).

| Android | iOS |
| :--- | :--- |
| ![Route on the map Android](/assets/images/map/route_layer_android.png) |![Route on the map iOS](/assets/images/map/route_layer_ios.png) |

### Customize route line (Android)

In OsmAnd for Android, [a user can customize](/osmand/personal/profiles) route line: color and width.

{% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %} → {% data variables.android-values.profile_appearance %} → {% data variables.android-values.customize_route_line %}

![Route Customization Android](/assets/images/map/route_custom_android.png)


## Read more

- [Configure map menu](/osmand/map/configure-map-menu).
  
- [Trip recording](/osmand/plugins/trip-recording).
  
- [Plan a route](/osmand/plan-route) tool.
