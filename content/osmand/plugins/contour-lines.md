---
title: Contour lines maps and Terrain
intro: "Terrain information, such as Contour lines, Hillshades, Slopes - helps to build an optimal off-road routes by considering the curvature, extremes, steepness, points of equal height, and other surface shape characteristics of the specific area of travel."
versions: '*'
---

{% data reusables.general.article-not-complete %}

For the Contour lines and Terrain data to show up on the map, the following configuration is required:
1. Purchase the Contour lines package.  
2. Enable the Coutour lines plugin in the Plugins section of the main menu.
3. Download Contour lines and/or Terrain variants for the required regions. 
4. Toggle on Contour lines and/or Terrain variants per profile.
5. If needed, configure the map view. 

## General info

The Contour lines plugin is an autonomous functionality that can be enabled/disabled as needed. The plugin provides for downloading the following maps: 

- the **Contour lines** map in vector points, and
- two Terrain maps in raster pixels: the **Hillshade** map, and the **Slopes** map. 

Each map of the Contour lines plugin is an independent option, which if toggled on, is displayed above, or underneath the Map Source. 

The terrain information on the map can be represented by hill shading, with the contour lines of the uphill and downhill, as an angle of diviation from flat. By means of contour lines, shades and colors, the map shows slopes, peaks, rugged terrain, and other elevation above the sea level. 

The global data for the map - between 70 degrees north and 70 degrees south - is based on the measurements made by the Shuttle Radar Topography Mission (abbrev.as *SRTM*). It uses the Advanced Spaceborne Thermal Emission and Reflection Radiometer (abbrev. as *ASTER*), which is a sensor onboard the Terra satellite and the flagship imaging instrument of NASA's Earth Observing System. ASTER is a cooperative effort between NASA, Japan's Ministry of Economy, Trade and Industry (abbrev. as *METI*), and Japan Space Systems (also known as *J-spacesystems*).

![Contour lines and Terrain](/assets/images/plugins/contour-lines/contour_lines_terrain.png)

## Purchase Contour lines 

Puchase of the Contour lines services is required to enable the plugin and start downloading maps per region. 

{% data reusables.general.android-ios-switcher %}

{% ios % }



{% endios %}

{% android %}

For the **Android** version, to use Contour line, any of the following [subscriptions](/osmand/purchases/android#free-and-paid-features) is needed: 

- **OsmAnd+**
- **OsmAndPro**

{% endandroid %}


## Enable plugin 

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.plugin_settings %} → {% data variables.android-values.srtm_plugin_name %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.plugins %} → {% data variables.ios-values.product_title_srtm %}

![Contour lines plugin on Android](/assets/images/plugins/contour-lines/contour_lines_plugin_android.png) ![Contour lines plugin on iOS](/assets/images/plugins/contour-lines/contour_lines_plugin_ios.png)

## Download maps

To see the contours of a specific area, just go to  [Download maps menu](/osmand/start-with/download-maps#download---main-menu), find your country or region, choose Contour lines, Hillshades, Slopes or all and download the files. Then zoom your desired area until you see the lines and zoom even more to check the height of a specific spot (the number on the line). 

![Contour lines download Android](/assets/images/plugins/contour-lines/contour_lines_plugin_download_android.png) ![Contour lines download iOS](/assets/images/plugins/contour-lines/contour_lines_plugin_download_ios.png)


### Choose Meters or Feet

When you click to ["Contour lines"](/osmand/plugins/contour-lines#downloading-files-and-enable-on-the-map) in the country maps list you see dialogue of choosing Contour lines file in meter or feet. 

You need to choose the meter or feet parameter and download the file.

You will need to re-download the file to change the format.

![Contour lines download dialogue Android](/assets/images/plugins/contour-lines/contour_lines_plugin_download_dialogue_android.png)


## Enable maps per profile

Check to enable Contour Lines option in [Configure map menu](/osmand/map/vector-maps#contour-lines).

To view hillshade or slope, make sure you enable this option in  [Configure map menu](/osmand/map/raster-maps#hillshade--slope). Also, please note that while contour lines file can be split by regions, hillshade/slopes files can be available by country, thus, you'll see the Hillshade/Slopes download on the list of downloads of a country, not on the region maps page.

![Terrain and Contour lines enable Android](/assets/images/plugins/contour-lines/contour_lines_terrain_enable_android.png) ![Terrain and Contour lines enable iOS](/assets/images/plugins/contour-lines/contour_lines_terrain_enable_ios.png)


## Terrain settings

In the  Terrain  menu you can change Hillshade or Slope for the visible layer. Here you can set Transparency and Zoom levels for the layer.

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_map %} → {% data variables.android-values.shared_string_terrain %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.configure_map %} → {% data variables.ios-values.shared_string_terrain %}

### Hillshade

![Terrain menu Android](/assets/images/plugins/contour-lines/terrain_menu_android.png) ![Terrain menu iOS](/assets/images/plugins/contour-lines/terrain_menu_ios.png) 

- "{% data variables.android-values.shared_string_menu %}" button - switch on/off the Terrain layer on the map.
- "{% data variables.android-values.shared_string_hillshade %}" and "{% data variables.android-values.shared_string_slope %}" button - switcher between slopes and hillshades layers.
- {% data variables.android-values.shared_string_transparency %} - choosing trasparence for the terrain layer.
- {% data variables.android-values.shared_string_zoom_levels %} - setting zoom levels for the terrain layer.
- {% data variables.android-values.welmode_download_maps %} - {% data variables.android-values.hillshade_download_description %}.

### Slope

![Terrain menu slopes Android](/assets/images/plugins/contour-lines/terrain_menu_slopes_android.png) ![Terrain menu slopes iOS](/assets/images/plugins/contour-lines/terrain_menu_slopes_ios.png) 

- "{% data variables.android-values.shared_string_menu %}" button - switch on/off the Terrain layer on the map.
- "{% data variables.android-values.shared_string_hillshade %}" and "{% data variables.android-values.shared_string_slope %}" button - switcher between slopes and hillshades layers.
- {% data variables.android-values.shared_string_transparency %} - choosing trasparence for the terrain layer.
- {% data variables.android-values.shared_string_zoom_levels %} - setting zoom levels for the terrain layer.
- {% data variables.android-values.shared_string_legend %} - legend of slopes, read more [here](https://en.m.wikipedia.org/wiki/Grade_(slope)).
- {% data variables.android-values.welmode_download_maps %} - {% data variables.android-values.slope_download_description %}.

## Contour lines settings

For Contour lines you can set the minimal zoom level where the contour lines will become visible, color scheme, width and density for lines.
[Configure map](/osmand/map/vector-maps#contour-lines).

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_map %} → {% data variables.android-values.index_srtm_ele %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.configure_map %} → {% data variables.ios-values.product_title_srtm %}

![Contour lines menu Android](/assets/images/plugins/contour-lines/contour_lines_menu_android.png) ![Contour lines menu iOS](/assets/images/plugins/contour-lines/contour_lines_menu_ios.png) 


- "{% data variables.android-values.shared_string_menu %}" button - switch on/off the Terrain layer on the map.
- {% data variables.android-values.show_from_zoom_level %} - select zoom level, from which contour lines will be displayed.
- {% data variables.android-values.srtm_color_scheme %} - select color for contour lines.
- {% data variables.android-values.rendering_attr_contourWidth_name %} - select width for contour lines.
- {% data variables.android-values.rendering_attr_contourDensity_name %} - select density for contour lines on the map.

## Note

You can use both contour lines and terrain together to get the information from both layers. Just go to  [Configure map](/osmand/map/configure-map-menu)  menu and enable both  [Contour lines](/osmand/map/vector-maps#contour-lines)  and  [Terrain layer](/osmand/map/raster-maps#hillshade--slope)  options. If you cannot see the hillshade/slopes after downloading it, please restart the application.

After that, you'll be able to enjoy a map with all the hills and peaks. A nice option for both practical use and a general knowledge about the area you live in or travel to.

![Contour lines and Terrain Android](/assets/images/plugins/contour-lines/contour_lines_terrain_android.png) ![Contour lines and Terrain iOS](/assets/images/plugins/contour-lines/contour_lines_terrain_ios.png) 

Please see full video guide below:
[Link to Youtube](https://www.youtube.com/watch?v=z8kp_M3FKoc&feature=emb_logo&ab_channel=BartEisenberg)

