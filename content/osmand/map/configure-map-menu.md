---
title: "Configure Map"
intro: "OsmAnd gives great possibilities for using the maps. Typically maps needs to be configured for your needs, so you could highlight Favorite points, Navigation markers or special Points of Interests on the map. You could also make visible specific routes or 3rd party GPX files and you could overlay the map with relief information or satellite imagery. All visible map information is configurable via Configure Map menu."
versions: '*'
---

**{% data variables.android-values.configure_map %}** menu divides into 2 categories:
- [Map style parameters](#map-style-parameters) - **{% data variables.android-values.map_widget_map_rendering %}** or **{% data variables.ios-values.map_settings_style %}** groups all parameters that allow to change how the main map is displayed.
- [Map layers](#map-layers). These layers allow to put information on top (or under) of the main map layer but it doesn't change the display of the map itself.

{% data reusables.general.image-needs-to-be-updated %}

![Configure map](/assets/images/map/configure-map.png)

**Notes:** 
- In order to change screen information (widgets, icons) you can set parametres in [{% data variables.android-values.layer_map_appearance %}](/osmand/widgets/general)
- Configure map settings are [profile dependent](/osmand/personal/profiles)

## Map Layers
   - [Favorites](/osmand/map/point-layers-on-map) - display favorites points.
   - [POI](/osmand/map/point-layers-on-map) - display points of interests of selected categories.
   - [Map markers](/osmand/map/point-layers-on-map) - display map markers.
   - [Overlay labels](/osmand/map/point-layers-on-map) - show names of points, favorites on the map.
   - [Transport](/osmand/map/map-styles-and-parameters#transport) - show public transport stops.
   - [Tracks](/osmand/map/tracks-on-map) - display imported, planned or recorded tracks over the map.
   - [Map sources](/osmand/map/online-raster-maps#select-map-as-main--underlay--overlay-layer) - select underlay / main source / overlay map with transparency levels.
   - [Street level imagery](/osmand/map/street-level-imagery) - display points with available street-level imagery.
   - [Wikipedia](/osmand/map/wikipedia) - highlight wikipedia articles linked to the map.
   - [Contour lines](/osmand/map/contour-lines-hillshade) - display depth or height contour lines.
   - [Terrain](/osmand/map/contour-lines-hillshade) - display raster slope or hillshade information.
   - [Other plugin layers](/osmand/plugins) - many plugins add own layers with extra information.

## Map style parameters
Map style parameters are dependent on the main map style be displayed on the map. You can read more about it in [Map Styles article](/osmand/map/map-styles-and-parameters).
   - [Map style](/osmand/map/map-styles-and-parameters#default-map-styles) - OsmAnd (City), Topo, Nautical and others.
   - [Map mode](/osmand/map/map-styles-and-parameters#map-mode) - select to browse map or to run a navigation.
   - [Map magnifier](/osmand/map/map-styles-and-parameters#map-magnifier) - more or less detailed map display.
   - [Text size](/osmand/map/map-styles-and-parameters#text-size) - increase or decrease text size on the map.
   - [Map language](/osmand/map/map-styles-and-parameters#map-language) - select preferred language displayed on the map.
   - [Details](/osmand/map/map-styles-and-parameters#details) - highlight specific objects .
   - [Hide](/osmand/map/map-styles-and-parameters#hide) - hide specific objects.
   - [Routes](/osmand/map/map-styles-and-parameters#routes) - highlight specific routes and their symbols.
   
## UI Customization (Android)
   
You can reorder or hide items from the {% data variables.android-values.configure_map %} per selected profile.
   
{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %} → {% data variables.android-values.ui_customization %} → {% data variables.android-values.configure_map %} 

![Configure map items ](/assets/images/settings/configure_map_items.png)