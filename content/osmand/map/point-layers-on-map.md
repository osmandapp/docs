---
title: "Points (Layers)"
intro: "On map you could display points such as Favorites, POI, Markers, Wikipedia, Search results, Audio Video Notes, OSM Edits"
versions: '*'
---
{% data reusables.general.article-not-complete %}

## Favorites on the map

Favorites are user's customized points that were added on the map. Favorite points have [GPX-format](/development/osmand-file-formats/osmand-gpx).

For adding Favorite on the map you need to make long tap on the map or short tap on any [ways](https://wiki.openstreetmap.org/wiki/Way) or [node](https://wiki.openstreetmap.org/wiki/Node) and choose [{% data variables.android-values.shared_string_actions %} -> {% data variables.android-values.favourites_context_menu_add %}](/osmand/map/map-context-menu#actions). 

How to create and modify Favorite read [here](/osmand/personal/myplaces).

**For showing Favorites on the map ** 

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_map %} → {% data variables.android-values.favorites_item %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.map_settings_map %} → {% data variables.ios-values.favorites %}

![Favotires layer](/assets/images/map/favorites_layer.png)

**In order to shown POI overlay labels (Favorites name)**

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_map %} → {% data variables.android-values.layer_amenity_label %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.map_settings_map %} → {% data variables.ios-values.layer_amenity_label %}

![Favotire labels layer](/assets/images/map/favorite_labels_layer.png)

## Points of interest (POIs) on the map

[A point of interest (POI)](https://en.wikipedia.org/wiki/Point_of_interest) is a specific point location that someone may find useful or interesting. [Data of POI](https://wiki.openstreetmap.org/wiki/Points_of_interest) is from OpenStreetMap project.

POIs have many types, some example:

- Churches, schools, town halls, distinctive buildings
- Post offices, shops, postboxes, telephone boxes
- Pubs (pub names are useful when navigating by map)
- Car parks and lay-bys (and whether free or not)
- Speed cameras
- Tourist attractions

In OsmAnd each type of POI has own icon and color. [Zoom level](/osmand/map/vector-maps#details) and style for POIs are different for some [map styles](/osmand/map/vector-maps#default-map-styles).

![POI layer](/assets/images/map/poi_layer.png)

Just to do short tap to POI for opening [Map Context menu](/osmand/map/map-context-menu#select-objects-on-map) and finding tag name, POI name and other useful information about POI.

![POI info menu](/assets/images/map/poi_info_menu.png)

**In order to shown POI overlay (Selected POI type)**

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_map %} → {% data variables.android-values.layer_poi %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.map_settings_map %} → {% data variables.ios-values.poi_overlay %}


## Search results on the map

- Description favorites on the map
- Description POI on the map
- Description Search results on the map
# Plugins 
- Description Wikipedia  on the map + Link to Wikipedia plugin
- Description Audio / Video results on the map + link
- Description osm edits on the map + link
- Description osm notes on the map + link

- Update links in Configure Map
