---
title: Contour lines maps and Terrain
intro: "This plugin gives the terrain information you can view over the basic map."
versions: '*'
---
{% data reusables.general.article-not-complete %}

![Contour lines](/assets/images/plugins/contour-lines/contour-lines-intro.png)

## General info

This plugin gives the terrain information you can view over the basic map. It actually works several ways — as a terrain contour lines data provider and as a full hillshade map using dark shades and colors to show slopes, peaks and lowlands.

The global data (between 70 degrees north and 70 degrees south) is based on measurements by SRTM (Shuttle Radar Topography Mission) and ASTER (Advanced Spaceborne Thermal Emission and Reflection Radiometer), an imaging instrument onboard Terra, the flagship satellite of NASA's Earth Observing System. ASTER is a cooperative effort between NASA, Japan's Ministry of Economy, Trade and Industry (METI), and Japan Space Systems (J-spacesystems).

Contour lines plugin is a handy tool for hikers, tourists and anyone who needs the information about the terrain in a specific area.

## Where Plugin find?

For using this feature you should buy  [Paid version or OsmAnd subscription](/osmand/purchases). 

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.plugin_settings %} → {% data variables.android-values.srtm_plugin_name %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.plugins %} → {% data variables.ios-values.product_title_srtm %}

![Contour lines plugin on Android](/assets/images/plugins/contour-lines/contour_lines_plugin_android.png) ![Contour lines plugin on iOS](/assets/images/plugins/contour-lines/contour_lines_plugin_ios.png)

## Downloading files and enable on the map

To see the contours of a specific area, just go to  [Download maps  menu](/osmand/start-with/download-maps#download---main-menu), find your country or region, choose Contour lines, Hillshades, Slopes or all and download the files. Then zoom your desired area until you see the lines and zoom even more to check the height of a specific spot (the number on the line). 

![Contour lines download Android](/assets/images/plugins/contour-lines/contour_lines_plugin_download_android.png) ![Contour lines download iOS](/assets/images/plugins/contour-lines/contour_lines_plugin_download_ios.png)

Check to enable Contour Lines option in [Configure map menu](/osmand/map/vector-maps#contour-lines).
To view hillshade or slope, make sure you enable this option in  [Configure map menu](/osmand/map/raster-maps#hillshade--slope). Also, please note that while contour lines file can be split by regions, hillshade/slopes files can be available by country, thus, you'll see the Hillshade/Slopes download on the list of downloads of a country, not on the region maps page.

![Terrain and Contour lines enable Android](/assets/images/plugins/contour-lines/contour_lines_terrain_enable_android.png) ![Terrain and Contour lines enable iOS](/assets/images/plugins/contour-lines/contour_lines_terrain_enable_ios.png)
 
## Terrain settings

In the  Terrain  menu you can change Hillshade or Slope for the visible layer. Here you can set Transparency and Zoom levels for the layer.

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_map %} → {% data variables.android-values.shared_string_terrain %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.configure_map %} → {% data variables.ios-values.shared_string_terrain %}

Hillshades:

![Terrain menu Android](/assets/images/plugins/contour-lines/terrain_menu_android.png) ![Terrain menu iOS](/assets/images/plugins/contour-lines/terrain_menu_ios.png) 

Slopes:

![Terrain menu slopes Android](/assets/images/plugins/contour-lines/terrain_menu_slopes_android.png) ![Terrain menu slopes iOS](/assets/images/plugins/contour-lines/terrain_menu_slopes_ios.png) 

## Contour lines settings

For Contour lines you can set the minimal zoom level where the contour lines will become visible, color scheme, width and density for lines.
[Configure map](/osmand/map/vector-maps#contour-lines).

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_map %} → {% data variables.android-values.index_srtm_ele %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.configure_map %} → {% data variables.ios-values.product_title_srtm %}

![Contour lines menu Android](/assets/images/plugins/contour-lines/contour_lines_menu_android.png) ![Contour lines menu iOS](/assets/images/plugins/contour-lines/contour_lines_menu_ios.png) 

## Note

You can use both contour lines and terrain together to get the information from both layers. Just go to  _Configure map_  menu and enable both  _Contour lines_  and  _Terrain layer_  options. If you cannot see the hillshade/slopes after downloading it, please restart the application.


After that, you'll be able to enjoy a map with all the hills and peaks. A nice option for both practical use and a general knowledge about the area you live in or travel to.

Please see full video guide below:
[Link to Youtube](https://www.youtube.com/watch?v=z8kp_M3FKoc&feature=emb_logo&ab_channel=BartEisenberg)




