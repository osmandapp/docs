---
title: "Global settings"
intro: "Common settings to all application profiles."
versions: '*'
---

## Global settings

Global settings are common to all application profiles. In fact, these settings are the settings of OsmAnd system.

{% default %}

{% enddefault %}

{% android %}

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.shared_string_settings %} → {% data variables.android-values.osmand_settings %}

![Profiles General Settings Android](/assets/images/personal/profiles/general_settings_android.png)

- {% data variables.android-values.settings_preset %} - select the profile, that will be used on application start (lase used or from profile list). Here you can choose "{% data variables.android-values.shared_string_last_used %}" profile. It means that the last chosen profile will be used for the application.

![General Settings Default profile Android](/assets/images/personal/profiles/general_settings_default_profile_android.png)

- {% data variables.android-values.preferred_locale %} - allows choosing the display language of OsmAnd menu.
- {% data variables.android-values.application_dir %} - allows [to change storage folder and to know OsmAnd usage memorу](/osmand/personal/storage#data-storage-folder-android).
- {% data variables.android-values.analytics_pref_title %} - allows collecting or not next anonymous usage data of OsmAnd: Maps downloaded, Screens visited. No data about your position or locations you view on the map are collected. [Privace Policy of OsmAnd](https://osmand.net/help-online/privacy-policy).

![General Settings Collected data Android](/assets/images/personal/profiles/general_settings_collected_data_android.png)

- {% data variables.android-values.dialogs_and_notifications_title %} - allows switching on/off popups, dialogs and notifications. It's [the download map dialog](/osmand/start-with/download-maps#download---map-zoom-in) and startp-up message (like promotion, quiz and etc.).

![General Settings notifications Android](/assets/images/personal/profiles/general_settings_notifications_android.png)

- {% data variables.android-values.shared_string_history %} - allows disabling history logging individually for each history type: [search history](/osmand/search/search-history), [navigation history](/osmand/navigation/route-navigation#history), [map markers history](/osmand/personal/markers#history). Here you can export history info a file, you can clear all history or for each categories ([search history](/osmand/search/search-history), [navigation history](/osmand/navigation/route-navigation#history), [map markers history](/osmand/personal/markers#history)).

![General Settings History Android](/assets/images/personal/profiles/general_settings_history_android.png)

- {% data variables.android-values.proxy_pref_title %} - allows configuring an HTTP proxy for all network requests. You can set Proxy Host and Proxy Port.

![General Settings Proxy Android](/assets/images/personal/profiles/general_settings_proxy_android.png)

- {% data variables.android-values.uninstall_speed_cameras %} - allows activating or not Speed camera POI's ([alert widget of speed camearas](/osmand/widgets/nav-widgets#alert-types)). In some countries or regions, the use of speed camera warning applications is prohibited by law. You need to make a choice depending on the law of your country.
Select "Keep active" and you will receive alerts and warnings about speed cameras.
Select "Uninstall". All data related to speed cameras: alerts, notifications, POIs will be deleted until OsmAnd is completely reinstalled.

![General Settings Cameras Android](/assets/images/personal/profiles/general_settings_cameras_android.png)

{% endandroid %}

{% ios %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.sett_settings %} → {% data variables.ios-values.osmand_settings %}

![Profiles General Settings iOS](/assets/images/personal/profiles/general_settings_ios.png)

- {% data variables.ios-values.settings_preset %} - select the profile, that will be used on application start (lase used or from profile list). Here you can choose "{% data variables.ios-values.last_used %}" profile. It means that the last chosen profile will be used for the application.

![General Settings Profile iOS](/assets/images/personal/profiles/general_settings_profile_ios.png)

- {% data variables.ios-values.carplay_profile %} - profile that will be used while connected to [CarPlay](https://support.apple.com/en-gb/HT205634).
- {% data variables.ios-values.do_not_show_discount %} - allows switching on/off popups, dialogs and notifications. It's [the download map dialog](/osmand/start-with/download-maps#download---map-zoom-in) and startp-up message (like promotion, quiz and etc.).

![General Settings Dialogs iOS](/assets/images/personal/profiles/general_settings_dialogs_ios.png)

- {% data variables.ios-values.send_anonymous_data %} - allows collecting or not next anonymous usage data of OsmAnd: Maps downloaded. No data about your position or locations you view on the map are collected. [Privace Policy of OsmAnd](https://osmand.net/help-online/privacy-policy).

{% note %}
Changing OsmAnd app language: iOS device -> Settings -> OsmAnd maps -> Language
{% endnote %}

{% endios %}


{% data reusables.general.article-not-complete %}

