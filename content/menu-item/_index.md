---
title: Menu Item
weight: 60
---

There is only 1 front-end menu item for CM Short URL, it is called `Short URL`. This menu item is required and used as the parent menu item of shortened URLs to prevent conflicts with other menu items and other components on the site. If you don't have this menu item you will get the message

	Menu item for "Short URL (hidden menu item)" menu item type is not found.
	You need to create one otherwise short URLs don't work.

After you create the menu item, the message disappears.

This `Short URL` menu item needs to be used a hidden menu item. Hidden menu or hidden menu item are not visible in your front-end.

If you don't have any hidden menu yet, you create one by navigating to `Menus` -> `Manage` -> `New`.

![](/images/cmshorturl_hidden_menu.jpg)

To create a new menu item in this menu, you go to `Menus` -> Your hidden menu's name -> `New` or click the `+` button next to your hidden menu's name.

![](/images/cmshorturl_menu_item.jpg)

In the form, you click `Select` button of `Menu Item Type` field, in the modal window you select `Short URL (hidden menu item)` in `CM Short URL` section.

![](/images/cmshorturl_menu_item_type.jpg)

Give the menu item a title and a short value for `Alias` option, this alias value decides what your short URLs look like. For example of your alias is `go` like in the screenshot below, then the shortened URLs could look like this: `http://www.yoursite.com/go/my-web-page`

![](/images/cmshorturl_menu_item_form.jpg)

`go` alias is inspired by NASA's shortening URL system - for example [https://go.nasa.gov/mars2020pass](https://go.nasa.gov/mars2020pass).