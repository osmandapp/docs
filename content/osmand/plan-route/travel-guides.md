---
title: "Travel Guides"
intro: "Travel Guides (Android): enjoy offline guides for basically any destination. "
versions: '*'
---
{% data reusables.general.article-not-complete %}


## Travel Guides data

The guides are based on [Wikivoyage](https://www.wikivoyage.org/), a community project similar to Wikipedia, where volunteer writers create articles with real and up-to-date information. Such information includes the main facts about a place, transport, landmarks, shopping spots, etc. Going to London, Shanghai or planning a visit to the Grand Canyon? Your guide is there to help you.

## How to use

To start using the feature, please go to OsmAnd menu-> Travel guides. Make sure to download the travel guide file to be able to use the feature. This file is also available in Download map-> 'Travel guides' menu. Now all your guides are saved on device and you can look up any information, even if you're abroad or out of a mobile network area.

As soon as the file is downloaded, you can start using the guides. Just go to OsmAnd-> 'Travel guides' and enter the name of the city into the search field. As soon as you open the article, you'll see the information conveniently arranged by topic. The information often includes topics like 'Understand' with the details about local culture and habits, 'Talk', 'Get in', 'Get Around', 'See' that covers main places of interest, 'Buy' with the recommended shopping spots, 'Sleep', 'Drink', and 'Go next' suggesting the locations you may be interested in after visiting the current one. You can also press 'Bookmark' to have a quick access to this article later. All such articles will be saved in your 'Bookmarked articles' list.

The articles are sharable. Just press Share button in the upper-right corner and send it to your friend. That person will be able to open your link in OsmAnd directly if they have the app on their device.

### Download 

OsmAnd menu - Download maps - Travel guides

### Options

You can also choose if you'd like to download the images or not, clear image cache or delete the search history. To do that, please press the 'Options' button in the upper-right corner of the screen.

(Image not available offline) (Image not available offline)
The articles are available in different languages. By default, the language you're using in OsmAnd will be also picked for Travel guides. But if you'd like, you can view your article in a different one. To do that, press the translation button next to the name of the article.

For example, the article about London is available in Chinese, Dutch, English, French, German and many other languages.

### Points

Articles often contain points grouped by topic. They are available in the 'Points' menu at the bottom of the article. You'll see food locations, airports, railway stations, places to shop, main historical attractions, accommodation options, etc. To view them all on the map, please enable 'Show on map' option. The track with the points will be also available in My places-> My tracks-> Travel. To remove the points from the map, please go to 'Configure map' menu and disable the 'GPX track' option.


## Other guides

Besides the city guides, you can read about regions or countries, and even scroll through special guides like the list of UNESCO Global Geoparks Network or even a phrasebook of a country you're visiting. To see more exciting articles, please see the 'Explore' tab of the travel guides menu.

## Building Travel book

Custom Travel - creating your one-of-a-kind travel guide

Custom Travel tool helps you create your own travel guide and use it via OsmAnd Travel feature. Basically, you can use the text from any source (from Wikipedia to your friend's blog) and pair it with a GPX track.

 
### Prepare the files

To start, please prepare your files. Save your track with '.GPX' extension and the text file as '.html'. In order to create your custom database successfully, the names of the GPX file and the html have to be identical. For example, 'Milan.gpx' and 'Milan.html'.

The GPX tracks can be downloaded from the internet or you can create one (using OsmAnd or any online GPX creation tool).

For example, you can use Brouter, or a simialr one.

Add the points you'd like to visit into your route and then save that route as a GPX track. .

Preparing your GPX track in OsmAnd is also possible, you can read about it here: Plan a route.

Choosing the source for your guide's text is completely up to you. It can be an article in a travel blog, a Wikipedia page, etc. Simply copy the text, then paste it into a text editor and save it with an 'HTML' extension. Make sure to make the name of the GPX track and the HTML file identical.

### Launch the tool

[Download OsmAnd MapCreator](http://download.osmand.net/latest-night-build/OsmAndMapCreator-main.zip)
Linux.

Download MapCreator and extract the files from the archive.
Start your console and open the MapCreator folder.

Example: cd /home/user/OsmAndMapCreator-main/

Run ./utilites.sh travel-guide-creator
When asked to provide the path, please paste the path to the folder where you have your files prepared.

Example: cd /home/user/MyCustomGuides/

We do not recommend locating your files in the 'TravelGuideCreator' folder itself. Kindly see the 'Read me' file for step-by-step commands.

Windows. Open utilities.bat file.

### Import files

Your file should be created in seconds. By default, it will be named 'travel_guide.sqlite', but you can rename it as you want making sure to save it with 'sqlite' file extension. For example, 'Milan_weekend_tour.sqlite'. After that, please transfer it to your device. Specifically, to the folder where OsmAnd travel guides are stored. You can check the path to that folder in 'OsmAnd > Settings > General > Data storage folder > Manually specified. Please copy the file there using any mobile file manager or by connecting your phone to computer. Restart the app.

### Use your guide

After you start the app, please go to 'Travel' menu. Press Options > 'Travel book' to select your database as a source. After that, you'll be able to use search normally in order to view the articles. You'll find all the points from your GPX track in 'Points' menu. Please use 'Show on map' button to view your points on the map. You can bookmark any article to have a quicker access to it.

