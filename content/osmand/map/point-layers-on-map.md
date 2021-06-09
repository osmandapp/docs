---
title: "Points on the map"
intro: "On map you could display points such as Favorites, POI, Markers, Wikipedia, Search results, Audio Video Notes, OSM Edits"
versions: '*'
---

{% data reusables.general.article-not-complete %}

## Favorites

[Favorites](/osmand/personal/favorites) are special points marked by user and by default displayed as yellow star. Though it could be customized with any color, shape and icon. They become visible on the map from the zoom level 6.

![Favotires layer](/assets/images/map/favorites_layer.png)

Enable / disable favorites on the map:

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_map %} → {% data variables.android-values.favorites_item %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.configure_map %} → {% data variables.ios-values.favorites %}

**Note** (Android): you could disable certain groups of favorites to be displayed on the map and during search - {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.shared_string_my_places %}  →  {% data variables.android-values.shared_string_favorites %} → Select folder and press '{% data variables.android-values.shared_string_show_on_map %}'.


## Favorite / POI names

By default favorites and point of interests are displayed without name to not clutter map with text. You can enable names in {% data variables.android-values.shared_string_configure_map %}  settings.

![Favotire labels layer](/assets/images/map/favorite_labels_layer.png) 

Enable / disable POI overlay labels on the map:

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_map %} → {% data variables.android-values.layer_amenity_label %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.configure_map %} → {% data variables.ios-values.layer_amenity_label %}


## Points of interest (POI)

[Points of interest (POI)](https://en.wikipedia.org/wiki/Point_of_interest) are specific points highlighted with an icon on the map. They represent interesting or useful places & objects and they are part of [Vector Maps](/osmand/map/vector-maps). Most prominent points of interest are displayed on the map automatically, though you could select specific type of POI (i.e. Restaurants) and they will be all highlighted on the map within an **orange circle** (from zoom level 9). You can find detailed information about point of interest in the [Context menu](/osmand/map/map-context-menu) that appears on a [short tap](/osmand/map/map-context-menu#select-an-object-short-tap) on the point.

![POI overlay Android](/assets/images/map/poi_overlay_Android.png) ![POI overlay iOS](/assets/images/map/poi_overlay_iOS.png)

Enable / disable points of interest of **selected** type on the map:

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_map %} → {% data variables.android-values.layer_poi %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.configure_map %} → {% data variables.ios-values.poi_overlay %}

### POI Types

You can select one or many from standard OsmAnd POI types or make your own [POI filter](/osmand/search/custom-poi-search) and select it to display POI on the map.

![Single POI Selection](/assets/images/map/single_selection_Android.png) ![Multiple POI Selection](/assets/images/map/multiple_selection_Android.png)

**Android**: to switch between single and multiple POI selection click the lower left button.

### Map style POI

Each POI type in OsmAnd assigned a specific icon and color. POIs' [zoom level](/osmand/map/vector-maps#details) and design could be different in some [map styles](/osmand/map/vector-maps#default-map-styles).

![POI on map style](/assets/images/map/poi_layer.png) ![POI on topo style](/assets/images/map/poi_layer_topo_style.png)

Hide POIs from map style:

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_map %} → {% data variables.android-values.map_widget_map_rendering %} → {% data variables.android-values.shared_string_hide %} 

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.map_settings_map %} → {% data variables.ios-values.configure_map %} → {% data variables.ios-values.rendering_category_hide %}

[Read more](/osmand/map/vector-maps#hide).

## Markers

[Map markers](/osmand/personal/markers) are special points marked as flags on the map. You can customize their look & feel with **arrows** ({% data variables.android-values.show_arrows_on_the_map %}) and **distance indication** ({% data variables.android-values.show_direction %}). 

![Map markers Android](/assets/images/map/map_markers_Android.png) ![Map markers iOS](/assets/images/map/map_markers_iOS.png)

Enable / disable markers on the map:

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_map %} → {% data variables.android-values.map_markers_item %} 

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.configure_map %} → {% data variables.ios-values.map_markers %}

[Read more](/osmand/widgets/markers#configure-marker-widgets-and-marker-appearance) about marker appearance.

## Track points

Track points (waypoints) are points that are part of Track (GPX) files. These points displayed automatically if track is displayed on the map. They look & could be configured similar to [Favorites](#favorites) - icon, names, color, shape.

![Track on map](/assets/images/map/track_point_on_map.png)

[Read more](/osmand/map/tracks-on-map) about tracks on the map.


## Search results (POI)

Search results could be displayed on the map as a special POI layer. During search click on a special row (**{% data variables.android-values.shared_string_show_on_map %}**) to display POIs on the map.

![POI search](/assets/images/map/poi_search.png) ![POI search result](/assets/images/map/poi_search_result.png)

To switch off POIs, hit "X" on the top right corner.

Read more about [search](/osmand/search).

## * Street-level imagery

[Street-level imagery (Mapillary)](https://docs.osmand.net/en/main@latest/osmand/plugins/mapillary) are green points on the map. Street-view photos attached to these points. You can create a filter and select what photos you would like to display on the map. In order to open street-view photo you need to press on the green point.

![Mapillary filter](/assets/images/map/mapillary_filter.png) ![Mapillary street view](/assets/images/map/mapillary_street-view.png)

Enable / disable Street-level imagery on the map: 

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_map %} → {% data variables.android-values.street_level_imagery %} 

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.configure_map %} → {% data variables.ios-values.street_level_imagery %}

Requires [Mapillary plugin](/osmand/plugins/mapillary)

## * Wikipedia

OsmAnd has special Point of Interests indicated with 'W' logo and Wikipedia articles attacheted to it. These points could be displayed exactly as any other POI type via Search or {% data variables.android-values.configure_map %} → {% data variables.android-values.layer_poi %}, though there is a special way to filter Wikipedia articles by **available languages**.

![Wikipedia on map](/assets/images/map/map-wikipedia-on-map.png) ![Wikipedia language - iOS](/assets/images/map/map-wikipedia-language-ios.png)

Enable / disable wikipedia articles on the map and filter by language:

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_map %} → {% data variables.android-values.shared_string_wikipedia %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.configure_map %} → {% data variables.ios-values.poi_overlay %} → {% data variables.ios-values.res_wiki %} 

[Read more](osmand/plugins/wikipedia) how to download and use the Wikipedia feature in OsmAnd.

## * Audio / Video points (Android)

Audio / Video notes are user's made points with audio/photo/video data on the map. 

![AV POI](/assets/images/map/av_poi.png)

Enable / disable recording points on the map:

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_map %} → {% data variables.android-values.layer_recordings %}

Requires [Audio / Video note plugin](/osmand/plugins/audio-video-notes).

## * OSM edit points 

OSM edit points are user's made POIs for adding its for [OpenStreetMap project](https://www.openstreetmap.org/).

![OSM edit POI](/assets/images/map/osm_edit_poi.png)

Enable / disable OSM edits on the map:

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_map %} → {% data variables.android-values.osm_edits %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.configure_map %} → {% data variables.ios-values.osm_edits_title %} 

Requires [OSM Editing plugin](/osmand/plugins/osm-editing).

## * OSM notes 

TODO more text about context menu with screenshots.

OSM note points are user's made POIs for reporting issue about map data in [OpenStreetMap](https://www.openstreetmap.org/). New note (not uploaded to OpenStreetMap) is marked as green with '+', closed note is marked as green with 'v', open note is marked as red.

![OSM notes](/assets/images/map/osm_note.png)

Enable / disable OSM notes on the map:

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_map %} → {% data variables.android-values.layer_osm_bugs %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.configure_map %} → {% data variables.ios-values.osm_notes_online_layer %} 

Requires [OSM Editing plugin](/osmand/plugins/osm-editing#how-to-report-a-mistake).

## Read more
  [Configure map menu](/osmand/map/configure-map-menu).
