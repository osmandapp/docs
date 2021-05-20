---
title: "Main menu"
intro: "The 'Main menu' is a primary list of options available to use in the application. It contains profile configuration, features, settings."
versions: '*'
---
{% data reusables.general.article-not-complete %}

- Make similar description of Main menu to [Configure map menu](/osmand/map/configure-map-menu)
- explain each item in the drawer with links if they are not present
- explain how to configure items list in the drawer

The Main menu icon &#8801; is located on the left bottom corner of the Map screen. In navigation mode this button is not visible by default. It appears after a short tap on the map. 

| | |
|------------|------------|
| **Android** | **iOS** |
|add picture|add picture|

**Main menu** divides into 3 parts:
- [Profiles menu] ()
- Features
- Settings

## Profiles menu
In this section is available to manage navigation [profiles](osmand/personal/profiles). 
- When you press on gray 'arrow' on the top bar appears the list of [profile types](osmand/personal/profiles#profile-types). 
- When you press on the 'Configure profile' text, entering the [profile settings](osmand/personal/profiles#profile-settings) menu.

## Features
| | | |
|------------|------------|------------|
|Name|Description|Contains|
|[Map markers](osmand/widgets/markers)|Selected points marked as flags on the map|Two kind of list view (as list and as groups), history, more|
|My places|------------|------------|
|Search|------------|------------|
|Trip recording|------------|------------|
|Directions|------------|------------|
|Configure map|------------|------------|
|Download maps|------------|------------|
|Travel guides (Beta)|----------|------------|
|Plan route|------------|------------|

## Settings
- [Configure screen](osmand/widgets/configure-screen) - is a menu that allows to configure what widgets will be displayed over the map
- [Plugins](osmand/plugins) - is a list of additional functionality
- [Settings](write separately settings description)
- [Help] (write help page description)

## UI Customization (Android)

It is a menu where the user can reorder or hide items from the Drawer, to see hidden items from the menu, copy the list of items from the another profile and reset to default settings.

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %} → {% data variables.android-values.ui_customization %} → {% data variables.android-values.shared_string_drawer%}

![Drawer menu items ](/assets/images/settings/drawer_menu_items.png)

The *bin on the left* side of the item will remove the item from the main list.
Spin up or down the *line on the right* will give an opportunity to move the item up or down along the list.

The items that was moved to the bin would be moved to the section 'Hidden' below. They and can be restored by clicking the green button on the left.

![Drawer menu hidden items ](/assets/images/settings/drawer_menu_hidden_items.png)

