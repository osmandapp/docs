---
title: "Wikipedia"
intro: "Having Wikipedia with you on a trip helps to learn more about the places you are visiting. It is available offline, and shows the Wikipedia articles in relation to the points of interest directly on the map."
versions: '*'
---
{% data reusables.general.article-not-complete %}


For the Wikipedia data to show up on the map, the following configuration is required: 

<ol>
	<li>If needed, purchase paid services.</li>
	<li>Enable the Wikipedia plugin in the Plugins section of the main menu.</li> 
	<li>Download the Wikipedia data for the required regions.</li>
	<li>Enable the Wikipedia POI for the needed profile.</li>
</ol>

### Overview 

The Wikipedia plugin is an autonomous functionality that can be enabled/disabled as needed. Once enabled, it allows the Wikipedia data to be downloaded per geographical region. There are two views to display the downloaded Wikipedia knowledge on the map: a short summary, and a full article. 

The short summary is provided via the Wikipedia POI (abbrev. from 'point of interest'). If the Wikipedia option is toggled on in the menu, the Wikipedia POI shows up on the map. On tap, the POI expands and provides a summary of the available Wikipedia information and the option to open the full article. The Wikipedia POI as well as the associated articles are available offline. It is possible to read them whenever needed, switch languages, and search for other Wikipedia information. 


> [Wikipedia](https://en.wikipedia.org/wiki/Wikipedia) is a free, multilingual open-collaborative online encyclopedia created and maintained by a community of volunteer editors using a wiki-based editing system. ![Wikipedia](/assets/images/map/map-wikipedia.png)
<p><br></p>




### Pre-requisites 
Depending on the mobile application you are using, whether it is the Android version, or the iOS version, a [paid subscription](/osmand/purchases) might be required, to allow the Wikipedia plugin to be enabled among other plugins. With the purchase done, Wikipedia Offline can be enabled in the Plugins section of the menu, and then it is possible to download the Wikipedia data for the needed geographical regions. 
<p><br></p>

{% data reusables.general.android-ios-switcher %}

{% ios%}

The **iOS** version provides the Wikipedia plugin by default. To enable the plugin, turn on the **Wikipedia** option in the following menu of the app:
<p><br></p>

&nbsp;&nbsp;&nbsp;&nbsp;{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.plugins %} → {% data variables.ios-values.product_title_wiki %}

{% endios%}

{% android %}

<p>The **Android** version requires one of the following paid services:</p> 
<ul>
	<li>**OsmAnd+** application,</li>
	<li>**OsmAnd Unlimited** in-app for Free version,</li>
	<li>**OsmAnd Live** subscription.</li>
</ul>
<p>Having purchased any of the paid services mentioned above, to enable the Wikipedia plugin, turn on **the Wikipedia** option in the Plugins section of the main menu.</p>

{% endandroid %}





### Download Wikipedia data
The Wikipedia data is available per geographical region. If it is downloaded for one region, and not downloaded for another, in the first case the Wikipedia information can be visible when browsing across the region on the map, and in the other case, the region will lack any Wikipedia information. Being downloaded, the Wikipedia data becomes available in general, as well as offline. 
<p><br></p> 

To download the Wikipedia data for a region, go to the available packages for [download in the main menu](/osmand/start-with/download-maps#download---main-menu), find the needed region and open it. The Wikipedia data will be among other packages.

{% data reusables.general.android-ios-switcher %}

{% ios%}

For the **iOS** version, the Wikipedia data to download per region can be opened, as follows: {% data variables.ios-values.menu %} → {% data variables.ios-values.res_mapsres %} → {% data variables.ios-values.res_worldwide %} 
<p><br></p>

For the **iOS** version, to view what data is already downloaded, go to: {% data variables.ios-values.menu %} → {% data variables.ios-values.res_mapsres %} → {% data variables.ios-values.download_tab_local %}

{% endios%}

{% android %}

For the **Android** version, the Wikipedia data to download per region can be opened, as follows: {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.welmode_download_maps %} → {% data variables.android-values.regions %}
<p><br></p>

For the **Android** version, to view what data is already downloaded, go to: {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.download_tab_local %} → {% data variables.android-values.download_wikipedia_maps %}

{% endandroid %}





### Show/Hide Wikipedia POI per profile
With the Wikipedia data downloaded for the required regions, it is possible to manage the visibility of this data on the map. The visibility is managed via the [Wikipedia POI](/osmand/map/point-layers-on-map#-wikipedia), which can be shown, or hidden for all downloaded regions per specific [profile](/osmand/personal/profiles), such as: a profile for driving a car, a profile for cycling, another one to show the Public Transport, etc. Thus, to show, or hide the Wikipedia POI, select the profile first, and then toggle the **Wikipedia** option on/off.

{% data reusables.general.android-ios-switcher %}

{% ios%}

For the **iOS** version, to show/hide the Wikipedia POI, go to: {% data variables.ios-values.menu %} → {% data variables.ios-values.map_settings_map %} → {% data variables.ios-values.poi_overlay %} → {% data variables.ios-values.res_wiki %} 
![Wikipedia on map iOS](/assets/images/map/map-wikipedia-on-map_ios.png)

{% endios%}

{% android %}

For the **Android** version, to show/hide the Wikipedia POI, go to: {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_map %} → {% data variables.android-values.shared_string_show %} → {% data variables.android-values.shared_string_wikipedia %}
![Wikipedia on map Android](/assets/images/map/map-wikipedia-on-map.png)

{% endandroid %}




### Search Wikipedia

In OsmAnd you can [find Wiki-articles on the map by searching](/osmand/map/point-layers-on-map#-wikipedia) the menu in the left corner of the screen.

![Wikipedia search Android](/assets/images/map/map-wikipedia-search.png) ![Wikipedia search iOS](/assets/images/map/map-wikipedia-search_ios.png)

In {% data variables.android-values.search_categories %} search menu you need to choose {% data variables.android-values.shared_string_wikipedia %} category:

{% data variables.product.android_button_seq %} {% data variables.android-values.map_widget_search %} → {% data variables.android-values.search_categories %} → {% data variables.android-values.shared_string_wikipedia %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.shared_string_search %} → {% data variables.ios-values.categories %} → {% data variables.ios-values.res_wiki %}

You see all the nearest {% data variables.android-values.shared_string_wikipedia %} articles. You can click to "Show Wikipedia on the map" for showing POI on the map:

![Wikipedia search on map Android](/assets/images/map/map-wikipedia-search-on-map.png) ![Wikipedia search on map iOS](/assets/images/map/map-wikipedia-search-on-map_ios.png)




### Filter by language

In OsmAnd for Android, you can select languages for Wikipedia articles on the map:

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_map %} → {% data variables.android-values.shared_string_show %} → {% data variables.android-values.shared_string_wikipedia %} → {% data variables.android-values.shared_string_language %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.android-values.configure_map %} → {% data variables.android-values.shared_string_show %} → {% data variables.android-values.shared_string_wikipedia %} → {% data variables.android-values.shared_string_language %}

![Wikipedia language - iOS](/assets/images/map/map-wikipedia-language-ios.png) ![Wikipedia language - iOS](/assets/images/map/map-wikipedia-language-2-ios.png)

Enjoy Wikipedia on the map in your trip.


