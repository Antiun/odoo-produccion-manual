---
title: Odoo - PRODUCCIÓN
author: Antiun Ingenieria
layout: default
---

{% for post in site.posts reversed %}
<section class="slide">
{{ post.content }}
</section>
{% endfor %}
