---
layout: page
title: "POSTS"
permalink: /posts/
---

***
### Reflections and ideas
[In English](#wp) | [In Korean](#pr) <br>
Updated: 25 October 2024 <br>

Here, I share reflections and ideas inspired by my interests and research. You can read these entries in both English and Korean. <br>

아래는 제가 관심 있는 주제와 연구 분야에 대해 자유롭게 작성한 글들입니다. 한국어와 영어로 보실 수 있습니다.

***
#### <a name="wp"></a> In English
<ul>
  {% for post in site.posts %}
    {% if post.lang == "en" %}
      <li>
        <strong>{{ post.date | date: "%B %d, %Y" }}</strong><br>
        <a href="{{ post.url | relative_url }}"><strong>{{ post.title }}</strong></a>
      </li>
    {% endif %}
  {% endfor %}
</ul>

***

#### <a name="pr"></a> In Korean
<ul>
  {% for post in site.posts %}
    {% if post.lang == "ko" %}
      <li>
        <strong>{{ post.date | date: "%B %d, %Y" }}</strong><br>
        <a href="{{ post.url | relative_url }}"><strong>{{ post.title }}</strong></a>
      </li>
    {% endif %}
  {% endfor %}
</ul>