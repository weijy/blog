---
layout: page
title: 首页随机出现
---

{% for quote in site.data.quotes %}

> {{ quote.quote }}

<p class="cite">——{{ quote.author }}</p>

{% endfor %}
<!--
<div id="all_quotes"></div>
-->