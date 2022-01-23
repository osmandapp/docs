---
title: "Contour lines and Terrain"
intro: "Terrain information, such as Contour lines, Hillshades, Slopes - helps to make a visual assessment of the shape of the land surface by considering the curvature, extremes, steepness, points of equal height, and other."
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


## Overview

The Contour lines plugin is an autonomous functionality that can be enabled/disabled as needed. The plugin provides for [downloading](/osmand/personal/maps#download-maps-maps) the following maps: 

- the **Contour lines** map in [vector](/osmand/map/vector-maps) points, and

- two Terrain maps in [raster](/osmand/map/raster-maps) pixels: 

    - the **Hillshade** map, and 

    - the **Slopes** map. 

Each map of the Contour lines plugin is an independent option, which if toggled on, is displayed above, or underneath the Map Source, depending on the established settings.

The terrain information on the map can be represented by hill shading, with the contour lines of the uphill and downhill, with the color of the slope angle of diviation from flat. By means of contour lines, shades and colors, the map shows slopes, peaks, rugged terrain, and other elevation above the sea level. 

The elevation data on the map - between 70 degrees north and 70 degrees south - is produced on the basis of the measurements made by the Shuttle Radar Topography Mission (abbrev.as *SRTM*). It used the Advanced Spaceborne Thermal Emission and Reflection Radiometer (abbrev. as *ASTER*), which is a sensor onboard the Terra satellite and the flagship imaging instrument of NASA's Earth Observing System. ASTER represents a cooperative effort between NASA, Japan's Ministry of Economy, Trade and Industry (abbrev. as *METI*), and Japan Space Systems (also known as *J-spacesystems*).


## Prerequisites  

Puchase of the Contour lines package is required to enable the plugin and start downloading Contour lines, and/or Hillshade, and/or Slope maps per region. 

{% data reusables.general.android-ios-switcher %}

{% default %}

The maps of the Contour lines plugin are distributed through In-App Purchases, subsciptions, and an Android app purchase. For more details on available purchase options, visit [Purchases](/osmand/purchases).  

Having purchased Contour lines, the plugin can be enabled, as displayed on the figures below. 

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



## Download Contour lines/Terrain 

There are three types of the elevation data packages for [download per region](osmand/start-with/download-maps): Contour lines, Hillshade and Slope. Most often all of them can be downloaded at the country level. And also, there are maps available per lower region level. 

### Consider country/region levels 

By combining the maps of both levels and different types, you can achieve an optimal configuration of the elevation data that suites your current needs. 

For example, you can combine the Contour lines region map of the Sicily island with the Slope map of Italy as one at the country level. Another example is the maps of Canada, where all three types of maps are available at the region level. And to display both the Slope and Contour lines data for Alberta, it is enough to download respectively two maps at the region level.  

{% data reusables.general.android-ios-switcher %}

{% default %}

![Hillshade over Sicily](/assets/images/plugins/contour-lines/2_hillshade_only.png) ![Slope over Sicily](/assets/images/plugins/contour-lines/3_slope_only.png)


{% enddefault %}

{% ios%}

![Hillshade over Sicily in iOS](/assets/images/plugins/contour-lines/ios_hillshade1.png) ![Slope over Sicily in iOS](/assets/images/plugins/contour-lines/ios_slope1.png)

{% endios%}

{% android%}

![Hillshade over Sicily in Android](/assets/images/plugins/contour-lines/2_hillshade_only.png) ![Slope over Sicily in Androis](/assets/images/plugins/contour-lines/3_slope_only.png)

{% endandroid%}


> **NOTE**: The Contour lines, Hillshade and Slope angle colors become viewable at a certain zoom level, which is established in the settings for the specific map type.




### Combine map types

When downloading different types of the maps: Contour lines, Hillshade, and/or Slope, consider the possiblity further to combine them.

For example, to make an assessment of curvature, especially for a mountain ridge, the combination of Contour lines with Hillshade will be an obvious choice for download. And to assess the steepness of the slope, points of equal height, you can display the Slope and Contour lines maps together.

{% data reusables.general.android-ios-switcher %}

{% default %}

![Contour lines combined with Hillshade](/assets/images/plugins/contour-lines/4_hillshade_n_contour.png) ![Contour lines combined with Slope](/assets/images/plugins/contour-lines/5_slope_n_contour.png) 

{% enddefault %}

{% ios%}

![Contour lines combined with Hillshade in iOS](/assets/images/plugins/contour-lines/ios_hillshade_n_cont_lines1.png) ![Contour lines combined with Slope in iOS](/assets/images/plugins/contour-lines/ios_slope_n_cont_lines1.png)

{% endios%}

{% android%}

![Contour lines combined with Hillshade](/assets/images/plugins/contour-lines/4_hillshade_n_contour.png) ![Contour lines combined with Slope](/assets/images/plugins/contour-lines/5_slope_n_contour.png) 

{% endandroid%}


>**NOTE**: There is a legend of colors that shows how each color aligns with the angle of deviation from flat. The legend is available in the settings of the Slope map. ![Slope color legend](/assets/images/plugins/contour-lines/Slope_legend.png)



### Choose Meters or Feet

The contour interval can be displayed in feet, or meters. It is important to decide what units it is convenient for you to see Contour lines in, so that to download the respective version of the Contour lines map. The units are not interchangeable, and in case if feet are needed to be switched into meters, or vice versa, the previous version of the Contour lines map has to be removed, so that anew to download the other version. 

{% data reusables.general.android-ios-switcher %}

{% default %}

The versions - in feet, or meters - are displayed on the download popup, when the [**Contour lines**](/osmand/map/vector-maps#contour-lines) option is clicked in the country, or region map list. It allows you to choose what Contour lines file is needed: in meters, or in feet. 

![Contour lines download dialogue Android](/assets/images/plugins/contour-lines/contour_lines_plugin_download_dialogue_android.png) ![Contour lines download dialogue iOS](/assets/images/plugins/contour-lines/ios_cont_lines_meters_feet1.png) 

{% enddefault %}

{% ios%}

The versions - in feet, or meters - are displayed on the download popup, when the [**Contour lines**](/osmand/map/vector-maps#contour-lines) option is clicked in the country, or region map list. It allows you to choose what Contour lines file is needed: in meters, or in feet. 

![Contour lines download dialogue iOS](/assets/images/plugins/contour-lines/ios_cont_lines_meters_feet1.png) 

{% endios%}

{% android%}

The versions - in feet, or meters - are displayed on the download popup, when the [**Contour lines**](/osmand/map/vector-maps#contour-lines) option is clicked in the country, or region map list. It allows you to choose what Contour lines file is needed: in meters, or in feet. 

![Contour lines download dialogue Android](/assets/images/plugins/contour-lines/contour_lines_plugin_download_dialogue_android.png)

{% endandroid%}



### How to download

{% data reusables.general.android-ios-switcher %}

{% default %}

To download Contour lines, Hillshade, and/or Slope for a specific area, do the following:

1. Go to  [Download maps menu](/osmand/start-with/download-maps#download---main-menu).

2. Find your country or region.

3. Choose any of the packages: 
    - Contour lines, 
    - Hillshade, and/or 
    - Slope.

4. For Contour lines, select Meters, or Feet.

5. Download the files. 

![Contour lines download iOS](/assets/images/plugins/contour-lines/contour_lines_plugin_download_ios.png) ![Contour lines download Android](/assets/images/plugins/contour-lines/contour_lines_plugin_download_android.png)

{% enddefault %}

{% ios%}

In the **iOS** version, to download any of the available packages of Contour lines, Hillshade, and/or Slope, do the following:

1. Go to: {% data variables.ios-values.menu %} → {% data variables.ios-values.res_mapsres %} → {% data variables.ios-values.res_worldwide %} 

2. Select a country, and observe any of the following sections:

    2.1. The **{% data variables.ios-values.res_region_map %}** section provides available packages with maps for the entire country. If needed, download ones. 

    2.2.  The **{% data variables.ios-values.res_mapsres %}** section lists the regions of the country. If to tap a region, there will be available map packages to download for the region. 

![Contour lines download iOS](/assets/images/plugins/contour-lines/contour_lines_plugin_download_ios.png)

{% endios%}

{% android%}

In the **Android** version, to download any of the available packages of Contour lines, Hillshade, and/or Slope, do the following:

1. Go to: {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.welmode_download_maps %} → {% data variables.android-values.regions %}

2. Select a country, and observe any of the following sections:

    2.1. The **{% data variables.android-values.region_maps %}** section provides available packages with maps for the entire country. If needed, download ones.

    2.2. The **{% data variables.android-values.regions %}** section lists the regions of the country. If to tap a region, there will be available map packages to download for the region.

![Contour lines download Android](/assets/images/plugins/contour-lines/contour_lines_plugin_download_android.png)

{% endandroid%}


## Show Contour lines/Terrain per profile

Usually as many packages of Contour lines, Hillshade, and/or Slope are downloaded for as many specific areas as needed. Once all downloads are done, it is possible to determine what [map types](/osmand/personal/maps#map-types) to show for what profile. There are two options - Contour lines and/or Terrain - to enable per [profile](/osmand/personal/profiles):

- only Contour lines
- only Terrain
- both Contour lines and Terrain together. 

For the **Terrain** option, it is possible to enable only one map at a time: either **Hillshade**, or **Slope**. You can determine which one of the two is currently on by opening the Terrain settings, where the toggled option will be the one which is currently on. 

{% data reusables.general.android-ios-switcher %}

{% default %}

![Terrain and Contour lines enable Android](/assets/images/plugins/contour-lines/contour_lines_terrain_enable_android.png) ![Terrain and Contour lines enable iOS](/assets/images/plugins/contour-lines/contour_lines_terrain_enable_ios.png)


{% enddefault %}

{% ios%}

#### CONTOUR LINES

In the **iOS** version, to show the **Contour lines** map for the selected profile and all downloaded areas, do the following:

1. Go to: {% data variables.ios-values.menu %} → {% data variables.ios-values.configure_map %}.

2. Scroll down up to **{% data variables.ios-values.map_settings_style %}**, and toggle on the **Contour lines** option. 

![Terrain and Contour lines enable iOS](/assets/images/plugins/contour-lines/contour_lines_terrain_enable_ios.png)

#### TERRAIN

In the **iOS** version, to show one of the **Terrain** maps for the selected profile and all downloaded areas, do the following:

1. Go to: {% data variables.ios-values.menu %} → {% data variables.ios-values.configure_map %}.

2. Scroll down up to **{% data variables.ios-values.map_settings_overunder %}**, toggle on the **Terrain** option, and tap it, to open the context menu, see the figure below.

3. Select one of the options: either **Hillshade**, or **Slope**. 

![Hillshade, or Slope options](/assets/images/plugins/contour-lines/Terrain_menu_ios_selected.png) 


{% endios%}

{% android%}

#### CONTOUR LINES 

In the **Android** version, to show the **Contour lines** map for the selected profile and all downloaded areas, do the following:

1. Go to: {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_map %}

2. Select a Profile, and look for the **{% data variables.android-values.shared_string_show %}** section of settings in the menu.

3. Within the section, scroll down up to **{% data variables.android-values.index_srtm_ele %}**, and toggle on the **Contour lines** option. 

![Terrain and Contour lines enable Android](/assets/images/plugins/contour-lines/contour_lines_terrain_enable_android.png)


#### TERRAIN

In the **Android** version, to show one of the **Terrain** maps for the selected profile and all downloaded areas, do the following:

1. Go to: {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_map %}

2. Select a Profile, and look for the **{% data variables.android-values.shared_string_show %}** section in the menu.

3. Within the section, scroll down up to **{% data variables.android-values.shared_string_terrain %}**, toggle on the **Terrain** option, and tap it, to open the context menu, see the figure below.

4. Select one of the options: either **Hillshade**, or **Slope**. 

![Hillshade, or Slope options](/assets/images/plugins/contour-lines/Terrain_menu_android_selected.png) 


{% endandroid%}


>**NOTE**: If you cannot see the enabled Hillshade, or Slope after downloading the respective map, please restart the application.



## Configure Hillshade

Hillshade allows you to research the relief by highlighting it with the hypothetical  illumination to simulate the cast of shadow, and thus to reveal the curvature, which is normally hidden, or unclear, for example, due to lots of vegetation. There are some aspects of the Hillshade map available for [configuration](/osmand/map/configure-map-menu): transparency of the shadow, the zoom level at which the Hillshade map is expected to be visible. 

The **Hillshade** settings are available in the context menu of the **Terrain** option in the **Configure map** of a specific [profile](/osmand/personal/profiles). 

{% data reusables.general.android-ios-switcher %}

{% default %}

![Terrain menu Android](/assets/images/plugins/contour-lines/terrain_menu_android.png) ![Terrain menu iOS](/assets/images/plugins/contour-lines/terrain_menu_ios.png) 

{% enddefault %}

{% ios%}

- **{% data variables.ios-values.shared_string_enabled %}** - a toggle to show, or hide the terrain data on/from the map;
- **{%  data variables.ios-values.map_settings_hillshade %}** / **{% data variables.ios-values.gpx_slope %}** - a choice to display one of the terrain data types: either Hillshade, or Slope;
- **{% data variables.ios-values.map_settings_layer_transparency %}** - the percentage bar to determine the preferable level of the transparency for the displayed shadow; 
- **{% data variables.ios-values.res_zoom_levels %}** - the minimum and maximum options to tap, to select:
    - the minimum [zoom level](/osmand/map/interact-with-map#my-location--zoom) at which Hillshade is expected to be viewable on the map; and 
    - the maximum zoom level at which it is expected to disappear;
- **{% data variables.ios-values.osmand_live_available_maps %}** - an offer to download a Hillshade package if none is still downloaded for the current geographical location displayed on the screen. 

![Terrain menu iOS](/assets/images/plugins/contour-lines/terrain_menu_ios.png) 

{% endios%}

{% android%}

- **{% data variables.android-values.shared_string_terrain %}** -  a toggle to show, or hide the terrain data on/from the map;
- **{% data variables.android-values.shared_string_hillshade %}** / **{% data variables.android-values.shared_string_slope %}** - a choice to display one of the terrain data types: either Hillshade, or Slope;
- **{% data variables.android-values.shared_string_transparency %}** - the percentage bar to determine the preferable level of the transparency for the displayed shadow; 
- **{% data variables.android-values.shared_string_zoom_levels %}** - two slider options to move to the left, or right, to determine:
    - the minimum [zoom level](/osmand/map/interact-with-map#my-location--zoom) at which Hillshade is expected to be viewable on the map; and 
    - the maximum zoom level at which it is expected to disappear;
- **{% data variables.android-values.welmode_download_maps %}** - an offer to download a Hillshade package if none is still downloaded for the current geographical location displayed on the screen.

![Terrain menu Android](/assets/images/plugins/contour-lines/terrain_menu_android.png) 

{% endandroid%}



## Configure Slope

Slope allows you to research the steepness, or incline of the slope expressed as an angle in the number of degrees of deviation from flat, which corresponds to the vertical distance divided by the horizontal distance. There are some aspects of the Slope map available for [configuration](/osmand/map/configure-map-menu): transparency of the colors used to show the angle, the zoom level at which the Slope map is expected to be visible.

The **Slope** settings are available in the context menu of the **Terrain** option in the **Configure map** of a specific [profile](/osmand/personal/profiles). 

{% data reusables.general.android-ios-switcher %}

{% default %}

![Terrain menu slopes Android](/assets/images/plugins/contour-lines/terrain_menu_slopes_android.png) ![Terrain menu slopes iOS](/assets/images/plugins/contour-lines/terrain_menu_slopes_ios.png) 

{% enddefault %}

{% ios%}

- **{% data variables.ios-values.shared_string_enabled %}** - a toggle to show, or hide the terrain data on/from the map;
- **{%  data variables.ios-values.map_settings_hillshade %}** / **{% data variables.ios-values.gpx_slope %}** - a choice to display one of the terrain data types: either Hillshade, or Slope;
- **{% data variables.ios-values.map_settings_layer_transparency %}** - the percentage bar to determine the preferable level of the transparency for the colors used to show the angle; 
- **{% data variables.ios-values.res_zoom_levels %}** - the minimum and maximum options to tap, to select:
    - the minimum [zoom level](/osmand/map/interact-with-map#my-location--zoom) at which Slope angle colors are expected to be viewable on the map; and 
    - the maximum zoom level at which the colors are expected to disappear;
- **{% data variables.ios-values.map_settings_legend %}** - the legend of colors to show the angle range at which the steepness of the slope can differ. For more details, refer to [Wikipedia](https://en.m.wikipedia.org/wiki/Grade_(slope))
- **{% data variables.ios-values.osmand_live_available_maps %}** - an offer to download a Slope package if none is still downloaded for the current geographical location displayed on the screen. 

![Terrain menu slopes iOS](/assets/images/plugins/contour-lines/terrain_menu_slopes_ios.png) 

{% endios%}

{% android%}

- **{% data variables.android-values.shared_string_terrain %}** -  a toggle to show, or hide the terrain data on/from the map;
- **{% data variables.android-values.shared_string_hillshade %}** / **{% data variables.android-values.shared_string_slope %}** - a choice to display one of the terrain data types: either Hillshade, or Slope;
- **{% data variables.android-values.shared_string_transparency %}** - the percentage bar to determine the preferable level of the transparency for the colors used to show the angle; 
- **{% data variables.android-values.shared_string_zoom_levels %}** - the minimum and maximum options to tap, to select:
    - the minimum [zoom level](/osmand/map/interact-with-map#my-location--zoom) at which Slope angle colors are expected to be viewable on the map; and 
    - the maximum zoom level at which the colors are expected to disappear;
- **{% data variables.android-values.shared_string_legend %}** - the legend of colors to show the angle range at which the steepness of the slope can differ. For more details, refer to [Wikipedia](https://en.m.wikipedia.org/wiki/Grade_(slope))
- **{% data variables.android-values.welmode_download_maps %}** - an offer to download a Slope package if none is still downloaded for the current geographical location displayed on the screen.

![Terrain menu slopes Android](/assets/images/plugins/contour-lines/terrain_menu_slopes_android.png)

{% endandroid%} 


## Configure Contour lines

Contour lines allows you to research in which direction and how much the surface inclines by analyzing the contour lines, which are placed closely for steep ground and more curved when going upward. There are some aspects of the Contour lines map available for [configuration](/osmand/map/configure-map-menu): the minimal zoom level where the contour lines will become visible, color scheme, width and density of lines. 

The **Contour lines** settings are available in the context menu of the **Contour lines** option in the [Configure map](/osmand/map/vector-maps#contour-lines) of a specific [profile](/osmand/personal/profiles). 


{% data reusables.general.android-ios-switcher %}

{% default %}

![Contour lines menu Android](/assets/images/plugins/contour-lines/contour_lines_menu_android.png) ![Contour lines menu iOS](/assets/images/plugins/contour-lines/contour_lines_menu_ios.png) 

{% enddefault %}

{% ios%}

- **{% data variables.ios-values.shared_string_enabled %}** - a toggle to show, or hide the Contour lines on/from the map;
- **{% data variables.ios-values.display_starting_at_zoom_level %}** - the minimum [zoom level](/osmand/map/interact-with-map#my-location--zoom) at which Contour lines is expected to be viewable on the map;
- **{%  data variables.ios-values.map_settings_color_scheme %}** - a choice of color options in which to view the Contour lines on the map;
- **{%  data variables.ios-values.map_settings_line_width %}** - the width of the Contour lines displayed on the map;
- **{%  data variables.ios-values.map_settings_line_density %}** - the density of the Contour lines displayed on the map. The higher the density, the slower the map might be rendered;
- **{% data variables.ios-values.osmand_live_available_maps %}** - an offer to download a Contour lines package if none is still downloaded for the current geographical location displayed on the screen.

![Contour lines menu iOS](/assets/images/plugins/contour-lines/contour_lines_menu_ios.png) 

{% endios%}

{% android%}

- **{% data variables.android-values.shared_string_on %}** -  a toggle to show, or hide the Contour lines on/from the map;
- **{% data variables.android-values.show_from_zoom_level%}** - the minimum [zoom level](/osmand/map/interact-with-map#my-location--zoom) at which Contour lines is expected to be viewable on the map;
- **{% data variables.android-values.srtm_color_scheme %}** - a choice of color options in which to view the Contour lines on the map; 
- **{% data variables.android-values.rendering_attr_contourWidth_name %}** - a choice of the width options to establish for the Contour lines; 
- **{% data variables.android-values.rendering_attr_contourDensity_name %}** - a choice of the density options to establish for the Contour lines. The higher the density, the slower the map might be rendered;
- **{% data variables.android-values.welmode_download_maps %}** - an offer to download a Contour lines package if none is still downloaded for the current geographical location displayed on the screen.

![Contour lines menu Android](/assets/images/plugins/contour-lines/contour_lines_menu_android.png)

{% endandroid%} 


Please see full video guide below:
[Link to Youtube](https://www.youtube.com/watch?v=z8kp_M3FKoc&feature=emb_logo&ab_channel=BartEisenberg)

