---
layout: home
---
{% for post in site.categories[page.category] %}
  * [{{ post.title }}]({{ post.url | absolute_url }})  
      <small>{{ post.excerpt }}</small>
{% endfor %}
