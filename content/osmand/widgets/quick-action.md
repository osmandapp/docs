---
title: "Quick Action"
intro: "Quick Action Widget is a quick access button on the map with frequently used actions accessible 'just in 2 clicks'."
versions: '*'
---
{% data reusables.general.article-not-complete %}

![Quick action widget](/assets/images/widgets/quick_action_widget.png)

## Enable widget
{% data reusables.general.image-needs-to-be-updated %}

In order to use the Quick Actions button you need to enable this widget first.

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.layer_map_appearance %} → {% data variables.android-values.configure_screen_quick_action %} 

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.layer_map_appearance %} → {% data variables.ios-values.configure_screen_quick_action %}

By default the Quick action button will appear on the right corner (above the zoom buttons), but it can be moved to the any part of the screen by long tap on it. 

To open Quick action menu just press on the button.

## Edit actions list

### Add new action
{% data reusables.general.image-needs-to-be-updated %}

There are 2 ways to add items to the Quick actions list: 
- Menu → Configure screen → Quick action → &#8230;&#124; → Add action (The plus symbol also gives an option to add new actions to the list)
- On the map click on the Quick action icon → Add action

First you need to select [type of the action](#quick-actions-types) and then you could change its name and parameters ([See below](#quick-actions-types) which parameters could be configured for each action type). Every action should have a unique name.

### Reorder actions
{% data reusables.general.image-needs-to-be-updated %}

Quick action panel has only **6 slots** for actions per screen. However you could have multiple screens and actions are grouped by the specified order. In order to change the order of items:

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.layer_map_appearance %} → {% data variables.android-values.configure_screen_quick_action %} → Hold & Drag selected action up and down by the icon (three vertical lines) in the list

{% data variables.product.android_button_seq %} Open Quick action menu  → Long tap on 'Add action' → Hold & Drag selected action up and down by the icon (three vertical lines) in the list

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.layer_map_appearance %} → {% data variables.ios-values.configure_screen_quick_action %} → Click Edit (Pencil icon) → Hold & Drag selected action up and down by the icon (three vertical lines) in the list → Done

### Edit / Remove action
{% data reusables.general.image-needs-to-be-updated %}

There are several ways how to access Quick Action to edit or delete it:

 - Open via Edit actions list

    {% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.layer_map_appearance %} → {% data variables.android-values.configure_screen_quick_action %}

    {% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.layer_map_appearance %} → {% data variables.ios-values.configure_screen_quick_action %}

 - Long tap on the action 

    Open Quick action menu → Long tap on the action (short tap to execute the action)

 - Bulk delete

    {% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.layer_map_appearance %} → {% data variables.android-values.configure_screen_quick_action %} → Click Delete (Bin icon on the right top corner) → Select actions → Delete

    {% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.layer_map_appearance %} → {% data variables.ios-values.configure_screen_quick_action %} → Click Edit (Pencil icon on the right top corner) → Select actions → Delete
 

## Quick actions types

| Name | Actions |
|:-------------|:-------------|
| **{% data variables.android-values.quick_action_add_create_items %}** | |
| {% data variables.android-values.quick_action_add_favorite %} | Adds favorite to a selected (center) point of the map. <br> - **Show an interim dialog**: displays confirmation dialog <br> - **Group**: adds favorite to a selected group <br> - **Color**: adds favorite with a preselected color <br> - **Name**: adds favorite with a given name prefix  |
| {% data variables.android-values.quick_action_add_gpx %} | Adds new Track waypoint to currently recording track. <br> - **Show an interim dialog**: displays confirmation dialog <br> - **Group**: adds favorite to a selected group <br> - **Color**: adds favorite with a preselected color <br> - **Name**: adds favorite with a given name prefix  |
| {% data variables.android-values.quick_action_add_marker %} | Adds marker to a selected (center) point of the map. |
| {% data variables.android-values.quick_action_add_parking %} | Adds/Replaces parking to a selected (center) point of the map. |
| {% data variables.android-values.quick_action_add_poi %} | xxx |
| {% data variables.android-values.quick_action_add_osm_bug %} | xxx |
| New photo/video/audio note (Android) | xxx |
| **{% data variables.android-values.quick_action_add_configure_map %}** | |
| {% data variables.ios-values.toggle_fav %} | Allows to show or hide the favourite points on the map (that selected on the My places → Favorits as Visible) |
| {% data variables.ios-values.show_hide_gpx %} | Allows to show or hide the last opened track on the map|
| {% data variables.ios-values.toggle_poi %} | Allows to selected POI categories that you want to display on the map. It is possible to select multiply categories in one button or set separately each button for each category|
| {% data variables.ios-values.toggle_public_transport %}| Allows displaying public transport on the map. When you click on this button for the first time you need to choose what type of public transport would you like to display |
| {% data variables.ios-values.quick_action_showhide_mapillary_title %} | Allows to display Mapillary layer on the map |
| {% data variables.ios-values.toggle_contour_lines %} | Allows show or hide contour lines on the map |
| {% data variables.android-values.quick_action_show_hide_title %} {% data variables.android-values.shared_string_terrain %} | Allows to display terrian layer on the map |
| {% data variables.android-values.quick_action_show_hide_title %} {% data variables.android-values.osm_notes %} | Allows to display on the map all exist notes |
| {% data variables.android-values.quick_action_map_style %} | Allows you to create a list of the frequently used map styles. You can add to one button a few map styles or make separately each button for each map style. If you turn on 'Show on an interim dialog' will be available to select what map display now. If turn off  'Show on an interim dialog' while tapping on the Quick action button map styles will change in order.  |
| {% data variables.ios-values.change_map_source %} | Allows you to create a list of the frequently used map source. You can add to one button a few map sources or make separately each button for each map source. If you turn on 'Show on an interim dialog' will be available to select what map source display now. If turn off  'Show on an interim dialog' while tapping on the Quick action button map source will change in order.  |
| {% data variables.ios-values.change_map_overlay %} | Allows you to create a list of the frequently used overlay maps. You can add to one button a few overlay maps or make separately each button for each map. If you turn on 'Show on an interim dialog' will be available to select what overlay map display now. If turn off  'Show on an interim dialog' while tapping on the Quick action button overlay maps will change in order. |
| {% data variables.ios-values.change_map_underlay %} | Allows you to create a list of the frequently used underlay maps. You can add to one button a few underlay maps or make separately each button for each map. If you turn on 'Show on an interim dialog' will be available to select what underlay map display now. If turn off  'Show on an interim dialog' while tapping on the Quick action button underlay maps will change in order.  |
| **{% data variables.android-values.quick_action_add_navigation %}**  | |
| {% data variables.android-values.quick_action_day_night_switch_mode %} | A toggle between day and night modes |
| {% data variables.android-values.quick_action_navigation_voice %} | A toggle that allows you mute or unmute voice guidance during navigation |
| {% data variables.android-values.context_menu_item_directions_from %} | Allows to make the screen center as the point of departure|
| {% data variables.android-values.quick_action_add_destination %} | Allows to make the screen center as the endpoint |
| {% data variables.android-values.quick_action_add_first_intermediate %} | Allows to make the screen center as the first intermediate point |
| {% data variables.android-values.quick_action_replace_destination %} | yyyyyyyy |
| {% data variables.android-values.quick_action_remove_next_destination %} | This button will be active only if you select a destinayion. Allows you to recalculate the route or finish navigation   |
| {% data variables.android-values.quick_action_auto_zoom %} | yyyyyyyy |
| {% data variables.android-values.quick_action_start_stop_navigation %} | yyyyyyyy |
| {% data variables.android-values.quick_action_resume_pause_navigation %} | yyyyyyyy |
| {% data variables.android-values.change_application_profile %} | yyyyyyyy |
