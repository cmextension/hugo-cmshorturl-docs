---
title: Logs
weight: 80
---

If you enable logging, CM Short URL stores the requests to your shorten URLs. In Joomla! back-end, navigate to `Components` -> `CM Short URL` -> `Logs`.

![](/images/cmshorturl_log_list.jpg)

The logged information is based on the information in the request from visitor. It is calculated the same as Hits value in URL list (using session).

Referral webiste is where visitor clicks short URL. If this information is not available then visitor may directly access short URL or the information is not included in the request.

Web browser column includes 2 icons for web browser and operating system. You can hover your mouse pointer over the icons to see the names of web browser/operating system.

IP address field contains the IP address from which visitor accesses short URL.

If your site is big and has many visitors coming to your site from short URLs, enabling logging may increase the size of your database because the number logged accesses is so big, so you may consider to disable logging.