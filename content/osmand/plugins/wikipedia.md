---
title: "Wikipedia"
intro: "Having Wikipedia with you on a trip helps to learn more about the places you are visiting. It is available offline, and shows the Wikipedia articles in relation to the points of interest directly on the map."
versions: '*'
---
{% data reusables.general.article-not-complete %}


For the Wikipedia data to show up on the map, the following configuration is required: 

1. If needed, purchase paid services.

2. Enable the Wikipedia plugin in the Plugins section of the main menu.

3. Download the Wikipedia data for the required regions.

4. Enable the Wikipedia POI for the needed profile.


## Overview 

The Wikipedia plugin is an autonomous functionality that can be enabled/disabled as needed. Once enabled, it allows the Wikipedia data to be [downloaded](/osmand/personal/maps#download-maps-maps) per geographical region. There are two views to display the downloaded Wikipedia knowledge on the map: a short summary, and a full article. 

The short summary is provided via the Wikipedia POI (abbrev. from '[point of interest](/osmand/map/point-layers-on-map)'). If the Wikipedia option is toggled on in the menu, the Wikipedia POI shows up on the map. On tap, the POI expands and provides a summary of the available Wikipedia information and the option to open the full article. The Wikipedia POI as well as the associated articles are available offline. It is possible to read them whenever needed, switch languages, and search for other Wikipedia information. 


> [Wikipedia](https://en.wikipedia.org/wiki/Wikipedia) is a free, multilingual open-collaborative online encyclopedia created and maintained by a community of volunteer editors using a wiki-based editing system. ![Wikipedia](/assets/images/map/map-wikipedia.png)
<p><br></p>




## Prerequisites 

Depending on the mobile application you are using, whether it is the Android version, or the iOS version, a [paid subscription](/osmand/purchases) might be required, to allow the Wikipedia plugin to be enabled among other plugins. 

{% data reusables.general.android-ios-switcher %}

{% default%}

With the purchase done, Wikipedia Offline can be enabled in the Plugins section of the menu, and then it is possible to download the Wikipedia data for the needed geographical regions.

![Wikipedia plugin in iOS](/assets/images/plugins/wikipedia/Wikipedia_plugin_ios2.png) ![Wikipedia plugin in Android](/assets/images/plugins/wikipedia/Wikipedia_plugin_android2.png)

{% enddefault %}

{% ios%}

The **iOS** version provides the Wikipedia plugin by default. To enable the plugin, turn on the **Wikipedia** option in the following menu of the app: {% data variables.ios-values.menu %} → {% data variables.ios-values.plugins %} → {% data variables.ios-values.product_title_wiki %}

![Wikipedia plugin in iOS](/assets/images/plugins/wikipedia/Wikipedia_plugin_ios2.png)

{% endios%}

{% android %}

The **Android** version requires one of the [paid services](/osmand/purchases/android#free-and-paid-features): in-app purchases, or a subscription. Having made a purchase, to enable the Wikipedia plugin, turn on the **Wikipedia** option in the Plugins section of the main menu.

![Wikipedia plugin in Android](/assets/images/plugins/wikipedia/Wikipedia_plugin_android2.png)

{% endandroid %}



## Download Wikipedia data

The Wikipedia data is available per geographical region. If it is downloaded for one region, and not downloaded for another, in the first case it would be possible to work with the Wikipedia information when browsing across the region on the map, and in the other case, the region will lack any Wikipedia information. Being downloaded, the Wikipedia data becomes available in general, as well as offline. 

{% data reusables.general.android-ios-switcher %}

{% default %}

To download the Wikipedia data for a region, go to the [available packages for download in the main menu](/osmand/start-with/download-maps#download---main-menu), find the needed region and open it. The Wikipedia data will be among other packages.

![Download Wikipedia in iOS](/assets/images/plugins/wikipedia/download_wikipedia_ios2.png) ![Download Wikipedia in Android](/assets/images/plugins/wikipedia/download_wikipedia_android2.png)

{% enddefault %}


{% ios%}

In the **iOS** version, the Wikipedia data to download per region can be opened, as follows: {% data variables.ios-values.menu %} → {% data variables.ios-values.res_mapsres %} → {% data variables.ios-values.res_worldwide %} and select the required region. Once the region is opened, the Wikipedia data will be among other packages. To view what data is already downloaded, go to: {% data variables.ios-values.menu %} → {% data variables.ios-values.res_mapsres %} → {% data variables.ios-values.download_tab_local %}

![Download Wikipedia in iOS](/assets/images/plugins/wikipedia/download_wikipedia_ios2.png) 

{% endios%}

{% android %}

In the **Android** version, the Wikipedia data to download per region can be opened, as follows: {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.welmode_download_maps %} → {% data variables.android-values.regions %} and select the required region. Once the region is opened, the Wikipedia data will be among other packages. To view what data is already downloaded, go to: {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.download_tab_local %} → {% data variables.android-values.download_wikipedia_maps %}

![Download Wikipedia in Android](/assets/images/plugins/wikipedia/download_wikipedia_android2.png)

{% endandroid %}





## Show/Hide Wikipedia POI 

With the Wikipedia data downloaded for the required regions, it is possible to manage the visibility of this data on the map. The visibility is managed via the [Wikipedia POI](/osmand/map/point-layers-on-map#-wikipedia), which can be shown, or hidden for all downloaded regions per specific [profile](/osmand/personal/profiles), such as: a profile for driving a car, a profile for cycling, another one to show the Public Transport, etc. 

{% data reusables.general.android-ios-switcher %}

{% default %}

To show, or hide the Wikipedia POI, select the profile first, and then toggle the **Wikipedia** option on/off.

![Wikipedia POI on iOS](/assets/images/map/map-wikipedia-on-map_ios.png) ![Wikipedia POI on Android](/assets/images/map/map-wikipedia-on-map.png)

{% enddefault %}

{% ios%}

In the **iOS** version, to show/hide the Wikipedia POI, go to: {% data variables.ios-values.menu %} → {% data variables.ios-values.configure_map %} → <*specific Profile*> →  {% data variables.ios-values.map_settings_show %} → {% data variables.ios-values.res_wiki %} 

![Wikipedia POI on iOS](/assets/images/map/map-wikipedia-on-map_ios.png) 

{% endios%}

{% android %}

In the **Android** version, to show/hide the Wikipedia POI, go to: {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_map %} → <*specific Profile*> → {% data variables.android-values.shared_string_show %} → {% data variables.android-values.shared_string_wikipedia %}

![Wikipedia POI on Android](/assets/images/map/map-wikipedia-on-map.png)

{% endandroid %}








## Search Wikipedia

With the Wikipedia data downloaded, regardless of the visibility mode of the [Wikipedia POI](/osmand/map/point-layers-on-map#-wikipedia) on the map, it is possible to [search](/osmand/search/search-poi) for any Wikipedia information.


{% data reusables.general.android-ios-switcher %}

{% default %}

By tapping Search, an extra pane pops up and allows you to search everything, and/or by the specific category. In the first case, the search results will show the Wikipedia POI with associated Wikipedia articles among other types of the information. In case of the search by the Wikipedia category, the search results will show only the Wikipedia information sorted by the nearest location in relation to the area of the map currently viewable on the screen. 

![Wikipedia category on iOS](/assets/images/map/map-wikipedia-search-on-map_ios.png) ![Wikipedia category on Android](/assets/images/map/map-wikipedia-search-on-map.png) 

{% enddefault %}


{% ios%}

In the **iOS** version, tap the Search icon in the left-hand top corner of the screen. 

![Wikipedia search on iOS](/assets/images/map/map-wikipedia-search_ios.png)

To search by the Wikipedia category, select: {% data variables.ios-values.shared_string_search %} → {% data variables.ios-values.categories %} → {% data variables.ios-values.res_wiki %}

![Wikipedia category on iOS](/assets/images/map/map-wikipedia-search-on-map_ios.png)

If needed, tap the **Show Wikipedia on the map** option at the top of the search panel, and the search results retrieved by the Wikipedia category will show up on the map. 

{% endios%}

{% android %}

In the **Android** version, you can use:

- the Search icon in the left-hand top corner of the screen, and/or
- the Search option in the menu.

![Wikipedia search on Android](/assets/images/map/map-wikipedia-search.png) 

To search by the Wikipedia category, select: {% data variables.android-values.map_widget_search %} → {% data variables.android-values.search_categories %} → {% data variables.android-values.shared_string_wikipedia %}

![Wikipedia category on Android](/assets/images/map/map-wikipedia-search-on-map.png) 

If needed, tap the **Show Wikipedia on the map** option at the top of the search panel, and the search results retrieved by the Wikipedia category will show up on the map. 

{% endandroid %}



## Wikipedia languages 

{% data reusables.general.android-ios-switcher %}

{% default %}

In case when there is a choice of languages to display the Wikipedia data in, you can set the language you prefer to read the text in. The figure below shows an example of the Wikipedia POI and the article, which are written in French by default, and displayed in English, thanks to the availability of other translations for this Wikipedia data and the English language established for the Wikipedia in the Profile settings. 

![French Wikipedia POI in English in iOS](/assets/images/plugins/wikipedia/ios_wiki_language2.png) ![French Wikipedia POI in English](/assets/images/plugins/wikipedia/Andr-french-wikipedia-in-eng1.png) 

{% enddefault %}

{% ios%}

With the preferred language established for Wikipedia, for example, a French POI will show the text in English. 

![French Wikipedia POI in English in iOS](/assets/images/plugins/wikipedia/ios_wiki_language2.png)

{% endios%}

{% android %}

With the preferred language established for Wikipedia, for example, a French POI will show the text in English. 

![French Wikipedia POI in English](/assets/images/plugins/wikipedia/Andr-french-wikipedia-in-eng1.png) 

{% endandroid %}


### Set preferred language

{% data reusables.general.android-ios-switcher %}

{% default %}

To set the preferred language, so that to view the Wikipedia data in, go to the required profile, click the triple dots beside the **Wikipedia** option, and in the opened list, deselect **All language** and check a specific option. In case of some languages selected, the displayed text will be in any of the languages. 

![Setting a preferred language on iOS](/assets/images/map/map-wikipedia-language-2-ios.png) ![Setting a preferred language on Android](/assets/images/plugins/wikipedia/Android-wiki-languages.png)

{% enddefault %}

{% ios%}

In the **iOS** version, to set the preferred language for the Wikipedia data, do the following:

1. Go to: {% data variables.ios-values.menu %} → {% data variables.ios-values.configure_map %}.

2. Select a profile and find the {% data variables.ios-values.map_settings_show %} section of settings.

3. Tap {% data variables.ois-values.res_wiki %} and then tap {% data variables.ios-values.language %}. 

4. Check the preferred language(-s) in the opened list. 


![Setting a preferred language on iOS](/assets/images/map/map-wikipedia-language-2-ios.png) 

{% endios%}

{% android %}

In the **Android** version, to set the preferred language for the Wikipedia data, do the following:

1. Go to: {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_map %}.

2. Select a profile and find the {% data variables.android-values.shared_string_show %} section of settings.

3. Tap {% data variables.android-values.shared_string_wikipedia %} and then tap {% data variables.android-values.shared_string_language %}. 

4. Check the preferred language(-s) in the opened list. 

![Setting a preferred language on Android](/assets/images/plugins/wikipedia/Android-wiki-languages.png) 

{% endandroid %}

### Switch languages inside article

{% data reusables.general.android-ios-switcher %}

{% default %}

In case if some translation options are available, it is possible to switch the language when viewing a specific Wikipedia article. A language icon at the right-hand top area of the article will offer the options for selection. 

![Switching languages for a specific article in iOS](/assets/images/plugins/wikipedia/ios_switch_lang_inside_article2.png) ![Switching languages for a specific article](/assets/images/plugins/wikipedia/Andr-french-wikipedia-in-eng3.png) 

{% enddefault %}

{% ios%}

In the **iOS** version, with the Wikipedia POI turned on for a specific profile, it is enough to tap a POI, then scroll the opened context menu upwards till viewing an abstract of the Wikipedia article:

- tap the article, 
- tap the current language icon in the header at the right-hand top corner of the screen, and the list of available language options opens,
- select the required language. 

![Switching languages for a specific article in iOS](/assets/images/plugins/wikipedia/ios_switch_lang_inside_article2.png) 

{% endios%}

{% android %}
In the **Android** version, with the Wikipedia POI turned on for a specific profile, it is enough to tap a POI, then scroll the opened context menu upwards till viewing an abstract of the Wikipedia article:

- tap the article, 
- tap the current language icon in the header at the right-hand top corner of the screen, and the list of available language options opens,
- select the required language.


![Switching languages for a specific article](/assets/images/plugins/wikipedia/Andr-french-wikipedia-in-eng3.png) 

{% endandroid %}