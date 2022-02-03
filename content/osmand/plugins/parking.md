---
title: "{% data variables.android-values.osmand_parking_plugin_name %}"
intro: "Setting a point on the map of where your car is left in the street, and a calendar notice of when the parking time started to count down, will comfort your efforts in keeping track of the time and the car location."
versions: '*'
---
{% data reusables.general.article-not-complete %}

## Overview 

A Parking point on the map and a notice in the calendar are provided by the Parking plugin. It is free, and works well with the downloaded OsmAnd Maps and Navigation. A Parking point will help you remember the exact location of where the car is left as well as to stay aware of how far it is already from your parking spot, and if needed, to return on time, avoid additional unnecessary costs, share the location with your loved ones. It is easy to set a Parking point, with or without time-tracking, and to remove it after successful use. 

![Parking overdue in Android](/assets/images/plugins/parking/and_parking_overdue.png) ![Heading to Parking point in iOS](/assets/images/plugins/parking/ios_going_to_parking.png)

&nbsp;&nbsp;&nbsp;&nbsp;

## Setup

For using a Parking point on the map, the following setup is required:

1. Enable the plugin.

2. Make certain the Parking widget is added to the screen. 


### Enable plugin

{% data reusables.general.android-ios-switcher %}

{% default %}

The [Parking widget](/osmand/widgets/info-widgets#-parking-widget) becomes available with the Parking plugin enabled. In the list of the plugins, find the Parking one and enable it. 

![Parking plugin in Android](/assets/images/plugins/parking/parking_plugin_android.png) ![Parking plugin in iOS](/assets/images/plugins/parking/parking_plugin_ios.png)

{% enddefault %}

{% ios%}

In the **iOS** version, to enable the Parking plugin, open the list of plugins, find the Parking one, check it and confirm with the **Ok** button in the next dialog. 

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.plugins %} → {% data variables.ios-values.product_title_parking %}

![Plugin confirmation in iOS](/assets/images/plugins/parking/ios_add_parking_plugin.png)

{% endios%}

{% android%}

In the **Android** version, to enable the Parking plugin, tap the triple dots at the right side of the {% data variables.android-values.osmand_parking_plugin_name %} option, then tap **Enable**, and confirm with the **OK** button in the next dialog.

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.plugins_menu_group %} → {% data variables.android-values.osmand_parking_plugin_name %}

![Plugin confirmation in Android](/assets/images/plugins/parking/and_add_parking_plugin.png)

{% endandroid%}


&nbsp;&nbsp;&nbsp;&nbsp;

### Add Parking widget

{% data reusables.general.android-ios-switcher %}

{% default %}

The [Parking widget](/osmand/widgets/info-widgets#-parking-widget) is added automatically to the screen once the Parking plugin is enabled. However, before setting a Parking point, make certain you have the plugin on the screen, and if not, add it by enabling the respective option in the [Configure Screen](/osmand/widgets/configure-screen) menu. The Parking widget will help you quickly reach out to the Parking point on the map. 

![Adding Parking widget in iOS](/assets/images/plugins/parking/ios_adding_parking_widget.png) ![Adding Parking widget in Android](/assets/images/plugins/parking/and_adding_parking_widget.png)

{% enddefault %}

{% ios%}

In the **iOS** version, toggle on the {% data variables.ios-values.product_title_parking %} widget in: 

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.layer_map_appearance %} → {% data variables.ios-values.product_title_parking %}

![Adding Parking widget in iOS](/assets/images/plugins/parking/ios_adding_parking_widget.png)

{% endios%}

{% android%}

In the **Android** version, toggle on the {% data variables.android-values.map_widget_parking %} widget in: 

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.layer_map_appearance %} → {% data variables.android-values.map_widget_parking %}

![Adding Parking widget in Android](/assets/images/plugins/parking/and_adding_parking_widget.png)

{% endandroid%}


&nbsp;&nbsp;&nbsp;&nbsp;

## Parking point on the map

A Parking point on the map stores the latitude and longitude to show where your car was left. It is used as follows:

1. Set a point.
2. Stay informed.
3. Navigate to the point, if needed. 
4. Remove it, once done. 


###  Set a Parking point

{% data reusables.general.android-ios-switcher %}

{% default %}

To set a Parking point on the map, zoom in to the required level, then long-tap a spot on the map, and in the opened [Context menu](/osmand/map/map-context-menu), do the following: 

1. Tap [**Actions**](/osmand/map/map-context-menu#-add--delete-parking-point).
2. Tap **Parking**.
3. If needed, set time, and add a reminder to the Calendar app. 
4. **Save** the point. 

![Set Parking point in iOS](/assets/images/plugins/parking/ios_set_p_point3_.png) ![Set Parking point in Android](/assets/images/plugins/parking/and_set_p_point_limit.png) 

{% enddefault %}

{% ios%}

In the **iOS** version, to set a Parking point, long-tap a spot on the map and in the opened [Context menu](/osmand/map/map-context-menu), do the following:

1. Tap **{% data variables.ios-values.actions %}**.
2. Tap **{% data variables.ios-values.add_parking_short %}**.
3. Consider time limits in the opened {% data variables.ios-values.parking_marker %} dialog. If a time limit is needed, enable the **{% data variables.ios-values.time_limited %}** option, and establish the following:

    - time when to end parking;
    - reminder for the Calendar app.

4. Tap **Save** to close the context menu and save the point. 

![Select Parking in Actions in iOS](/assets/images/plugins/parking/ios_set_p_point2.png)  ![Set Parking point in iOS](/assets/images/plugins/parking/ios_set_p_point3_.png)

{% endios%}

{% android%}



{% endandroid%}



&nbsp;&nbsp;&nbsp;&nbsp;

### Stay informed about Parking

Use the [Parking widget](/osmand/widgets/info-widgets#-parking-widget): 

- to view the distance to the Parking point from your current position or the center of the map on the screen;

- to move the map to the Parking point by tapping the Parking widget. 

![Parking widget Android](/assets/images/plugins/parking/parking_widget_android.png) ![Parking widget iOS](/assets/images/plugins/parking/parking_widget_ios.png)

The following menu will show the configurations of the parking spot such as parking time and date, information about parking limitation, distance from the current location to the parking spot.

![Action Parking set point Android](/assets/images/plugins/parking/parking_set_android.png) ![Action Parking set point iOS](/assets/images/plugins/parking/parking_set_ios.png)


&nbsp;&nbsp;&nbsp;&nbsp;

### Navigate to Parking



&nbsp;&nbsp;&nbsp;&nbsp;

### Remove the Parking point

User can delete the parking location marker anytime. Click to the parking point and ‘Delete’ button in [Map Context menu](/osmand/map/map-context-menu#-add--delete-parking-point).

It will be removed from the map and from the calendar if such option has been chosen earlier.

![Action Delete Parking Android](/assets/images/map/context_menu_limited_parking.png) ![Action Delete Parking iOS](/assets/images/map/context_menu_limited_parking_ios.png)
