---
title: "Coordinate input"
intro: "A simple and fast tool for creating points by specifying geographic coordinates."
versions: '*'
---

{% data reusables.general.article-not-complete %}

If you have coordinates of your places you can create this points by just coordinates input in OsmAnd.

## Actions

{% android %}

Points are set as waypoints in [My places menu](/osmand/personal/tracks). For starting creation of Points by coordinate input:

[{% data variables.android-values.shared_string_menu %}](/osmand/start-with/main-menu) → [{% data variables.android-values.shared_string_my_places %}](/osmand/personal/myplaces) → [{% data variables.android-values.shared_string_gpx_tracks%}](/osmand/personal/tracks) → ["earth" button](/osmand/personal/tracks#my-places) on the bottom of the screen.

This action opens "{% data variables.android-values.coord_input_edit_point %}" menu. 

![Coordinate input Actions Android](/assets/images/personal/tracks/coordinate_input_android.png) 

This screen contains a template for adding a point by coordinates:
- ["{% data variables.android-values.shared_string_options %}" menu](/osmand/plan-route/coordinate-input#options) - opening the menu of options and choosing of coordinate format.
- {% data variables.android-values.navigate_point_latitude %} and {% data variables.android-values.navigate_point_longitude %} line - allows to input latitude and longitude in the selected format (D - degrees, M - minutes, S - seconds). You can change coordinates format in ["{% data variables.android-values.shared_string_options %}" menu](/osmand/plan-route/coordinate-input#options).
- {% data variables.android-values.navigate_point_latitude %} and {% data variables.android-values.navigate_point_longitude %} buttons - allows to change "South <-> North" and "West <-> East" for coordinates input.
- "Point name" line - allows adding a point name or use a name by default.
- "Clearing" ("X") buttons - allow to reset data for inputting coordinates.

![Coordinate input menu Android](/assets/images/personal/tracks/coordinate_input_menu_android.png) ![Coordinate input menu Android](/assets/images/personal/tracks/coordinate_input_menu_1_android.png)

- Points list - shows added points: name, distance and direction to this point. "&#8285;" button opens the action menu for Editing or Deleting chosen point. Tapping to a point opens the editing action of this point.

![Coordinate input point list Android](/assets/images/personal/tracks/coordinate_input_point_list_android.png)

- "{% data variables.android-values.shared_string_add %}" button - allows adding a new point after input of coordinates.
- "{% data variables.android-values.shared_string_cancel %}" button - reset all adding data.

![Coordinate input Add point Android](/assets/images/personal/tracks/coordinate_input_add_point_android.png) 

- "&#8592;" button - allows to open the action "{% data variables.android-values.coord_input_save_as_track %}" for your adding points. Here you can input a track name or stay name by default. Click to "{% data variables.android-values.shared_string_save %}" button for saving added points like a new track. You find saving track in [My places menu](/osmand/personal/myplaces): {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.shared_string_my_places %} → {% data variables.android-values.shared_string_gpx_tracks%} → "{% data variables.android-values.map_markers_item %}" folder. The action "{% data variables.android-values.coord_input_save_as_track %}" is in [Options menu](/osmand/plan-route/coordinate-input#options) too.

![Coordinate input Add point Android](/assets/images/personal/tracks/coordinate_input_save_track_android.png) ![Coordinate input Add point Android](/assets/images/personal/tracks/coordinate_input_save_track_1_android.png)

{% endandroid %}

## Options

{% android %}

Tapping to "{% data variables.android-values.shared_string_options %}" button opens {% data variables.android-values.shared_string_options %} menu with next actions

![Coordinate input Options menu Android](/assets/images/personal/tracks/coordinate_input_options_menu_android.png)

- {% data variables.android-values.coord_input_save_as_track %} - allows to open "{% data variables.android-values.coord_input_save_as_track %}" action for your adding points. Here you can input a track name or stay name by default. Click to "{% data variables.android-values.shared_string_save %}" button for saving added points like a new track. You find saving track in [My places menu](/osmand/personal/myplaces): {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.shared_string_my_places %} → {% data variables.android-values.shared_string_gpx_tracks%} → "{% data variables.android-values.map_markers_item %}" folder. The action "{% data variables.android-values.coord_input_save_as_track %}" button is in [Actions](/osmand/plan-route/coordinate-input#actions) too.
- {% data variables.android-values.use_system_keyboard %} - allows to use system keyboard for input coordinate.
- {% data variables.android-values.use_two_digits_longitude %} - allows to use double digit longitude.
- {% data variables.android-values.coordinates_format %} - allows changing the coordinate format for inputting.

|Coordinates format|
|:------|
|{% data variables.android-values.dd_mm_mmm_format %} |
|{% data variables.android-values.dd_mm_mmmm_format %} |
|{% data variables.android-values.dd_ddddd_format %} |
|{% data variables.android-values.dd_dddddd_format %} |
|{% data variables.android-values.dd_mm_ss_format %} |

{% endandroid %}