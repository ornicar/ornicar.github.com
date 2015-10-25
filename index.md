---
layout: page
title: un guique en liberté
---
{% include JB/setup %}

Salut les hiverneux ! Ce blog servira à rassurer les inquiets, enrager les jaloux, et m’épargner les emails individuels.

Je n'ai pas d'appareil photo, aussi je piocherai sur Internet des images de ce que j'ai vu.

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
