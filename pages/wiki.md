---
layout: page
title: Wiki
description: 靜態的筆記頁面
keywords: 維基, Wiki, 筆記
comments: false
menu: 維基
permalink: /wiki/
---

> 記多少命令和快捷鍵會讓腦袋爆炸呢？

<ul class="listing">
{% for wiki in site.wiki %}
{% if wiki.title != "Wiki Template" %}
<li class="listing-item"><a href="{{ site.url }}{{ wiki.url }}">{{ wiki.title }}</a></li>
{% endif %}
{% endfor %}
</ul>
