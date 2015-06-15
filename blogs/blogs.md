---
layout: page
title: Archive

---

## Blog Posts

{% for post in site.posts %}
  * [ {{ post.title }} ]({{ post.url }}) <span class="span-time"> &raquo; {{ post.date | date_to_string }}</span>  
{% endfor %}