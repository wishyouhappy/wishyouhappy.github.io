---
layout: page
title: Gallery

---

## Gallery

{% for post in site.gallery %}
  * [ {{ post.title }} ]({{ post.url }}) <span class="span-time"> &raquo; {{ post.date | date_to_string }}</span>  
{% endfor %}