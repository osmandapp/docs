---
title: "{% data variables.android-values.record_plugin_name %}"
intro: "GPS data recorded and stored in a file can be re-used, improved, tweaked, added with waypoints, provided for navigation, shared with friends, etc. to tell a story of where you have been."
versions: '*'
---
{% data reusables.general.article-not-complete %}


## Overview

GPS data consists of the latitude and longitude of your location at a specific moment in time. If it is recorded into a file as a set of location points in a particular order, the file stores the course of your trip. By placing the points from the file onto the map, the trip is visualized as a track with exact start and destination, as well as the route along which it is possible to go again, or share with somebody, or improve, etc. 

There are three base capabilities in regard to Trip recording: creating new tracks, showing the existing tracks on the map, and working with the ready records. The plugin is required to be enabled only for making new records. Using already created tracks is possible whenever needed. 



## Setup 

To start making new recording, the following setup is required: 

1. Enable the plugin. 

2. Configure Trip recording for the required profile.

3. If needed, add the REC widget to the screen. 

Once setup completed, it is possible to make new records, as well as to display tracks on the map, and if needed, manage the existing tracks by changing their appearance, editing the route, adding waypoints, etc. 

![Recorded trip in iOS](/assets/images/plugins/trip-recording/ios_recorded_trip1.png) ![Recorded trip in Android](assets/images/plugins/trip-recording/and_recorded_trip1.png)


### Enable plugin

{% data reusables.general.android-ios-switcher %}

{% default %}

The Trip recording plugin is needed for recording new tracks. It is possible to do either with the [REC widget](/osmand/widgets/info-widgets#-trip-recording-widget), or the Trip recording option in the menu. Both are added to the app with the Trip recording plugin. 

![Enable / Disable Plugin iOS](/assets/images/plugins/enable_disable_plugin_ios.png) ![Enable / Disable Plugin Android](/assets/images/plugins/enable_disable_plugin_android.png) 

{% enddefault %}

{% ios%}

In the **iOS** version, the Trip recording plugin is enabled by tapping the respective option in:

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.plugins %} → tab {% data variables.ios-values.track_recording %}

![Enable / Disable Plugin iOS](/assets/images/plugins/enable_disable_plugin_ios.png)

{% endios%}

{% android%}

In the **Android** version, to enable the Trip recording plugin, tap the triple dots at the right side of the option and select **Enable**: 

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.plugins_menu_group: %} → {% data variables.android-values.map_widget_monitoring %} 

![Enable / Disable Plugin Android](/assets/images/plugins/enable_disable_plugin_android.png) 

{% endandroid%}




### Configure Trip recording per profile

{% data reusables.general.android-ios-switcher %}

{% default %}


![Trip recording settings per profile in iOS](/assets/images/plugins/trip-recording/ios_profile_trip_rec2.png) ![Trip recording settings per profile in Android](/assets/images/plugins/trip-recording/and_profile_trip_rec2.png)

{% enddefault %}

{% ios%}

![Trip recording settings per profile in iOS](/assets/images/plugins/trip-recording/ios_profile_trip_rec2.png) 


{% endios%}

{% android%}

![Trip recording settings per profile in Android](/assets/images/plugins/trip-recording/and_profile_trip_rec2.png)

{% endandroid%}



### Configure trip recording navigation

![REC navigation Android](/assets/images/plugins/trip-recording/rec_plugin_navigation_android.png)

Auto-record track during navigation – the function that enables saving each 'trip recording' track automatically. <br>
User may find his track under {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.shared_string_my_places %} → {% data variables.android-values.shared_string_gpx_files %} tab

> :warning: **Track recording impacts the battery life**. Even if the screen is off, it continues to run. Check the notifications in the background in status bar!

Logging interval during navigation controls the frequency of queries to the GPS sensor along with the frequency of new dots appearing in the track line. <br>
By default, it is set to 5 seconds, but it can be configured in the range from 0 seconds to 5 minutes.

### Configure trip recording logging accuracy

![REC logging accuracy Android](/assets/images/plugins/trip-recording/rec_plugin_logging_accuracy_android.png)

| Parameter | Description |
|--------------------------|-------------|
| General logging interval |Specifies the logging interval for the general track recording. Can be set to 'always ask' or optionally chosen in the range between 0 to 5 minutes. Can be turned on via [Trip recording (REC) widget](/osmand/widgets/info-widgets#-trip-recording-widget). |
| Minimum displacement | Specifies the minimum displacement for the track recording. Can be chosen as 'not selected' or optionally chosen from 2 meters  to 50 meters.  This function should be configured to avoid duplicating points being recorded where too little actual motion may have occurred. |
| Minimum accuracy | Accuracy means the proximity of  measurements to the actual position. It is not directly related to precision, which is the spread of repeated measurements. Lowering the accuracy range value may reduce the amount of points recorded depending on GPS signal quality. |
| Minimum speed | Used to filter out the points while object is not moving or moving with a low speed. By using this option User may eliminate recording the bunch of points during the stop time and make resulting track look smoother on the map. |
| Auto-split recording after gap | When enabled, enforces new segment start after 6 minutes gap, new track start after 2 hours gap, new file start when date changed. |
| Prevent standalone logging | When enabled - disables track recording when the app is stopped. In this case, the OsmAnd background indication will disappear from the Android's notification bar.  |
| Include heading | Enables saving of the heading to each track point recorded. |   


> **_TIP:_**
> Set 5 meters distance for 'Minimum displacement' function if there is no need to capture precise data while not moving.

> **_TIP:_**
> It is hard to predict the set of data that will be recorded. If the user is not sure about GPS signal quality it makes sense to turn off (not select) the 'Minimum accuracy' filter.

> **_TIP:_**
> Try to disable 'Minimum displacement' first (set to 'Not selected'). It will help you not to lose data.  If the resulting track looks noisy, try non zero value for this parameter and also raise 'Minimum speed'.

### Configure trip informational settings

![REC informational settings Android](/assets/images/plugins/trip-recording/rec_plugin_info_settings_android.png)

**Track storage folder**

Is used to define where the tracks will be stored. There are two options:

- Record tracks to 'rec' folder
- Store recorded tracks in monthly folder

> **_Note:_** User can find his tracks in {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.shared_string_my_places   %} → {% data variables.android-values.shared_string_gpx_files %} tab.

**Notification**

Displays system notification allowing to start trip recording.

**Online tracking**

Allows sharing current location using trip recording.

- Web address 
- Tracking interval - Allows user to specify online tracking interval from 0 seconds to 5 minutes.
- Time buffer - Allows user to specify a time buffer that will keep locations for certain period of time when Internet connection lost.

**Configure trip general settings**

![REC general settings Android](/assets/images/plugins/trip-recording/rec_plugin_general_settings_android.png)

- The track folder will redirect user to {% data variables.android-values.shared_string_gpx_files %} tab in {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.shared_string_my_places  %}
- 'Reset plugin settings to default'  - resets all plugin settings to default values. All user settings for this plugin will be lost!
- 'Copy from another profile' - copies plugin settings from another profile.


## From widget
 Before recording the trip a Trip recording settings to be defined. Trip recording settings menu is displayed when user clicks on [the REC widget](/osmand/widgets/info-widgets#-trip-recording-widget). 

![Trip recording (REC) Settings Android](/assets/images/plugins/trip-recording/rec_settings_android.png) ![Trip recording (REC) Settings iOS](/assets/images/plugins/trip-recording/rec_settings_ios.png)

### Settings menu (Android)

In the REC settings menu user can enable 'Show track' on the map feature and configure the style of the track line (for Android only). 

The 'Line configuration button' (for Android only) next to the toggle button 'Show track on the map' switcher gives the user an opportunity to change track appearance. User may change the color, width and enable/disable direction arrows, enable show start and finish icons. 

Optionally, user can configure Custom width by moving slider from 1 to 24. 


![Trip recording Appearence Android](/assets/images/plugins/trip-recording/appearance_trip_recording_android.png)

In the REC Settings menu user can configure the logging interval from 0 seconds to 5 minutes. 
The Logging interval controls the frequency of queries to the GPS sensor along with frequency of new dots appearing in the track line. <br>

![Logging interval in Trip recording Appearence Android](/assets/images/plugins/trip-recording/logging_interval_in_tr_widget_android.png)

If a user wants to apply all configurations to all others tracks recorded in future, the toggle button (switcher) ‘Always ask’ should be off. Please leave this switcher in 'on' position to be able to configure tracks individually. <br>
When all settings are defined, user can push the ‘Start recording’ button.


The Logging interval can be additionally checked/ changed in: 
{% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %} → {% data variables.android-values.shared_string_trip_recording %} → {% data variables.android-values.save_track_interval %}. 


When all settings are configured, press ‘Start recording’ button.
***For Android devices*** the REC widget will change to the red circle.  The distance passed will be displayed in the widget.  
![REC widget Android](/assets/images/plugins/trip-recording/rec_widget_android.png)

To tap REC widget again will give an opportunity  to:

![REC widget info Android](/assets/images/plugins/trip-recording/rec_widget_info_android.png)

* See all general information about the track: distance, ascent, descent, average speed, maximum speed, time span. This panel can  be scrolled by the user right and back.
* Enable 'Show track' on the map feature and configure the style of the track line.
* Clear recorded data
* Start new segment
* Save (save the recorded track and change GPX file name)
* Pause and stop recording

User can find his track in {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.shared_string_my_places   %} →  tab {% data variables.android-values.shared_string_gpx_files %} <br>

### Settings menu (iOS)

![REC widget iOS](/assets/images/plugins/trip-recording/rec_widget_ios.png)

***For IOS devices*** when the REC widget will change to the red circle, the  distance passed will be displayed in the widget.

![REC widget menu iOS](/assets/images/plugins/trip-recording/rec_widget_menu_ios.png)

To tap REC widget again will give an opportunity  to:
* Stop recording - will pause The trip recording. Then pressing the widget again will give and options to 'Continue recording'
* Show Info - will display statistics data such as speed, route time, uphills/downhills
* Start new segment
* Save current trip - the track will be automatically saved.

User can find his track in {% data variables.ios-values.menu %} → {% data variables.ios-values.menu_my_places %} → tab {% data variables.ios-values.shared_string_tracks %}.

[Track recording issues](https://docs.osmand.net/en/main@latest/osmand/troubleshooting/track-recording-issues) 
