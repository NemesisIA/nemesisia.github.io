---
layout: default
---

<div class="main-content">
  <h2>Derniers articles</h2>
  
  {% for post in site.posts %}
    <article class="post-preview">
      <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
      <small>Publié le {{ post.date | date: "%d/%m/%Y" }}</small>
      <p>{{ post.excerpt | strip_html | truncatewords: 30 }}</p>
      <a href="{{ post.url }}">Lire la suite →</a>
    </article>
    <hr>
  {% endfor %}
</div>
