---
title: "Import / Export"
intro: "Import / Export"
versions: '*'
---

{% data reusables.general.article-not-complete %}

## Export

[Link](/osmand/personal/profiles#actions)

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %} → {% data variables.android-values.shared_string_actions %} → {% data variables.android-values.export_profile %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.sett_settings %} → {% data variables.ios-values.app_profiles %} → {% data variables.ios-values.actions %} → {% data variables.ios-values.export_profile %}

![Profiles Actions Settings Android](/assets/images/personal/profiles/profile_actions_settings_android.png) ![Profiles Actions Settings iOS](/assets/images/personal/profiles/profile_actions_settings_ios.png)

_________________

![Profiles Actions Export Android](/assets/images/personal/profiles/profile_actions_export_android.png) ![Profiles Actions Export iOS](/assets/images/personal/profiles/profile_actions_export_ios.png)

## Import

![Profiles Actions Import Android](/assets/images/personal/profiles/profile_actions_import_android.png) ![Profiles Actions Import iOS](/assets/images/personal/profiles/profile_actions_import_ios.png)
________


![Profiles Actions Import 1 Android](/assets/images/personal/profiles/profile_actions_import_1_android.png) ![Profiles Actions Import 1 iOS](/assets/images/personal/profiles/profile_actions_import_1_ios.png)

_______


![Profiles Actions Import 2 Android](/assets/images/personal/profiles/profile_actions_import_2_android.png) ![Profiles Actions Import 2 iOS](/assets/images/personal/profiles/profile_actions_import_2_ios.png)


## Reinstall 
Please note that most versions of Android also remove an app's data folder when you uninstall an app (or when in Android's App manager settings you tap 'Clear data' to reset the app settings to default). If no precaution is taken, this will for OsmAnd mean you **lose all downloaded maps as well as any stored Favorites, GPX tracks, etc.(!)**
On most systems the following procedure can be used to reset or uninstall/reinstall OsmAnd while preserving the original app data on the SD card:
-   Before any Uninstall or Clear data operation, **rename the app data folder**, e.g. from *net.osmand.plus* to *net.osmand.plus0*
-   Then either in the Android App manager force stop / clear cache / clear data to reset the app, or uninstall/reinstall OsmAnd, as desired
-   Start OsmAnd
-   On its 'First Start' screen tap: Get started `-> Change the data folder to the SD card -> Skip -> Skip downloading maps`
-   Force-stop OsmAnd
-   Using a file manager app, delete the newly created (almost empty) OsmAnd data folder, and rename your old (preserved) data folder back
-   Restart OsmAnd
-   Go to `Settings / Download maps`: Your existing offline maps should now be listed on tab Local. Go to the tab Update and tap the refresh icon, this should make OsmAnd finally aware maps are already present and can be used.


## Online sources
In order **to export** online map sources, you can select them in the export file list of your [application profile](/osmand/app-profile):

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %} → {% data variables.android-values.export_profile %} → {% data variables.android-values.select_data_to_export %} → {% data variables.android-values.shared_string_resources %} → {% data variables.android-values.quick_action_map_source_title %}  

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.sett_settings %} → choose your {% data variables.ios-values.app_profiles %} → {% data variables.ios-values.actions %} → {% data variables.ios-values.export_profile %}

In order **to import** online map sources, you can click to osf-file of application profile in your storage, messenger, mail and etc, that choose OsmAnd app for opening, select the data to be imported.

{% data variables.product.android_button_seq %}

A. {% data variables.android-values.shared_string_import %} → {% data variables.android-values.select_data_to_import %} → {% data variables.android-values.quick_action_map_source_title %} → {% data variables.android-values.shared_string_import_complete %} → {% data variables.android-values.shared_string_continue %} → {% data variables.android-values.shared_string_close %}

![Import package Android](/assets/images/plugins/online-maps/import-package-android.png)

B. You can click the SQLiteDb-file on your email, cloud, or messenger, download it and choose OsmAnd app to open. Map package is added automatically to your online maps list in OsmAnd.

![Import online source Android](/assets/images/plugins/online-maps/import-online-source-android.png)

{% data variables.product.ios_button_seq %}

A. {% data variables.ios-values.shared_string_import %} → {% data variables.ios-values.quick_action_map_source_title %} → {% data variables.ios-values.shared_string_continue %} → {% data variables.ios-values.shared_string_import_complete %} → {% data variables.ios-values.gpx_finish %}

![Import package iOS](/assets/images/plugins/online-maps/import-package-ios.png)

B. {% data variables.ios-values.menu %} → {% data variables.ios-values.map_settings_map %} → {% data variables.ios-values.map_settings_overunder %} → {% data variables.ios-values.import_from_docs %}

C. You can click the SQLiteDb-file on your email, cloud, or messenger, download it and choose OsmAnd app to open. Map package is added automatically to your online maps list in OsmAnd.

