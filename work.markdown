---
layout: page
title: Work
permalink: /work/
---

Here's some things I've done! Click the links for more information, videos, context, all kinds of good stuff 😬.

{% for work in site.work %}

  <br>
  <h3>
    <a href="{{ work.url }}">{{ work.title }}</a>
  </h3>
  <a href="{{ work. url }}"><img src="{{ work.banner.src }}" alt="{{ work.banner.alt }}" width="100%"></a>
  <p>{{ work.description }}<p>
  <hr>
      
{% endfor %}
