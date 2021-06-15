---
title: "Favorites"
intro: "Favorites is the list of Favorites (user's points) in 'My Places' menu."
versions: '*'
---

{% data reusables.general.article-not-complete %}

Favorites are special points marked by user and by default displayed as yellow star. Though it could be customized with any color, shape and icon. They become visible on the map from the zoom level 6. Any user can add places on the map to Favorites, to save it location and description. Favorites are like user notes on the map.

![Favorites introduction android](/assets/images/personal/favorites_intro_android.png) ![Favorites introduction ios](/assets/images/personal/favorites_intro_ios.png)


## Favorites (My Places)

In order to open Favorites list:

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.shared_string_my_places%} → {% data variables.android-values.favourites %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.menu_my_places %} → {% data variables.ios-values.favorites %}

![My places favorites android](/assets/images/personal/my_places_android.png) ![my_places_ios](/assets/images/personal/my_places_ios.png)


### View

Favorites list in 'My Places' menu is not only a list, but function buttons and switchers. With these we can make any manipulation with Favorites folders and points.

**Android**: Favorites list is a list of Favorites folders, functions buttons, searching.

![Favorites menu android](/assets/images/personal/favorites_menu_android.png)

**iOS**: Favorites list is a list of Favorites folders/points; Editing button; Import/Export buttons.

![Favorites menu iOS](/assets/images/personal/favorites_menu_ios.png)

### Order / Sorting

An order in the Favorites list for Favorites folders is by alfabet. [Personal folder](/osmand/personal/favorites#special-favorites-personal) is the first of the list.

![Favorites folders android](/assets/images/personal/favorites_folders_android.png) ![Favorites folders ios](/assets/images/personal/favorites_folders_ios.png)

An order for Favorites points is by distance from device location (Android) and by alfabet (iOS).

![Favorites points order android](/assets/images/personal/favorites_points_order_android.png) ![Favorites points order ios](/assets/images/personal/favorites_points_order_ios.png)

For iOS version, switching between Folders <-> Points list, you need to use switcher button on top corner of the screen. For Points list, an order for Favorites points is by distance from device location.

![Favorites folders list iOS](/assets/images/personal/favorites_folders_list_ios.png) ![Favorites points list iOS](/assets/images/personal/favorites_points_list_ios.png) 

An order for [searching list (Android)](/osmand/personal/favorites#search-android) is by distance from the map center on the device screen.

### Search (Android)

Searching function opens a points list of Favorites sorted by distance from map center on the device screen.

![Searching menu Favorite android](/assets/images/personal/searching_favorites_menu_android.png)

Click to 'Magnifier' buttons opens seaching menu for Favorites, where user can start to find needed points from Favorites. Clicking to a chosen point opens [Context menu](/osmand/map/map-context-menu#select-an-object-short-tap) of this point.

![Searching menu Favorite android](/assets/images/personal/searching_favorites_menu_2_android.png)


### Actions

The second part is list of folders of Favorites groups. Folder of Favorites is one Favorites group.

User can expand and collapse list of Favorite points for one group by clicking to a folder line or to '&#8743;', '&#8744;'  symbols (Android) and to '&#62;', '&#8744;'  symbols (iOS). Each point from Favorite list has a name, distance and direction from your location.

![Favorites folders expand android](/assets/images/personal/favorites_folders_expand_android.png) ![Favorites folders expand ios](/assets/images/personal/favorites_folders_expand_ios.png)

Click to any point from Favorite list opens [Map Context menu](/osmand/map/map-context-menu#select-an-object-short-tap) for chosen point.

![Favorites context menu android](/assets/images/personal/favorites_context_menu_android.png) ![Favorites context menu ios](/assets/images/personal/favorites_context_menu_ios.png)

Click to '&#8942;' button (**Android**) opens special functions for a chosen Favorite folder.

![Favorites folder functions android](/assets/images/personal/favorites_folder_functions_android.png)

Functions for Favorite folder:
- {% data variables.android-values.edit_name %} - changing folder name.
- {% data variables.android-values.change_color %} - changing folder color.
- {% data variables.android-values.shared_string_show_on_map %} - showing or not Favorite points from the folder on the map.
- {% data variables.android-values.shared_string_add_to_map_markers %} or {% data variables.android-values.remove_from_map_markers %}  - add or remove all Favorite points from a folder in [Map markers list](/osmand/personal/markers).
- {% data variables.android-values.shared_string_share %} - sharing Favorite points with other users (like Favorites.gpx file).
- Button '{% data variables.android-values.shared_string_cancel %}' - close this menu.


At the bottom of the screen are four Actions buttons. 

![Favorites actions android](/assets/images/personal/favorites_actions_android.png)

Actions:
- '&#43;' - allows to import Favorites points (favorite.gpx) from device storage.
- '&#60;' - allows to export (share) all Favorites points like "favorite.gpx" file.
- '&#128681;' - allows to add or to remove chosen Favorites points (folders) in [Map markers](/osmand/personal/markers) list.
- '&#x1F5D1;' - allows to delete chosen Favorites points (folders).

Click to 'Pencil' button (**iOS**) opens special functions for a chosen Favorite folder. You need to choose folder or points for actions.

![Favorites actions ios](/assets/images/personal/favorites_actions_ios.png)

Actions:
- 'Import loader' - allows to share/import Favorites points (folders) like "favorite.gpx" file.
- 'Folder' - allows to move your Favorites points (folders) to others Favorites folders (named Groups) or to new creating folders (Group). 
- 'Palette of colors' - allows to change colors for Favorites points (folders).
- 'BIN' - allows to delete chosen Favorites points (folders).

Export/Import favorite for iOS version like special menu in "My Favorites" menu.

![Favorites export import ios](/assets/images/personal/favorites_export_import_ios.png)

'{% data variables.ios-values.fav_import_title %}' - {% data variables.ios-values.fav_import_desc %}. 

'{% data variables.ios-values.fav_export_title %}' - You can export all your favorites like Favorites.gpx file.


## Favorite Point



### View on the map

Favorites are one of the vector layers on the map. User can show or not Favorites and their names on the map:

[Switch on/off favorites on the map](/osmand/map/point-layers-on-map#favorites)  - 'Configure map' menu

[Switch on/off favorite names](/osmand/map/point-layers-on-map#favorite--poi-names)  - 'Configure map' menu

![Favotires layer Android](/assets/images/map/favorites_layer.png) ![Favotires layer iOS](/assets/images/map/favorites_layer_ios.png)

### Favorite Context menu

Click to favorite point on "My Favorites" menu or on favorite point on the map opens [Map Context menu](/osmand/map/map-context-menu#favorites--track-points-from-the-group). Where user can find needed information about point or [add/edit favorite point](/osmand/map/map-context-menu#add--edit-favorite).

### Create

For creating new Favorite an user needs [to tap on the map](/osmand/map/map-context-menu#select-any-point-long-tap) at the place where he wants to add Favorite. 

When an user clicks at chosen place appeares ['Map Context menu'](/osmand/map/map-context-menu) with ['Action menu'](/osmand/map/map-context-menu#add--edit-favorite). 

Click to [**Add**](/osmand/map/map-context-menu#add--edit-favorite) for opening 'Add favorite' menu.

![Favorite add menu Android](/assets/images/personal/favorite_add_android.png) ![Favorite add menu iOS](/assets/images/personal/favorite_add_ios.png)

Here you can add: name, description, address for favorite. 

![Favorite add description Android](/assets/images/personal/favorite_add_descr_android.png) ![Favorite add description iOS](/assets/images/personal/favorite_add_descr_ios.png)

Select Favorite group (folder) for your favorite point or add new group (folder).

![Favorite group Android](/assets/images/personal/favorite_group_android.png) ![Favorite group iOS](/assets/images/personal/favorite_group_ios.png)

For adding new favorite group(folder), you need to add name, to select color. This color will be used for all new favorites added to the group by default.

![Favorite new group Android](/assets/images/personal/favorite_new_group_android.png) ![Favorite new group iOS](/assets/images/personal/favorite_new_group_ios.png)

Next, you can select icon for your favorite from our list.

![Favorite icon Android](/assets/images/personal/favorite_icon_android.png) ![Favorite icon iOS](/assets/images/personal/favorite_icon_ios.png)

After, you can choose color and shape for favorite icon.

![Favorite color and shape Android](/assets/images/personal/favorite_color_shape_android.png) ![Favorite color and shape iOS](/assets/images/personal/favorite_color_shape_ios.png)

In 'Actions', you can replace another point with this. For Android, this 'Replace' button repeats in up corner of 'Add favorite' menu.

After creation, you can click 'Save' button for saving new Favorite point or 'Cancel' button for canceling point creation.

![Favorite actions Android](/assets/images/personal/favorite_actions_android.png) ![Favorite actions iOS](/assets/images/personal/favorite_actions_ios.png)

### Edit

For editing a Favorite point an user need [to short tap](/osmand/map/map-context-menu#select-an-object-short-tap) on chosen a Favorite point.

After that, you need to click ['Edit favorite' button on 'Map Context menu'](/osmand/map/map-context-menu#add--edit-favorite). 

'Edit favorite' menu opens. It's look like ['Add favorite' menu](/osmand/personal/favorites#create). But in Action part there is one more action - 'Delete' button. For Android, there is additional 'Delete' button in up corner of 'Edit favorite' menu. 

![Favorite edit Android](/assets/images/personal/favorite_edit_android.png) ![Favorite edit iOS](/assets/images/personal/favorite_edit_ios.png)

You can change name, description, address for chosen favorite, change or create new group for it, select another icon, color and shap, replace another point with this.


### Search 

Using [Search function](/osmand/search) of OsmAnd.

Using Search in 'My Favorites' menu (only for Android).

## Favorite Groups 


### Change color

**Android:**

Click to '&#8942;' button (**Android**) opens special functions for a chosen Favorite folder.

![Favorites folder functions android](/assets/images/personal/favorites_folder_functions_android.png)

Functions for Favorite folder:
- {% data variables.android-values.edit_name %} - changing folder name.
- {% data variables.android-values.change_color %} - changing folder color.
- {% data variables.android-values.shared_string_show_on_map %} - showing or not Favorite points from the folder on the map.
- {% data variables.android-values.shared_string_add_to_map_markers %} or {% data variables.android-values.remove_from_map_markers %}  - add or remove all Favorite points from a folder in [Map markers list](/osmand/personal/markers).
- {% data variables.android-values.shared_string_share %} - sharing Favorite points with other users (like Favorites.gpx file).
- Button '{% data variables.android-values.shared_string_cancel %}' - close this menu.

**iOS:**

Click to 'Pencil' button (**iOS**) opens special functions for a chosen Favorite folder. You need to choose folder or points for action: to change colors for Favorites points (folders).

![Favorites actions ios](/assets/images/personal/favorites_actions_ios.png)

### Bulk move (iOS)

Click to 'Pencil' button (**iOS**) opens special functions for a chosen Favorite folder. You need to choose folder or points for action: to move your Favorites points (folders) to others Favorites folders (named Groups) or to new creating folder (Group).

![Favorites actions ios](/assets/images/personal/favorites_actions_ios.png)

### Rename (Android)

TODO text. 

### Bulk delete

TODO text. 

### Add to Map Markers (Android)

TODO text.

## Special Favorites (Personal) 

"Personal" folder is a special folder for '{% data variables.android-values.favorite_home_category %}' and '{% data variables.android-values.work_button %}' points of [Navigation Context menu](/osmand/navigation). This folder doesn't have '&#8942;' button, because you can not change the parameters for this folder. 

![Favorites personal android](/assets/images/personal/favorites_personal_android.png)

## Export / Import

TODO text. 
