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
<p>Depending on the mobile application you are using, whether it is the Android version, or the iOS version, a <a href="/osmand/purchases">paid subscription</a> might be required, to allow the Wikipedia plugin to be enabled among other plugins. With the purchase done, Wikipedia Offline can be enabled in the Plugins section of the menu, and then it is possible to download the Wikipedia data for the needed geographical regions. </p>

{% data reusables.general.android-ios-switcher %}

{% ios%}

The <strong>iOS</strong> version provides the Wikipedia plugin by default. To enable the plugin, turn on the <strong>Wikipedia</strong> option in the following menu of the app: {% data variables.ios-values.menu %} → {% data variables.ios-values.plugins %} → {% data variables.ios-values.product_title_wiki %}

{% endios%}

{% android %}

<p>The <strong>Android</strong> version requires one of the following paid services:</p> 
<ul>
	<li><strong>OsmAnd+</strong> application,</li>
	<li><strong>OsmAnd Unlimited</strong> in-app for Free version,</li>
	<li><strong>OsmAnd Live</strong> subscription.</li>
</ul>
<p>Having purchased any of the paid services mentioned above, to enable the Wikipedia plugin, turn on the <strong>Wikipedia</strong> option in the Plugins section of the main menu.</p>

{% endandroid %}





### Download Wikipedia data
<p>The Wikipedia data is available per geographical region. If it is downloaded for one region, and not downloaded for another, in the first case it would be possible to work with the Wikipedia information when browsing across the region on the map, and in the other case, the region will lack any Wikipedia information. Being downloaded, the Wikipedia data becomes available in general, as well as offline. </p>

To download the Wikipedia data for a region, go to the available packages for [download in the main menu](/osmand/start-with/download-maps#download---main-menu), find the needed region and open it. The Wikipedia data will be among other packages.

{% data reusables.general.android-ios-switcher %}

{% ios%}

<p>For the <strong>iOS</strong> version, the Wikipedia data to download per region can be opened, as follows: </p>
&nbsp;&nbsp;&nbsp;&nbsp;{% data variables.ios-values.menu %} → {% data variables.ios-values.res_mapsres %} → {% data variables.ios-values.res_worldwide %} 

<p>For the <strong>iOS</strong> version, to view what data is already downloaded, go to: </p>
&nbsp;&nbsp;&nbsp;&nbsp;{% data variables.ios-values.menu %} → {% data variables.ios-values.res_mapsres %} → {% data variables.ios-values.download_tab_local %}

{% endios%}

{% android %}

<p>For the <strong>Android</strong> version, the Wikipedia data to download per region can be opened, as follows:</p> 
&nbsp;&nbsp;&nbsp;&nbsp;{% data variables.android-values.shared_string_menu %} → {% data variables.android-values.welmode_download_maps %} → {% data variables.android-values.regions %}

<p>For the <strong>Android</strong> version, to view what data is already downloaded, go to: </p>
&nbsp;&nbsp;&nbsp;&nbsp;{% data variables.android-values.shared_string_menu %} → {% data variables.android-values.download_tab_local %} → {% data variables.android-values.download_wikipedia_maps %}

{% endandroid %}





### Show/Hide Wikipedia POI 
With the Wikipedia data downloaded for the required regions, it is possible to manage the visibility of this data on the map. The visibility is managed via the [Wikipedia POI](/osmand/map/point-layers-on-map#-wikipedia), which can be shown, or hidden for all downloaded regions per specific [profile](/osmand/personal/profiles), such as: a profile for driving a car, a profile for cycling, another one to show the Public Transport, etc. Thus, to show, or hide the Wikipedia POI, select the profile first, and then toggle the **Wikipedia** option on/off.

{% data reusables.general.android-ios-switcher %}

{% ios%}

For the **iOS** version, to show/hide the Wikipedia POI, go to: {% data variables.ios-values.menu %} → {% data variables.ios-values.configure_map %} → <*specific Profile*> →  {% data variables.ios-values.map_settings_show %} → {% data variables.ios-values.res_wiki %} 

<p align="center"><img src="/assets/images/map/map-wikipedia-on-map_ios.png" alt="Wikipedia POI on iOS"></p>

{% endios%}

{% android %}

For the **Android** version, to show/hide the Wikipedia POI, go to: {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_map %} → <*specific Profile*> → {% data variables.android-values.shared_string_show %} → {% data variables.android-values.shared_string_wikipedia %}

<p align="center"><img src="/assets/images/map/map-wikipedia-on-map.png" alt="Wikipedia POI on Android"></p>

{% endandroid %}








### Search Wikipedia

With the Wikipedia data downloaded, regardless of the visibility mode of the <a href="/osmand/map/point-layers-on-map#-wikipedia">Wikipedia POI</a> on the map, it is possible to search for any Wikipedia information.


{% data reusables.general.android-ios-switcher %}

{% ios%}
For the <strong>iOS</strong> version, tap the Search icon in the left-hand top corner of the screen. 

<p align="center"><img src="/assets/images/map/map-wikipedia-search_ios.png" alt="Wikipedia search on iOS"></p>

{% endios%}

{% android %}
For the <strong>Android</strong> version, you can use:
<ul>
	<li>the Search icon in the left-hand top corner of the screen, and/or</li>
	<li>the Search option in the menu.</li>
</ul>
<p align="center"><img src="/assets/images/map/map-wikipedia-search.png" alt="Wikipedia search on Android"></p>

{% endandroid %}

By tapping Search, an extra pane pops up and allows you to search everything, and/or by the specific category. In the first case, the search results will show the Wikipedia POI with associated Wikipedia articles among other types of the information. In case of the search by the Wikipedia category, the search results will show only the Wikipedia information sorted by the nearest location in relation to the area of the map currently viewable on the screen. 

{% data reusables.general.android-ios-switcher %}

{% ios%}
<p>To search by the Wikipedia category, select:</p>

&nbsp;&nbsp;&nbsp;&nbsp;{% data variables.product.ios_button_seq %} {% data variables.ios-values.shared_string_search %} → {% data variables.ios-values.categories %} → {% data variables.ios-values.res_wiki %}

<p align="center"><img src="/assets/images/map/map-wikipedia-search-on-map_ios.png" alt="Wikipedia category on iOS"></p>
{% endios%}

{% android %}
<p>To search by the Wikipedia category, select:</p>

&nbsp;&nbsp;&nbsp;&nbsp;{% data variables.product.android_button_seq %} {% data variables.android-values.map_widget_search %} → {% data variables.android-values.search_categories %} → {% data variables.android-values.shared_string_wikipedia %}

<p align="center"><img src="/assets/images/map/map-wikipedia-search-on-map.png" alt="Wikipedia category on Android"></p>

{% endandroid %}

<p><br></p>

<p> If needed, tap the <strong>Show Wikipedia on the map</strong> option at the top of the search panel, and the search results retrieved by the Wikipedia category will show up on the map.</p> 



### Set language for Wikipedia

In case when there is a choice of languages to display the Wikipedia data in, you can set the language you prefer to read the text in. The figure below shows an example of the Wikipedia POI and the article, which are written in French by default, and displayed in English, thanks to the availability of other translations for this Wikipedia data and the English language established for the Wikipedia in the Profile settings. 

<p align="center"><img src="/assets/images/plugins/wikipedia/Andr-french-wikipedia-in-eng1.png" alt="French Wikipedia POI in English"></p>


To set the preferred language, so that to view the Wikipedia data in, go to the required profile, click the triple dots beside the **Wikipedia** option, and in the opened list, deselect **All language** and check a specific option. In case of some languages selected, the displayed text will be in any of the languages. 


{% data reusables.general.android-ios-switcher %}

{% ios%}

For the **iOS** version, to set the preferred language for the Wikipedia data, go to: 

&nbsp;&nbsp;&nbsp;&nbsp;{% data variables.ios-values.menu %} → {% data variables.ios-values.configure_map %} → <*specific Profile*> → {% data variables.ios-values.map_settings_show %} → {% data variables.ois-values.res_wiki %} → {% data variables.ios-values.language %} → {% data variables.ios-values.preferred_languages %}


<p align="center"><img src="/assets/images/map/map-wikipedia-language-2-ios.png" alt="Setting a preferred language on iOS"></p>

{% endios%}

{% android %}

For the **Android** version, to set the preferred language for the Wikipedia data, go to: 

&nbsp;&nbsp;&nbsp;&nbsp;{% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_map %} → <*specific Profile*> → {% data variables.android-values.shared_string_show %} → {% data variables.android-values.shared_string_wikipedia %} → {% data variables.android-values.shared_string_language %}

<p align="center"><img src="/assets/images/plugins/wikipedia/Android-wiki-languages.png" alt="Setting a preferred language on Android"></p>

{% endandroid %}

In case if some translation options are available, it is possible to switch the language when viewing a specific Wikipedia article. A language icon at the right-hand top area of the article will offer the options for selection. 

<p align="center"><img src="/assets/images/plugins/wikipedia/Andr-french-wikipedia-in-eng3.png" alt="Switching languages for a specific article"></p>
