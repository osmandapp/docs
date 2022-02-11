---
title: "{% data variables.android-values.audionotes_plugin_name %}"
intro: "Making memorable notes is one of the main pleasures of traveling. **For Android only**."
versions: '*'
---
{% data reusables.general.article-not-complete %}

Making memorable notes is one of the main pleasures of traveling. With OsmAnd Audio/video notes plugin, you can add media right to the map to watch it later. Want your pictures to be added to the locations they were made at? Easy. Need a comfortable video recorder? No problem. Want to make an audio note and link it to the location? Problem solved.

![Audio video notes intro](/assets/images/plugins/audio-video-notes/audio-video-intro.png)


## Enable / Disable Plugin

Before starting to use or not option for making your notes on the map you need to Enable / Disable plugin:

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.plugins_menu_group: %} → {% data variables.android-values.audionotes_plugin_name %}

![Audio video plugin Android](/assets/images/plugins/audio-video-notes/audio_video_plugin_android.png)

## Plugin settings

User can set any parameters for media files in Settings menu of the Plugin. 

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.plugins_menu_group: %} → {% data variables.android-values.audionotes_plugin_name %} → {% data variables.android-values.shared_string_settings %}


**Photo notes:**

![Audio video plugin settings Photo Android](/assets/images/plugins/audio-video-notes/audio_video_plugin_settings_photo_android.png)

- {% data variables.android-values.multimedia_use_system_camera %} - use or not system application for photos.
- {% data variables.android-values.av_camera_pic_size %}- set camera picture size.
- {% data variables.android-values.av_camera_focus %} - set focus mode: {% data variables.android-values.av_camera_focus_infinity %}, {% data variables.android-values.av_camera_focus_auto %}, {% data variables.android-values.av_camera_focus_continuous %}.
- {% data variables.android-values.multimedia_photo_play_sound %} - switch on/off camera shutter sound.


**Audio notes:**

![Audio video plugin settings Audio Android](/assets/images/plugins/audio-video-notes/audio_video_plugin_settings_audio_android.png)

- {% data variables.android-values.av_audio_format %} - select audio output format: Default or ACC.
- {% data variables.android-values.av_audio_bitrate %}- select audio bitrate: Default, 16kbps, 32 kbps... 128 kbps.


**Video notes:**


![Audio video plugin settings Video Android](/assets/images/plugins/audio-video-notes/audio_video_plugin_settings_video_android.png)

- {% data variables.android-values.multimedia_use_system_camera %} - use or not system recorder for video.
- {% data variables.android-values.av_video_quality %}- select video quality.
- {% data variables.android-values.multimedia_rec_split_title %}- choose option: Rewrite clips when used space exceeds the storage size.
- {% data variables.android-values.rec_split_clip_length %}- set upper time limit for recorded clips.
- {% data variables.android-values.rec_split_storage_size %}- set amount of space that can be occupied by all recorded clips.

**Action button:**

![Audio video plugin settings Action Android](/assets/images/plugins/audio-video-notes/audio_video_plugin_settings_action_android.png)

- [The way to your media notes in OsmAnd menu](/osmand/personal/myplaces): click to '{% data variables.android-values.notes %}' opening menu.
- {% data variables.android-values.reset_plugin_to_default %} - tapping discards all your changes.
- {% data variables.android-values.copy_from_other_profile %} - tapping for copy plugin settings from another profile.


{% data variables.android-values.audionotes_plugin_name %} Plugin stores media files in a format:

{SHORTLINK_LOCATION}_Description.{avi,mp3,jpg} where SHORTLINK_LOCATION is encoded latitude/longitude according to specification https://wiki.openstreetmap.org/wiki/Shortlink.


## Add note on the map

For viewing your notes on the map you can switch on the  [Recording layer](/osmand/map/point-layers-on-map#-audio--video-points-android)  in  [Configure map menu](/osmand/map/configure-map-menu).

There are two ways how to add your notes on the map:
- [by Widget](/osmand/widgets/info-widgets#-audio-video-notes-widget-android): adding a note in the point of your location.
- [by Map Context menu](/osmand/map/map-context-menu#-record-av-note-android): adding a note in the chosen point on the map.


### By Widget

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

### By Map Context menu

User can add [a note in chosen point on the map](/osmand/map/map-context-menu#-record-av-note-android). Just make long tap on the map and choose [special Actions on Map Context menu](/osmand/map/map-context-menu):

- {% data variables.android-values.recording_context_menu_arecord %} - makes a audio note on selected point (creates new point on the overlay with audio icon).
- {% data variables.android-values.recording_context_menu_vrecord%} - makes a video note on selected point (creates new point on the overlay with video icon).
- {% data variables.android-values.recording_context_menu_precord %} - makes a photo point on the map.

![Audio video plugin  Context menu take a note](/assets/images/plugins/audio-video-notes/context-menu-take-note.png)

## Actions with notes

All notes keep in [My places menu](/osmand/personal/myplaces). User can make needed actions with notes in My places menu or in Map Context menu.

### My places menu

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


### Actions in Map Context menu

[Short tap](/osmand/map/map-context-menu#select-an-object-short-tap) on a/v note on the map or in [My places menu](/osmand/plugins/audio-video-notes#my-places-menu) opens [Map Context menu](/osmand/map/map-context-menu).

In this menu user can see [Details](/osmand/map/map-context-menu#-audiovideo-note-android) of chosen note and make Actions (Delete, Play, Show) with chosen note.

![Audio video plugin Context menu](/assets/images/plugins/audio-video-notes/audio_video_notes_map_context_menu_1.png)


## Add notes to your GPX track

You can use this plugin while  [recording the GPX track](/osmand/plugins/trip-recording). This way, all your notes will be added to the track as waypoints automatically.

![Audio video plugin to Track](/assets/images/plugins/audio-video-notes/audio_video_notes_to_track.png)

When [viewing the track](/osmand/map/track-context-menu), you'll see exactly what was recorded where.

![Audio video plugin to Track view](/assets/images/plugins/audio-video-notes/audio_video_notes_to_track_view.png)

To view everything later, you can export the track together with all the media and see them in the  [JOSM editor](https://josm.openstreetmap.de/). Please note that you'll need to put the media in the corresponding folder (you'll know which one if you click on a video note and see the message about a missing file. Just put it in the indicated folder).

![Audio video notes in Josm](/assets/images/plugins/audio-video-notes/josm-track-points.png)


So there you have it: your personal notes linked to the map and stored in one place. Document your adventures!
