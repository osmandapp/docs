---
title: "Marker widgets"
intro: "Map markers are used to display selected points on the map along the trip. The information can be viewed via using the top bar on the map screen or the widget."
versions: '*'
---
## Map markers on the Top bar widget  

![Map markers on the Top bar widget  ](/assets/images/widgets/map_markers_top_bar_widget.png)

Shows direction and distance from users current position to the marker and the location name.

| | |
|------------|------------|
| Enable | {% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.map_markers_item %} → ≡ → {% data variables.android-values.appearance_on_the_map %} → {% data variables.android-values.shared_string_topbar %} |
|  | {% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.map_markers %} → {% data variables.ios-values.appearance_on_map %} → {% data variables.ios-values.shared_string_topbar %} |
| Click | {% data variables.product.android_button_seq %} Moves focus to the marker. Redirects to 'Map markers' menu where the and user can sort markers from the list, group them, view the history and configure markers settings.|
|   | {% data variables.product.ios_button_seq %} Moves focus to the marker. Opens description menu where user can configure markers settings.   |
| Format | {% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %} → {% data variables.android-values.general_settings_2 %} → {% data variables.android-values.units_and_formats %} → {% data variables.android-values.unit_of_length %} |
|        | {% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.sett_settings %} → {% data variables.ios-values.app_profiles %} → {% data variables.ios-values.general_settings_2 %} → {% data variables.ios-values.units_and_formats %} → {% data variables.ios-values.unit_of_length %}  |

## Map markers widget  

![Map markers widget ](/assets/images/widgets/map_markers_widget.png)

Shows the distance from users current position to the marker.

| | |
|------------|------------|
| Enable | {% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.map_markers_item %} → ≡ → {% data variables.android-values.appearance_on_the_map %} → {% data variables.android-values.shared_string_widgets %} |
|  | {% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.map_markers %} → {% data variables.ios-values.appearance_on_map %} → {% data variables.ios-values.shared_string_widgets%} |
| Click | {% data variables.product.android_button_seq %} Moves focus to the marker.  |
|   |  {% data variables.product.ios_button_seq %} Moves focus to the marker. Opens description menu where user can configure markers settings.  |
| Format | {% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %} → {% data variables.android-values.general_settings_2 %} → {% data variables.android-values.units_and_formats %} → {% data variables.android-values.unit_of_length %}  |
|        | {% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.sett_settings %} → {% data variables.ios-values.app_profiles %} → {% data variables.ios-values.general_settings_2 %} → {% data variables.ios-values.units_and_formats %} → {% data variables.ios-values.unit_of_length %}  |

## Configurations of appearance on the map for Map markers

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.map_markers_item %} → ≡ → {% data variables.android-values.appearance_on_the_map %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.map_markers %} → {% data variables.ios-values.appearance_on_map %}

|    | Description    | State |  OS |
| :------------- | :------------- | :------------- | :------------- |
| {% data variables.android-values.active_markers %} | Specifies number of direction indicators| 1 - ∞ | Android/iOS  |
|  {% data variables.android-values.show_direction %}  | Gives an option to activate and choose the way of displaying the distance to active markers | {% data variables.android-values.shared_string_topbar %}/ {% data variables.android-values.shared_string_widgets %} | Android/iOS  |
|  {% data variables.android-values.show_arrows_on_the_map %} |  Gives an option to activate and show one or two arrows that indicate the direction to the active markers | -  | Android/iOS  |
|  {% data variables.android-values.show_guide_line%} | Gives an option to activate and show direction line from users position  to the active markers  | -  | Android/iOS  |
| {% data variables.android-values.one_tap_active %}  |  Gives an option to activate function to move marker to the top other active markers by tapping a marker. Without opening the context menu |  - | Android  |
| {% data variables.android-values.keep_passed_markers %}  | Gives an option to activate a function that will remain on the map a group of Favorites or FPS waypoints marked as 'Passed'. If the group is not active, the markers will disappear from the map.  | -  | Android  |
