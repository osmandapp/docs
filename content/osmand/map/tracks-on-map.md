---
title: "Tracks and Routes"
intro: "On the map, a user can display GPX-tracks and navigation routes."
versions: '*'
---

{% data reusables.general.article-not-complete %}

## Type of routes

Routes on the map have next type:
- Tracks (GPX) - recorded or planning trip in [GPX-format](https://en.wikipedia.org/wiki/GPS_Exchange_Format).

![Tracks on the map](/assets/images/map/tracks_layer.png)

- Navigation Route - trip from A to B which built by [routing type](/osmand/navigation/route-navigation).

![Route on the map](/assets/images/map/route_layer.png)

- Routes and route networks on the map - [objects which rendering](/osmand/map/vector-maps#routes) on the map from [data OpenStreetMap](https://wiki.openstreetmap.org/wiki/Relation:route).

![Routes on the map](/assets/images/map/routes_layer.png)


## Tracks 

Track is [user data](/osmand/personal/myplaces) that showed [recorded](/osmand/plugins/trip-recording) or [planning trip](/osmand/plan-route). 

OsmAnd app uses [GPX-format](https://en.wikipedia.org/wiki/GPS_Exchange_Format)

![Tracks on the map Android](/assets/images/map/tracks_layer_android.png) ![Tracks on the map iOS](/assets/images/map/tracks_layer_ios.png) 

There are several ways to show or not [GPX-tracks](/osmand/personal/myplaces) on the map:

### {% data variables.android-values.configure_map %} menu

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_map %} → {% data variables.android-values.show_gpx %} → &#8230 → Choosing tracks for displayed from the list and setting of track appearance. Info below {% data variables.android-values.show_gpx %} shows number of selected tracks on the map: 

![Tracks note](/assets/images/map/tracks_note.png)

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.configure_map %} → {% data variables.ios-values.tracks %} → Choosing tracks for displayed from the list 

![Tracks menu Android](/assets/images/map/tracks_menu_android.png) ![Tracks menu iOS](/assets/images/map/tracks_menu_ios.png) 

###  {% data variables.android-values.shared_string_my_places %} menu


{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.shared_string_my_places %} → {% data variables.android-values.shared_string_gpx_files %} → &#xe802; → {% data variables.android-values.shared_string_show_on_map %}  or ["Map" button](/osmand/personal/tracks#my-places-android) for choosing multiple tracks. 

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.menu_my_places %} → {% data variables.ios-values.tracks %} → &#8250; → {% data variables.ios-values.map_settings_show %} or ["Layer" button](/osmand/personal/tracks#my-places-ios) for choosing multiple tracks.

![Tracks my places Android](/assets/images/map/tracks_myplaces_android.png) ![Tracks menu iOS](/assets/images/map/tracks_myplaces_ios.png)


### Track Appearance (Android)

Click to the track on the map -> {% data variables.android-values.shared_string_overview %} -> click to "eye" button.

![Track menu options Android](/assets/images/map/eye_button_android.png)   


- Split interval
- Direction arrows
- Show start / finish
- Solid color
- Color by speed
- Color by altitude
- Color by slope
- Thickness

## Navigation Route

The route is a line on the map that shows a user's creating trip. In OsmAnd users create a route by [Navigation function](/osmand/navigation).

| Android | iOS |
| :--- | :--- |
| ![Route on the map Android](/assets/images/map/route_layer_android.png) |![Route on the map iOS](/assets/images/map/route_layer_ios.png) |

### Route Appearance (Android)

In OsmAnd for Android, [a user can customize](/osmand/personal/profiles) route line: color and width.

{% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %} → {% data variables.android-values.profile_appearance %} → {% data variables.android-values.customize_route_line %}

![Route Customization Android](/assets/images/map/route_custom_android.png)

## Travel Routes


- Hiking 
- Bicycle
- Node networks

Link to [Vector map style](/osmand/map/vector-maps#routes).


## Analyze Route on Map (Android)

![Track menu analyze on map Android](/assets/images/personal/tracks/track_analyze_on_map_android.png) ![Track menu analize on the map distance Android](/assets/images/personal/tracks/track_analyze_on_map_distance_android.png) 

- Interact with map & graph
- Follow My location 
- Graph: altitude / slope / speed
- Graph: distance / time



## Read more

### [Tracks](/osmand/personal/tracks)
### [Track Context menu](/osmand/map/track-context-menu)
### [Configure map menu](/osmand/map/configure-map-menu)
### [Trip recording](/osmand/plugins/trip-recording)
### [Plan a route](/osmand/plan-route)
### [Navigation by track](/osmand/navigation/gpx-navigation)
