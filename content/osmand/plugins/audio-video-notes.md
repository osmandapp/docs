---
title: "{% data variables.android-values.audionotes_plugin_name %}"
intro: "Making memorable notes is one of the main pleasures of traveling. For Android only."
versions: '*'
---
{% data reusables.general.article-not-complete %}

Making memorable notes is one of the main pleasures of traveling. With OsmAnd Audio/video notes plugin, you can add media right to the map to watch it later. Want your pictures to be added to the locations they were made at? Easy. Need a comfortable video recorder? No problem. Want to make an audio note and link it to the location? Problem solved.

![Audio video notes intro](/assets/images/plugins/audio-video-notes/audio-video-intro.png)

## How to use it

### Enable / Disable Plugin

Before starting to use or not option for making your notes on the map you need to Enable / Disable plugin:

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.plugins_menu_group: %} → {% data variables.android-values.audionotes_plugin_name %}

![Audio video plugin Android](/assets/images/plugins/audio-video-notes/audio_video_plugin_android.png)

### Plugin settings

User can set any parameters for media files in Settings menu of the Plugin. 

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.plugins_menu_group: %} → {% data variables.android-values.audionotes_plugin_name %} → {% data variables.android-values.shared_string_settings %}


Photo notes:

![Audio video plugin settings Photo Android](/assets/images/plugins/audio-video-notes/audio_video_plugin_settings_photo_android.png)

- {% data variables.android-values.multimedia_use_system_camera %} - use or not system application for photos.
- {% data variables.android-values.av_camera_pic_size %}- set camera picture size.
- {% data variables.android-values.av_camera_focus %} - set focus mode: {% data variables.android-values.av_camera_focus_infinity %}, {% data variables.android-values.av_camera_focus_auto %}, {% data variables.android-values.av_camera_focus_continuous %}.
- {% data variables.android-values.multimedia_photo_play_sound %} - switch on/off camera shutter sound.


Audio notes:

![Audio video plugin settings Audio Android](/assets/images/plugins/audio-video-notes/audio_video_plugin_settings_audio_android.png)

- {% data variables.android-values.av_audio_format %} - select audio output format: Default or ACC.
- {% data variables.android-values.av_audio_bitrate %}- select audio bitrate: Default, 16kbps, 32 kbps... 128 kbps.


Video notes:


![Audio video plugin settings Video Android](/assets/images/plugins/audio-video-notes/audio_video_plugin_settings_video_android.png)

- {% data variables.android-values.multimedia_use_system_camera %} - use or not system recorder for video.
- {% data variables.android-values.av_video_quality %}- select video quality.
- {% data variables.android-values.multimedia_rec_split_title %}- choose option: Rewrite clips when used space exceeds the storage size.
- {% data variables.android-values.rec_split_clip_length %}- set upper time limit for recorded clips.
- {% data variables.android-values.rec_split_storage_size %}- set amount of space that can be occupied by all recorded clips.

Action button:

![Audio video plugin settings Action Android](/assets/images/plugins/audio-video-notes/audio_video_plugin_settings_action_android.png)

- [The way to your media notes in OsmAnd menu](/osmand/personal/myplaces): click to '{% data variables.android-values.notes %}' opening menu.
- {% data variables.android-values.reset_plugin_to_default %} - tapping discards all your changes.
- {% data variables.android-values.copy_from_other_profile %} - tapping for copy plugin settings from another profile.


### Add note on the map

### View note in Context menu

### Delete note


## Widget

[Widget link](/osmand/widgets/info-widgets#-audio-video-notes-widget-android)

![Audio-video notes widget](/assets/images/plugins/audio-video-notes/audio_video_notes_widget.png)

__________________________


You have to install  {% data variables.android-values.audionotes_plugin_name %}. It is free of charge and all you have to do is go to the plugins menu, then choose {% data variables.android-values.audionotes_plugin_name %} and tap Enable. That's it. Now you can make audio, video or photo notes and link them to the exact location of your choice.

You can choose settings for your photo, video, audio files. You can click ![Overflow menu](/assets/images/icons/android/ic_overflow_menu_white.svg) to Settings of  {% data variables.android-values.audionotes_plugin_name %} plugin.

![Audio video notes plugin settings](/assets/images/plugins/audio-video-notes/plugin-settings.png)
Just tap onto a spot on _the map-> Actions_, then choose  {% data variables.android-values.recording_context_menu_vrecord %}/{% data variables.android-values.recording_context_menu_arecord %}/{% data variables.android-values.av_def_action_picture %}, depending on what you need right now. The recording of audio and video will start automatically, you can stop it by tapping on  [the widget](https://osmand.net/features/map-viewing#Viewing_widgets_Android)  in the upper-right corner of your screen. You can also use  [the same widget](https://osmand.net/features/map-viewing#Viewing_widgets_Android)  to make a new note. Great, the media is now ready. What next? You can store it to watch later, play it, view it on the map, rename, delete and, of course, share it.

For viewing your notes on the map you can switch on the  [Recording layer](https://osmand.net/features/map-viewing#Customize_map_Android)  in  _app menu -> Configure map -> Show (Recording layer)_.

![Context menu take a note](/assets/images/plugins/audio-video-notes/context-menu-take-note.png)
You can tap on your note on the map. After that you see details screen where you can play/show your note or delete it. Of course you can share this note or make other _Actions_ with it.
 
![Context menu play a note](/assets/images/plugins/audio-video-notes/context-menu-play-note.png)

All your notes you can find in  _{% data.reusables.plugins.audio-video-notes-my-places %}_. Here you can sort your list, share your notes or delete it. If you click to one of your note you will see it on the map.

You can click to three points ![Overflow menu](/assets/images/icons/android/ic_overflow_menu_white.svg) button of note for _play/show, share, show on map, rename, delete it_.

![My Places - play a note](/assets/images/plugins/audio-video-notes/my-places-play-note.png)
{% data variables.android-values.audionotes_plugin_name %} Plugin stores media files in a format:
{SHORTLINK_LOCATION}_Description.{avi,mp3,jpg} where SHORTLINK_LOCATION is encoded latitude/longitude according to specification https://wiki.openstreetmap.org/wiki/Shortlink.

# Widget
Link to widget?
The Audio-video notes widget is a clickable widget. It changes its state according to settings chosen in the Configure screen menu. <br>

To make  audio, video, photo notes  user have to choose the needed option by clicking on the widget. <br>

If 'On request' option is selected  user will see three options to choose. <br>
* Take an audio note <br>
* Take a video note <br>
* Take a photo <br>

When the 'Take an audio note' option is selected, the user  can start doing audio recording.  To stop audio recording the user has to click on the widget or the button 'Stop' at the bottom of the screen. <br>

![Take an Audio video notes](/assets/images/plugins/audio-video-notes/take_an_audio_note_widget.png) <br>
When the 'Take a video note' option is selected, the user  can start doing video recording.  To stop video recording the user has to click on the widget or the button 'Stop' at the bottom of the screen. User can optionally show or hide the  video screen view by clicking the relevant button in the bottom-left corner. <br>

![Take a video note](/assets/images/plugins/audio-video-notes/take_a_video_note_widget.png) <br>

When the 'Take a photo' option is selected, the user can take a picture. <br>

All audio, video files and photos will be in the {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.shared_string_my_places %} → tab {% data variables.android-values.notes %} . <br>
User can sort files by type/data, share and delete them. <br>

# Add notes to your GPX track

You can use this plugin while  [recording the GPX track](https://osmand.net/features/trip-recording-plugin). This way, all your notes will be added to the track as waypoints automatically. When viewing the track, you'll see exactly what was recorded where.

![Add notes to track](/assets/images/plugins/audio-video-notes/add-notes-track.png)
To view everything later, you can export the track together with all the media and see them in the  [JOSM editor](https://josm.openstreetmap.de/). Please note that you'll need to put the media in the corresponding folder (you'll know which one if you click on a video note and see the message about a missing file. Just put it in the indicated folder).

![Audio video notes in Josm](/assets/images/plugins/audio-video-notes/josm-track-points.png)


So there you have it: your personal notes linked to the map and stored in one place. Document your adventures!
