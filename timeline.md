---
layout: timeline
---

<section class="timeline">
  <div class="container">
  {% for post in site.posts reversed %}
    {% if post.categories contains '网站' %}
    <div class="timeline-item">
      <div class="timeline-img"></div>
        {% if post.image %}
        <div class="timeline-content timeline-card">
          <div class="timeline-img-header">
            <h2>{{ post.title }}</h2>
          </div>
        {% else %}
        <div class="timeline-content">
          <h2>{{ post.title }}</h2>
        {% endif %}
          <div class="date">{{ post.date | date: "%b %-d, %Y" }}</div>
          <p>{{ post.excerpt | strip_html | strip_newlines | truncate: 150 }}</p>
          <a class="btn-more" href="javascript:void(0)">More</a>
        </div>
    </div>
    {% endif %}
  {% endfor %}
  </div>
</section>