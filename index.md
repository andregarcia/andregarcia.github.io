---
{% for p in site.posts %}
     * [{{ p.title }}]({{ p.url | absolute_url }})
        <small>{{ p.excerpt }}</small>
{% endfor %}
---


