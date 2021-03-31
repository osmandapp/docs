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
|  {% data variables.android-values.quick_action_add_osm_bug %}  |  Android |   |   |
|   {% data variables.android-values.quick_action_showhide_favorites_descr %}  | -   | Android/iOS   | -   |


**Item actions**:  

![Quick action create items](/assets/images/widgets/quick_action_create_items.png)
<!--Add Favorite, Add track way points, Add map markers, Add parking place (for Android).-->

**'Configure map' actions**:  

![Quick action configure map](/assets/images/widgets/quick_action_configure_map.png)
<!--Show/hide Favorites, Show/hide tracks, Show/hide POI, Change map style, Show/Hide public transport, Show/hide Mapillary, Show/hide contour lines, Show/hide terrain, Switch day/night mode (for iOS), Change map source (for iOS), Change map overlay (for iOS),Change map underlay (for iOS).-->

**Navigation actions**:

![Quick action navigation actions](/assets/images/widgets/quick_action_navigation_actions.png)
<!--Switch day/night mode (for Android), Voice on/off, Directions from, Set destination, Add first intermediate, Replace destination, Auto zoom map on/off, Start/Stop navigation, Pause/resume navigation, Change app profile, Delete nearest destination point, Add destination (for iOS).-->

| | |
|------------|------------|
| Enable | {% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.layer_map_appearance %} → {% data variables.android-values.configure_screen_quick_action %} |
|   | {% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.layer_map_appearance %} → {% data variables.ios-values.configure_screen_quick_action %} |
| Remove actions |  {% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.layer_map_appearance %} → {% data variables.android-values.configure_screen_quick_action %}. The bin icon on the left will delete the action and the line icon on the right can edit the action.     |
|   | {% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.layer_map_appearance %} → {% data variables.ios-values.configure_screen_quick_action %}. The pen icon in the top-right corner will give the user an opportunity to delete the action. The plus symbol in the top-right corner gives an option to add new actions to the list.  |
| Click |  Open Quick action menu.   |
| Note   | The Quick action widget can be moved to the other part of the screen with long tap. By default, it is on the left bottom corner. |
