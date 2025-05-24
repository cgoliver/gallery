---
layout: collection
title: Collections
---
<ul>
{% for collection in site.data.collections %}
  <li><a href="/collections/{{ collection.slug }}">{{ collection.name }}</a></li>
{% endfor %}
</ul>
