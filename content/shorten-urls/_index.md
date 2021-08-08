---
title: Shortened URLs
weight: 70
---

In Joomla! back-end, navigate to `Components` -> `CM Short URL` to access the list of short URLs.

![](/images/cmshorturl_empty_url_list.jpg)

Click `New` button on the toolbar to create new short URL.

![](/images/cmshorturl_url_form.jpg)

Enter the long URL into `URL` field. If you use `Google Analytics`, select `Campaign`, `UTM source` and `UTM content`.

If you leave `Alias` field empty, a random alias will be generated for you. The length of this alias is the limit which you configure in the component's configuration. If you want to have a meaningful and easy to remember alias, you need the alias you want to use into the field.

When you have short URLs, the list of short URLs looks similar to the below screen shot.

![](/images/cmshorturl_url_list.jpg)

The `Hits` column displays how many times short URL is visited. We use session to check for unique hit, so if you visit a URL again and again in a browser, they are only counted as 1 hit

The last column in the list is the icon which open short URL in a new browser/tab when you click. You can test to see if your short URL by clicking the icon of it.