---
layout: category
title: Diary
---

This section contains some of my daily reflections.  
Small moments from school or work, touching experiences in everyday life, and occasional travel stories and practical tips.  
  
このページでは、日常のささやかな出来事を記録しています。  
学校や職場での小さなエピソード、日々の中で心に残った出来事、そして旅行の体験やちょっとした工夫などを書き留めています。  
  
这里记录了我的一些日常。  
包括一些学校或职场中遭遇的小事，或者一些日常的感动，抑或是一些旅游的经验分享。  
---
<ul class="Diary_navi-list">
{% for post in site.categories.Diary %}
  <li class="Diary_navi-item">
    <a class="Diary_navi-link" href="{{ post.url | relative_url }}">
      {{ post.title }}
      <small>({{ post.date | date_to_string }})</small>
    </a>
  </li>
{% endfor %}
</ul>