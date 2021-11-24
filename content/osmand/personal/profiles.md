---
title: "Profiles (Settings)"
intro: "Each profile is available for full customization. In fact, each profile can become a separate application for the needs of the user."
versions: '*'
---

{% data reusables.general.article-not-complete %}


{% android %}

To start setting up an application profile:

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %} (Browse map or any other profile)

![Profiles Settings Android](/assets/images/personal/profiles/profile_settings_android.png)

{% endandroid %}

{% ios %}

To start setting up an application profile:

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.sett_settings %} → {% data variables.ios-values.app_profiles %}

![Profiles Settings iOS](/assets/images/personal/profiles/profile_settings_ios.png)

{% endios %}

## Profile configuration

This section contains all the settings related to the appearance, navigation settings, map rendering, configure menu, and screen of a profile.

{% note %}
All settings affect the selected application profile only.
{% endnote %}

{% android %}

![Profiles Settings Android](/assets/images/personal/profiles/profile_settings_menu_android.png)

{% endandroid %}

{% ios %}

![Profiles Settings iOS](/assets/images/personal/profiles/profile_settings_menu_ios.png)

{% endios %}


### General settings

This section of settings contains settings of the cursor on the map and map view, settings of units & formats of map and profile data, settings of external input devices, and other sensors.

{% android %}

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %} (Browse map or any other profile) → {% data variables.android-values.general_settings_2 %}

{% endandroid %}

{% ios %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.sett_settings %} → {% data variables.ios-values.app_profiles %} → {% data variables.ios-values.general_settings_2 %}

{% endios %}

#### **Appearance**

In this section of the General settings menu, you can set parameters for the cursor on the map and map view for the chosen profile.

{% android %}

![Profiles General Settings Appearance Android](/assets/images/personal/profiles/profile_gs_appearance_android.png)

- {% data variables.android-values.choose_osmand_theme %} - sets a day or night theme for the application. This setting doesn't change ["Map mode"](/osmand/map/vector-maps#map-mode) parameter.
- {% data variables.android-values.rotate_map_to_bearing %} - allows [to set orientation the map view](/osmand/map/interact-with-map#map-orientation-modes).
- {% data variables.android-values.always_center_position_on_map %} - allows to use center or bottom screen position for the cursor (["My location"](/osmand/map/interact-with-map#my-location--zoom)). In this mode the center of the map will be located slightly below the center of the device. It allows seeing more map information ahead of your movement which is usable in the navigation mode.
- {% data variables.android-values.map_screen_orientation %} - sets the screen position for the OsmAnd application: {% data variables.android-values.map_orientation_portrait %}, {% data variables.android-values.map_orientation_landscape %}, {% data variables.android-values.map_screen_orientation %}.
- {% data variables.android-values.screen_control %} - opens [the screen control menu](/osmand/navigation/route-navigation#turn-on-screen), where you can select parameters for your device screen during navigation for keeping device battery consumption.

{% endandroid %}

{% ios %}

![Profiles General Settings Apperance iOS](/assets/images/personal/profiles/profile_gs_appearance_ios.png)

- {% data variables.ios-values.rotate_map_to_bearing %} - allows [to set orientation the map view](/osmand/map/interact-with-map#map-orientation-modes).
- {% data variables.ios-values.allow_3D_view%} - enables/disables 2.5D view of the map view. Use ["Gesture"](/osmand/map/interact-with-map#gestures) or ["My Location button"](/osmand/map/interact-with-map#my-location--zoom) for 3D view
- {% data variables.ios-values.always_center_position_on_map %} - allows to use center or bottom screen position for the cursor (["My location"](/osmand/map/interact-with-map#my-location--zoom)). In this mode the center of the map will be located slightly below the center of the device. It allows seeing more map information ahead of your movement which is usable in the navigation mode.

{% endios %}


#### **Units & formats**

In this section you can set parameters of units & formats for chosen application profile.

{% android %}

![Profiles General Settings Units & formats Android](/assets/images/personal/profiles/profile_gs_unitsformats_android.png)

| Parameter | Format | Note |
|:------------|:---------------|:---------------|
|**{% data variables.android-values.driving_region %}**| {% data variables.android-values.driving_region_automatic %} |  |
|            | {% data variables.android-values.driving_region_europe_asia %}   | {% data variables.android-values.right_side_navigation %}, {% data variables.android-values.si_km_m %}  |
|            | {% data variables.android-values.driving_region_us %}   |  {% data variables.android-values.right_side_navigation %}, {% data variables.android-values.si_mi_feet %}  |
|            | {% data variables.android-values.driving_region_canada %}   | {% data variables.android-values.right_side_navigation %}, {% data variables.android-values.si_km_m %}   |
|            | {% data variables.android-values.driving_region_uk %}   |  {% data variables.android-values.left_side_navigation %}, {% data variables.android-values.si_mi_feet %}   |
|            | {% data variables.android-values.driving_region_japan %}   | {% data variables.android-values.left_side_navigation %}, {% data variables.android-values.si_km_m %}   |
|            | {% data variables.android-values.driving_region_australia %}   |  {% data variables.android-values.left_side_navigation %}, {% data variables.android-values.si_km_m %}  |
|**{% data variables.android-values.unit_of_length %}**| {% data variables.android-values.si_km_m %} |  |
|          | {% data variables.android-values.si_mi_feet %} |  |
|          | {% data variables.android-values.si_mi_meters %} |  |
|          | {% data variables.android-values.si_mi_yard %} |  |
|          | {% data variables.android-values.si_nm %} |  |
|**{% data variables.android-values.coordinates_format %}**| {% data variables.android-values.dd_mm_mmmm_format %} | Example: 50.12333° 19.93233° (Lat Long) |
|          | {% data variables.android-values.dd_mm_mmm_format %} | Example: 50°7.393′ 19°55.941′ (Lat Long)  |
|          | {% data variables.android-values.dd_mm_ss_format %} | Example: 50°7′23.6″ 19°55′56.4″ (Lat Long) 23°27′30″ |
|          | {% data variables.android-values.navigate_point_format_utm %} | 34N 5552876 423678 (Zone Northing Easting) . [{% data variables.android-values.utm_format_descr %}](https://en.wikipedia.org/wiki/Universal_Transverse_Mercator_coordinate_system) |
|          | {% data variables.android-values.navigate_point_format_mgrs %} | Example: 34U DA 23678 52873 . [{% data variables.android-values.mgrs_format_descr %}](https://en.wikipedia.org/wiki/Military_Grid_Reference_System)  |
|          | {% data variables.android-values.navigate_point_format_olc %} | Example:  9F2X4WFJ+7W ([Open Location Code](https://en.wikipedia.org/wiki/Open_Location_Code) represents area 9m x 14m)  |
|**{% data variables.android-values.coordinates_format %}**| Degrees 180° | All angular values have readings from 0° to 180° and from 0° to -180°.  |
|          | Degrees 360° | All angular values have readings from 0° to 360°.  |
|          | {% data variables.android-values.shared_string_milliradians %} | All angular values have [milliradian value](https://en.wikipedia.org/wiki/Milliradian).  |
|**{% data variables.android-values.default_speed_system %}**| {% data variables.android-values.si_kmh %} | 90 km/h  |
|          | {% data variables.android-values.si_mph %} | 55.92 mph  |
|          | {% data variables.android-values.si_m_s %} | 30 m/s |
|          | {% data variables.android-values.si_min_m %} | 1.073 min/m |
|          | {% data variables.android-values.si_min_km %} | 0.667 min/km |
|          | {% data variables.android-values.si_nm_h %} | 48.59 kn |

#### **Other**

In this section, you can enable/disable buttons and input devices for OsmAnd, on or off animations for navigation mode, use or not fullscreen mode, magnetic sensor, Kalman filter.

![Profiles General Settings Other Android](/assets/images/personal/profiles/profile_gs_other_android.png)


- {% data variables.android-values.use_volume_buttons_as_zoom %} - allows to use or not volume buttons of a device as [zoom](/osmand/map/interact-with-map#my-location--zoom).
- [{% data variables.android-values.use_kalman_filter_compass %}](/osmand/map/interact-with-map#extra-compass-settings) - allows to use or not [Kalman filter](https://en.wikipedia.org/wiki/Kalman_filter) for smoothen rotation of the map with a slower rotation animation though it introduces a small delay (< 1 second) till.
- [{% data variables.android-values.use_magnetic_sensor %}](/osmand/map/interact-with-map#extra-compass-settings) - allows to use or not [Magnetic sensor](https://en.wikipedia.org/wiki/Kalman_filter) for smoothen rotation of the map with a slower rotation animation though it introduces a small delay (< 1 second) till.
- {% data variables.android-values.tap_on_map_to_hide_interface %} - use or not fullscreen mode of OsmAnd app on the device.
- [{% data variables.android-values.do_not_use_animations %}](/osmand/map/interact-with-map#disable-all-animations) - allows to switch on/off animation for navigation mode. 
- [{% data variables.android-values.external_input_device %}](/osmand/map/interact-with-map#external-input-device-buttons) - allows adding external input devices for control OsmAnd app by buttons of these devices. External input devices: {% data variables.android-values.sett_wunderlinq_ext_input %}, {% data variables.android-values.sett_generic_ext_input %}, {% data variables.android-values.sett_parrot_ext_input %}.

{% endandroid %}

{% ios %}

![Profiles General Settings Units & formats iOS](/assets/images/personal/profiles/profile_gs_unitsformats_ios.png)

- {% data variables.android-values.driving_region %} - 
- {% data variables.android-values.unit_of_length %} - 
- {% data variables.android-values.coordinates_format %} - 
- {% data variables.android-values.angular_measeurement %} - 
- {% data variables.android-values.default_speed_system %} - 

{% endios %}

#### Other

![Profiles General Settings Other Android](/assets/images/personal/profiles/profile_gs_other_android.png)

- {% data variables.android-values.external_input_device %} - {% data variables.android-values.sett_wunderlinq_ext_input %}, {% data variables.android-values.sett_generic_ext_input %}, {% data variables.android-values.sett_parrot_ext_input %}(Android).
- {% data variables.android-values.use_volume_buttons_as_zoom %}(Android) -  
- {% data variables.android-values.use_kalman_filter_compass %}(Android) -  
- {% data variables.android-values.use_magnetic_sensor %}(Android) -  
- {% data variables.android-values.tap_on_map_to_hide_interface %}(Android) -  
- {% data variables.android-values.do_not_use_animations %}(Android) -  

{% android %}

![Profiles General Settings Other iOS](/assets/images/personal/profiles/profile_gs_unitsformats_ios.png)

- {% data variables.android-values.use_volume_buttons_as_zoom %}(Android) -  
- {% data variables.android-values.use_kalman_filter_compass %}(Android) -  
- {% data variables.android-values.use_magnetic_sensor %}(Android) -  
- {% data variables.android-values.tap_on_map_to_hide_interface %}(Android) -  
- {% data variables.android-values.do_not_use_animations %}(Android) -  
- {% data variables.android-values.external_input_device %} - {% data variables.android-values.sett_wunderlinq_ext_input %}, {% data variables.android-values.sett_generic_ext_input %}, {% data variables.android-values.sett_parrot_ext_input %}(Android).

{% endandroid %}

{% ios %}

![Profiles General Settings Other iOS](/assets/images/personal/profiles/profile_gs_unitsformats_ios.png)

- {% data variables.android-values.external_input_device %} - {% data variables.android-values.sett_wunderlinq_ext_input %}, {% data variables.android-values.sett_generic_ext_input %}, {% data variables.android-values.sett_parrot_ext_input %}(Android).
- {% data variables.android-values.use_volume_buttons_as_zoom %}(Android) -  
- {% data variables.android-values.use_kalman_filter_compass %}(Android) -  
- {% data variables.android-values.use_magnetic_sensor %}(Android) -  
- {% data variables.android-values.tap_on_map_to_hide_interface %}(Android) -  
- {% data variables.android-values.do_not_use_animations %}(Android) -  

{% endios %}

### Navigation settings

Not for Browse profile

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %} → {% data variables.android-values.routing_settings_2 %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.sett_settings %} → {% data variables.ios-values.app_profiles %} → {% data variables.ios-values.routing_settings_2 %}

![Profiles Navigation Settings Android](/assets/images/personal/profiles/profile_navigation_settings_android.png) ![Profiles Navigation Settings iOS](/assets/images/personal/profiles/profile_navigation_settings_ios.png)

{% android %}
Not for Browse profile

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %} → {% data variables.android-values.routing_settings_2 %}

![Profiles Navigation Settings Android](/assets/images/personal/profiles/profile_navigation_settings_android.png)

{% endandroid %}

{% ios %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.sett_settings %} → {% data variables.ios-values.app_profiles %} → {% data variables.ios-values.routing_settings_2 %}

![Profiles Navigation Settings iOS](/assets/images/personal/profiles/profile_navigation_settings_ios.png)

{% endios %}

#### Navigation

- {% data variables.android-values.nav_type_hint %} - link
- {% data variables.android-values.route_parameters %} - link
- {% data variables.android-values.screen_alerts %} - [link](https://docs.osmand.net/en/main@latest/osmand/widgets/nav-widgets#alert-widget)
- {% data variables.android-values.voice_announcements %} - link
- {% data variables.android-values.vehicle_parameters %} - link

{% android %}

- {% data variables.android-values.nav_type_hint %} - link
- {% data variables.android-values.route_parameters %} - link
- {% data variables.android-values.screen_alerts %} - [link](https://docs.osmand.net/en/main@latest/osmand/widgets/nav-widgets#alert-widget)
- {% data variables.android-values.voice_announcements %} - link
- {% data variables.android-values.vehicle_parameters %} - link


Cuztomize route line 

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %} → {% data variables.android-values.profile_appearance %} → {% data variables.android-values.customize_route_line %}

![Profile Appearance route line Android](/assets/images/personal/profiles/profile_appearance_route_line_android.png)

- {% data variables.android-values.shared_string_color %} - 0
- {% data variables.android-values.select_track_width %} - 


{% endandroid %}

{% ios %}

- {% data variables.android-values.nav_type_hint %} - link
- {% data variables.android-values.route_parameters %} - link
- {% data variables.android-values.screen_alerts %} - [link](https://docs.osmand.net/en/main@latest/osmand/widgets/nav-widgets#alert-widget)
- {% data variables.android-values.voice_announcements %} - link
- {% data variables.android-values.vehicle_parameters %} - link


{% endios %}

#### Other

- {% data variables.android-values.map_during_navigation %} - link
- {% data variables.android-values.animate_my_location %}(Android) - description

{% android %}

- {% data variables.android-values.map_during_navigation %} - link
- {% data variables.android-values.animate_my_location %}(Android) - description

{% endandroid %}

{% ios %}

- {% data variables.android-values.map_during_navigation %} - link
- {% data variables.android-values.animate_my_location %}(Android) - description


{% endios %}


### Configure map

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %} → {% data variables.android-values.configure_map %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.sett_settings %} → {% data variables.ios-values.app_profiles %} → {% data variables.ios-values.configure_map %}

Set parameters for [Configure map](/osmand/map/configure-map-menu) menu for chosen profile.
[LINK](/osmand/map/configure-map-menu)

![Profiles Configure map Settings Android](/assets/images/personal/profiles/profile_configure_map_settings_android.png) ![Profiles Configure map Settings iOS](/assets/images/personal/profiles/profile_configure_map_settings_ios.png)

{% android %}

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %} → {% data variables.android-values.configure_map %}

Set parameters for [Configure map](/osmand/map/configure-map-menu) menu for chosen profile.
[LINK](/osmand/map/configure-map-menu)

![Profiles Configure map Settings Android](/assets/images/personal/profiles/profile_configure_map_settings_android.png)

{% endandroid %}

{% ios %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.sett_settings %} → {% data variables.ios-values.app_profiles %} → {% data variables.ios-values.configure_map %}

Set parameters for [Configure map](/osmand/map/configure-map-menu) menu for chosen profile.
[LINK](/osmand/map/configure-map-menu)

![Profiles Configure map Settings iOS](/assets/images/personal/profiles/profile_configure_map_settings_ios.png


{% endios %}


### Configure screen

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %} → {% data variables.android-values.layer_map_appearance %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.sett_settings %} → {% data variables.ios-values.app_profiles %} → {% data variables.ios-values.layer_map_appearance %}

Set parameters for [Configure screen](/osmand/widgets/configure-screen) menu for chosen profile.
[LINK](/osmand/widgets/configure-screen)

![Profiles Configure screen Settings Android](/assets/images/personal/profiles/profile_configure_screen_settings_android.png) ![Profiles Configure screen Settings iOS](/assets/images/personal/profiles/profile_configure_screen_settings_ios.png)

{% android %}

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %} → {% data variables.android-values.layer_map_appearance %}

![Profiles Configure screen Settings Android](/assets/images/personal/profiles/profile_configure_screen_settings_android.png)

{% endandroid %}

{% ios %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.sett_settings %} → {% data variables.ios-values.app_profiles %} → {% data variables.ios-values.layer_map_appearance %}

![Profiles Configure screen Settings iOS](/assets/images/personal/profiles/profile_configure_screen_settings_ios.png)

{% endios %}

### Profile appearance

Change profile appearance

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %} → {% data variables.android-values.profile_appearance %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.sett_settings %} → {% data variables.ios-values.app_profiles %} → {% data variables.ios-values.profile_appearance %}

{% android %}

Change profile appearance

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %} → {% data variables.android-values.profile_appearance %}

{% endandroid %}

{% ios %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.sett_settings %} → {% data variables.ios-values.app_profiles %} → {% data variables.ios-values.profile_appearance %}

{% endios %}


#### Name, Color, Icon

![Profile Appearance Android](/assets/images/personal/profiles/profile_appearance_settings_android.png) ![Profile Appearance iOS](/assets/images/personal/profiles/profile_appearance_settings_ios.png)

- {% data variables.android-values.profile_type_osmand_string %}(Android) - link
- {% data variables.android-values.profile_name_hint %} - 
- {% data variables.android-values.select_color %} - 
- {% data variables.android-values.select_icon_profile_dialog_title %} - 

{% android %}

![Profile Appearance Android](/assets/images/personal/profiles/profile_appearance_settings_android.png)

- {% data variables.android-values.profile_type_osmand_string %}(Android) - link
- {% data variables.android-values.profile_name_hint %} - 
- {% data variables.android-values.select_color %} - 
- {% data variables.android-values.select_icon_profile_dialog_title %} - 

{% endandroid %}

{% ios %}

![Profile Appearance iOS](/assets/images/personal/profiles/profile_appearance_settings_ios.png)

- {% data variables.android-values.profile_type_osmand_string %}(Android) - link
- {% data variables.android-values.profile_name_hint %} - 
- {% data variables.android-values.select_color %} - 
- {% data variables.android-values.select_icon_profile_dialog_title %} - 

{% endios %}


#### Appearance on the map

![Profile Appearance on the map Android](/assets/images/personal/profiles/profile_appearance_map_android.png) ![Profile Appearance on the map iOS](/assets/images/personal/profiles/profile_appearance_map_ios.png)

- {% data variables.android-values.select_navigation_icon %} - 
- {% data variables.android-values.select_map_icon %} - 

{% android %}

![Profile Appearance on the map Android](/assets/images/personal/profiles/profile_appearance_map_android.png)

- {% data variables.android-values.select_navigation_icon %} - 
- {% data variables.android-values.select_map_icon %} - 

{% endandroid %}

{% ios %}

![Profile Appearance on the map iOS](/assets/images/personal/profiles/profile_appearance_map_ios.png)

- {% data variables.android-values.select_navigation_icon %} - 
- {% data variables.android-values.select_map_icon %} - 

{% endios %}


### UI Customization

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %} → {% data variables.android-values.ui_customization %}

Turn off unused [plugins](/osmand/personal/profiles#plugin-settings-android) for hide all their controls.

![Profile UI Customization Android](/assets/images/personal/profiles/profile_ui_customization_android.png)

{% android %}

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %} → {% data variables.android-values.ui_customization %}

Turn off unused [plugins](/osmand/personal/profiles#plugin-settings-android) for hide all their controls.

![Profile UI Customization Android](/assets/images/personal/profiles/profile_ui_customization_android.png)

{% endandroid %}

{% ios %}


{% endios %}

#### Drawer

Reorder or hide items from the Drawer. 
Button:
- minus
- reset
- move

![Profile UI Customization Drawer Android](/assets/images/personal/profiles/profile_ui_customization_drawer_android.png) ![Profile UI Customization Drawer 1 Android](/assets/images/personal/profiles/profile_ui_customization_drawer_1_android.png)

- {% data variables.android-values.reset_to_default %} - 
- {% data variables.android-values.copy_from_other_profile %} - 

{% android %}

Reorder or hide items from the Drawer. 
Button:
- minus
- reset
- move

![Profile UI Customization Drawer Android](/assets/images/personal/profiles/profile_ui_customization_drawer_android.png) ![Profile UI Customization Drawer 1 Android](/assets/images/personal/profiles/profile_ui_customization_drawer_1_android.png)

- {% data variables.android-values.reset_to_default %} - 
- {% data variables.android-values.copy_from_other_profile %} - 

{% endandroid %}

{% ios %}


{% endios %}

#### Configure map

Reorder or hide items from the [Configur map](/osmand/map/configure-map-menu).
Button:
- minus
- reset
- move

![Profile UI Customization Configure map Android](/assets/images/personal/profiles/profile_ui_customization_configure_map_android.png) ![Profile UI Customization Configure map 1 Android](/assets/images/personal/profiles/profile_ui_customization_configure_map_1_android.png)

- {% data variables.android-values.reset_to_default %} - 
- {% data variables.android-values.copy_from_other_profile %} - 

{% android %}

Reorder or hide items from the [Configur map](/osmand/map/configure-map-menu).
Button:
- minus
- reset
- move

![Profile UI Customization Configure map Android](/assets/images/personal/profiles/profile_ui_customization_configure_map_android.png) ![Profile UI Customization Configure map 1 Android](/assets/images/personal/profiles/profile_ui_customization_configure_map_1_android.png)

- {% data variables.android-values.reset_to_default %} - 
- {% data variables.android-values.copy_from_other_profile %} - 

{% endandroid %}

{% ios %}


{% endios %}

#### Context menu actions

Reorder or hide items from the [Context menu actions](/osmand/map/map-context-menu).
Button:
- minus
- reset
- move
- 
![Profile UI Customization Context menu Android](/assets/images/personal/profiles/profile_ui_customization_context_menu_android.png) ![Profile UI Customization Context menu 1 Android](/assets/images/personal/profiles/profile_ui_customization_context_menu_1_android.png)

{% android %}

Reorder or hide items from the [Context menu actions](/osmand/map/map-context-menu).
Button:
- minus
- reset
- move
- 
![Profile UI Customization Context menu Android](/assets/images/personal/profiles/profile_ui_customization_context_menu_android.png) ![Profile UI Customization Context menu 1 Android](/assets/images/personal/profiles/profile_ui_customization_context_menu_1_android.png)

{% endandroid %}

{% ios %}


{% endios %}

## Plugin settings

Settings of plugin for chosen profile
[Link to Plugins](https://docs.osmand.net/en/main@latest/osmand/plugins)

{% android %}


{% endandroid %}

{% ios %}


{% endios %}

### Trip recording

link

### Audio / Video notes

### OpenStreetMap editing

### OpenPlaceReviews

### Accesibility

### OsmAnd developmnet

## Actions

![Profiles Actions Settings Android](/assets/images/personal/profiles/profile_actions_settings_android.png) ![Profiles Actions Settings iOS](/assets/images/personal/profiles/profile_actions_settings_ios.png)

- {% data variables.android-values.export_profile %}
- {% data variables.android-values.copy_from_other_profile %}
- {% data variables.android-values.map_widget_reset %}
- {% data variables.android-values.profile_alert_delete_title %}

{% android %}

![Profiles Actions Settings Android](/assets/images/personal/profiles/profile_actions_settings_android.png)

- {% data variables.android-values.export_profile %}
- {% data variables.android-values.copy_from_other_profile %}
- {% data variables.android-values.map_widget_reset %}
- {% data variables.android-values.profile_alert_delete_title %}

{% endandroid %}

{% ios %}

![Profiles Actions Settings iOS](/assets/images/personal/profiles/profile_actions_settings_ios.png)
- {% data variables.android-values.export_profile %}
- {% data variables.android-values.copy_from_other_profile %}
- {% data variables.android-values.map_widget_reset %}
- {% data variables.android-values.profile_alert_delete_title %}

{% endios %}
