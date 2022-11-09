---
layout: default
---
{% seo %}

# Hiking Journal

I'll try my best to document all the hikes that I go on and take some good pictures.

<ul>
  {% for post in site.categories.hiking %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
