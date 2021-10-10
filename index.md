---
layout: default
title: Accueil
permalink: /
---
## Yassin AGX
Bienvenue sur mon site internet dédié à mes occupations numériques et analogiques.  

<div>
  <ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | prepend: site.baseurl }}">
        {{ post.date | date: "%d-%m-%Y" }} {{ post.title }}
      </a>
    </li>
  {% endfor %}
  </ul>
</div>
