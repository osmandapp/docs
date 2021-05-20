---
title: "Map buttons"
intro: "Map buttons such as Zoom buttons, Search, Direction, Compass, My Location and Menu represent main controls on the map."
versions: '*'
---

## My Location & Zoom

![Configure screen menu](/assets/images/widgets/location_zoom_buttons.png)

My location & zoom buttons control the map display. You can read more in [Interact with map](/osmand/map/interact-with-map#my-location--zoom) article.

## Directions

![Directions button allows](/assets/images/widgets/directions_button_allows.png)

**Directions** button allows to [build a route](/osmand/navigation) and [start navigation](/osmand/navigation). In navigation mode this button is not visible by default and it appears after a short tap on the map.

**Directions** button has 3 different indicative states:
- Default grey icon - the route has not been built yet. A dialog to build a new route will appear by click.
- Default blue icon - the route is built, but navigation has not started yet. A dialog with route information will appear by click.
- Blue arrow icon - the route is built and navigation has started. A dialog with route information will appear by click.

## Configure Map

![Configure Map](/assets/images/widgets/configure_map.png)

**Configure Map** button allows to access to [Configure Map menu](/osmand/map/configure-map-menu). Icon on it indicates [Current app profile](/osmand/personal/profiles).

## Main menu

![Main menu button](/assets/images/widgets/main_menu_button.png)

[Main menu](/osmand/starts-with/main-menu) button allows to access to [all features](/osmand/main-menu) of the application. In navigation mode this button is not visible by default. It appears after a short tap on the map.

## Search

![Search button](/assets/images/widgets/search_button.png)

Search button buttons provides quick access from the map to [search capabilities](/osmand/search/).

## Compass

![Compass widget](/assets/images/widgets/compass_widget.png)

Compass widget indicates how map is oriented on the device screen and top arrow / red arrow points where the north of map is located. It also shows the current **[Map orientation mode](/osmand/map/interact-with-map#map-orientation--compass)**. Clicking on the compass will cycle through all Map orientation modes.

**Configure visibility**

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.map_widget_config %} → {% data variables.android-values.map_widget_left %} → {% data variables.android-values.map_widget_compass %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.layer_map_appearance %} → {% data variables.ios-values.map_widget_left %} → {% data variables.ios-values.map_widget_compass %}

Compass widget could be hidden if current orientation mode is `{% data variables.android-values.rotate_map_none_opt %}` and north of the map is pointed exactly to the top of device.
