---
title: "Public transport"
intro: "Public transport is an additional layer that allows you to display transport routes and stops on the map, to check detailed information about them and to navigate."
versions: '*'
---

{% data reusables.general.article-not-complete %}

## Transport Stops (Layer)

Enable/Disable Public transport layer:

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_map %} → {% data variables.android-values.rendering_category_transport %} → &#8230

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.map_settings_map %} → {% data variables.ios-values.rendering_category_transport %} → &#8230

![Public transport layer Android](/assets/images/map/pt_layer_android.png) ![Public transport layer iOS](/assets/images/map/pt_layer_ios.png) 

Choose between 1 or more transport categories for displaying:
- {% data variables.android-values.rendering_attr_transportStops_name %}
- {% data variables.android-values.rendering_attr_publicTransportMode_name %}
- {% data variables.android-values.rendering_attr_tramTrainRoutes_name %}
- {% data variables.android-values.rendering_attr_subwayMode_name %}

[Read more](/osmand/map/vector-maps#transport) about how transport is displayed on the map.

## Transport Routes (Context menu)

![Public transport Route menu Android](/assets/images/map/pt_routemenu_android.png) ![Public transport Route menu iOS](/assets/images/map/pt_routemenu_ios.png)

To open Transport menu, you can click on the the transport icon. It displays:
- Public transport coloured Shields (**clickable**)
- List of the routes stopping on that stop
- List of the nearby routes (within 150 m)
- Name of the stop and other [details](#transport-stop-details)

**Shield color**:
- Subway - own color line 
- Railway - brown
- Bus and other  - red
- Tram - blue,
- Trolleybus - purple


### Transport Stop details

**Update ios screenshot** 

![Public transport Route menu details Android](/assets/images/map/pt_routemenu_details_android.png) ![Public transport Route menu iOS](/assets/images/map/pt_routemenu_details_ios.png)

Clicking to {% data variables.android-values.rendering_category_details %} button or [Slide](/osmand/map/interact-with-map#gestures) up Context menu opens panel with additional information about the Public transport station. This menu includes:

- Bench
- Cover
- Wheelchair accessibility
- Operator name
- Coordinates
- Online photos
- OpenStreetMap link
- etc.

In the Android version, some tags can be helpful for search filters. For example, if you enter in the search area "Bench" then "Yes" you can see the list  the stops that have bench if you press 'Show on the map' all object with this tag will be [shown on the map](/osmand/map/point-layers-on-map#search-results-poi-on-the-map).


### Routes List 

In the Transport Routes list are all public transport routes that approach via selected stop and nearby routes (within 150m).

Each Route in the list has such information: color shield with the route number, route number, name of the selected station and end station,  public transport type icon and name, distance to the stop for nearby routes (within 150m).

![Public transport Routes Android](/assets/images/map/pt_routes_android.png) ![Public transport Routes iOS](/assets/images/map/pt_routes_ios.png) 

### Browse Route

If you click on the Route from the Route list or click on a shield in the Context menu on the map will display the route of this transport with all stops. In the Context menu will display the name of the stop, number of the transport route and the name of the start and end stops.

In this menu there are two additional buttons '{% data variables.android-values.shared_string_previous %}' and '{% data variables.android-values.shared_string_next %}' for moving between neighbor stops. By switching between stops you can see the name of the neighbor stop, number of the route and names of the start and end stops.

![Public transport Route Info Android](/assets/images/map/pt_route_info_android.png)  ![Public transport Route Info iOS](/assets/images/map/pt_route_info_ios.png) 

Clicking to {% data variables.android-values.rendering_category_details %} button or [Slide](/osmand/map/interact-with-map#gestures) up Context menu opens list of all stops for choosing route.

In this list, you can switch between stations (switching will be also displayed on the map) by clicking on the name of the stop. Selected stop is marked as 'location' icon on the Routes list (instead of transport icon).

![Public transport Route list Android](/assets/images/map/pt_route_list_android.png) ![Public transport Route list iOS](/assets/images/map/pt_route_list_ios.png) 

If you click {% data variables.android-values.get_directions %} button you will get a route from your current location to the selected Public Transport Station.

## Read more

- [Vector maps](osmand/map/vector-maps) 
- [Public transport navigation](/osmand/navigation/public-transport-navigation)
  
