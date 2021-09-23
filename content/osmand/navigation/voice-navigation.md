---
title: "Voice navigation"
intro: "Navigation instructions and announcements"
versions: '*'
---
{% data reusables.general.article-not-complete %}

Receiving voice prompts during navigation: turn-by-turn insctructions, allerts, additional info.

## Settings of voice prompts

User can receive voice prompts during navigation. To enable voice prompts for app profiles, turn on or turn off voice prompts (You can also turn on or turn off voice prompts on [the icon of sound on the navigation screen](/osmand/navigation/route-navigation#navigation-options)):

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %} → {% data variables.android-values.routing_settings_2 %} → {% data variables.android-values.voice_announces %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.sett_settings %} → {% data variables.ios-values.app_profiles %} → {% data variables.ios-values.sett_settings %} → {% data variables.ios-values.routing_settings_2 %} → {% data variables.ios-values.voice_announces %}

![Voice Navigation settings Android](/assets/images/navigation/voice/voice_navigation_android.png) ![Voice Navigation settings iOS](/assets/images/navigation/voice/voice_navigation_ios.png)

- {% data variables.android-values.shared_string_on %}/{% data variables.android-values.shared_string_off %} - allows to configure to announce street names, traffic warnings, speed camera warnings, speed limits.
- {% data variables.android-values.shared_string_language %} - select preferred language and type of voice (for Android: TTS or recorded).
- {% data variables.android-values.accessibility_announce %} - allows to sound next types: {% data variables.android-values.speak_street_names %}, {% data variables.android-values.exit_number %}, {% data variables.android-values.way_alarms %}, {% data variables.android-values.speak_pedestrian %}, {% data variables.android-values.speak_cameras %}({% data variables.android-values.speed_cameras_alert %}), {% data variables.android-values.show_tunnels %}, {% data variables.android-values.shared_string_gpx_waypoints %}, {% data variables.android-values.speak_favorites %},  {% data variables.android-values.speak_favorites %}, {% data variables.android-values.speak_favorites %}. You can enable [Alert widget](/osmand/widgets/nav-widgets#alert-widget) for this categories.
- {% data variables.android-values.speak_speed_limit %} - allows to announce when exceeded {% data variables.android-values.speed_limit_exceed %}. Choose speed limit tolerance margin, above which you will receive a voice warning.

- {% data variables.android-values.shared_string_options %}: 

{% data variables.android-values.keep_informing %} - allows to re-announce navigation instructions at regular intervals or Only manually [(tap arrow)](/osmand/widgets/nav-widgets#next-turns).

{% data variables.android-values.announcement_time_title %} - the announcement timing of different voice prompts depends on prompt type, current navigation speed, and default navigation speed.

![Voice Navigation announcement timing Android](/assets/images/navigation/voice/voice_navigation_announcement_android.png)

- {% data variables.android-values.output %} (Android):

{% data variables.android-values.choose_audio_stream %} - allows to select loudspeaker for voice guidance: {% data variables.android-values.voice_stream_music %}, {% data variables.android-values.voice_stream_notification %}, {% data variables.android-values.voice_stream_voice_call %}.

{% data variables.android-values.interrupt_music %} - voice prompts pause music playback.

### Download voice prompts (Android)

For OsmAnd (Android version) you can download voice prompts files:

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.welmode_download_maps %} → {% data variables.android-values.other_location %} → {% data variables.android-values.index_name_tts_voice %} or {% data variables.android-values.index_name_voice %}


## TTS and recorded

If you select a TTS voice, you need to have a respective text-to-speech engine in your Android operating system. These are partly included in Android or can be installed separately. Please go to your Android (device) settings, find Language and keyboard / Text-to-speech output or similar. Select or install an engine, then also install the language support for the language you need, this may be an extra setting or small download.

Please test ('Listen to an example' or similar test button provided) if your Android TTS is working ok. Then you may also test if your OsmAnd voice prompts have been selected properly by going to Settings-> Plugins-> OsmAnd development-> Test voice prompts. (OsmAnd development plugin must be activated to see the setting). To disable voice prompts, please go to "Configure profile"-> "Navigation Settings"-> "Voice prompts"-> "Voice guidance" and select 'Do not use' option.

## How to use

## Testing of voice prompts (Android)