---
layout: timeline
---


{% for post in site.posts reversed %}
  {% if post.categories contains '网站' %}
    <div class="timeline-item">
      <div class="timeline-img"></div>
      <div class="timeline-content js--fadeInLeft">
        <h2>{{ post.title }}</h2>
        <div class="date">{{ post.date | date: "%b %-d, %Y" }}</div>
        <p>{{ post.excerpt | strip_html | strip_newlines | truncate: 150 }}</p>
        <a class="bnt-more" href="javascript:void(0)">More</a>
      </div>
    </div>
  {% endif %}
{% endfor %}
