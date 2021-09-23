---
title: "Voice navigation"
intro: "Receiving voice prompts during navigation"
versions: '*'
---
{% data reusables.general.article-not-complete %}

Receiving voice prompts during navigation: turn-by-turn insctructions, allerts, additional info.

## How to use

User can receive voice prompts during navigation. To receive them in your language, you 

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %}({% data variables.android-values.app_mode_boat %}) → {% data variables.android-values.routing_settings_2 %} → {% data variables.android-values.route_parameters %} → {% data variables.android-values.route_recalculation_dist_title %} and {% data variables.android-values.recalc_angle_dialog_title %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.sett_settings %} → {% data variables.ios-values.app_profiles %} ({% data variables.ios-values.app_mode_boat %}) → {% data variables.ios-values.sett_settings %} → {% data variables.ios-values.routing_settings_2 %} → {% data variables.ios-values.route_parameters %} → {% data variables.ios-values.recalculate_route %} and {% data variables.android-values.recalc_angle_dialog_title %}

 If you want your music to pause when scoring a route, in the same menu (Language and Output), turn on the “Pause music” option.


There are many settings for voice prompts on this screen. You can choose any variant for you.

You can turn off voice prompts if you don’t need them right now. To turn off voice prompts, go to the main menu "Configure profile"-> "Navigation settings"-> "Voice prompts". You can also turn on or turn off voice prompts on the icon of sound on the navigation screen.

## Download voice prompts

To set the language for voice prompts, go to the main menu-> then select the Navigation profile you want to configure "Configure profile"-> "Navigation Settings"-> "Voice prompts"-> "Voice guidance" and select your language. You can also get to the "Navigation Settings" menu for each Navigation profile through Main menu-> Settings-> App profiles-> choose profile. Note that you can't get to Navigation settings when you chose Browse map profile.

## Settings

If you select a TTS voice, you need to have a respective text-to-speech engine in your Android operating system. These are partly included in Android or can be installed separately. Please go to your Android (device) settings, find Language and keyboard / Text-to-speech output or similar. Select or install an engine, then also install the language support for the language you need, this may be an extra setting or small download.

Please test ('Listen to an example' or similar test button provided) if your Android TTS is working ok. Then you may also test if your OsmAnd voice prompts have been selected properly by going to Settings-> Plugins-> OsmAnd development-> Test voice prompts. (OsmAnd development plugin must be activated to see the setting). To disable voice prompts, please go to "Configure profile"-> "Navigation Settings"-> "Voice prompts"-> "Voice guidance" and select 'Do not use' option.