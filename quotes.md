---
layout: page
title: 首页随机出现
---

{% for quote in site.data.quotes %}

> {{ quote.quote }} <cite>—— {{ quote.author }}</cite>

{% endfor %}
