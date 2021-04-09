---
title: "Marker widgets"
intro: "Map markers are selected points marked as flags on the map. The additional information about them could be displayed as widgets on the map screen."
versions: '*'
---


## Top bar widget (markers)  
![Map markers on the Top bar widget](/assets/images/widgets/map_markers_top_bar_widget.png)
On the top bar widget you could see the distance and the direction to the marker from current location. It is possible to configure to see 1 or 2 markers in the widget.

| | |
|------------|------------|
| Enable | {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.map_markers_item %} → ≡ → {% data variables.android-values.appearance_on_the_map %} → {% data variables.android-values.shared_string_topbar %} |
| On Click | Centers map view to the marker position |
| On Map Hold | In order to measure the distance and view the direction from a specific map point to the map marker, press & hold on the map and slightly change map position (so context menu won't open) |
| Approach marker | In case your location is within a short radius of the map marker (< 50m), you could see a quick button to remove the map marker (mark as passed).  |
| Format distance | {% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %} → {% data variables.android-values.general_settings_2 %} → {% data variables.android-values.units_and_formats %} → {% data variables.android-values.unit_of_length %} |
|        | {% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.sett_settings %} → {% data variables.ios-values.app_profiles %} → {% data variables.ios-values.general_settings_2 %} → {% data variables.ios-values.units_and_formats %} → {% data variables.ios-values.unit_of_length %}  |

## Panel widgets (markers)  

![Panel widgets](/assets/images/widgets/map_markers_widget.png)
On panel widgets only distance to the map marker is displayed.

| | |
|------------|------------|
| Enable | {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.map_markers_item %} → ≡ → {% data variables.android-values.appearance_on_the_map %} → {% data variables.android-values.shared_string_widgets %} |
| On Click | Centers map view to the marker position |
| On Map Hold | In order to measure the distance and view the direction from a specific map point to the map marker, press & hold on the map and slightly change map position (so context menu won't open) |
| Format | {% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %} → {% data variables.android-values.general_settings_2 %} → {% data variables.android-values.units_and_formats %} → {% data variables.android-values.unit_of_length %}  |
|        | {% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.sett_settings %} → {% data variables.ios-values.app_profiles %} → {% data variables.ios-values.general_settings_2 %} → {% data variables.ios-values.units_and_formats %} → {% data variables.ios-values.unit_of_length %}  |

## Configure Marker widgets and Marker appearance

All Markers appearance settings and widget settings are configurable via same menu.

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.map_markers_item %} → ≡ → {% data variables.android-values.appearance_on_the_map %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.map_markers %} → {% data variables.ios-values.appearance_on_map %}

|    | Description    | State |  OS |
| :------------- | :------------- | :------------- | :------------- |
| {% data variables.android-values.active_markers %} | Specifies number of direction indicators| 1 or 2 | Android/iOS  |
|  {% data variables.android-values.show_direction %}  | Gives an option to activate and choose the way of displaying the distance to active markers | {% data variables.android-values.shared_string_topbar %} / {% data variables.android-values.shared_string_widgets %} | Android/iOS  |
|  {% data variables.android-values.show_arrows_on_the_map %} |  Gives an option to activate and show one or two arrows that indicate the direction to the active markers | -  | Android/iOS  |
|  {% data variables.android-values.show_guide_line%} | Gives an option to activate and show direction line from users position  to the active markers  | -  | Android/iOS  |
| {% data variables.android-values.one_tap_active %}  |  Gives an option to activate function to move marker to the top other active markers by tapping a marker. Without opening the context menu |  - | Android  |
| {% data variables.android-values.keep_passed_markers %}  | Gives an option to activate a function that will remain on the map a group of Favorites or FPS waypoints marked as 'Passed'. If the group is not active, the markers will disappear from the map.  | -  | Android  |
