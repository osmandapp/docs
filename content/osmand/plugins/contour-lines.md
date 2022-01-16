---
title: "Contour lines and Terrain"
intro: "Terrain information, such as Contour lines, Hillshades, Slopes - helps to make a visual assessment of the shape of the land surface by considering the curvature, extremes, steepness, points of equal height, and other characteristics."
versions: '*'
---

{% data reusables.general.article-not-complete %}

For the Contour lines and Terrain data to show up on the map, the following configuration is needed:

1. Purchase any of the Contour lines maps.  
2. Enable the Coutour lines plugin in the Plugins section of the main menu.
3. Download the Contour lines and/or Terrain maps for the required regions. 
4. Toggle on the Contour lines and/or Terrain maps per profile.
5. If needed, configure the map view. 

![Contour lines and Terrain](/assets/images/plugins/contour-lines/contour_lines_terrain.png)


## General info

The Contour lines plugin is an autonomous functionality that can be enabled/disabled as needed. The plugin provides for downloading the following maps: 

- the **Contour lines** map in vector points, and

- two Terrain maps in raster pixels: 

    - the **Hillshade** map, and 

    - the **Slopes** map. 

Each map of the Contour lines plugin is an independent option, which if toggled on, is displayed above, or underneath the Map Source, depending on the established settings.

The terrain information on the map can be represented by hill shading, with the contour lines of the uphill and downhill, with the color of the slope angle of diviation from flat. By means of contour lines, shades and colors, the map shows slopes, peaks, rugged terrain, and other elevation above the sea level. 

The elevation data on the map - between 70 degrees north and 70 degrees south - is produced on the basis of the measurements made by the Shuttle Radar Topography Mission (abbrev.as *SRTM*). It used the Advanced Spaceborne Thermal Emission and Reflection Radiometer (abbrev. as *ASTER*), which is a sensor onboard the Terra satellite and the flagship imaging instrument of NASA's Earth Observing System. ASTER represents a cooperative effort between NASA, Japan's Ministry of Economy, Trade and Industry (abbrev. as *METI*), and Japan Space Systems (also known as *J-spacesystems*).


## Prerequisites  

Puchase of the Contour lines package is required to enable the plugin and start downloading Contour lines, and/or Hillshade, and/or Slope maps per region. 

{% data reusables.general.android-ios-switcher%}

{% default %}

The maps of the Contour lines plugin are distributed through In-App Purchases, subsciptions, and an Android app purchase. For more details on available options per version, visit [Purchases](/osmand/purchases).  

With any Contour lines purchases made, the plugin can be enabled, as displayed on the figures below. 

![Contour lines plugin on iOS](/assets/images/plugins/contour-lines/contour_lines_plugin_ios.png) ![Contour lines plugin on Android](/assets/images/plugins/contour-lines/contour_lines_plugin_android.png) 

{% enddefault %}

{% ios%}

For purchases on **iOS**, refer to [in-app purchases, or a subscription](/osmand/purchases/ios#in-app-purchases). To view the already made purchases, go to: {% data variables.ios-values.menu %} → {% data variables.ios-values.sett_settings %} → {% data variables.ios-values.purchases %} 

In the **iOS** version, to enable the plugin, check **Contour lines** in: {% data variables.ios-values.menu %} → {% data variables.ios-values.plugins %} → {% data variables.ios-values.product_title_srtm %} 

![Contour lines plugin on iOS](/assets/images/plugins/contour-lines/contour_lines_plugin_ios.png) 

{% endios%}

{% android%}

For purchases on **Android**, refer to [in-app purchases, a subscription, or the full version of the app](/osmand/purchases/android#free-and-paid-features). To view the already made purchases, go to: {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.shared_string_settings %} → {% data variables.android-values.purchases %}

In the **Android** version, to enable the plugin, tap Enable for **Contour lines** in: {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.plugin_settings %} → {% data variables.android-values.srtm_plugin_name %} 

![Contour lines plugin on Android](/assets/images/plugins/contour-lines/contour_lines_plugin_android.png) 

{% endandroid%}



## Download maps

There are three types of the elevation data packages for [download per region](osmand/start-with/download-maps.md): Contour lines, Hillshade and Slope. Most often all of them can be downloaded at the country level. And also, there are maps available per lower region level. 

### Maps at country and/or region levels 

By combining the maps of both levels and different types, you can achieve an optimal configuration of the elevation data that suites your current needs. 

For example, you can combine the Contour lines region map of the Sicily island with the Slope map of Italy as the entire country map. Another example is the maps of Canada, where all three types of maps are available at the region level. And to display both the Slope and Contour lines data for Alberta, it is enough to download respectively two maps at the region level, i.g. for Alberta only.  

![Hillshade over Sicily](/assets/images/plugins/contour-lines/2_hillshade_only.png) ![Slope over Sicily](/assets/images/plugins/contour-lines/3_slope_only.png)

> **NOTE**: The Contour lines, Hillshade and Slope angle colors become viewable at a certain zoom level, which is established at the settings for the specific map type.

### Combining types of maps

When downloading different types of the maps: Contour lines, Hillshade, and/or Slope, it is possible to combine them.

For example, to make an assessment of curvature, especially for a mountain ridge, the combination of Contour lines with Hillshade will be an obvious choice for download. And to assess the steepness of the slope, points of equal height, you can download the Slope and Contour lines maps.

![Contour lines combined with Hillshade](/assets/images/plugins/contour-lines/4_hillshade_n_contour.png) ![Contour lines combined with Slope](/assets/images/plugins/contour-lines/5_slope_n_contour.png) 

### Choose Meters or Feet

The contour interval can be displayed in feet, or meters. It is important to decide what units it is convenient for you to see Contour lines in, so that to download the respective version of the Contour lines map. The units are not interchangeable, and in case if feet are needed to be switched into meters, or vice versa, the previous version of the Contour lines map has to be removed, so that anew to download the other version. 

The versions - feet or meters - are displayed on the download popup, when the ["Contour lines"](/osmand/plugins/contour-lines#downloading-files-and-enable-on-the-map) option is clicked in the country, or region map list. It allows you to choose what Contour lines file is needed: in meters, or in feet. 

![Contour lines download dialogue Android](/assets/images/plugins/contour-lines/contour_lines_plugin_download_dialogue_android.png)

{% data reusables.general.android-ios-switcher%}

{% default %}

To download a map of the Contour lines plugin for a specific area, do the following:

1. Go to  [Download maps menu](/osmand/start-with/download-maps#download---main-menu).

2. Find your country or region.
3. Choose any of the packages: 
    - Contour lines, 
    - Hillshade, and/or 
    - Slopes.
4. For Contour lines, select Meters, or Feet.
5. Download the files. 

![Contour lines download iOS](/assets/images/plugins/contour-lines/contour_lines_plugin_download_ios.png) ![Contour lines download Android](/assets/images/plugins/contour-lines/contour_lines_plugin_download_android.png)

{% enddefault %}

{% ios%}

In the **iOS** version, for the available packages of maps to download, go to: {% data variables.ios-values.menu %} → {% data variables.ios-values.res_mapsres %} → {% data variables.ios-values.res_worldwide %} and select the required country, and/or region.

![Contour lines download iOS](/assets/images/plugins/contour-lines/contour_lines_plugin_download_ios.png)

{% endios%}

{% android%}

In the **Android** version, for the available packages of maps to download, go to: {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.welmode_download_maps %} → {% data variables.android-values.regions %} and select the required country, and/or region. 

![Contour lines download Android](/assets/images/plugins/contour-lines/contour_lines_plugin_download_android.png)

{% endandroid%}


## Toggle maps on per profile

Downloaded can be as many maps as required, and then it is possible to determine what map to show for what profile.

Check to enable Contour Lines option in [Configure map menu](/osmand/map/vector-maps#contour-lines).

To view hillshade or slope, make sure you enable this option in  [Configure map menu](/osmand/map/raster-maps#hillshade--slope). Also, please note that while contour lines file can be split by regions, hillshade/slopes files can be available by country, thus, you'll see the Hillshade/Slopes download on the list of downloads of a country, not on the region maps page.

![Terrain and Contour lines enable Android](/assets/images/plugins/contour-lines/contour_lines_terrain_enable_android.png) ![Terrain and Contour lines enable iOS](/assets/images/plugins/contour-lines/contour_lines_terrain_enable_ios.png)



## Note

Then zoom your desired area until you see the lines and zoom even more to check the height of a specific spot (the number on the line). 

You can use both contour lines and terrain together to get the information from both layers. Just go to  [Configure map](/osmand/map/configure-map-menu)  menu and enable both  [Contour lines](/osmand/map/vector-maps#contour-lines)  and  [Terrain layer](/osmand/map/raster-maps#hillshade--slope)  options. If you cannot see the hillshade/slopes after downloading it, please restart the application.

After that, you'll be able to enjoy a map with all the hills and peaks. A nice option for both practical use and a general knowledge about the area you live in or travel to.

![Contour lines and Terrain Android](/assets/images/plugins/contour-lines/contour_lines_terrain_android.png) ![Contour lines and Terrain iOS](/assets/images/plugins/contour-lines/contour_lines_terrain_ios.png) 



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



Please see full video guide below:
[Link to Youtube](https://www.youtube.com/watch?v=z8kp_M3FKoc&feature=emb_logo&ab_channel=BartEisenberg)

