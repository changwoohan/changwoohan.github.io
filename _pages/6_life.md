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

<ul>

  {% assign life_posts = site.life | sort: "date" | reverse %}

  {% for post in life_posts %}

    <li>

      {{ post.date | date: "%B %d, %Y" }} —

      <a href="{{ post.url | relative_url }}">

        {{ post.title }}

      </a>

    </li>

  {% endfor %}

</ul>