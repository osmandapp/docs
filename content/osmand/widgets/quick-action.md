---
title: "Quick action"
intro: "Quick Actions Widget is an additional customizable panel that allows you in two clicks activate all frequently used actions."
versions: '*'
---
{% data reusables.general.article-not-complete %}

![Quick action widget](/assets/images/widgets/quick_action_widget.png)

## Configure quick actions list
### Enable widget
In order to use the Quick Actions button you need to enable this widget on the home screen.

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.layer_map_appearance %} → {% data variables.android-values.configure_screen_quick_action %} 

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.layer_map_appearance %} → {% data variables.ios-values.configure_screen_quick_action %}

By default, the Quick action button will appear on the right corner (above the zoom button). But it can be moved to the other part of the screen by long tap on it. 

To open Quick action menu click on it.

### Create Quick action list
There are two ways to add items to the Quick actions list: 
- Menu → Configure screen → Quick action → &#8230;&#124; → Add action (The plus symbol also gives an option to add new actions to the list)
- On the map click on the Quick action icon → Add action

![Quick action edit action](/assets/images/widgets/quick_action_edit_action.png)

When you select the action you should assign a name. By default, it will be named as a chosen category but you can rename it. Another way to rename is to click on the Quick action widget then with a long tap select the needed item and rename in editing menu that will appear .

Сhange the order of items in a list:

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.layer_map_appearance %} → {% data variables.android-values.configure_screen_quick_action %} → Hold the lines on the right, allows you to move items along the list

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.layer_map_appearance %} → {% data variables.ios-values.configure_screen_quick_action %} → Swiping up and down on the three vertical lines in the editing menu will allow you to move the action along the list.

In order to remove items from Quick actions widget:

- 1 {% data variables.product.android_button_seq %}
 - 1.1 {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.layer_map_appearance %} → {% data variables.android-values.configure_screen_quick_action %} → The bin icon on the left
 - 1.2 {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.layer_map_appearance %} → {% data variables.android-values.configure_screen_quick_action %} → Tap on the bin icon on the right top corner → Select actions that you would like to delete11
 - 1.3 {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.layer_map_appearance %} → {% data variables.android-values.configure_screen_quick_action %} → At the very bottom is available 'Delete all' button
 - 1.4 Open Quick action menu → Long tap on the action → The bin icon on the right top corner
- 2 {% data variables.product.ios_button_seq %} 
 - 2.1 {% data variables.ios-values.menu %} → {% data variables.ios-values.layer_map_appearance %} → {% data variables.ios-values.configure_screen_quick_action %} → The pen icon in the top-right corner

## Quick actions types

| Name | Actions |
|:-------------|:-------------|
| **{% data variables.android-values.quick_action_add_create_items %}** | |
| {% data variables.android-values.quick_action_add_favorite %} | xxx |
| {% data variables.android-values.quick_action_add_gpx %} | xxx |
| {% data variables.android-values.quick_action_add_marker %} | xxx |
| {% data variables.android-values.quick_action_add_parking %} | xxx |
| {% data variables.android-values.quick_action_add_poi %} | xxx |
| {% data variables.android-values.quick_action_add_osm_bug %} | xxx |
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
