---
title: "Quick Action"
intro: "Quick Action Widget is a configurable quick access button on the map with selected actions accessible 'just in 2 clicks'."
versions: '*'
---

![Quick action widget](/assets/images/widgets/quick_action_widget.png)

## Enable widget

In order to use the Quick Actions button you need to enable this widget first.

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.layer_map_appearance %} → {% data variables.android-values.configure_screen_quick_action %} 

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.layer_map_appearance %} → {% data variables.ios-values.configure_screen_quick_action %}

By default the Quick action button will appear on the right corner (above the zoom buttons), but it can be moved to the any part of the screen by long tap on it. 

| | |
|------------|------------|
|First appearing  | ![Quick action widget_view](/assets/images/widgets/quick_action_widget_view.png) |
|Long tap and moving  | ![Quick action widget_tap](/assets/images/widgets/quick_action_widget_tap.png) |
|New place  | ![Quick action widget_move](/assets/images/widgets/quick_action_widget_move.png) |

To open Quick action menu just press on the button.

| | |
|------------|------------|
|**Android**  | **iOS** |
| ![Quick action widget_android](/assets/images/widgets/quick_action_widget_android.png) | ![Quick action widget_ios](/assets/images/widgets/quick_action_widget_ios.png) |

## Edit actions list

### Add new action

There are 2 ways to add items to the Quick actions list: 
- Menu → Configure screen → Quick action → &#8230;&#124; → Add action(+) 

| | |
|------------|------------|
|**Android**  | **iOS** |
| ![Quick action widget_android_add](/assets/images/widgets/quick_action_widget_android_add.png) | ![Quick action widget_ios_add](/assets/images/widgets/quick_action_widget_ios_add.png) |

- Click "Quick action" button → "Quick action" menu → Add action

| | |
|------------|------------|
|**Android**  | **iOS** |
| ![Quick action widget_android_add2](/assets/images/widgets/quick_action_widget_android_add2.png) | ![Quick action widget_ios_add2](/assets/images/widgets/quick_action_widget_ios_add2.png) |

First you need to select [type of the action](#quick-actions-types) and then you could change its name and parameters ([See below](#quick-actions-types) which parameters could be configured for each action type). Every action should have a unique name.

### Reorder actions

Quick action panel has only **6 slots** for actions per screen. However you could have multiple screens and actions are grouped by the specified order. In order to change the order of items:

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.layer_map_appearance %} → {% data variables.android-values.configure_screen_quick_action %} → Hold & Drag selected action up and down by the icon (three vertical lines) in the list

{% data variables.product.android_button_seq %} Open Quick action menu  → Long tap on 'Add action' → Hold & Drag selected action up and down by the icon (three vertical lines) in the list

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.layer_map_appearance %} → {% data variables.ios-values.configure_screen_quick_action %} → Click Edit (Pencil icon) → Hold & Drag selected action up and down by the icon (three vertical lines) in the list → Done

| | |
|------------|------------|
|**Android**  | **iOS** |
| ![Quick action widget_android_order](/assets/images/widgets/quick_action_widget_android_order.png) | ![Quick action widget_ios_order](/assets/images/widgets/quick_action_widget_ios_order.png) |

### Edit / Remove action

There are several ways how to access Quick Action to edit or delete it:

 - Long tap on the action (Android)

    Open Quick action menu → Long tap on the action (short tap to execute the action)

 - Delete via "Edit actions" list

    {% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.layer_map_appearance %} → {% data variables.android-values.configure_screen_quick_action %} → Click Delete (Bin icon on the right top corner) → Select actions → Delete

    {% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.layer_map_appearance %} → {% data variables.ios-values.configure_screen_quick_action %} → Click Edit (Pencil icon on the right top corner) → Select actions → Delete
 
| | |
|------------|------------| 
|**Android**  | **iOS** |
| ![Quick action widget_android_del](/assets/images/widgets/quick_action_widget_android_del.png) | ![Quick action widget_ios_del](/assets/images/widgets/quick_action_widget_ios_del.png) |


## Quick action types

### {% data variables.android-values.quick_action_add_create_items %}
| Action | Description |
|:-------------|:-------------|
| [{% data variables.android-values.quick_action_add_favorite %}](/osmand/map/configure-map-menu#map-layers) | Adds favorite to a selected (center) map location. <br> - **Show an interim dialog**: displays confirmation dialog <br> - **Group**: adds favorite to a selected group <br> - **Color**: adds favorite with a preselected color <br> - **Name**: adds favorite with a given name prefix  |
| [{% data variables.android-values.quick_action_add_gpx %}](/osmand/map/configure-map-menu#map-layers) | Adds new Track waypoint to currently recording track. <br> - **Show an interim dialog**: displays confirmation dialog <br> - **Group**: adds favorite to a selected group <br> - **Color**: adds favorite with a preselected color <br> - **Name**: adds favorite with a given name prefix  |
| [{% data variables.android-values.quick_action_add_marker %}](/osmand/map/configure-map-menu#map-layers) | Adds marker to a selected (center) map location. |
| {% data variables.android-values.quick_action_add_parking %} <br> [Plugin](/osmand/plugins/parking) | Adds parking to a selected (center) map location. Old parking position is deleted. |
| {% data variables.android-values.quick_action_add_poi %} <br> [Plugin](/osmand/plugins/osm-editing) | Adds POI to a selected (center) map location map (same as context menu action). <br> - **Show an interim dialog**: displays confirmation dialog <br> - **POI type** (optional): preselect OSM type <br> - **Tag/Value** (multiple): add [OpenStreetMap](https://wiki.openstreetmap.org/wiki/Map_Features) tags / values |
| {% data variables.android-values.quick_action_add_osm_bug %} <br> [Plugin](/osmand/plugins/osm-editing) | Adds [OSM Note](https://wiki.openstreetmap.org/wiki/Notes)  <br> - **Show an interim dialog**: displays confirmation dialog <br> - **Message**: adds default message to the note |
| Add media note <br> [Android Plugin](osmand/plugins/audio-video-notes) | Starts audio / photo / video note recording  for a selected (center) map location. |

### {% data variables.android-values.quick_action_add_configure_map %}
| Action | Description |
|:-------------|:-------------|
| {% data variables.ios-values.toggle_fav %} | Show or hide the favourite points on the map. |
| {% data variables.ios-values.show_hide_gpx %} | Show or hide the last visible tracks on the map. |
| {% data variables.ios-values.toggle_poi %} | Enable or disable POI layer with selected categories. <br> - **POI Categories**: allows to select multiple categories <br> Note: Action will replace previously selected categories, if POI layer was active before.   |
| [{% data variables.ios-values.toggle_public_transport %}](/osmand/map/vector-maps#transport) | Enable or disable public transport map layer. <br> - **Transport type** (on first click): select one or many options from 'Transport stops', 'Bus, trolleybus, shuttle routes', 'Tram and train routes', 'Subway routes' |
| [{% data variables.ios-values.change_map_source %}](/osmand/map/raster-maps) | Create a list of map sources and cycle through them.  <br> - **Show an interim dialog**: displays dialog with maps list <br> - **Do not show an interim dialog**: map sources will be changed by defined  order. <br> - Displayed name: **Map source >**. '>' after the map name indicates what is current selected map source. <br> - Displayed Name: **> Next map source**. '>' before the map name indciates what is next selected map source if action is executed. <br> - **Note**: you could have 1 action to change source and select multiple map sources or many quick actions with 1 map source selected, so you could quickly select the map source just from quick aciton list. |
| [{% data variables.ios-values.change_map_overlay %}](/osmand/map/raster-maps) | Create a list of map sources as map overlay and cycle through them. <br> Note: works similar to **{% data variables.ios-values.change_map_source %}** (see above) |
| [{% data variables.ios-values.change_map_underlay %}](/osmand/map/raster-maps) |  Create a list of map sources as map underlay and cycle through them. <br> Note: works similar to **{% data variables.ios-values.change_map_source %}** (see above)  |
| [{% data variables.android-values.quick_action_map_style %}](/osmand/map/vector-maps#default-map-styles) | Create a list of map styles for vector maps and cycle through them. <br> Note: works similar to **{% data variables.ios-values.change_map_source %}** (see above) |
| {% data variables.ios-values.quick_action_showhide_mapillary_title %} <br> [Plugin](/osmand/plugins/mapillary) | Display or hide Mapillary layer on the map |
| {% data variables.ios-values.toggle_contour_lines %} <br> [Plugin](/osmand/plugins/contour-lines) | Display or hide contour lines on the map |
| {% data variables.android-values.quick_action_show_hide_title %} {% data variables.android-values.shared_string_terrain %} <br> [Plugin](/osmand/plugins/contour-lines) | Display and hide terrain layer on the map |
| {% data variables.android-values.quick_action_show_hide_title %} {% data variables.android-values.osm_notes %} <br> [Plugin](/osmand/plugins/osm-editing) | Allows to display on the map all OSM notes |

### {% data variables.android-values.quick_action_add_navigation %}

| Action | Description |
|:-------------|:-------------|
| [{% data variables.android-values.quick_action_day_night_switch_mode %}](/osmand/map/vector-maps#map-mode) | Switche between day and night map modes |
| {% data variables.android-values.quick_action_navigation_voice %} | Mute or unmute voice guidance during navigation |
| {% data variables.android-values.context_menu_item_directions_from %} | Mark a selected (center) map location as a point of departure |
| {% data variables.android-values.quick_action_add_destination %} | Add a selected (center) map location as a destination. Previous destination becomes last intermediate point.  |
| {% data variables.android-values.quick_action_add_first_intermediate %} | Add a selected (center) map location as first intermediate point. Previous destination stays the same. |
| {% data variables.android-values.quick_action_replace_destination %} | Set / Replace a selected (center) map location as a destination. Previous destination is deleted. |
| {% data variables.android-values.quick_action_remove_next_destination %} | Remove next intermediate point, if present, otherwise removes destination and displays finish navigation dialog. Action is inactive if you don't have any destination. |
| {% data variables.android-values.quick_action_auto_zoom %} | Enable or disable map auto zoom during navigation |
| {% data variables.android-values.quick_action_start_stop_navigation %} | Start navigation (if there is a destination point present) or stop navigation |
| {% data variables.android-values.quick_action_resume_pause_navigation %} | Pause / Resume navigation |
| {% data variables.android-values.change_application_profile %} | Create a list of application profiles and cycle through them.  <br> - **Show an interim dialog**: displays dialog with profiles list <br> - **Do not show an interim dialog**: profiles will be changed by defined order. <br> - **Note**: you could have 1 action with multiple profiles or many actions with 1 profile. |


### {% data variables.android-values.layer_map_appearance %}

| Action | Description |
|:-------------|:-------------|
| [{% data variables.android-values.quick_action_show_hide_title %} {% data variables.android-values.coordinates_widget %}](/osmand/widgets/info-widgets#coordinates-widget) | Show and hide coordinates widget |
