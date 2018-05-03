---
{% for p in site.pages %}
     * [{{ p.title }}]({{ p.url | absolute_url }})
        <small>{{ p.excerpt }}</small>
{% endfor %}
---


