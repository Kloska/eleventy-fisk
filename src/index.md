---

title: "Trooper Fisk"
layout: "base.njk"
templateEngineOverride: njk,md
---

### Fisk fisk fisk

### Från bloggen

{% for post in collections.posts | randomPost %}
<a href="{{ post.url }}">{{ post.data.title }}</a>
{% endfor %}

## Ursäkta röran

Jag är väl medveten om att min hemsida ej fungerar speciellt bra. Jag jobbar på ändringar, men ingen skillnad kommer ske.