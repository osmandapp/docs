---
title: "Quick action"
intro: "Quick action button gives access to the  frequently used features."
versions: '*'
---

## Quick action widget

![Quick action widget](/assets/images/widgets/quick_action_widget.png)

Gives an opportunity to add action that will be frequently used. It can be:

|    | {% data variables.android-values.quick_action_add_create_items %}   | {% data variables.android-values.quick_action_add_configure_map %} | {% data variables.android-values.quick_action_add_navigation %}  |
| :------------- | :------------- | :------------- | :------------- |
| {% data variables.android-values.quick_action_add_favorite %} | Android/iOS | - | - |
|  {% data variables.android-values.quick_action_add_gpx %}  | Android | - | - |
|  {% data variables.ios-values.add_gpx_waypoint %} | iOS | - | - |
| {% data variables.android-values.quick_action_add_marker %} | Android/iOS | - | - |
| {% data variables.android-values.quick_action_add_parking %} | Android | - | - |
|  {% data variables.android-values.quick_action_add_poi %} | Android  | -  | -  |
|  {% data variables.android-values.quick_action_add_osm_bug %}  |  Android | -  | -  |
|   {% data variables.ios-values.toggle_fav %} | -   | Android/iOS   | -   |
|  {% data variables.ios-values.show_hide_gpx %}  | -  | Android/iOS   |  - |
| {% data variables.ios-values.toggle_poi %}    |  - |  Android/iOS  | -  |
| {% data variables.android-values.quick_action_map_style %}    | -  |  Android/iOS  | -  |
| {% data variables.ios-values.toggle_public_transport %}    |-   | Android/iOS   | -  |
| {% data variables.ios-values.quick_action_showhide_mapillary_title %}    | -  | Android/iOS   | -  |   
|{% data variables.android-values.quick_action_show_hide_title %} {% data variables.android-values.coordinates_widget %}   | -  |  Android | -  |   
|  {% data variables.android-values.quick_action_show_hide_title %} % data variables.android-values.shared_string_terrain %} | -  | Android  | -  |  
| {% data variables.android-values.quick_action_show_hide_title %} {% data variables.android-values.osm_notes %}    | -  | Android  | -  |  
|  {% data variables.ios-values.change_map_source %}   | -  | iOS  |  - |  
| {% data variables.ios-values.change_map_overlay %}   | -  | iOS  | -  |   
|  {% data variables.ios-values.change_map_underlay %}  |  - |  iOS | -  |  
| {% data variables.ios-values.day_mode %}   | -  | iOS  |-   |   
|  {% data variables.ios-values.toggle_contour_lines %} |  - |  iOS |  - |   
|  {% data variables.ios-values.toggle_hillshade %}  | -  | iOS  | -  |  
|  {% data variables.android-values.quick_action_day_night_switch_mode %}    | -  |  - | Android   |  
|  {% data variables.android-values.quick_action_navigation_voice %}  |  - | -  | Android/iOS   |   
| {% data variables.android-values.context_menu_item_directions_from %}   | -  |  - | Android/iOS    |
| {% data variables.android-values.quick_action_add_destination %}  |  - |  - |  Android |   
|{% data variables.ios-values.add_destination%}    |  - |  - | iOS  |   
|  {% data variables.android-values.quick_action_remove_next_destination %}  | -  |  - | Android/iOS  |   
|  {% data variables.android-values.quick_action_add_first_intermediate %}  | -  |-   | Android/iOS  |  
|  {% data variables.android-values.quick_action_replace_destination %}  | -  | -  | Android/iOS  |
|{% data variables.android-values.quick_action_auto_zoom %}    | -  | -  |  Android/iOS |  
|{% data variables.android-values.quick_action_start_stop_navigation %}   | -  | -  | Android/iOS  |   
|{% data variables.android-values.quick_action_resume_pause_navigation %}   |  - | -  |  Android/iOS |   
|  {% data variables.android-values.change_application_profile %} | -  |  - |  Android/iOS  |  

<!--**Item actions**:  

![Quick action create items](/assets/images/widgets/quick_action_create_items.png)
Add Favorite, Add track way points, Add map markers, Add parking place (for Android).-->

<!--**'Configure map' actions**:  

![Quick action configure map](/assets/images/widgets/quick_action_configure_map.png)
Show/hide Favorites, Show/hide tracks, Show/hide POI, Change map style, Show/Hide public transport, Show/hide Mapillary, Show/hide contour lines, Show/hide terrain, Switch day/night mode (for iOS), Change map source (for iOS), Change map overlay (for iOS),Change map underlay (for iOS).-->

<!--**Navigation actions**:

![Quick action navigation actions](/assets/images/widgets/quick_action_navigation_actions.png)
Switch day/night mode (for Android), Voice on/off, Directions from, Set destination, Add first intermediate, Replace destination, Auto zoom map on/off, Start/Stop navigation, Pause/resume navigation, Change app profile, Delete nearest destination point, Add destination (for iOS).-->

![Quick action edit action](/assets/images/widgets/quick_action_edit_action.png)

| | |
|------------|------------|
| Enable | {% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.layer_map_appearance %} → {% data variables.android-values.configure_screen_quick_action %} |
|   | {% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.layer_map_appearance %} → {% data variables.ios-values.configure_screen_quick_action %} |
| Remove actions |  {% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.layer_map_appearance %} → {% data variables.android-values.configure_screen_quick_action %}. The bin icon on the left will delete the action and the line icon on the right can edit the action.     |
|   | {% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.layer_map_appearance %} → {% data variables.ios-values.configure_screen_quick_action %}. The pen icon in the top-right corner will give the user an opportunity to delete the action. The plus symbol in the top-right corner gives an option to add new actions to the list. Swiping up and down on the three vertical lines in the editing menu will give you an opportunity to move action along the list. |
| Click |  Open Quick action menu.   |
| Note   | The Quick action widget can be moved to the other part of the screen with long tap. By default, it is on the left bottom corner. |
