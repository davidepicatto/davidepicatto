---
layout: default
title: Racconti
---
  {% for item in site.data.racconti %}
  <div class="racconti">
  <h2>{{ item.name }}</h2>
  <span class="info">{{ item.year }} </span>| <a href="{{ item.pdf }}">pdf</a>
  <p class="info">{{ item.note }}</p>
  <p>{{ item.description }}</p>
  </div>
  {% endfor %}
