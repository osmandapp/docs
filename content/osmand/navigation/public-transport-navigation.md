---
title: "Public Transport navigation"
intro: "Public Transport navigation is your help during trips in cities"
versions: '*'
---
{% data reusables.general.article-not-complete %}

Public Transport navigation allows our users to work out their routes using public transport, which will certainly help one to move through the concrete jungle faster. 

Data of Public route lines is from [OpenStreetMap project](http://openstreetmap.org/), OsmAnd uses [PTv2 scheme](https://wiki.openstreetmap.org/wiki/Public_transport) for Public transport navigation.

![Navigation public transport Android](/assets/images/navigation/public/navigation_android.png) ![avigation public transport iOS](/assets/images/navigation/public/navigation_ios.png)

## How to use

To start the navigation in your city by public transport, you need to use [the navigation button](/osmand/widgets/map-buttons#directions) on the map screen. Or choose navigation option in the main menu:

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.shared_string_navigation %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.routing_settings %}

- You need to choose Public transport navigation profile, start an destination points.

![Navigation public transport way Android](/assets/images/navigation/public/navigation_way_android.png) ![avigation public transport way iOS](/assets/images/navigation/public/navigation_way_ios.png)

OsmAnd proposes route variants with walking time and publict transport routes. You need to swap navigation screen for choosing your variant.

![Navigation public transport way Android](/assets/images/navigation/public/navigation_way_android.png) ![avigation public transport way iOS](/assets/images/navigation/public/navigation_way_ios.png)

"Show on map" button allow to view all chosen route on the map (swap menu to view the next route variant)
Click to "Details" button for open Description menu of choosing route. 
Here you can open all stops list by clicking to "" button.

![Navigation public transport way Android](/assets/images/navigation/public/navigation_way_android.png) ![avigation public transport way iOS](/assets/images/navigation/public/navigation_way_ios.png)

**Note**: Public transport navigaiton in OsmAnd has testing variant. While you can build and view your route without full navigation function.

## Data for public transport

OsmAnd use New Public Transport Schema that is also called Public Transport Version 2 (PTv2) for OsmAnd Public Transport navigation algorithm. You can check your public transport [here](http://tools.geofabrik.de/osmi/). Guidelines on how to build or correct public transport routes is provided in [our blog](https://osmand.net/blog/guideline-pt).

## Read more

- [Guideline for public transport](https://osmand.net/blog/guideline-pt).
- [Presentation in SotM-2019](https://www.youtube.com/watch?v=SPab09kaWPc&ab_channel=StateoftheMap).
