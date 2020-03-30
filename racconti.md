---
layout: default
title: Racconti
---
{% assign raccontilist = site.data.racconti | sort: "year" %}
  {% for item in raccontilist reversed %}
  <div class="racconti">
  <h2>{{ item.name }}</h2>
  <div class="info">{{ item.year }} 
  {% if item.pdf %} | <a href="{{ item.pdf }}">pdf</a>{% endif %}
  {% if item.epub %} | <a href="{{ item.epub }}">epub</a>{% endif %}
  {% if item.mobi %} | <a href="{{ item.mobi }}">mobi</a>{% endif %}
  {% if item.note %}<p class="info">{{ item.note }}</p>{% endif %}
  </div>
  <p>{{ item.description }}</p>
  </div>
  {% endfor %}
