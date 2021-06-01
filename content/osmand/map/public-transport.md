---
title: "Public transport (Layers)"
intro: "Explore public transport routes / stops on the map."
versions: '*'
---
{% data reusables.general.article-not-complete %}

## Public transport layer on the map

Detailed info about Public transport layer on the map read [here](/osmand/map/vector-maps#transport).


| Android | iOS |
| :--- | :--- |
| Enable/Disenable Public transport layer.| Enable/Disenable Public transport layer. |
|{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_map %} → {% data variables.android-values.rendering_category_transport %} → &#8230 → Choosing types of categories for displayed: {% data variables.android-values.rendering_attr_transportStops_name %}; {% data variables.android-values.rendering_attr_publicTransportMode_name %}; {% data variables.android-values.rendering_attr_tramTrainRoutes_name %}; {% data variables.android-values.rendering_attr_subwayMode_name %} | {% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.map_settings_map %} → {% data variables.ios-values.rendering_category_transport %} → &#8230 → Choosing types of categories for displayed: {% data variables.ios-values.rendering_attr_publicTransportMode_name %}; {% data variables.ios-values.rendering_attr_subwayMode_name %}; {% data variables.ios-values.rendering_attr_tramTrainRoutes_name %}; {% data variables.ios-values.rendering_attr_transportStops_name %}  |
|   ![Public transport layer Android](/assets/images/map/pt_layer_android.png) | ![Public transport layer iOS](/assets/images/map/pt_layer_ios.png) |

## Public transport Route (Menu)

Clicking on a point {% data variables.android-values.rendering_attr_transportStops_name %} on the map opens Public transport Routes information in Map Context menu.

Here we can find the name of public stop, an icon of public transport type for this stop, Public transport Routes with different colors for each transport types(red for bus, blue for tramp, purple for trolleybus, color line for subway), nearest routes within 150m, directions and distance to the stop.

| Android | iOS |
| :---: | :---: |
| ![Public transport Route menu Android](/assets/images/map/pt_routemenu_android.png) | ![Public transport Route menu iOS](/assets/images/map/pt_routemenu_ios.png) |


Clicking to {% data variables.android-values.rendering_category_details %} button or [Slide](/osmand/map/interact-with-map#gestures) up Context menu opens list of Routes (Nearby routes within 150m. too) and Public transport stop description.

**Public transport stop description**

In the description, there is full information from [point tag of Public transport platform](https://wiki.openstreetmap.org/wiki/Tag:public_transport%3Dplatform). For example, the name of stop, operator name, covered or not, coordinates of the stop, online photos, link to the point in OpenStreetMap and etc.

For Android version, some of tag can be useful for search filter. For example "Bench", when we click to "Yes", [all object with this tag are shown on the map](/osmand/map/point-layers-on-map#search-results-poi-on-the-map).


| Android | iOS |
| :---: | :---: |
| ![Public transport Route menu details Android](/assets/images/map/pt_routemenu_details_android.png) | ![Public transport Route menu iOS](/assets/images/map//assets/images/map/pt_routemenu_details_ios.png) |

**Routes list**








## Read more

- [Vector maps](osmand/map/vector-maps)
  
- [Public transport navigation](/osmand/navigation/public-transport-navigation)
  
