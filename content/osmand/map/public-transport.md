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
- [List of the routes](#routes) stopping on that stop or nearby (within 150 m)
- Name of the stop and other [details](#transport-stop-details)

### Transport Stop details

**Cut android screenshot*
**Update ios screenshot** 

![Public transport Route menu details Android](/assets/images/map/pt_routemenu_details_android.png) ![Public transport Route menu iOS](/assets/images/map/pt_routemenu_details_ios.png)

Public transport stop provides extra details comparing to standard OpenStreetMap object [menu](/osmand/map/map-context-menu#details):
- Bench presence
- Cover presence
- Wheelchair accessibility
- Operator name

**Note**: you can filter stops by certain criteria. For example, expand & click on "Bench" / "Yes" and you can see the list of stops with benches. Also they could be [shown on the map](/osmand/map/point-layers-on-map#search-results-poi-on-the-map).


### Routes 

**Cut and align screenshots by top** 

![Public transport Routes Android](/assets/images/map/pt_routes_android.png) ![Public transport Routes iOS](/assets/images/map/pt_routes_ios.png) 

Transport Routes are all public transport routes that approach via selected stop and nearby routes (within 150m). Routes information is taken from [OpenStreetMap data](https://wiki.openstreetmap.org/wiki/Public_transport) such as ref, name, colour and type.

**Shield color**:
- Subway - own color line 
- Railway - brown
- Bus and other - red
- Tram - blue
- Trolleybus - purple

### Browse Route

**Update screenshot ios**

![Public transport Route list Android](/assets/images/map/pt_route_list_android.png)  ![Public transport Route Info iOS](/assets/images/map/pt_route_info_ios.png) 

You can enter Browse Route menu by **clicking on a shield** or **selecting a route** from the routes list. After that you can browse between stops by clicking  '{% data variables.android-values.shared_string_previous %}' and '{% data variables.android-values.shared_string_next %}'. Stop info will be updated in the menu and stop will be located on the map.

You can see the full list of stops by clicking {% data variables.android-values.rendering_category_details %}. Currently selected stop is marked with 'location' icon on the Routes list.

**Note**: If you click {% data variables.android-values.get_directions %} button you will get a route from your current location to the selected Public Transport Station.

## Read more

- [Vector maps](osmand/map/vector-maps) 
- [Public transport navigation](/osmand/navigation/public-transport-navigation)
  
