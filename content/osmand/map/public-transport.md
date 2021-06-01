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

Click to {% data variables.android-values.rendering_attr_transportStops_name %} on the map opens Public transport Routes information in Map Context menu. Where we can find name of Publick stop, icon of public transport type for this stop, Public transport Routes with different colors for each transporst types(red for bus, blue for tramp, purple for trolleybus, color line for subway), nearest routes within 150m, directions and distance to the stop.

![Public transport Route menu Android](/assets/images/map/pt_routemenu_android.png) ![Public transport Route menu iOS](/assets/images/map/pt_routemenu_ios.png)

## Read more

- [Vector maps](osmand/map/vector-maps)
  
- [Public transport navigation](/osmand/navigation/public-transport-navigation)
  
