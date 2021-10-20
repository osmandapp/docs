---
title: "{% data variables.android-values.plan_a_route %}"
intro: "Plan future routes and trips"
versions: '*'
---
{% data reusables.general.article-not-complete %}
The **'Plan route'** tool is a powerful feature of OsmAnd allows you to measure distances on the map, create GPX tracks or add new segments to your own ones, to snap your track to the nearest available road with one of your navigation profiles. Of course, it works offline and available for Android and iOS versions of OsmAnd.

The route is many strings between points. Strings can be straight lines or routes of chosen navigation profiles. The sum of all these points and strings is a route, that can be saved, imported, or modified. 


![Plan route android](/assets/images/plan-route/plan-route-android.png)  ![Plan route ios](/assets/images/plan-route/plan-route-ios.png)

## Opening 'Plan route'

The 'Plan route' can be switched on:

- Main menu


{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.plan_a_route %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.plan_route %} 

![Plan route android_menu](/assets/images/plan-route/plan-route-android-menu.png)  ![Plan route ios_menu](/assets/images/plan-route/plan-route-ios-menu.png) 

- Track context menu (Android)

{% data variables.android-values.shared_string_options %} → {% data variables.android-values.edit_track %}

or to click to {% data variables.android-values.edit_track %} on the context menu screen:

![Plan route android_contextmenu](/assets/images/plan-route/plan-route-android-contextmenu.png)

## 'Plan route' 

### Main menu

In the tool, you can create a new GPX route or open and modify the existing track. When you open 'Plan route' tool menu you find the next buttons:
- **{% data variables.android-values.plan_route_create_new_route %}** - create a new GPX route.
- **{% data variables.android-values.plan_route_open_existing_track %}** - open existing GPX track from OsmAnd track folder.
- **{% data variables.android-values.plan_route_import_track %}** - import GPX track from your device storage (Android).
- **{% data variables.android-values.plan_route_last_edited %}** - choose GPX track from last modified.

![Plan route android_choosemenu](/assets/images/plan-route/plan-route-android-choose-menu.png) ![Plan route ios_choosemenu](/assets/images/plan-route/plan-route-ios-choosemenu.png) 

### Main screen

At the main screen of the tool there are the next elements:

![Plan route android-screen](/assets/images/plan-route/plan-route-android-screen.png)  ![Plan route ios-screen](/assets/images/plan-route/plan-route-ios-screen.png) 

**1.** ['{% data variables.android-values.shared_string_options %}'](/osmand/plan-route/create-route#options-menu) menu.

**2.** '{% data variables.android-values.shared_string_add %}' button for shaping points.

**3.** Back/forward - move along planning process steps.

**4.** [Points list and Graph (Android) list](/osmand/plan-route/create-route#points-list-and-graph).

**5.** 'Profile' button for choosing [application profile](/osmand/personal/profiles).

**6.** 'Done' button - finish and save GPX route.

**7.** Name of GPX route by default (Android).

**8.** 'Close' button - exit from the tool with saving GPX route or no saving.

**9.** Widgets (Android) - [Configure map
](/osmand/widgets/map-buttons#configure-map), [Search](/osmand/widgets/map-buttons#search), [Compass](/osmand/widgets/map-buttons#compass).

**10.** Widgets (Android) - [Informational widgets
](/osmand/widgets/info-widgets), [Navigational widgets
](/osmand/widgets/nav-widgets).

**11.** Widgets - [My Location & Zoom](/osmand/widgets/map-buttons#my-location--zoom).

### Route line

The Route line shows an [automatically-generated road or straight route](/osmand/plan-route/create-route#creating-a-route) which you can save like a GPX track.


![Plan route android-routeline](/assets/images/plan-route/plan-route-routeline-android.png) ![Plan route ios-screen](/assets/images/plan-route/plan-route-routeline-ios.png)

**1.** Profile icon (Android). It's mean that this segment was built by this profile routing.

**2.** Shaping points - basic points building the route.

**3.** Calculated route segment between shaping points. Colors of your chosen application profiles (Android) or last chosen application profile (iOS).

**4.** Straight-line from last shaping point and target point.

### 'Points' list and Graph

For opening 'Points' list and Graph:


**1.Click to ['Points' list](/osmand/plan-route/create-route#main-screen).** (Android)

**1.Click to the open icon &#710 on ['Points' list](/osmand/plan-route/create-route#main-screen).** (iOS)

![Plan route android-pointslist](/assets/images/plan-route/plan-route-pointslist-android.png)  ![Plan route ios-pointslist](/assets/images/plan-route/plan-route-pointslist-ios.png) 

Description:  Each point has information about distance and azimuth for a new making route, and additional altitude, and the speed information for recorded GPX track. In ['Points' list](/osmand/plan-route/create-route#main-screen) we can delete points (click to 'Delete' button near chosen point) or change the order of it (move a line of chosen point to up or below). Clicking to a point opens ['Point' menu](/osmand/plan-route/create-route#actions-of-point-menu). 

**2.Click to "Graph" button.** (Android)

![Plan route android-graph](/assets/images/plan-route/plan-route-graph-android.png)

Description: [Click to graph](/osmand/plan-route/create-route#actions-of-points-list-and-graph) shows information about point and its location on the route. View of the graph of a route with Overview, Altitude, Slope, Road type, Surface, Steepness.

## Creating a route

[Start creating a route](/osmand/plan-route/create-route#main-menu):

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.plan_a_route %} → {% data variables.android-values.plan_route_create_new_route %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.plan_route %} → {% data variables.ios-values.plan_route_create_new_route%}

### Drawing a line

Choose how to draw:
- By default **straight line** - only plain line stretches between shaping points:

![Plan route straight_line](/assets/images/plan-route/plan-route-straight-line.png)

The straight line is useful for simple distance measurement, azimuth info or for areas not covered by routing data (off-road and off-path areas).

- Click to 'Add' button for adding shaping points or just click on the screen.

**Note**: Overview data available only on roads, calculate a route using ["Route between points”](/osmand/plan-route/create-route#drawing-a-route) to see graphs.

### Drawing a route

- Click on ['Profile' button](/osmand/plan-route/create-route#main-screen) for choosing an application profile. The route will be calculated between points by routing of your profile.
- Click to ['Add' button](/osmand/plan-route/create-route#main-screen) for adding shaping points or just click on the screen.

![Plan route app_button](/assets/images/plan-route/plan-route-app-button.png)

For Android we can modify routing parameters for chosen app profile by clicking to settings icon ![icon-settings](/assets/images/plan-route/icon-settings.png) on ['Profile' button](/osmand/plan-route/create-route#main-screen):

![app-settings](/assets/images/plan-route/plan-route-app-set.png)

- Choose two or more application profiles for creating a route. Click to ['Profile' button](/osmand/plan-route/create-route#main-screen):

 ![Plan route app_choosing](/assets/images/plan-route/plan-route-app-choosing.png) 

Choose how to connect the points, by a straight line, or calculate a route between them as specified:

{% data variables.android-values.whole_track %} - {% data variables.android-values.route_between_points_whole_track_button_desc %}

{% data variables.android-values.next_segment %} - {% data variables.android-values.route_between_points_next_segment_button_desc %}

 - When you use two or more application profiles for your route:

for Android each segment has [a profile icon and color](/osmand/plan-route/create-route#route-line) of the application profile which using for calculated route between shaping points;

for iOS all segments have [color of last using application profile](/osmand/plan-route/create-route#route-line) for calculated route.

### Actions of 'Point' menu

Actions in 'Point' menu (by clicking to a point in ['Points' list](/osmand/plan-route/create-route#points-list-and-graph)):

| | |
|------------|------------|
| **1.Click to a point from 'Points' list**: | Open 'Point' menu| 
|**Actions in 'Point' menu:** |   |
|1. Point info | Showed Number of point, Distance, Speed, Altitude of point. |
|2. {% data variables.ios-values.move_point %}|  {% data variables.ios-values.move_point_descr %} |
|3. {% data variables.ios-values.add_after %}| Move map to add points after a chosen point.  |
|4. {% data variables.ios-values.add_before %}|  Move map to add points before a chosen point.  |
|5. {% data variables.ios-values.trim_before %}| The trim route before a chosen point.  |
|6. {% data variables.ios-values.trim_after %}| The trim route after a chosen point. |
| 7. {% data variables.ios-values.split_before %}|  Split route before a chosen point.   |
|8. {% data variables.ios-values.split_after %}| Split route after a chosen point. |
| 9. {% data variables.ios-values.change_route_type_before %}| Change route type (application profile) before a chosen point. |
|10. {% data variables.ios-values.change_route_type_after %}| Change route type (application profile) after a chosen point.  |
|11. {% data variables.ios-values.delete_point %}| Delete chosen point from the route.  |

### Saving a route

Click to ['Done' button](/osmand/plan-route/create-route#main-screen) to save your route like the GPX file.

![Plan route android-save](/assets/images/plan-route/plan-route-animation.gif)

Find your track in 'My Places' menu:

{% data variables.android-values.shared_string_menu %} → {% data variables.android-values.shared_string_my_places %} → {% data variables.android-values.show_gpx %}



## 'Options' menu

In 'Options' menu you can make the next actions with your route:

![Plan route android-options](/assets/images/plan-route/plan-route-options-android.png) ![Plan route ios-options](/assets/images/plan-route/plan-route-options-ios.png)

| | |
|------------|------------|
|Action|Description|
| 1. {% data variables.android-values.route_between_points %} | Showing chosen application profile (The straight line by default). Click to this action is equal ['Profile' button](/osmand/plan-route/create-route#main-screen)  with opening [application profile menu](/osmand/plan-route/create-route#drawing-a-route). |
| 2. {% data variables.android-values.plan_route_add_new_segment %} or {% data variables.ios-values.track_new_segment %} | Drawing new segments of the route which not connect with the previous segment. |
| 3. {% data variables.android-values.shared_string_save_changes %} | Save your route like GPX track and continue to create the next segment. |
| 4. {% data variables.android-values.save_as_new_track %} | Save your route like GPX track.|
| 5. {% data variables.android-values.add_to_a_track %} | Add your route to a track from your track folder and save the new track. |
| 6. {% data variables.android-values.get_directions %} |Start navigation from your position to the finish point using a drawn route.|
| 7. {% data variables.android-values.reverse_route %} | Change the direction of a drawn route. |
| 8. {% data variables.android-values.shared_string_clear_all %} | Clear all shaping points.  |


## Modify existing GPX track

### Modify GPX track

'Plan route' tool allows modifying existing GPX track. You can make any actions with your tracks.

[Open any GPX track](/osmand/plan-route/create-route#modify-gpx-track) for modifying it:

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.plan_a_route %} → {% data variables.android-values.plan_route_open_existing_track %} or {% data variables.android-values.plan_route_import_track %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.plan_route %} → {% data variables.ios-values.plan_route_open_existing_track %}

In ['Points' list](/osmand/plan-route/create-route#points-list-and-graph), there is information about the number  of points and a track distance.


![Plan route modify-track-android](/assets/images/plan-route/plan-route-modify-track-android.png) ![Plan route modify-track-ios](/assets/images/plan-route/plan-route-modify-track-ios.png)

You can make all actions with points in ['Points' list](/osmand/plan-route/create-route#points-list-and-graph) and ['Point' menu](/osmand/plan-route/create-route#actions-of-point-menu): delete, change order, move and etc.

For [Graph (Android)](/osmand/plan-route/create-route#points-list-and-graph) you can see the actual information for a GPX track: Altitude, Slope, Speed.

In ['Options' menu](/osmand/plan-route/create-route#options-menu) is available all actions for GPX track too: add a new segment, reverse route, directions, etc.


### Snap to roads

For example, you have recorded tracks. 'Plan route' tool allows snapping your track to the nearest allowed road with one of your application profiles.

For using this option you need to open your track by 'Plan route' tool:

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.plan_a_route %} → {% data variables.android-values.plan_route_open_existing_track %} or {% data variables.android-values.plan_route_import_track %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.plan_route %} → {% data variables.ios-values.plan_route_open_existing_track %}

Next, choose the needed application profile for snapping your track to the nearest road. For this, you need to click ['Profile' button](/osmand/plan-route/create-route#main-screen) or choose in ['Options' menu](/osmand/plan-route/create-route#options-menu) → {% data variables.android-values.route_between_points %}. For Android, you can set {% data variables.android-values.threshold_distance %} parameter.

After calculating the new route you click ['Done' button](/osmand/plan-route/create-route#main-screen) for saving the new GPX track which snapping to roads.


![Plan route snap-road-android](/assets/images/plan-route/plan-route-snap-android.gif) ![Plan route snap-road-ios](/assets/images/plan-route/plan-route-snap-ios.gif)

## Useful links

{% link_with_intro /travel-guides %}

