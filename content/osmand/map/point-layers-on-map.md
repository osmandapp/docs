---
title: "Points (Overlay layer)"
intro: "On map you could display points such as Favorites, POI, Markers, Wikipedia, Search results, Audio Video Notes, OSM Edits"
versions: '*'
---
{% data reusables.general.article-not-complete %}

## Favorites

Favorites are points marked by user on the map. Favorite points have [GPX-format](/development/osmand-file-formats/osmand-gpx).

In order to mark point as favorite you need to make long tap on the map or short tap on any [ways](https://wiki.openstreetmap.org/wiki/Way) or [node](https://wiki.openstreetmap.org/wiki/Node) and in the [Context menu](/osmand/map/map-context-menu) choose [{% data variables.android-values.shared_string_actions %} -> {% data variables.android-values.favourites_context_menu_add %}](/osmand/map/map-context-menu#actions). 

Detailed information on how to create and modify Favorite you can read [here](/osmand/personal/myplaces).

### Configure favorites visibility

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_map %} → {% data variables.android-values.favorites_item %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.map_settings_map %} → {% data variables.ios-values.favorites %}

**Note**: you can select what favorites you would like to display on the map. 

Menu → My places → Favorites → Show on the map selected folder.

Favorites are become visible on the map from zoom level 6.

![Favotires layer](/assets/images/map/favorites_layer.png)

You can turn on display Favorite names: {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_map %} → {% data variables.android-values.layer_amenity_label %}

![Favotire labels layer](/assets/images/map/favorite_labels_layer.png) 

## Points of interest (POI)

[A point of interest (POI)](https://en.wikipedia.org/wiki/Point_of_interest) is specific interesting or useful places and objects that have been marked on the map. [POI data](https://wiki.openstreetmap.org/wiki/Points_of_interest) have been taken from the OpenStreetMap project.

### POI categories and types
There are many types of POI. For example: 

- Churches, schools, town halls, distinctive buildings
- Post offices, shops, postboxes, telephone boxes
- Pubs (pub names are useful when navigating by map)
- Car parks and lay-bys (and whether free or not)
- Speed cameras
- Tourist attractions

Each POI type in OsmAnd assigned a specific icon and color. POIs' [zoom level](/osmand/map/vector-maps#details) and design could be different in some [map styles](/osmand/map/vector-maps#default-map-styles).

![POI layer](/assets/images/map/poi_layer.png) ![POI layer topo style](/assets/images/map/poi_layer_topo_style.png)

In order to see information about POI you need to make a [short tap](/osmand/map/map-context-menu#select-an-object-short-tap) on the POI icon. The [Context menu](/osmand/map/map-context-menu) will provide you with information about POI:
- Name
- Address
- Distance from your current position
- Icon

### Configure POI visibility 

You can find two kinds of POI in OsmAnd:
-  Default POI - are multicolored circles with specific signs inside that always visible on the map and could be manually hidden. [Hide](/osmand/map/vector-maps#hide)

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_map %} → {% data variables.android-values.map_widget_map_rendering %} → {% data variables.android-values.shared_string_hide %} 

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.map_settings_map %} → {% data variables.ios-values.map_settings_style %} → {% data variables.ios-values.rendering_category_hide %}

- Customized POI - are orange circles that appear as an overlay on the map only when you select what  POI types should be displaying. 

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_map %} → {% data variables.android-values.layer_poi %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.map_settings_map %} → {% data variables.ios-values.poi_overlay %}

Chosen categories of POIs show from zoom level 9 on the map and have an orange circle. 

![POI overlay](/assets/images/map/poi_overlay.png)

**Note**: you can make your own [POI categories filters](/osmand/search/custom-poi-search) for choosing and showing it on the map.

## Search results on the map

- Description favorites on the map
- Description POI on the map
- Description Search results on the map

### Favorites search result

You can search and display on the map your favorite points.

When you need to find  on the map point from your favorites, you need to:
- Enable 'Show on the map' folder with a needed point inside.
- Enter the name of the point in the search area
- Select needed point from the list 

(For searching Favorites on the map you need to click to [Search button](/osmand/widgets/map-buttons#search) on the screen. After writing Favorite name you see search results below . Clicking to chosen Favorite opens [Map Context menu](/osmand/map/map-context-menu) of Favorite.)

![Favorite search](/assets/images/map/favorite_search.png) ![Favorite search result](/assets/images/map/favorite_search_result.png)

### Search results POI on the map

For searching POIs on the map you need to click to [Search button](/osmand/widgets/map-buttons#search) on the screen. Next you need to write name for searching, after than you can see searching results below.

The first seacrch result is categories, next - nearest POIs.

Click to "Show POI in the map" for showing POIs on the map.

![POI search](/assets/images/map/poi_search.png)

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
