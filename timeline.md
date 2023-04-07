---
layout: timeline
title: 建站历程时间轴
---

<header>
  <div class="container text-center">
    <h1>建站历程时间轴</h1>
    <p>Honux</p>
  </div>
</header>
<section class="timeline">
  <div class="container">
  {% for post in site.posts reversed %}
    {% if post.categories contains '网站' %}
    <div class="timeline-item">
      <div class="timeline-img"></div>
        {% if post.image %}
        <div class="timeline-content timeline-card">
          <div class="timeline-img-header" style="background: linear-gradient(transparent, rgba(0, 0, 0, 0.4)), url('{{ post.image }}') center center no-repeat; background-size: cover;">
            <h2>{{ post.title }}</h2>
          </div>
        {% else %}
        <div class="timeline-content">
          <h2>{{ post.title }}</h2>
        {% endif %}
          <div class="date">{{ post.date | date: "%b %-d, %Y" }}</div>
          <p>{{ post.excerpt | strip_html | strip_newlines | truncate: 150 }}</p>
          <a class="btn-more" href="{{ post.url }}">详情</a>
          {% if post.site %}
          <a class="btn-more" href="post.site" target="_blank">回看</a>
          {% endif %}
        </div>
    </div>
    {% endif %}
  {% endfor %}
  </div>
</section>