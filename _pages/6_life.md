---
layout: page
title: "LIFE"
permalink: /life/
---

***

### Life

Here, I share daily moments, personal reflections, and small notes from everyday life.

이곳에는 일상의 기록, 개인적인 생각, 그리고 가볍게 남기고 싶은 이야기들을 공유합니다.

***

<ul class="threads-simple">
  {% assign threads_posts = site.data.threads | sort: "date" | reverse %}

  {% for post in threads_posts %}
    <li>
      {{ post.date | date: "%Y.%m.%d" }} —
      <a href="{{ post.url }}" target="_blank" rel="noopener">
        {{ post.title }}
      </a>
    </li>
  {% endfor %}
</ul>

<style>
.threads-simple {
  list-style: none;
  padding-left: 0;
}

.threads-simple li {
  margin-bottom: 0.6rem;
}

.threads-simple a {
  text-decoration: none;
  font-weight: 500;
}
</style>