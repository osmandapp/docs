---
title: "Markers"
intro: "Markers interface is a convenient tool that helps you save points on the map for your short-term needs."
versions: '*'
---

{% data reusables.general.article-not-complete %}


Map markers are special points marked as flags on the map. You can customize their look & feel with **arrows** ({% data variables.android-values.show_arrows_on_the_map %}) and **distance indication** ({% data variables.android-values.show_direction %}). 


{% default %}

![Map markers Android](/assets/images/map/map_markers_android.png) ![Map markers iOS](/assets/images/map/map_markers_ios.png)

{% enddefault %}

{% android %}

![Map markers Android](/assets/images/map/map_markers_android.png)

{% endandroid %}

{% ios %}

![Map markers iOS](/assets/images/map/map_markers_ios.png)

{% endios %}


## Map markers menu

{% data reusables.general.android-ios-switcher %}

{% default %}

![Map markers menu Android](/assets/images/personal/markers/map_markers_menu_android.png) ![Map markers menu iOS](/assets/images/personal/markers/map_markers_menu_ios.png)

{% enddefault %}

{% android %}

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.map_markers %}

![Map markers menu Android](/assets/images/personal/markers/map_markers_menu_android.png)

- {% data variables.android-values.shared_string_list %} - keeps all your Map markers in the one place. Here you can move Map marker to the History part or replace it.
- {% data variables.android-values.shared_string_groups %} - contains groups of your Map markers. 
- {% data variables.android-values.shared_string_history %} - keeps all Map markers which were deleted yearlier.
- {% data variables.android-values.shared_string_more_without_dots %} - keeps Options of Map markers (Appearance) and etc.


{% endandroid %}

{% ios %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.map_markers %}

![Map markers menu iOS](/assets/images/personal/markers/map_markers_menu_ios.png)

{% endios %}


### List

![Map markers List Android](/assets/images/personal/markers/map_markers_list_android.png) 

### Groups

![Map markers Groups Android](/assets/images/personal/markers/map_markers_groups_android.png) ![Map markers Groups Android](/assets/images/personal/markers/map_markers_groups_add_android.png) 

You can import groups from favorites or track waypoints.

Click to '&#43;' Button.  {% data variables.android-values.favourites_group %}:
- {% data variables.android-values.favourites_group %} - from Favorites.
- {% data variables.android-values.shared_string_gpx_waypoints %} - from track waypoints.

### History

![Map markers History Android](/assets/images/personal/markers/map_markers_history_android.png) ![Map markers History iOS](/assets/images/personal/markers/map_markers_history_ios.png) 

### More / Appearance 

![Map markers More Android](/assets/images/personal/markers/map_markers_more_android.png) ![Map markers Appearance iOS](/assets/images/personal/markers/map_markers_appearance_ios.png) 

- {% data variables.android-values.appearance_on_the_map %} or {% data variables.ios-values.map_settings_appearance %}  - [settings for Map markers](/osmand/personal/markers#appearance-on-the-map).
- {% data variables.android-values.sort_by %} (Android) - sort Makrers in [List](/osmand/personal/markers#list-android).
- {% data variables.android-values.coordinate_input %} (Android) - add Markers by [input coorditanes (like for Tracks)](/osmand/personal/tracks#coordinate-input-android)
- {% data variables.android-values.plan_route %} (Android) - build route [for navigation using chosen markers](/osmand/navigation/markers-navigation).
- {% data variables.android-values.marker_save_as_track %} (Android) - save active markers like file GPX.
- {% data variables.android-values.move_all_to_history %} (Android) - deactivate all markers and move its to [History](/osmand/personal/markers#history).

## Add Marker on the map

Short or long tap on the map and choose neede action in [Map Context menu](/osmand/map/map-context-menu#add--edit-marker).

### Actions in Map Context menu

[Link to the article](/osmand/map/map-context-menu#add--edit-marker)

## Appearance on the map

[Link to description](/osmand/widgets/markers#configure-marker-widgets-and-marker-appearance)

![Map markers Appearance Android](/assets/images/personal/markers/map_markers_appearance_android.png) ![Map markers Appearance iOS](/assets/images/personal/markers/map_markers_appearance_ios.png)

## Map markers widgets

[Link to description Top Bar](/osmand/widgets/markers#top-bar-widget-markers)

[Link to description Widget panel](/osmand/widgets/markers#panel-widgets-markers)

## Plan route for Markers (Android)

[Link to description](/osmand/navigation/markers-navigation)

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.map_markers %} → {% data variables.android-values.shared_string_more_without_dots %} → {% data variables.android-values.plan_route %}

![Map markers Plan Route Android](/assets/images/personal/markers/map_markers_plan_route_android.png)

You need choose markers for your route.

![Map markers Plan Route points Android](/assets/images/personal/markers/map_markers_plan_route_points_android.png)

Next 'Options' button (top corner):

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.map_markers %} → {% data variables.android-values.shared_string_more_without_dots %} → {% data variables.android-values.plan_route %} → {% data variables.android-values.shared_string_options %}

![Map markers Plan Route Options Android](/assets/images/personal/markers/map_markers_plan_route_options_android.png)

{% data variables.android-values.shared_string_options %}:
- {% data variables.android-values.get_directions %} - Starting build your route ([Navigation](/osmand/navigation)).
- {% data variables.android-values.make_round_trip %} - {% data variables.android-values.make_round_trip_descr %} Round trip or not. 

{% data variables.android-values.sort_by %}:
- {% data variables.android-values.intermediate_items_sort_by_distance %}  - Sort your markers in [List](/osmand/personal/markers#list-android).
- {% data variables.android-values.shared_string_reverse_order %} - Reverse order for markder in [List](/osmand/personal/markers#list-android).

Next, building a route.

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.map_markers %} → {% data variables.android-values.shared_string_more_without_dots %} → {% data variables.android-values.plan_route %} → {% data variables.android-values.shared_string_options %} → {% data variables.android-values.get_directions %}


![Map markers Plan Route Directions Android](/assets/images/personal/markers/map_markers_plan_route_directions_android.png)


## Add/Remove Markers from Favorites/Waypoints (Android)

[Favorites to Map Markers link](/osmand/personal/favorites#add-to-map-markers-android)

[Waypoints to Map Markers link](/osmand/personal/tracks#group-menu)







