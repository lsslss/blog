---
layout: page
title: Links
description: 友情連結
keywords: 友情連結
comments: true
menu: 連結
permalink: /links/
---

> God made relatives. Thank God we can choose our friends.

{% for link in site.data.links %}
* [{{ link.name }}]({{ link.url }})
{% endfor %}
