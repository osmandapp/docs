---
title: "{% data variables.android-values.audionotes_plugin_name %}"
intro: "Audio/video notes for future reference in case of need, or just to remember the moment, scene, or interaction, once made, are available from the central storage as well as on the map as an individual layer of user-made stories and thoughts tied to a geolocation.  **For Android only**."
versions: '*'
---
{% data reusables.general.article-not-complete %}

## Overview 

The Audio/video notes plugin extends the functional capabilities of storing the information about a geolocation by giving the user options to create their own representations in different formats, such as: a photo note, a video note, or an audio file, and tie them to a geographical place, or the current position. The recording options are provided with the Audio/video notes widget, and/or the context menu of a POI. The resulted data is automatically saved to the central storage from where it is convenient to manage and share anything needed. 

Simultaneously, all created audio/video notes make up a Recording layer that if configured to show up on the map, provides a different view on the recorded data and means for managing it. Within the Recording layer, the audio/video notes are laid out as POIs across the map, thus creating a user-made map narrative, visible only to the owner of the device.

![Audio video notes intro](/assets/images/plugins/audio-video-notes/audio-video-intro.png)


>**NOTE**: As of March, 2022, the audio/video notes functionality is available for **Android only**. 

&nbsp;&nbsp;&nbsp;&nbsp;


## Setup

The audio/video notes are provided with the Audio/video notes plugin, and require the following setup:

1. Enable the plugin. 

2. If needed, add the widget to the device screen, and/or configure. 

3. If needed, configure the recording settings per profile. 


### Enable plugin

The Audio/video notes plugin is required for working with the audio/video notes: from creating the notes to viewing them in My Places, and showing on the map. All audio/video notes will be hidden from the map and from My Places, if the plugin becomes disabled. 

To enable the plugin, tap the triple dots beside the enabled **{% data variables.android-values.audionotes_plugin_name %}** option in the list of [plugins](/osmand/start-with/first-steps#how-to-configure-plugins) and select **Enable**.  

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.plugins_menu_group %} → {% data variables.android-values.audionotes_plugin_name %}

![Audio video plugin Android](/assets/images/plugins/audio-video-notes/audio_video_plugin_android.png)


&nbsp;&nbsp;&nbsp;&nbsp;

### Add/Configure widget

The {% data variables.android-values.map_widget_av_notes %} widget makes records (i.e. photo, audio, video) and ties them to the current position of the user. The widget has several options that can be set up as the default action performed by the widget on tap. 

![The widget](/assets/images/plugins/audio-video-notes/audio_video_notes_widget.png)

Adding the widget to the screen is needed when you would rather skip looking for a geolocation on the map and by default link the notes to your current position. To add, and/or configure the widget, do the following:

1. Open {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.map_widget_config %}

2. Scroll down the **{% data variables.android-values.map_widget_right %}**.

3. Tap **{% data variables.android-values.map_widget_av_notes %}** and the context menu of the widget opens. 

4. Select an option you prefer to do by default by tapping the widget:

    - **{% data variables.android-values.av_def_action_choose %}** - to open a choice of options;

    - **{% data variables.android-values.av_def_action_audio %}** - to immediately start to record an audio message;

    - **{% data variables.android-values.av_def_action_video %}** - to immediately start to record a video;

    - **{% data variables.android-values.av_def_action_picture %}** - to immediately start taking a photo. 

5. Make certain {% data variables.android-values.shared_string_show %} or {% data variables.android-values.shared_string_collapse%} is selected, so that the widget to be displayed on the device screen. In the latter case, it will be available from an arrow icon opening the dropdown list of widgets in the top right-hand corner of the screen. 


![Widget options](/assets/images/plugins/audio-video-notes/av-widget-configure2.png)


&nbsp;&nbsp;&nbsp;&nbsp;

### Open settings

For every profile, it is possible to configure the recording settings. There are two options of how to open the {% data variables.android-values.audionotes_plugin_name %} settings: 

- from the plugin, so that to configure recording only for the default profile; 

- from the app settings, so that to configure recording for any of the profiles. 

From the [plugin](/osmand/start-with/first-steps#how-to-configure-plugins), the Audio/video recording settings are available on selecting **Settings** from the triple dots list of the plugin in: 

{% data variables.android-values.shared_string_menu %} → {% data variables.android-values.plugins_menu_group %} → {% data variables.android-values.audionotes_plugin_name %} → {% data variables.android-values.shared_string_settings %}

From the [settings](/osmand/start-with/first-steps#how-to-manage-your-settings) of the entire app, the Audio/video recording settings can be opened as follows:

1. Go to: {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.shared_string_settings %}.

2. Select a profile.

3. Tap the **{% data variables.android-values.audionotes_plugin_name %}** option. 

![Opening Audio video plugin settings](/assets/images/plugins/audio-video-notes/settings_avplugin_per_profile2.png) 



&nbsp;&nbsp;&nbsp;&nbsp;

### Establish options 

The way the Audio/video recording will work can be determined with the settings described below. Establish them as needed. 

![Audio video plugin settings Photo Android](/assets/images/plugins/audio-video-notes/audio_video_plugin_settings_photo_android.png)  ![Audio video plugin settings Video Android](/assets/images/plugins/audio-video-notes/audio_video_plugin_settings_video_android.png)


| Parameter | Description |
| --- | --- |
| **{% data variables.android-values.multimedia_use_system_camera %}** | If enabled, OsmAnd uses the system application to create photos.|
| **{% data variables.android-values.av_camera_pic_size %}** | This establishes a size to create photos in. The number of available options is determined with the capabilities of the device camera. If no option is selected, the app uses the size that is established in the system  settings for the device camera. |
| **{% data variables.android-values.av_camera_focus %}** | This establishes the method of how focus is set by the camera. The number of available options is determined with the capabilities of the device camera. Basically, there are the following three options: *{% data variables.android-values.av_camera_focus_auto %}*; *{% data variables.android-values.av_camera_focus_continuous %}*; and *{% data variables.android-values.av_camera_focus_infinity %}*, where **autofocus** is the most popular one and establishes the automatic mode for the camera to focus by rotating the lens focus ring; **continous** makes the camera detect movements and refocus accordingly; and **infinity** makes the lens to focus on a distance and thus keep everything extraordinarily wide in focus no matter how far it is. |
| **{% data variables.android-values.multimedia_photo_play_sound %}** | If enabled, a sound is produced on closing the camera.| 
| **{% data variables.android-values.av_audio_format %}** | This provides a choice of formats that an audio file should be created in. There are two options: either the default format, or the **.aac** format. |
| **{% data variables.android-values.av_audio_bitrate %}** | This provides a choice of bitrate options, which range from 16kbps, and to 128 kbps, or the Default option. The default option is determined with the default microphone settings of the device. | 
| **{% data variables.android-values.multimedia_use_system_camera %}** in {% data variables.android-values.video_notes %} | If enabled, OsmAnd uses the system application to record video. |
| **{% data variables.android-values.av_video_quality %}** | This provides a choice of options that determine the quality of recorded video.  |
| **{% data variables.android-values.multimedia_rec_split_title %}** | choose option: Rewrite clips when used space exceeds the storage size. |
| **{% data variables.android-values.rec_split_clip_length %}** | set upper time limit for recorded clips. |
| **{% data variables.android-values.rec_split_storage_size %}** | set amount of space that can be occupied by all recorded clips. |
| **{% data variables.android-values.notes %}** | [The way to your media notes in OsmAnd menu](/osmand/personal/myplaces): click to '{% data variables.android-values.notes %}' opening menu. |
| **{% data variables.android-values.reset_plugin_to_default %}** | tapping discards all your changes. |
| **{% data variables.android-values.copy_from_other_profile %}** | tapping for copy plugin settings from another profile.|



&nbsp;&nbsp;&nbsp;&nbsp;

### Media file format 

{% data variables.android-values.audionotes_plugin_name %} Plugin stores media files in a format:

{SHORTLINK_LOCATION}_Description.{avi,mp3,jpg} where SHORTLINK_LOCATION is encoded latitude/longitude according to specification https://wiki.openstreetmap.org/wiki/Shortlink.




&nbsp;&nbsp;&nbsp;&nbsp;


## Manage notes

For viewing your notes on the map you can switch on the  [Recording layer](/osmand/map/point-layers-on-map#-audio--video-points-android)  in  [Configure map menu](/osmand/map/configure-map-menu).

There are two ways how to add your notes on the map:
- [by Widget](/osmand/widgets/info-widgets#-audio-video-notes-widget-android): adding a note in the point of your location.
- [by Map Context menu](/osmand/map/map-context-menu#-record-av-note-android): adding a note in the chosen point on the map.




&nbsp;&nbsp;&nbsp;&nbsp;

### Create notes in relation to current position 

The Audio-video notes widget is a clickable widget. It changes its state according to settings chosen in [the Configure screen menu](/osmand/widgets/info-widgets#-audio-video-notes-widget-android) .

To make  audio, video, photo notes  user have to choose the needed option by clicking on the widget.

If 'On request' option is selected  user will see three options to choose:
- Take an audio note
- Take a video note
- Take a photo

![Audio video plugin widget Android](/assets/images/plugins/audio-video-notes/audio_video_plugin_widget_choice_android.png)

When the 'Take an audio / video note' option is selected, the user  can start doing audio or video recording.  To stop recording the user has to click on the widget or the button 'Stop' at the bottom of the screen. User can optionally show or hide the  video screen view by clicking the relevant button in the bottom-left corner.

![Audio video plugin Take a video note](/assets/images/plugins/audio-video-notes/take_a_video_note_widget.png) <br>

When the 'Take a photo' option is selected, the user can take a picture.

All audio, video files and photos will be in the {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.shared_string_my_places %} → tab {% data variables.android-values.notes %} . 
User can sort files by type/data, share and delete them.





&nbsp;&nbsp;&nbsp;&nbsp; 

### Create notes in relation to a geolocation 

User can add [a note in chosen point on the map](/osmand/map/map-context-menu#-record-av-note-android). Just make long tap on the map and choose [special Actions on Map Context menu](/osmand/map/map-context-menu):

- {% data variables.android-values.recording_context_menu_arecord %} - makes a audio note on selected point (creates new point on the overlay with audio icon).
- {% data variables.android-values.recording_context_menu_vrecord%} - makes a video note on selected point (creates new point on the overlay with video icon).
- {% data variables.android-values.recording_context_menu_precord %} - makes a photo point on the map.

![Audio video plugin  Context menu take a note](/assets/images/plugins/audio-video-notes/context-menu-take-note.png)




&nbsp;&nbsp;&nbsp;&nbsp;

###  Reach out everything in My Places

All notes keep in [My places menu](/osmand/personal/myplaces). User can make needed actions with notes in My places menu or in Map Context menu.

All user notes keep in [My places menu](/osmand/personal/myplaces). It's a list with all your notes.

{% data variables.android-values.shared_string_menu %} → {% data variables.android-values.shared_string_my_places %} → {% data variables.android-values.notes %}

![Audio video plugin My places menu](/assets/images/plugins/audio-video-notes/audio_video_notes_myplaces_menu.png)

Clicking to chosen point opens [Map Context menu](/osmand/plugins/audio-video-notes#actions-in-map-context-menu) of this note.

![Audio video plugin My places menu Context](/assets/images/plugins/audio-video-notes/audio_video_notes_myplaces_menu_context.png)

Clicking to &#8285; opens additional menu of chosen note:

{% data variables.android-values.shared_string_menu %} → {% data variables.android-values.shared_string_my_places %} → {% data variables.android-values.notes %} -> &#8285; of chosen note

![Audio video plugin My places menu actions](/assets/images/plugins/audio-video-notes/audio_video_notes_myplaces_menu_actions.png)

- name of a note - show the name of chosen a/v note.
- {% data variables.android-values.watch %} / {% data variables.android-values.recording_context_menu_play %} - play your audio /  video note, or show photo note.
- {% data variables.android-values.shared_string_share %} - share chosen note.
- {% data variables.android-values.shared_string_show_on_map %} - show chosen note on the map and open [Map Context menu](/osmand/plugins/audio-video-notes#actions-in-map-context-menu).
- {% data variables.android-values.shared_string_rename %} - rename chosen point.
- {% data variables.android-values.shared_string_delete %} - delete chosen point.

At the bottom of the screen are three Actions buttons:

![Audio video plugin My places menu Three actions](/assets/images/plugins/audio-video-notes/audio_video_notes_myplaces_menu_three_actions.png)

- {% data variables.android-values.shared_string_sort %} - sort your notes list by type or by date.
- {% data variables.android-values.shared_string_share %} - choose notes from the list and share its. You can choose a/v notes in GPX file too.
- {% data variables.android-values.shared_string_delete %} - choose notes from the list and delete its. You can choose a/v notes in GPX file too.




&nbsp;&nbsp;&nbsp;&nbsp;

### Show notes on the map 





&nbsp;&nbsp;&nbsp;&nbsp;

### View audio/video POI   

[Short tap](/osmand/map/map-context-menu#select-an-object-short-tap) on a/v note on the map or in [My places menu](/osmand/plugins/audio-video-notes#my-places-menu) opens [Map Context menu](/osmand/map/map-context-menu).

In this menu user can see [Details](/osmand/map/map-context-menu#-audiovideo-note-android) of chosen note and make Actions (Delete, Play, Show) with chosen note.

![Audio video plugin Context menu](/assets/images/plugins/audio-video-notes/audio_video_notes_map_context_menu_1.png)



&nbsp;&nbsp;&nbsp;&nbsp;

### Make notes during Trip recording 

You can use this plugin while  [recording the GPX track](/osmand/plugins/trip-recording). This way, all your notes will be added to the track as waypoints automatically.

![Audio video plugin to Track](/assets/images/plugins/audio-video-notes/audio_video_notes_to_track.png)

When [viewing the track](/osmand/map/track-context-menu), you'll see exactly what was recorded where.

![Audio video plugin to Track view](/assets/images/plugins/audio-video-notes/audio_video_notes_to_track_view.png)



&nbsp;&nbsp;&nbsp;&nbsp;

### Export for JOSM editor 


To view everything later, you can export the track together with all the media and see them in the  [JOSM editor](https://josm.openstreetmap.de/). Please note that you'll need to put the media in the corresponding folder (you'll know which one if you click on a video note and see the message about a missing file. Just put it in the indicated folder).

![Audio video notes in Josm](/assets/images/plugins/audio-video-notes/josm-track-points.png)


So there you have it: your personal notes linked to the map and stored in one place. Document your adventures!
