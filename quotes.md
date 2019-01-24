---
layout: page
title: 首页随机出现
---

{% for quote in site.data.quotes %}

> {{ quote.quote }}

——{{ quote.author }}{: .cite}

{% endfor %}
<!--
<div id="all_quotes"></div>
-->