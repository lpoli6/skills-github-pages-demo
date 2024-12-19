---
layout: default
title: Benvenuti a Solarolo Monasterolo!
---

## Solarolo Monasterolo è un piccolo paese in provincia di Cremona, vicino al fiume Po

Solarolo Monasterolo è in piena pianura padana, ci fu un allevamento di polli molto conosciuto e rinomato nella zona condotto da Giordano Gandolfi e Franca Minuti.

### Ultimi Post:

{% for post in site.posts %}
* [{{ post.title }}]({{ post.url | relative_url }}) - {{ post.date | date: "%d/%m/%Y" }}
{% endfor %}
