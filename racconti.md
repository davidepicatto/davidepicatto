---
layout: default
title: racconti
---
  {% for item in site.data.racconti %}
  <div class="racconti">
  <h3>{{ item.name }}</h3>
  <span class="info">{{ item.year }} </span>| <a href="{{ item.link }}">pdf</a>
  <p>{{ item.description }}</p>
  </div>
  {% endfor %}
