---
layout: default
---

  <ul>
    {% for post in site.posts %}
      <li>
        <a href="{{ post.url }}">{{ post.title }}</a>{{ post.categories[0] }}
      </li>
    {% endfor %}
  </ul>