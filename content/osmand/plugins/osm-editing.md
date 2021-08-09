---
title: "{% data variables.android-values.osm_settings %}"
intro: "Make contributions to OpenStreetMap."
versions: '*'
---


{% data reusables.general.article-not-complete %}


{% data variables.android-values.osm_editing %} plugin allows you to make contributions to OpenStreetMap, a global community aimed at creating a comprehensive map of the world and providing up-to date open-source data to every user.

Just launch OsmAnd Maps & Navigation app and update the information about different locations.

Make OSM contributions like creating or modifying OSM POI objects, opening or commenting OSM notes, and contributing recorded GPX files in OsmAnd by supplying your username and password. [OpenStreetMap](http://openstreetmap.org/) is a community driven, global public domain mapping project.


## Enable / Disable plugin

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.plugins_menu_group: %} → {% data variables.android-values.osm_settings %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.plugins %} → {% data variables.ios-values.product_title_osm_editing %}

![OpenStretMap editing Android](/assets/images/plugins/osm-editing/osm_plugin_android.png)  ![OpenStretMap editing](/assets/images/plugins/osm-editing/osm_plugin_ios.png)

### Plugin settings (Android)

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.plugins_menu_group: %} → {% data variables.android-values.osm_settings %} → {% data variables.android-values.shared_string_settings %}

![OpenStretMap editing plugin Settings Android](/assets/images/plugins/osm-editing/osm_plugin_settings_android.png)

Next settings:
- {% data variables.android-values.login_account %} - {% data variables.android-values.open_street_map_login_mode %} 
- {% data variables.android-values.offline_edition %} - enable or disable offline editing.
- {% data variables.android-values.use_dev_url %} - enable or disable [dev.openstreetmap.org](https://dev.openstreetmap.org/) instead of [openstreetmap.org](http://openstreetmap.org/) to testing uploading OSM Note / POI / GPX.
- {% data variables.android-values.map_updates_for_mappers %} - allows [OsmAnd live](/osmand/personal/maps#osmand-live) updating for mappers.

![OpenStretMap editing plugin Settings OsmAnd live Android](/assets/images/plugins/osm-editing/osm_plugin_settings_live_android.png)

- {% data variables.android-values.layer_osm_edits %} - allows to open OSM edits menu: [Menu → My Places → OSM edits](/osmand/personal/myplaces)  



## How to use

The plugin lets you create new objects, so-called  [points of interest or POI](/osmand/map/point-layers-on-map#points-of-interest-poi)  on the map. New shop opened next to you? Add it to the map! Your favorite monument is missing on the map? Put it there in seconds. Also, if you're the owner of a newly-opened business, adding it to the map is a great way to let people find you.

### How to add / modify POI

Tap on the map where the new POI has to be placed. Press on **{% data variables.android-values.shared_string_actions %}**, then choose **{% data variables.android-values.context_menu_item_create_poi %}**, add its name and other details like working hours, website, etc. You'll also have to register at {% data reusables.links.osm %} and then provide your OSM credentials to introduce changes.

[Actions in Map Context menu](/osmand/map/map-context-menu#actions) - [Create / Modify POI](/osmand/map/map-context-menu#-create--modify-poi)


{% note %}
Note: you can see your new POI on OsmAnd map after one hour after added it to OSM project if you have [OsmAnd live](/osmand/personal/maps#osmand-live).
{% endnote %}

### How to upload GPX track

You can add the tracks you've made to {% data reusables.links.osm %}. To do that, turn the [Trip recording plugin](/osmand/plugins/trip-recording) on, record a track, and then go to My places-> Tracks-> press the ![OpenStretMap editing](/assets/images/icons/android/ic_action_export.svg) button. Choose the required track and click _Yes_. You can change description, tags or visibility of the track. 

Kindly note, that {% data variables.android-values.osm_editing %} has to be turned on. 
In an hour, your track will be added to [https://www.openstreetmap.org/traces](https://www.openstreetmap.org/traces), so you can view it and other users can find it helpful, as well. 

You can participate in the work on the global map. Just share the tracks you've made. They become part of the {% data reusables.links.osm %} project. Make sure you tag objects and roads as well.


### How to report a mistake

You can also report about the mistakes on the map. All you have to do is tap on the location, choose **{% data reusables.plugins.osm-editing-android-add-osm-note %}** and then add the info about it. OSM editors would consider your comments.

![Open OSM Note](/assets/images/plugins/osm-editing/open-osm-note.png)

To view the OSM editing layer, go to **{% data reusables.configure-map.osm-note-layer-enable-android %}**. You'll see all the notes in the specific area. You can click to OSM note and choose your comment or delete it.
