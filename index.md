---
layout: default
title: The Alignment Architect
---

# The Alignment Architect

*Explorer les défis de la sûreté de l'IA pour construire des systèmes robustes*

[Accueil](/) | [À propos](/about/)

## Derniers articles

{% for post in site.posts %}
### [{{ post.title }}]({{ post.url }})
*{{ post.date | date: "%d/%m/%Y" }}*

{{ post.excerpt }}

[Lire la suite]({{ post.url }})

---
{% endfor %}
