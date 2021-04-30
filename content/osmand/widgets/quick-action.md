---
title: "Quick action"
intro: "Quick Actions Widget is an additional customizable panel that allows you to make access to all frequently used actions faster and more convenient."
versions: '*'
---

![Quick action widget](/assets/images/widgets/quick_action_widget.png)

## Configure quick actions list
### Enable widget
In order to use the Quick Actions button you need to enable this widget on the home screen.

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.layer_map_appearance %} → {% data variables.android-values.configure_screen_quick_action %} 

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.layer_map_appearance %} → {% data variables.ios-values.configure_screen_quick_action %}

By default, the Quick action button will appear on the right corner (above the Map magnifier). But it can be moved to the other part of the screen with long tap. 

To open Quick action menu click on it.

### Create Quick action list
There are two ways to add items to the Quick actions list: 
- Menu → Configure screen → Quick action → &#8230;&#124; → Add action
- On the map click on the Quick action icon → Add action

![Quick action enable widget](/assets/images/widgets/quick_action_enable_widget.png)
![Quick action edit action](/assets/images/widgets/quick_action_edit_action.png)

In order to remove items from Quick actions widget:
- {% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.layer_map_appearance %} → {% data variables.android-values.configure_screen_quick_action %}. The bin icon on the left will allows to delete the action and the line icon on the right can edit the action.
- {% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.layer_map_appearance %} → {% data variables.ios-values.configure_screen_quick_action %}. The pen icon in the top-right corner will allows you to delete the action. The plus symbol in the top-right corner gives an option to add new actions to the list. Swiping up and down on the three vertical lines in the editing menu will allows you to move action along the list.

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
| {% data variables.ios-values.toggle_fav %} | Allows to display the favourite points on the map |
| {% data variables.ios-values.show_hide_gpx %} | Allows to display selected tracks on the map |
| {% data variables.ios-values.toggle_poi %} | Allows to display selected POI categories on the map |
| {% data variables.ios-values.toggle_public_transport %}| Allows to display public transport on the map |
| {% data variables.ios-values.quick_action_showhide_mapillary_title %} | Display Mapillary layer on the map |
| {% data variables.ios-values.toggle_contour_lines %} | Allows to show or hide contour lines on the map |
| {% data variables.android-values.quick_action_show_hide_title %} {% data variables.android-values.shared_string_terrain %} | Allows to display terrian layer on the map |
| {% data variables.android-values.quick_action_show_hide_title %} {% data variables.android-values.osm_notes %} | Allows to add the comment and display it on the map |
| {% data variables.android-values.quick_action_map_style %} | Allows to add map styles that could be immediately selected |
| {% data variables.ios-values.change_map_source %} | Allows to add map source that could be immediately selected  |
| {% data variables.ios-values.change_map_overlay %} | Allows to add overlay map that could be immediately selected |
| {% data variables.ios-values.change_map_underlay %} | Allows to add underlay map that could be immediately selected |
| **{% data variables.android-values.quick_action_add_navigation %}**  | |
| {% data variables.android-values.quick_action_day_night_switch_mode %} | A toggle between day and night modes |
| {% data variables.android-values.quick_action_navigation_voice %} | A toggle to diable or enable voice guidance during navigation |
| {% data variables.android-values.context_menu_item_directions_from %} | Allows to make the screen center the point of departure|
| {% data variables.android-values.quick_action_add_destination %} | |
| {% data variables.android-values.quick_action_add_first_intermediate %} | Allows to add a first intermediate point at the screen centre location  |
| {% data variables.android-values.quick_action_replace_destination %} | yyyyyyyy |
| {% data variables.android-values.quick_action_remove_next_destination %} | yyyyyyyy |
| {% data variables.android-values.quick_action_auto_zoom %} | yyyyyyyy |
| {% data variables.android-values.quick_action_start_stop_navigation %} | yyyyyyyy |
| {% data variables.android-values.quick_action_resume_pause_navigation %} | yyyyyyyy |
| {% data variables.android-values.change_application_profile %} | yyyyyyyy |
