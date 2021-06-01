---
title: "Public transport"
intro: "Explore public transport routes / stops on the map."
versions: '*'
---
{% data reusables.general.article-not-complete %}

## Transport Stops (Layer)

Detailed info about Public transport layer on the map read [here](/osmand/map/vector-maps#transport).


| Android | iOS |
| :--- | :--- |
| Enable/Disenable Public transport layer.| Enable/Disenable Public transport layer. |
|{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_map %} → {% data variables.android-values.rendering_category_transport %} → &#8230 → Choosing types of categories for displayed: {% data variables.android-values.rendering_attr_transportStops_name %}; {% data variables.android-values.rendering_attr_publicTransportMode_name %}; {% data variables.android-values.rendering_attr_tramTrainRoutes_name %}; {% data variables.android-values.rendering_attr_subwayMode_name %} | {% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.map_settings_map %} → {% data variables.ios-values.rendering_category_transport %} → &#8230 → Choosing types of categories for displayed: {% data variables.ios-values.rendering_attr_publicTransportMode_name %}; {% data variables.ios-values.rendering_attr_subwayMode_name %}; {% data variables.ios-values.rendering_attr_tramTrainRoutes_name %}; {% data variables.ios-values.rendering_attr_transportStops_name %}  |
|   ![Public transport layer Android](/assets/images/map/pt_layer_android.png) | ![Public transport layer iOS](/assets/images/map/pt_layer_ios.png) |

## Transport Routes (Context menu)

Clicking on a point {% data variables.android-values.rendering_attr_transportStops_name %} on the map opens Public transport Routes information in Map Context menu.

Here we can find the name of public stop, an icon of public transport type for this stop, a shield with number of Public transport Routes and with different shield colors for each transport types(red for bus, blue for tramp, purple for trolleybus, color line for subway), nearest routes within 150m, directions and distance to the stop.

![Public transport Route menu Android](/assets/images/map/pt_routemenu_android.png) ![Public transport Route menu iOS](/assets/images/map/pt_routemenu_ios.png)

Clicking to {% data variables.android-values.rendering_category_details %} button or [Slide](/osmand/map/interact-with-map#gestures) up Context menu opens list of Routes (Nearby routes within 150m. too) and Public transport stop description.

Clicking to a shield of Public transport Route opens Route information menu.

### Transport stop description

In the description, there is full information from [point tag of Public transport platform](https://wiki.openstreetmap.org/wiki/Tag:public_transport%3Dplatform). For example, the name of stop, operator name, covered or not, coordinates of the stop, online photos, link to the point in OpenStreetMap and etc.

For Android version, some of tag can be useful for search filter. For example "Bench", when we click to "Yes", [all object with this tag are shown on the map](/osmand/map/point-layers-on-map#search-results-poi-on-the-map).


![Public transport Route menu details Android](/assets/images/map/pt_routemenu_details_android.png) ![Public transport Route menu iOS](/assets/images/map/pt_routemenu_details_ios.png)

### Transport Routes List 

In Routes list there are all public transport routes for chosen public stop and nearby routes within 150m.

Each public transport route has next information: color shield with the route number, route number with ending stations, type icon of public transport, distance to public stop for nearby routes (within 150m.).

![Public transport Routes Android](/assets/images/map/pt_routes_android.png) ![Public transport Routes iOS](/assets/images/map/pt_routes_ios.png) 

### Browse Route Stops

Clicking to one of the Public transport route in Route list (or clicking to a shield of Public transport Route) opens Route information menu and shows all route with public stops on the map.  

In this menu there are two additional buttons {% data variables.android-values.shared_string_previous %} and {% data variables.android-values.shared_string_next %} for choosing to neighboring public stops of the selected route, public stop name, number and type of Public transport with ending stations.     


![Public transport Route Info Android](/assets/images/map/pt_route_info_android.png)  ![Public transport Route Info iOS](/assets/images/map/pt_route_info_ios.png) 

Clicking to {% data variables.android-values.rendering_category_details %} button or [Slide](/osmand/map/interact-with-map#gestures) up Route information menu opens list of all public stops for choosing route.

Where you can click to a public stop name for moving to it on the map. Chosen public stop has position icon on this list.

![Public transport Route list Android](/assets/images/map/pt_route_list_android.png) ![Public transport Route list iOS](/assets/images/map/pt_route_list_ios.png) 

Clicking to {% data variables.android-values.get_directions %} button build navigation route from your location to chosen Public stop.

## Read more

- [Vector maps](osmand/map/vector-maps) 
- [Public transport navigation](/osmand/navigation/public-transport-navigation)
  
