---
layout: default
title: ainimarie
---

{% for page in site.pages %}
<div id="{{ page.tag }}" class="full-content">
    {{ page.content }}

</div>
{% endfor%}