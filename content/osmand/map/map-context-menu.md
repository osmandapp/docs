---
title: "Map Context menu"
intro: "How to select an object on the map, open context menu with long or short tap, get detailed information about point of intereset, navigate from and to the point and perform other actions"
versions: '*'
---
{% data reusables.general.article-not-complete %}

## Select objects on map

Taping to the map in OsmAnd we can select an object or point on the map and open Point Context menu. There are two actions of tap: short and long.

| |  |
|:------------|:---------------|
|**Short tap**| Selected only an object which has [a node](https://wiki.openstreetmap.org/wiki/Node) or [a way](https://wiki.openstreetmap.org/wiki/Way) with showing name and address of an object, distance and direction from current location to an object. Icon: showed POI icon on Point Context menu. |
|Android:![Context menu short_tap_Android](/assets/images/map/map_context_menu_short_tap_android.png) | iOS:![Context menu short_tap_iOS](/assets/images/map/map_context_menu_short_tap_ios.png)  |
|**Long tap**| Selected geographical point with info about address of the nearest place, distance and direction (Android) from current location to this point. Icon: showed Location icon on Point Context menu. |
|Android:![Context menu long_tap_Android](/assets/images/map/map_context_menu_long_tap_android.png) | iOS:![Context menu long_tap_iOS](/assets/images/map/map_context_menu_long_tap_ios.png)  |


## Detailed information

Click to "Details" button on Context point menu or move up Context point menu for opening Detailed information.

|Detail | Description |
|:------------|:---------------|
|Android:![Context menu details_Android](/assets/images/map/map_context_menu_details_android.png) | iOS:![Context menu details_iOS](/assets/images/map/map_context_menu_details_ios.png)  |
|Tag info| Additional info about an object: telefon, website, POI type, work time, height, .... |
|Nearby Wikipedia articles| Anothers Wikipedia articles |
|Nearby POI| POI |
|OSM link| Object link to OSM: https://www.openstreetmap.org/node... or https://www.openstreetmap.org/way... |
|Coordinates info| Geographical coordinates of an object |
|Online photos| Photos from Mappillary, OpenPlaceReviews, Wikimedia |

## Actions

Actions on Context Point menu

|Detail | Description |
|:------------|:---------------|
|Add|  |
|Share| |
|Map marker|  |
|Actions| additional menu of actions |
|Directons from|  |
|Search nearby| |

### Navigation 

Button "Directions"

## Customize context menu (Android, advanced)

It is a menu where the user can reorder or hide items from the 'Context menu actions', to see hidden items from the menu, copy the list of items from the another profile and reset to default settings.

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %} → {% data variables.android-values.ui_customization %} → {% data variables.android-values.context_menu_actions %}

![Context menu actions items ](/assets/images/settings/context_menu_actions_items.png)

 All settings will apply to the 'Browse map' profile by default. User can reset settings to default or copy from another profile.
