---
title: "Search Address"
intro: "Finding the nearest location of a certain type, view your own location or search for a place by zip code"
versions: '*'
---
{% data reusables.general.article-not-complete %}


You may want to find the nearest location of a certain type, view your own location or search for a place by zip code. Just use the guide below.

**Please note:** to accomplish some of these tasks (locate addresses, POI, etc.) you will need to have the offline vector map file.

Address - for searching by an address. This tab for Android version offers 4 more options, for iOS version offers 2 options:

Street and City (you can enter city, street and building number step by step)
Postcode – for finding your location by a zipcode
Coordinate search – offers different coordinate formats.

## How to use

Clicking to [Search button on the screen](/osmand/widgets/map-buttons#search) -> {% data variables.android-values.shared_string_address %}

- [{% data variables.android-values.search_street %}](/osmand/search/search-address#search-street)
- [{% data variables.android-values.start_search_from_city %}](/osmand/search/search-address#search-citytownlocality)
- [{% data variables.android-values.select_postcode %}](/osmand/search/search-address#postcode-search)
- [{% data variables.android-values.coords_search %}](/osmand/search/search-address#coordinates-search)

### Search street

Street Searching by ["addr:street=*"](https://wiki.openstreetmap.org/w/index.php?title=Key:addr). Result: showing all streets with this name.

Clicking to chosen variant opens building list and crossroads.

Shown direction, distance to objects, categories of objects.

Tap to chosen address in the list opens [Map Context menu](/osmand/map/map-context-menu#select-an-object-short-tap) of the object.

![Search Street Android](/assets/images/search/street_search.png) ![Search Street Android](/assets/images/search/street_search_1.png)


### Search City/Town/Locality

City/Town/Locality Searching by ["addr:city/hamlet/town/village/suburb=*"](https://wiki.openstreetmap.org/w/index.php?title=Key:addr). Result: showing all objects with this name.

Clicking to chosen variant opens building list and crossroads.

Shown direction, distance to objects, categories of objects.

Tap to a object in the list opens [Map Context menu](/osmand/map/map-context-menu#select-an-object-short-tap) of the object.

![Search Street Android](/assets/images/search/town_search_android.png) ![Search Street iOS](/assets/images/search/town_search_ios.png)


### Postcode search

Postcode Searching by ["addr:city/hamlet/town/village/suburb=*"](https://wiki.openstreetmap.org/w/index.php?title=Key:addr). Result: showing all objects with postcode tag.

Clicking to chosen postcode opens objects list which have this postcode in tags.

Shown direction, distance to objects, categories of objects.

Tap to a object in the list opens [Map Context menu](/osmand/map/map-context-menu#select-an-object-short-tap) of the object with additional info about chosen postcode below the object name.

**Note:** [United Kingdom Poscode data](https://github.com/hvdwolf/OsmAnd-UKpostcodes/releases).

![Search Postcode Android](/assets/images/search/postcode_android.png) ![Search Postcode iOS](/assets/images/search/postcode_ios.png)


### Coordinates search

Coordinates Searching by [Geographical coordingates](https://en.wikipedia.org/wiki/Geographic_coordinate_system). Result: showing a point on the map.

{% data variables.android-values.coordinates_format %} - choose needed format for input or transform your coordinates:
- {% data variables.android-values.navigate_point_format_D %} - 50.12333  19.93233 (Lat Long).
- {% data variables.android-values.navigate_point_format_DM %} - 50:7.39320  19:55.93980 (Lat Long).
- {% data variables.android-values.navigate_point_format_DMS %} - 50:7:23.59200  19:55:56.38800 (Lat Long).
- {% data variables.android-values.navigate_point_format_utm %} - 34N 5552876  423678 (Zone Northing Easting).
- {% data variables.android-values.navigate_point_format_olc %} (OLC) - 9F2X4WFJ+7W (Open Location Code represents area 9m x 14m).
- {% data variables.android-values.navigate_point_mgrs %} - 34U DA 23678 52873.

Search result shows direction, distance to a point on the map.

Tap to the result opens [Map Context menu](/osmand/map/map-context-menu#select-any-point-long-tap) of a point on the map with additional info.

![Search Coordinates Android](/assets/images/search/coordinates_search_android.png) ![Search Coordinates iOS](/assets/images/search/coordinates_search_ios.png)