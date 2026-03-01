---
layout: post
title: "Diary by English"
categories:
  - DiaryNavi
last_modified_at: 2026-03-02T22:15:00+09:00
---

This is all my diary wirte by English  

<ul class="Diary_en-list">
{% for post in site.categories.Diary %}
  <li class="Diary_en-item">
    <a class="Diary_en-link" href="{{ post.url | relative_url }}">
      {{ post.title }}
      <small>({{ post.date | date_to_string }})</small>
    </a>
  </li>
{% endfor %}
</ul>