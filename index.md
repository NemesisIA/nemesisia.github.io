---
layout: home
title: "The Alignment Architect"
---

# Derniers articles

{% for post in site.posts %}
## [{{ post.title }}]({{ post.url }})
*{{ post.date | date: "%d/%m/%Y" }}*

{{ post.excerpt }}

[Lire la suite]({{ post.url }})
---
{% endfor %}
