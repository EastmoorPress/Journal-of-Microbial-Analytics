---
layout: default
title: Articles
permalink: /articles/
---

## Published Articles

<ul>
{% for article in site.articles %}
  <li>
    <a href="{{ article.url | relative_url }}">
      {{ article.title }}
    </a>
  </li>
{% endfor %}
</ul>
