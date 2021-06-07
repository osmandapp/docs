---
title: "Points on the map"
intro: "On map you could display points such as Favorites, POI, Markers, Wikipedia, Search results, Audio Video Notes, OSM Edits"
versions: '*'
---
{% data reusables.general.article-not-complete %}

## Favorites

Enable / disable favorites on the map:

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_map %} → {% data variables.android-values.favorites_item %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.map_settings_map %} → {% data variables.ios-values.favorites %}

![Favotires layer](/assets/images/map/favorites_layer.png)


[Favorites](/osmand/personal/favorites) are special points marked by user and by default displayed as yellow star. Though it could be customized with any color, shape and icon. They become visible on the map from zoom level 6.

**Note** (Android): you could disable certain groups of favorites to be displayed on the map and during search:

{% data variables.android-values.shared_string_menu %} → My places  → Favorites → Select folder and press 'Show on the map'.


## Favorite / POI names

By default favorites and point of interests are displayed without name to not clutter map with text. You can enable names in Configure Map settings:

![Favotire labels layer](/assets/images/map/favorite_labels_layer.png) 

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_map %} → {% data variables.android-values.layer_amenity_label %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.map_settings_map %} → {% data variables.ios-values.layer_amenity_label %}.

## Points of interest (POI)

A [point of interest (POI)](https://en.wikipedia.org/wiki/Point_of_interest) is specific points that have been marked on the map as interesting or useful places/objects. [POI data](https://wiki.openstreetmap.org/wiki/Points_of_interest) has been taken from the OpenStreetMap project.

There are many types of POI. For example: 

- Churches, schools, town halls, distinctive buildings
- Post offices, shops, postboxes, telephone boxes
- Pubs (pub names are useful when navigating by map)
- Car parks and lay-bys (and whether free or not)
- Speed cameras
- Tourist attractions
- etc.

Each POI type in OsmAnd assigned a specific icon and color. POIs' [zoom level](/osmand/map/vector-maps#details) and design could be different in some [map styles](/osmand/map/vector-maps#default-map-styles).

![POI layer](/assets/images/map/poi_layer.png) ![POI layer topo style](/assets/images/map/poi_layer_topo_style.png)

You can find detailed information about the POI in the [Context menu](/osmand/map/map-context-menu) that appears after a [short tap](/osmand/map/map-context-menu#select-an-object-short-tap) on the point.

There are two kinds of POI in OsmAnd:
- Standard
- Customizable

They are identical in functionality and information availability. The only difference is that **standard** POI is set by default and may be partially displayed on the map depending on the style and rendering, **customizable**  POI is configurable POI types that display on the map as an overlay layer.

Standard POI has multicolored circles and could be [hidden](/osmand/map/vector-maps#hide) on the map in the {% data variables.android-values.configure_map %} menu.

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_map %} → {% data variables.android-values.map_widget_map_rendering %} → {% data variables.android-values.shared_string_hide %} 

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.map_settings_map %} → {% data variables.ios-values.map_settings_style %} → {% data variables.ios-values.rendering_category_hide %}

Customized POI - has orange circles that appear as an overlay on the map only when you select what  POI types should be displaying. 

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_map %} → {% data variables.android-values.layer_poi %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.map_settings_map %} → {% data variables.ios-values.poi_overlay %}

Chosen categories of POIs show from zoom level 9 on the map and have an orange circle.

**Note**: you can make your own [POI categories filters](/osmand/search/custom-poi-search) for choosing and showing it on the map.

![POI overlay Android](/assets/images/map/poi_overlay_Android.png) ![POI overlay iOS](/assets/images/map/poi_overlay_iOS.png)

## Markers

[Map markers](/osmand/personal/markers) are selected points marked as flags on the map. 

Enable/ disable markers on the map:

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_map %} → {% data variables.android-values.map_markers_item %} 

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.map_settings_map %} → {% data variables.ios-values.map_markers %}.

![Map markers Android](/assets/images/map/map_markers_Android.png) ![Map markers iOS](/assets/images/map/map_markers_iOS.png)

## Track points

One type of the points are track waypoints. 

[Track article](/osmand/map/tracks-on-map)
Redirect to track article

## Search results

- Description favorites on the map
- Description POI on the map
- Description Search results on the map

### Search results POI on the map

For searching POIs on the map you need to click to [Search button](/osmand/widgets/map-buttons#search) on the screen. Next you need to write name for searching, after than you can see searching results below.

The first seacrch result is categories, next - nearest POIs.

Click to "Show POI in the map" for showing POIs on the map.

![POI search](/assets/images/map/poi_search.png) ![POI search result](/assets/images/map/poi_search_result.png)

Click to "X" for switch off orange POI icons on the map.

Read more about Searching feature [here](/osmand/search).


**WIP Points of Plugins (delete)**

- Description Wikipedia  on the map + Link to Wikipedia plugin
- Description Audio / Video results on the map + link
- Description osm edits on the map + link
- Description osm notes on the map + link

## * Wikipedia points

Wikipedia feature has its own POIs on the map that has a full description for offline use. Read more how to download and use the Wikipedia feature in OsmAnd [here](osmand/plugins/wikipedia).

![Wikipedia POI](/assets/images/map/wikipedia_poi.png)

## * Audio / Video points

Audio / Video notes are user's made points with audio/photo/video data on the map. Read about this feature [here](/osmand/plugins/audio-video-notes).

![AV POI](/assets/images/map/av_poi.png)

## * OSM edit points 

OSM edit points are user's made POIs for adding its for [OpenStreetMap project](https://www.openstreetmap.org/). Read about this feature [here](/osmand/plugins/osm-editing).

![OSM edit POI](/assets/images/map/osm_edit_poi.png)

## * OSM notes 

OSM note points are user's made POIs for reporting issue about POI in [OpenStreetMap project](https://www.openstreetmap.org/). Read about this feature [here](/osmand/plugins/osm-editing#how-to-report-a-mistake).

![OSM note POI](/assets/images/map/osm_note_poi.png)

## Read more
  [Configure map menu](/osmand/map/configure-map-menu).
