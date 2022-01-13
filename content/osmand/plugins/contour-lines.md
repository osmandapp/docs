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


## Pre-requisites  

Puchase of the Contour lines package is required to enable the plugin and start downloading Contour lines, and/or Hillshade, and/or Slope maps per region. 

{% data reusables.general.android-ios-switcher%}

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

There are three types of the elevation data packages for download per region: Contour lines, Hillshade and Slope. Most often all of them can be downloaded at the country level. There are also regions where only Contour lines are available, for example, the Sicily island and Italy as the entire country; as well as regions where Hillshade and Slope are available too, for example, Alberta and Canada. 

For an optimal representation, the country level maps are combined with the region level maps. However, whether it should be all three, or any of the elevation data maps (i.e. Contour lines, and/or Hillshade, and/or Slope) depend on the current needs. As for the regional level, it may be enough to download only the required maps at the regional level. However, as there are no Slope maps at the regional level, then to see the slope angle color and contour lines on the map, for example, of Sicily, two downloads will be needed: the Contour lines map at the region level, and the Slope map at the country level, as for Italy the Slope map exists only at the country level. 

| None of Contour lines maps | Hillshade map only | Slope map only |
| --- | --- | --- |
|![None of Contour lines over Sicily](/assets/images/plugins/contour-lines/1_none_of_contour_maps.png) |  ![Hillshade over Sicily](/assets/images/plugins/contour-lines/2_hillshade_only.png) | ![Slope over Sicily](/assets/images/plugins/contour-lines/3_slope_only.png)  |

The Contour lines, Hillshade and Slope angle colors become viewable at a certain zoom level, which is established at the settings for the specific map type. 

| Contour lines combined with Hillshade | Contour lines combined with Slope | 
| --- | --- |
|![Contour lines combined with Hillshade](/assets/images/plugins/contour-lines/4_hillshade_n_contour.png) | ![Contour lines combined with Slope](/assets/images/plugins/contour-lines/5_slope_n_contour.png) | 
| If to use the legend of colors to determine the angle of the slope, it is possible to assume the steepness of the slope, points of equal height, etc. | ![Legend of slope angle colors](/assets/images/plugins/contour-lines/Slope_legend.png) |

To download a map of the Contour lines plugin for a specific area, go to  [Download maps menu](/osmand/start-with/download-maps#download---main-menu), find your country or region, choose any of the packages: Contour lines, Hillshades, and/or Slopes; and download the files. 


{% data reusables.general.android-ios-switcher%}

{% ios%}

![Contour lines download iOS](/assets/images/plugins/contour-lines/contour_lines_plugin_download_ios.png)

{% endios%}

{% android%}

![Contour lines download Android](/assets/images/plugins/contour-lines/contour_lines_plugin_download_android.png)

{% endandroid%}



### Choose Meters or Feet

When you click to ["Contour lines"](/osmand/plugins/contour-lines#downloading-files-and-enable-on-the-map) in the country maps list you see dialogue of choosing Contour lines file in meter or feet. 

You need to choose the meter or feet parameter and download the file.

You will need to re-download the file to change the format.

![Contour lines download dialogue Android](/assets/images/plugins/contour-lines/contour_lines_plugin_download_dialogue_android.png)


## Toggle maps on per profile

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

