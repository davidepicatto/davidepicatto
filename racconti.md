---
layout: default
title: Racconti
---
  {% for item in site.data.racconti %}
  <div class="racconti">
  <h2>{{ item.name }}</h2>
  <span class="info">{{ item.year }} </span>| <a href="{{ item.link }}">pdf</a>
  <p>{{ item.description }}</p>
  </div>
  {% endfor %}
