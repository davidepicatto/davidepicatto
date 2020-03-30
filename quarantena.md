---
layout: default
title: Quarantena
---
<h1>Quarantena</h1>
<div class="intro">
  <p><i>Quarantena</i> è un diario narrativo a puntate scritto nei giorni della grande quarantena del 2020.</p>
  <p>I personaggi e gli eventi narrati sono frutto di invenzione ma si intrecciano a nomi, luoghi e circostanze reali che compaiono come pure occasioni narrative. Qualsiasi lettura che non consideri l'aspetto meramente letterario di quanto scritto è da considerarsi forzata. Le opinioni espresse implicitamente o esplicitamente da un personaggio o dalla voce narrante non riflettono necessarimanete quelle dell'<a href="/chisono">autore</a>.</p>
  <p>Potete leggere <i>Quarantena</i> gratuitamente cliccando sui link che seguono. Se volete sostenere il mio lavoro potete lasciarmi un'<a href="https://www.paypal.me/davidepicatto">offerta libera tramite Paypal</a>.</p>
  <p>Contatti: <a href="https://t.me/davidepicatto">telegram</a> | <a href="mailto:davidepicatto@gmail.com">email</a> | <a href="https://www.facebook.com/davide.picatto">facebook</a></p>
</div>
  {% for post in site.categories.quarantena %}
  <div class="racconti">
  <li><h2><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></h2></li>
  </div>
  {% endfor %}
