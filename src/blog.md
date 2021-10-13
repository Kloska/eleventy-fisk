---
title: "Blog"
layout: "base.njk"
templateEngineOverride: njk,md
---

## Lilla Bloggen

<ul>
{% for post in collections.posts %}
<li><a href="{{ post.url }}"> {{ post.data.title }} </a></li>
{% endfor %}
</ul>    