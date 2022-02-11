---
title: "Search POI"
intro: ""
versions: '*'
---
{% data reusables.general.article-not-complete %}

Point of interesting (POI) seaching is one the general function of OsmAnd. [POI](https://wiki.openstreetmap.org/wiki/Points_of_interest) is any object on the map. How you know OsmAnd uses data from [OpenStreetMap](http://openstreetmap.org/).

**Please note:** to accomplish some of these tasks (locate addresses, POI, etc.) you will need to have the offline vector map file. Initially, the search is based on data located on the map in the visible area of the device screen. If you don't find nothing, OsmAnd propose to increase search radius.

## How to use

For starting search points you need to click to [Search button on the screen](/osmand/widgets/map-buttons#search) -> {% data variables.android-values.search_categories %}

Categories screen is list of POI categories and additional actions buttons below of the list:

![Search POI list Android](/assets/images/search/poi_list_android.png) ![Search POI list iOS](/assets/images/search/poi_list_ios.png)

Actions button:
- {% data variables.android-values.search_online_address %} (Android) - allows to use [online POI search](/osmand/search/search-poi#online-search-android).
- {% data variables.android-values.custom_search %} / {% data variables.ios-values.add_custom_category %} - allow to create [custom POI search and custom POI filter](/osmand/search/custom-poi-search).
- {% data variables.android-values.rearrange_categories %} - allows to change the list order and hide categories. [Import or export all changes as profiles](/osmand/personal/import-export).
- {% data variables.ios-values.delete_custom_categories %} - allows to delete [custom categories](/osmand/search/custom-poi-search).


### POI search

In Categories menu user can start searching by typping line.

OsmAnd starts to find names and categories of POI by entered words. First results will be categories, second resolts will be POI with additional info (full name, categorie name, direction and distance to POI, work time). Pressing to needed categorie opens POI list of this categorie. 

Tapping to chosen POI in the list opens [Map Context menu](/osmand/map/map-context-menu#select-an-object-short-tap) of POI.

![Search POI Android](/assets/images/search/poi_search_android.png) ![Search POI iOS](/assets/images/search/poi_search_ios.png)

Tapping to "{% data variables.android-values.shared_string_show_on_map %}" button allows [to show search results on the map like POI-overlay](/osmand/map/point-layers-on-map#points-of-interest-poi). It will be easy to find your places on the map, you can write search word on searching field or click to "x" for stopping your search and switch off POI-overlay. 

Enable / disable POI layer on the map:

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_map %} → {% data variables.android-values.layer_poi %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.configure_map %} → {% data variables.ios-values.poi_overlay %}

![POI overlay Android](/assets/images/search/poi_overlay_android.png) ![Search POI iOS](/assets/images/search/poi_overlay_ios.png)


### Favorite/Waypoint search

In this search menu (Categories) it's easy way to find your [Favorites](/osmand/map/point-layers-on-map#favorites) and [Waypoints](/osmand/map/point-layers-on-map#track-points) by searching. 

Just you need to enter your favorite/waypoint name, first results will be your favorites/waypoints.

![Favorite search Android](/assets/images/search/favorite_search_android.png) ![Favorite search iOS](/assets/images/search/favorite_search_ios.png)

### Online search (Android)

In [Categories menu](/osmand/search/search-poi#how-to-use) there is the button "Online search". Pressing to this button opens online search menu.

![Online search Android](/assets/images/search/online_search_android.png)

If OsmAnd can not find something you can increase search radius by tapping to "Increase search radius" button.

Or if you don't have any result you can provide feedback by clicking to "Send" button below device screen.

![Online search feedback Android](/assets/images/search/online_search_feedback_android.png)