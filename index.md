---
name: Ben
layout: default
---

# Hello world

This is an example of my awesome new website.

This page was made by {{ page.name }}.

{% for post in site.posts %} 
  * [{{ post.title }}]({{ post.url }})
{% endfor %}

<ul>
{% for post in site.posts %} 
  <li><a href="{{ post.url }}">{{ post.title }}</a>
{% endfor %}
</ul>
