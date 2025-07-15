---
layout: page
title: Blog
permalink: /blog/
---

# Blog Posts

Welcome to my blog! Here you'll find my thoughts on technology, software development, and other topics that interest me.

{% raw %}
{% if site.posts.size > 0 %}
  <ul class="post-list">
    {% for post in site.posts %}
      <li>
        <span class="post-meta">{{ post.date | date: "%B %-d, %Y" }}</span>
        <h3>
          <a class="post-link" href="{{ post.url | relative_url }}">
            {{ post.title | escape }}
          </a>
        </h3>
        {% if post.excerpt %}
          <p>{{ post.excerpt }}</p>
        {% endif %}
      </li>
    {% endfor %}
  </ul>
{% else %}
  <p>No blog posts yet. Check back soon!</p>
{% endif %}
{% endraw %} 