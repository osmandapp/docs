---
title: "{% data variables.android-values.plan_a_route %}"
intro: "Plan future routes and trips"
versions: '*'
---

The 'Plan route' tool is a powerful feature of OsmAnd allows you to measure distances on the map, create GPX tracks or add new segments to your own ones, to snap your track to the nearest available road with one of your navigation profiles. Of course, it works offline and available for Android and iOS versions of OsmAnd.

The route is many strings between points. Strings can be straight lines or routes of chosen navigation profiles. The sum of all these points and strings is a route, that can be saved, imported, or modified. 

| | |
|------------|------------|
| ![icon-android](/assets/images/site/icon-android.png)| ![icon-ios](/assets/images/site/icon-ios.png) |
| ![Plan route android](/assets/images/plan-route/plan-route-android.png) | ![Plan route ios](/assets/images/plan-route/plan-route-ios.png) |

## Where to find 'Plan route'

The 'Plan route' can be switched on:

- Main menu

| | |
|------------|------------|
| {% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.plan_a_route %} | {% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.plan_route %} |
| ![Plan route android_menu](/assets/images/plan-route/plan-route-android-menu.png) | ![Plan route ios_menu](/assets/images/plan-route/plan-route-ios-menu.png) |

- Track context menu (Android)

{% data variables.android-values.shared_string_options %} → {% data variables.android-values.edit_track %}

or to click to {% data variables.android-values.edit_track %} on context menu screen:

![Plan route android_contextmenu](/assets/images/plan-route/plan-route-android-contextmenu.png)

## 'Plan route' menu

In the tool you can create new GPX route or open existing track. When you open 'Plan route' tool menu you find the next buttons:

| | |  |
|------------|------------|------------|
| ![icon-android](/assets/images/site/icon-android.png)| ![icon-ios](/assets/images/site/icon-ios.png) |
| **{% data variables.android-values.plan_route_create_new_route %}** - create new GPX route | **{% data variables.ios-values.plan_route_create_new_route %}** - create new GPX route |
| **{% data variables.android-values.plan_route_open_existing_track %}** - open existing GPX track from OsmAnd track folder. | **{% data variables.ios-values.plan_route_open_existing_track%}** - open existing GPX track from OsmAnd track folder. |
| **{% data variables.android-values.plan_route_import_track %}** - import GPX track from your device storage |  |
| **{% data variables.android-values.plan_route_last_edited %}** - choose GPX track from last modified. | **{% data variables.ios-values.plan_route_last_modified %}** - choose GPX track from last modified. | 
| ![Plan route android_choosemenu](/assets/images/plan-route/plan-route-android-choose-menu.png) | ![Plan route ios_choosemenu](/assets/images/plan-route/plan-route-ios-choosemenu.png) |

## 'Plan route' main screen


| | |
|------------|------------|
| ![icon-android](/assets/images/site/icon-android.png)| ![icon-ios](/assets/images/site/icon-ios.png) |
| ![Plan route android-screen](/assets/images/plan-route/plan-route-android-screen.png) | ![Plan route ios-screen](/assets/images/plan-route/plan-route-ios-screen.png) |

**1.** {% data variables.android-values.shared_string_options %} menu.

**2.** {% data variables.android-values.shared_string_add %} shaping points.

**3.** back/forward - move along planning process steps.

**4.** Points list and Graph (Android) list with distance, azimuth (for next point), points number.

**5.** Profile button for choosing [application profile](/osmand/start-with/profiles).

**6.** Done button - finish and save GPX route.

**7.** Name of GPX route by default (Android).

**8.** Close button - exit from the tool with save or note GPX route.

**9.** Widgets (Android) - [Configure map
](/osmand/widgets/map-buttons#configure-map), [Search](/osmand/widgets/map-buttons#search), [Compass](/osmand/widgets/map-buttons#compass).

**10.** Widgets (Android) - {Informational widgets
](/osmand/widgets/info-widgets), [Navigational widgets
](/osmand/widgets/nav-widgets).

**11.** Widgets - [My Location & Zoom](/osmand/widgets/map-buttons#my-location--zoom).

## Route line, Points list and graph

| | |
|------------|------------|
| ![icon-android](/assets/images/site/icon-android.png)| ![icon-ios](/assets/images/site/icon-ios.png) |
| ![Plan route android-routeline](/assets/images/plan-route/plan-route-routeline-android.png) | ![Plan route ios-screen](/assets/images/plan-route/plan-route-routeline-ios.png) |

**1.** Profile icon (Android).

**2.** Shaping point - basic point building the route.

**3.** Calculated route segment between shaping points. Colors of your choosed application profiles (Android) or last choosed (iOS).

**4.** Straight line and target point.

### Drawing a route

Start drawing a route:

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.plan_a_route %} → {% data variables.android-values.plan_route_create_new_route %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.plan_route %} → {% data variables.ios-values.plan_route_create_new_route%}

Choose how to draw:
- By default **straight line** - only plain line stretches between shaping points:

![Plan route straight_line](/assets/images/plan-route/plan-route-straight-line.png)

Straight line is useful for simple distance measurement, azimuth info or for areas not covered by routing data (off-road and off-path areas).

- Click to the profile button for choosing application profile. The route will be calculated between points by routing of your profile.

![Plan route app_button](/assets/images/plan-route/plan-route-app-button.png)

For ![icon-android](/assets/images/site/icon-android.png) we can modify routing parameters for choosed app profile by clicking to settings icon ![icon-settings](/assets/images/plan-route/icon-settings.png) on the profile button:

![app-settings](/assets/images/plan-route/plan-route-app-set.png)

- Choose two or more application profiles for creating the route. Click to the application button:

 ![Plan route app_choosing](/assets/images/plan-route/plan-route-app-choosing.png) 

Choose how to connect the points, by a straight line, or calculate a route between them as specified:

{% data variables.android-values.whole_track %} - {% data variables.android-values.route_between_points_whole_track_button_desc %}

{% data variables.android-values.next_segment %} - {% data variables.android-values.route_between_points_next_segment_button_desc %}

 - When you use two or more application profiles for your route:

| | |
|------------|------------|
| ![icon-android](/assets/images/site/icon-android.png)| ![icon-ios](/assets/images/site/icon-ios.png) |
| ![Plan route android-screen](/assets/images/plan-route/plan-route-segments-android.png) | ![Plan route ios-screen](/assets/images/plan-route/plan-route-segments-ios.png) |

- Click to Done button for save your route like GPX file.


### Modify existing GPX track



## Useful links

{% link_with_intro /create-route %}
{% link_with_intro /travel-guides %}

