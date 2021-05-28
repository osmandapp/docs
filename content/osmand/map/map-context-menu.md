---
title: "Map Context menu"
intro: "'Map Context menu' provides information of selected object on the map and allows to share, to edit, to move or to navigate to this place."
versions: '*'
---
{% data reusables.general.article-not-complete %}

## Context menu 
In order to open Context menu you should tap on the object or place on the Map. There are two types of action: by short tap, by long tap.

### Select an object (short tap)
Context menu will appear when you **short tap** on the marked object on the Map. In this case context menu provides you with the information of the POI name, icon (how it marked on the map),  address, distance and direction from the current position.

**Note**: This only applies to objects that have [a node](https://wiki.openstreetmap.org/wiki/Node) or [a way](https://wiki.openstreetmap.org/wiki/Way).

![Context menu Android](/assets/images/map/map_context_menu_short_tap_android.png)  ![Context menu iOS](/assets/images/map/map_context_menu_short_tap_ios.png) 

### Select any point (long tap)
Context menu will appear  when you hold  the any point on the Map with **long tap**. In this case context menu provides you with the information of georraphical point address , distance and direction from the current position and as icon is the location mark. 

![Context menu long_tap_Android](/assets/images/map/map_context_menu_long_tap_android.png) ![Context menu long_tap_iOS](/assets/images/map/map_context_menu_long_tap_ios.png)  |

### Hide context menu

To hide the context menu, just click on any place on the map.

### Object information


## Details
In order to gain more details about object you need to click on the "Details" button in the Context menu or move this panel up. 

![Context menu details_Android](/assets/images/map/map_context_menu_details_android.png) 
![Context menu details_iOS](/assets/images/map/map_context_menu_details_ios.png)

|**Detail** | **Description** |
|:---------------|:---------------|
|[Tag info](https://taginfo.openstreetmap.org/)| Additional information about the object: phone number, website, POI type, work time, height... Click on the description for opening full information, copy to buffer, open website link and others. |
|[{% data variables.android-values.wiki_around %}](/osmand/plugins/wikipedia)| Nearby Wikipedia articles. Click the description for opening Wikipedia POIs list and the button '{% data variables.android-values.shared_string_show_on_map %}' for showing another Wikipedia POIs.|
|[{% data variables.android-values.speak_poi %}](https://wiki.openstreetmap.org/wiki/Points_of_interest)| Anothers POIs nearby chosen point. Click to description for opening POIs list and the button {% data variables.android-values.shared_string_show_on_map %} for showing another POIs near chosen point. |
|OSM link| Object link to 0penStreetMap source: https://www.openstreetmap.org/node... or https://www.openstreetmap.org/way... |
|Coordinates info| Geographical coordinates of an object. Click to the description for opening coordinates types with copy it to buffer.|
|Online photos| Photos from [Mappillary](/osmand/plugins/mapillary), [OpenPlaceReviews](/osmand/plugins/openplacereviews), [Wikimedia](https://www.wikimedia.org/) sources. Click to image for opening image resource. |

## Actions

### Directions
You can easily get a route from your location to the selected point (or reverse) by clicking the 'Direction' button in the context menu. 
### Share
You can share a selected point or object with another user by simply tap on the share icon in the Context menu.
### Search

### * Create POI


In the table below there are all "Actions" of "Map Context menu" for chosen point on the map. 

|Detail | Description |
|:---------------|:---------------|
|{% data variables.android-values.favourites_context_menu_add %}| [Opening {% data variables.android-values.favourites_context_menu_add %} menu and creating new favorite](/osmand/personal/favourites).  |
|{% data variables.android-values.shared_string_share %}| Opening {% data variables.android-values.share_menu_location %} menu. For iOS: you can send URL of the point location to your contacts. For Android: sendig URL of the point location to your contacts, coping URL of the point location in buffer, {% data variables.android-values.copy_address %}, {% data variables.android-values.copy_poi_name %}, {% data variables.android-values.copy_coordinates %}, opening point in others applications, making {% data variables.android-values.shared_string_qr_code %}. |
|{% data variables.android-values.shared_string_marker %}| Activating [Map marker](/osmand/personal/markers) in chosen point. |
|{% data variables.android-values.shared_string_actions %}| Opening hidden buttons of actions menu. |
|{% data variables.android-values.context_menu_item_directions_from %}| Making the chosen point like Start point for navigation. |
|{% data variables.android-values.context_menu_item_search %}| Opening seach menu and start seaching near the chosen point.|
|{% data variables.android-values.context_menu_item_add_parking_point %}| Making the chosen point like [Parking position](/osmand/plugins/parking). |
|{% data variables.android-values.context_menu_item_add_waypoint %}| Opening tracks list for making the point like a waypoint for the chosen track.|
|{% data variables.android-values.context_menu_item_create_poi %}| [Adding POI in chosen place on OpenStreetMap](/osmand/plugins/osm-editing).|
|{% data variables.android-values.context_menu_item_open_note %}| [Editing POI of OpenStreetMap data](/osmand/plugins/osm-editing).|
|{% data variables.android-values.shared_string_download_map %}| [Downloading tiles of a raster map for offline using](/osmand/map/raster-maps#download--update-tiles).|
|{% data variables.android-values.update_tile %}| [Updating tiles of a raster map ](/osmand/map/raster-maps#download--update-tiles).|
|{% data variables.android-values.change_markers_position %} (Android)| [Moving the map marker to new location](/osmand/personal/markers).|
|{% data variables.android-values.recording_context_menu_arecord %} (Android)| [Making audio point on the map](/osmand/map/point-layers-on-map#audio--video-notes-on-the-map).|
|{% data variables.android-values.recording_context_menu_vrecord%} (Android)| [Making video point on the map](/osmand/map/point-layers-on-map#audio--video-notes-on-the-map).|
|{% data variables.android-values.recording_context_menu_precord %} (Android)| [Making photo point on the map](/osmand/map/point-layers-on-map#audio--video-notes-on-the-map).|
|{% data variables.android-values.plan_a_route %} (Android)| [Opening "Plan a route" tool with chosen first point](/osmand/plan-route/create-route).|
|{% data variables.android-values.avoid_road %} (Android)| [Adding avoid point for navigation](/osmand/navigation/route-navigation).|


## Customize (Android advanced)

It is a menu where the user can reorder or hide items from the 'Context menu actions', to see hidden items from the menu, copy the list of items from the another profile and reset to default settings. 

Android users can reset to default configuration of the Context menu or copy configuration of the Context menu from another profile.

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %} → {% data variables.android-values.ui_customization %} → {% data variables.android-values.context_menu_actions %}

![Context menu actions items ](/assets/images/map/customize_actions_menu.png)

 
