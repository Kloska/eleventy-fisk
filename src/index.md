---

title: "Trooper Fisk"
layout: "base.njk"
templateEngineOverride: njk,md
---

### Fisk fisk fisk

### Från bloggen

{% for post in collections.post | randomPost %}
<a href="{{ post.url }}">{{ post.data.title }}</a>
{% endfor %}