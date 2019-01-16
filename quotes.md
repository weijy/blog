---
layout: page
title: 首页随机出现
---

{% for quote in site.data.quotes %}
    <blockquote>&ldquo;{{ quote.quote }}&rdquo;  <cite>---{{ quote.author }}</cite>
    </blockquote>
{% endfor %}
