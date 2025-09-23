---
layout: home
title: "The Alignment Architect"
---

Bienvenue sur mon blog dédié à la sûreté des intelligences artificielles.

{% for post in site.posts %}
## <a href="{{ post.url }}">{{ post.title }}</a>
<small>{{ post.date | date: "%d/%m/%Y" }}</small>
{{ post.excerpt }}
{% endfor %}
