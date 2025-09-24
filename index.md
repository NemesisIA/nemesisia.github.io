---
layout: default
title: "The Alignment Architect"
---

<div style="text-align: center; margin-bottom: 40px;">
  <h1>The Alignment Architect</h1>
  <p><em>Explorer les défis de la sûreté de l'IA pour construire des systèmes robustes</em></p>
  <nav>
    <strong><a href="/">Accueil</a> • <a href="/about/">À propos</a></strong>
  </nav>
</div>

## Derniers articles

{% for post in site.posts %}
### [{{ post.title }}]({{ post.url }})
*{{ post.date | date: "%d/%m/%Y" }} - par {{ post.author | default: site.author }}*

{{ post.excerpt }}

[Lire la suite]({{ post.url }})
---
{% endfor %}
