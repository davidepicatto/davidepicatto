---
layout: default
---
  {% for item in site.data.racconti %}
  <div class="racconti">
  <h3>{{ item.name }}</h3>
  {{ item.year }} | <a href="{{ item.link }}">pdf</a>
  <p>{{ item.description }}</p>
  </div>
  {% endfor %}
