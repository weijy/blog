---
layout: default
---

<section>

	<ul>
        {% for post in site.posts %}
        <li>
            <span class="code">{{ post.date | date: '%Y %b %d' }}</span> - <a href="{{ post.url }}">{{ post.title }}</a>
        </li>
        {% endfor %}
    </ul>

</section>
