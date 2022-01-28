---
title: "{% data variables.android-values.record_plugin_name %}"
intro: "To tell a story of where you have been, GPS data, as latitude and longitude of your location, can be recorded and stored in a file, and then re-used, improved, tweaked, added with waypoints, provided for navigation, shared with friends, etc."
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

Once setup completed, it is possible to make new records, as well as to display tracks on the map, and manage them by changing the appearance, editing the route, adding waypoints, etc. 

![Recorded trip in iOS](/assets/images/plugins/trip-recording/ios_recorded_trip1.png) ![Recorded trip in Android](/assets/images/plugins/trip-recording/and_recorded_trip1.png)

&nbsp;&nbsp;&nbsp;&nbsp;

### Enable plugin

{% data reusables.general.android-ios-switcher %}

{% default %}

The Trip recording plugin is needed for recording new tracks. It is possible to do with the [REC widget](/osmand/widgets/info-widgets#-trip-recording-widget), added to the app by the Trip recording plugin. To enable the Trip recording plugin, open the Plugins list and toggle the respective option. 

![Enable / Disable Plugin iOS](/assets/images/plugins/enable_disable_plugin_ios.png) ![Enable / Disable Plugin Android](/assets/images/plugins/enable_disable_plugin_android.png) 

{% enddefault %}

{% ios%}

In the **iOS** version, the Trip recording plugin is enabled by tapping the respective option in:

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.plugins %} → {% data variables.ios-values.track_recording %}

![Enable / Disable Plugin iOS](/assets/images/plugins/enable_disable_plugin_ios.png)

{% endios%}

{% android%}

In the **Android** version, to enable the Trip recording plugin, tap the triple dots at the right side of the option and select **Enable**: 

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.plugins_menu_group: %} → {% data variables.android-values.map_widget_monitoring %} 

![Enable / Disable Plugin Android](/assets/images/plugins/enable_disable_plugin_android.png) 

{% endandroid%}


&nbsp;&nbsp;&nbsp;&nbsp;


### Open settings 

{% data reusables.general.android-ios-switcher %}

{% default %}

For each specific profile, Trip recording can be configured individually, as the parameters could differ depending on the character of the movement, for example, whether it is the location of a car driver, a cyclist, or a nordic walker that is detected. All profiles are configured in the general settings of the entire app. First, it is needed to select the required profile, and then among other settings of the profile, to find the section dedicated to Trip recording. 

![Trip recording settings per profile in iOS](/assets/images/plugins/trip-recording/ios_profile_trip_rec2.png) ![Trip recording settings per profile in Android](/assets/images/plugins/trip-recording/and_profile_trip_rec2.png)

{% enddefault %}

{% ios%}

In the **iOS** version, to open settings for configuring Trip recording, do the following:

1. Go to: {% data variables.ios-values.menu %} → {% data variables.ios-values.sett_settings %}.

2. Select a profile. 

3. Tap **{% data variables.ios-values.track_recording %}**.

![Trip recording settings per profile in iOS](/assets/images/plugins/trip-recording/ios_profile_trip_rec2.png) 


{% endios%}

{% android%}

In the **Android** version, to open settings for configuring Trip recording, do the following:

1. Go to: {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.shared_string_settings %}.

2. Select a profile.

3. Tap **{% data variables.android-values.record_plugin_name %}**.


![Trip recording settings per profile in Android](/assets/images/plugins/trip-recording/and_profile_trip_rec2.png)

{% endandroid%}


&nbsp;&nbsp;&nbsp;&nbsp;


### Establish options

{% data reusables.general.android-ios-switcher %}

{% default %}

With the Trip recording settings opened for a profile, establish the required options as needed. Use the description of available parameters specified for the respective version of the application. 

![Configuring Trip recording in iOS](/assets/images/plugins/trip-recording/ios_trip_rec_settings1.png) ![Configuring Trip recording in Android](/assets/images/plugins/trip-recording/and_trip_rec_settings1.png)


{% enddefault %}

{% ios%}

In the **iOS** version, the available parameters are specified below. Establish them as needed. 

![Configuring Trip recording in iOS](/assets/images/plugins/trip-recording/ios_trip_rec_settings1.png)


| Parameter | Description |
|---|---|
| **General logging interval** | It is the frequency of the requests sent to the GPS sensor to detect and post a new point onto the route of the track that is started to be recorded manually. The option is duplicated on the [Start recording dialog](/osmand/widgets/info-widgets#-trip-recording-widget). 5 seconds is the default option. Available are the options in the range from 0 seconds to 5 minutes. The *Always ask* option requires the interval to be established anew on every start of the recording. |
| **Minimum displacement** | Given that two points are detected being close to one another, when a minimum displacement option is established, one of the points is removed, if it is detected to be closer than the established interval. It is helpful for none, or little movement, so that not to generate redundant points. The displacement interval is disabled if the *Not selected* option is set. Otherwise, an interval is considered to be between 2 meters and 50 meters depending on the selected option. For example, 5 meters is used, when there is no need in capturing more precise data than that, and no need in capturing any data at all when not moving. |
| **Minimum accuracy** | Given that your location is identified via GPS, when the longitude and latitude are calculated, the resulted location point can be detected accurately to a certain extend and expressed in meters/feet, as reported by Android for your chipset. It is possible to establish a minimum threshold between 1 meter and 50 meters for calculating the accuracy of the detected location in relation to the real location. A too small accuracy may cause the existence of blank spots on the track, for example, in circumstances when the route goes under the bridge, or between large trees, or high buildings, or is conducted in unfavorable weather conditions. It is recommended to disable the accuracy by establishing the *Not selected* option in case of uncertainty of the quality of the GPS signal. |
| **Minimum speed** | Given that at a low speed the recorded track can be noisy by showing lots of points on a small segment of the route, when the motion is detected and the speed level is calculated to be less than the established threshold, then the points will not be recorded. To disable the minimum speed detection, set the *Not selected* option. To detect only motion to start recording points, set the *>0* option. The rest of options are recommended to be used carefully, and to avoid losing too many points, decrease the minimum threshold. |
| **Auto-record track** | If enabled, whenever navigation is in progress, the track is recorded automatically, and saved to the folder specified for tracks. Please, note that Track recording consumes the battery energy, and continues to run in the background with the screen being closed. For efficient use of the battery life, check out its status. |
| **Logging interval during navigation** | It is the frequency of the requests sent to the GPS sensor to detect and post a new point onto the route of the track, which is recorded automatically during navigation, if the **Auto-record track** option is enabled. 5 seconds is the default option. Available are the options in the range from 0 seconds to 5 minutes. |
| **Auto-split recordings after gap** | If enabled, a new segment will automatically start after 6 minutes of inactivity; a new track will automatically start after 2 hours of inactivity; and a new file will automatically start when the date has changed. |
| **Tracks** | This is a quick re-direction to the folder: {% data variables.ios-values.menu %} → {% data variables.ios-values.my_places %} → {% data variables.ios-values.tracks %} tab. |
| **Reset plugin settings to default** | This establishes the default values for all of the above settings. |   



{% endios%}

{% android%}

In the **Android** version, the available parameters are specified below. Establish them as needed. 

![Configuring Trip recording in Android](/assets/images/plugins/trip-recording/and_trip_rec_settings1.png)

| Parameter | Description |
|---|---|
| **Show start dialog** | If enabled, to start the recording, it is needed to tap the respective option in the Start dialog. Otherwise, the recording will start automatically. |
| **Auto-record track during navigation** | If enabled, whenever navigation is in progress, the track is recorded automatically, and saved to the folder specified for tracks. Please, note that Track recording consumes the battery energy, and continues to run in the background with the screen being closed. For efficient use of the battery life, check out its status.| 
| **Logging interval** | It is the frequency of the requests sent to the GPS sensor to detect and post a new point onto the route of the track, which is recorded automatically during navigation, if the **Auto-record track during navigation** option is enabled. 5 seconds is the default option. Available are the options in the range from 0 seconds to 5 minutes. |
| **General logging interval** | It is the frequency of the requests sent to the GPS sensor to detect and post a new point onto the route of the track that is started to be recorded manually. The option is duplicated on the [Start recording dialog](/osmand/widgets/info-widgets#-trip-recording-widget). 5 seconds is the default option. Available are the options in the range from 0 seconds to 5 minutes. |
| **Minimum displacement** | Given that two points are detected being close to one another, when a minimum displacement option is established, one of the points is removed, if it is detected to be closer than the established interval. It is helpful for none, or little movement, so that not to generate redundant points. The displacement interval is disabled if the *Not selected* option is set. Otherwise, an interval is considered to be between 2 meters and 50 meters depending on the selected option. For example, 5 meters is used, when there is no need in capturing more precise data than that, and no need in capturing any data at all when not moving. |
| **Minimum accuracy** | Given that your location is identified via GPS, when the longitude and latitude are calculated, the resulted location point can be detected accurately to a certain extend and expressed in meters/feet, as reported by Android for your chipset. It is possible to establish a minimum threshold between 1 meter and 50 meters for calculating the accuracy of the detected location in relation to the real location. A too small accuracy may cause the existence of blank spots on the track, for example, in circumstances when the route goes under the bridge, or between large trees, or high buildings, or is conducted in unfavorable weather conditions. It is recommended to disable the accuracy by establishing the *Not selected* option in case of uncertainty of the quality of the GPS signal. |
| **Minimum speed** | Given that at a low speed the recorded track can be noisy by showing lots of points on a small segment of the route, when the motion is detected and the speed level is calculated to be less than the established threshold, then the points will not be recorded. To disable the minimum speed detection, set the *Not selected* option. To detect only motion to start recording points, set the *>0* option. The rest of options are recommended to be used carefully, and to avoid losing too many points, decrease the minimum threshold. |
| **Auto-split recordings after gap** | If enabled, a new segment will automatically start after 6 minutes of inactivity; a new track will automatically start after 2 hours of inactivity; and a new file will automatically start when the date has changed. |
| **Prevent standalone logging** | If enabled, Trip recording will automatically stop, when the OsmAnd app is stopped, and the notification bar of Android shows no indication of OsmAnd's working in the background. |
| **Include heading** | If enabled, the heading is saved for every point when the track is recorded. |
| **Track storage folder** | Given that all tracks are stored in: {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.shared_string_my_places   %} → {% data variables.android-values.shared_string_gpx_files %} tab; it is possible to establish the internal structure of this folder by selecting one of the following two options: either 1. to record all tracks to the *Rec* folder; or 2. to group all tracks by respective month folders, such as: *Rec/yyyy-mm* |
| **Notification** | If enabled, a system notification is displayed on start of Trip recording. | 
| **Online tracking** | It is real-time monitoring of your current location. If enabled, every point is transmitted to the specified URL. The **Web address** field is intended for entering the URL in the following format: *https://example.com?lat={0}&lon={1}&timestamp={2}&hdop={3}&altitude={4}&speed={5}* The **Tracking interval** parameter is used to determine the frequency of how often to send the location. The options can be selected in the range from 0 second to 5 minutes. The **Time buffer** parameter establishes the period of time during which the points will be accumulated in case if the Internet connection is lost.|
| **Tracks** | This is a quick re-direction to the folder: {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.shared_string_my_places  %} → {% data variables.android-values.shared_string_gpx_files %} tab. |
| **Reset plugin settings to default** | This establishes the default values for all of the above settings. |
| **Copy from another profile** | This opens a dialog to select a profile to copy the established Trip recording configuration of values from, and further to establish them for the current profile. |


{% endandroid%}


&nbsp;&nbsp;&nbsp;&nbsp;


## Create new track 

{% data reusables.general.android-ios-switcher %}

{% default %}

The [REC widget](/osmand/widgets/info-widgets#-trip-recording-widget) is used to create new records. The widget shows up in the list of widgets in the [Configure screen](/osmand/widgets/configure-screen) menu, after the Trip recording plugin is enabled. If toggled on in the list of widgets, the REC widget becomes displayed on the screen. 

- To start recording, tap the REC widget, and confirm in the opened Start dialog, if it is enabled to be displayed.  

- To finish recording, tap the REC widget again, and confirm in the Trip recording dialog. 

![Start recording in iOS](/assets/images/plugins/trip-recording/ios_widget_start2.png) ![Start recording in Android](/assets/images/plugins/trip-recording/and_widget_menu2.png)

{% enddefault %}

{% ios%}

#### START RECORDING 

In the **iOS** version, to start recording, tap the REC widget, and in the opened Start dialog, it is possible adjust the following recording settings before confirming the start of the recording by tapping **OK**:

- **Loggin interval** - to set the frequency of the requests sent to the GPS sensor to detect and post a new point onto the route of the track;

- **Remember my choice** - removes the Start dialog, so that recording to start without confirmation. Once toggled on, the Start dialog will be disabled, and can show up again only after re-start of the Trip recording plugin;

- **Show on map** - if enabled, shows detected points on the map. 

![Start recording in iOS](/assets/images/plugins/trip-recording/ios_widget_start2.png) ![Finish recording in iOS](/assets/images/plugins/trip-recording/ios_widget_finish1.png)


#### STOP RECORDING and OTHER OPTIONS

In the **iOS** version, to stop recording, or to do any of the following options, tap the REC widget again, and in the opened Track recording dialog, select:

- **Stop recording** - to stop the recording. The track will automatically put for storing in: {% data variables.ios-values.menu %} → {% data variables.ios-values.menu_my_places %} → tab {% data variables.ios-values.shared_string_tracks %}. 

- **Show Info** - opens the *Current recording track* context menu with options for managing the track described further. 

- **Start new segment** - starts a new segment of the current track. The number of segments are available for analysis with the context menu of the track described further.

- **Save current track** - saves the track for storing and asks if to continue to record, or stop. 


{% endios%}

{% android%}

#### START RECORDING 

In the **Android** version, there are two options to start recording: 

- either using the REC widget, 
- or with the Trip recording option in the menu. 

Both open the Start dialog, if it is enabled in the Trip recording settings described above. 


#### START DIALOG

In the opened Start dialog, it is possible adjust the following recording settings before confirming the start of the recording by tapping **Start**:

- **Show on map** - if enabled, shows the detected points on the map;

- **Appearance** - the *Line* icon - opens the context menu with options to adjust visual representation of the track on the map. The available options are described further;

- **Logging interval** - to set the frequency of the requests sent to the GPS sensor to detect and post a new point onto the route of the track;

- **Settings** - opens the Trip recording settings for the currently opened profile, described above. 


![Start recording in Android](/assets/images/plugins/trip-recording/and_recording_start1.png)
![Finish recording in Android](/assets/images/plugins/trip-recording/and_recording_finish1.png)


#### STOP RECORDING and OTHER OPTIONS

In the **Android** version, to stop recording, or to do any of the following options, tap the REC widget, or the Trip recording option in the menu again, and in the opened Trip recording dialog, select:

- **Show on map** - if enabled, shows the detected points on the map;

- **Appearance** - the *Line* icon - opens the context menu with options to adjust visual representation of the track on the map. The available options are described further;

- **Start time** / **End Time** - the timestamps of the first detected point and the last detected point;

- **Close** - to close the Trip recording dialog and continue recording; 

- **Pause** - to take a break in recording, and after a while to resume recording;

- **Finish** - to stop the recording. The track will automatically put for storing in: {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.shared_string_my_places   %} →  tab {% data variables.android-values.shared_string_gpx_files %}. 

- **Options** - opens the context menu with the following options: 

    - **Clear recorded data** - if any accumulated unsaved data, it will be deleted;
    
    - **Stop without saving** - stops recording and does not save a track;
    
    - **Stop online tracking** - stops sending recorded points to the specified online resource;
    
    - **Save and continue** - saves the track for storing and continues recording further; 
    
    - **Start new segment** - starts a new segment of the current track. The number of segments are available for analysis with the context menu of the track described further.


{% endandroid%}

>**NOTE**: For any troubleshooting details, refer to: [Track recording issues](https://docs.osmand.net/en/main@latest/osmand/troubleshooting/track-recording-issues) 



&nbsp;&nbsp;&nbsp;&nbsp;


### Show track on map

{% data reusables.general.android-ios-switcher %}

{% default %}

![Show tracks on the map in iOS](/assets/images/plugins/trip-recording/ios_show_tracks2.png) ![Show tracks on the map in Android](/assets/images/plugins/trip-recording/and_show_tracks2.png)


{% enddefault %}

{% ios%}


{% endios%}

{% android%}



{% endandroid%}




&nbsp;&nbsp;&nbsp;&nbsp;


### Tracks in My Places







&nbsp;&nbsp;&nbsp;&nbsp;


## Manage tracks 




{% data reusables.general.android-ios-switcher %}

{% default %}



{% enddefault %}

{% ios%}





{% endios%}

{% android%}




![Trip recording Appearence Android](/assets/images/plugins/trip-recording/appearance_trip_recording_android.png)



![REC widget info Android](/assets/images/plugins/trip-recording/rec_widget_info_android.png)

* See all general information about the track: distance, ascent, descent, average speed, maximum speed, time span. This panel can  be scrolled by the user right and back.
* Enable 'Show track' on the map feature and configure the style of the track line.
* Clear recorded data
* Start new segment
* Save (save the recorded track and change GPX file name)
* Pause and stop recording




{% endandroid%}


