---
title: "Configure Map"
intro: "'Configure map' menu is a central place where you could configure map display for your needs, i.e. highlight Favorite points, Navigation markers or special Points of Interests on the map; display specific routes or 3rd party GPX files; overlay the map with relief information, satellite imagery or any other available raster map; display public transport information and change the map style."
versions: '*'
---

| Android | iOS |
| :---: | :---: |
| ![Configure map_android](/assets/images/map/configure-map-android.png) | ![Configure map_ios](/assets/images/map/configure-map-ios.png) |

**{% data variables.android-values.configure_map %}** menu divides into 2 categories:
- [Map style parameters](#map-style-parameters) - **{% data variables.android-values.map_widget_map_rendering %}** or **{% data variables.ios-values.map_settings_style %}** groups all parameters that allow to change how the main map is displayed.
- [Map layers](#map-layers). These layers allow to put information on top (or under) of the main map layer but it doesn't change the display of the map itself.


**Notes:** 
- In order to change screen information (widgets, icons) you can set parametres in [{% data variables.android-values.layer_map_appearance %}](/osmand/widgets/general)
- Configure map settings are [profile dependent](/osmand/personal/profiles)

## Map Layers
   - [Vector Map Layer](//osmand/map/vector-maps) - displays all vector map information including OpenStreetMap, Contour lines, Nautical data.
   - [Map Raster sources](/osmand/map/raster-maps#select-map-as-main--underlay--overlay-layer) - select underlay / main source / overlay map with transparency levels.
   - [Terrain](/osmand/map/raster-maps#hillshade--slope) - display raster slope or hillshade information.

## Map Data Layers
   - [Favorites](/osmand/map/point-layers-on-map) - display favorites points.
   - [POI](/osmand/map/point-layers-on-map) - display points of interests of selected categories.
   - [Map markers](/osmand/map/point-layers-on-map) - display map markers.
   - [Overlay labels](/osmand/map/point-layers-on-map) - show names of points, favorites on the map.
   - [Transport](/osmand/map/vector-maps#transport) - show public transport stops.
   - [Tracks](/osmand/map/tracks-on-map) - display imported, planned or recorded tracks over the map.
   - [Street level imagery](/osmand/map/street-level-imagery) - display points with available street-level imagery.
   - [Travel guides](/osmand/plan-route/travel-guides) - display travel guides on the map.
   - [Wikipedia](/osmand/plugins/wikipedia) - highlight wikipedia articles linked to the map.
   - [Other plugin layers](/osmand/plugins) - many plugins add own layers with extra information.

## Map style parameters
Map style parameters are dependent on the main map style be displayed on the map. You can read more about it in [Map Styles article](/osmand/map/vector-maps).
   - [Map style](/osmand/map/vector-maps#default-map-styles) - OsmAnd (City), Topo, Nautical and others.
   - [Map mode](/osmand/map/vector-maps#map-mode) - select to browse map or to run a navigation.
   - [Map magnifier](/osmand/map/vector-maps#map-magnifier) - more or less detailed map display.
   - [Text size](/osmand/map/vector-maps#text-size) - increase or decrease text size on the map.
   - [Map language](/osmand/map/vector-maps#map-language) - select preferred language displayed on the map.
   - [Details](/osmand/map/vector-maps#details) - highlight specific objects.
   - [Hide](/osmand/map/vector-maps#hide) - hide specific objects.
   - [Routes](/osmand/map/vector-maps#routes) - highlight specific routes and their symbols.
   
## UI Customization (Android)
   
You can reorder or hide items from the {% data variables.android-values.configure_map %} per selected profile, reset to default or copy from another profile.
   
{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %} → {% data variables.android-values.ui_customization %} → {% data variables.android-values.configure_map %} 

![Configure map items ](/assets/images/settings/configure-screen-ui-customization.png)
