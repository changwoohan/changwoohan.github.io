---
layout: page
title: Publications
permalink: /publications/
---

***
### Publications
[Working topics](#wp) | [Peer-reviewed papers](#pr) 
<br>
Updated: 21 February 2025

The papers listed here are those for which I am either the first author or the corresponding author. You can find my full publication list on [Google Scholar](https://scholar.google.com/citations?user=0brjiRcAAAAJ&hl=en&oi=ao){:target="\_blank"} profile. † represents equal contribution.

아래는 제가 주저자 및 교신저자로 작성한 논문입니다. 제 전체 논문은 [Google Scholar](https://scholar.google.com/citations?user=0brjiRcAAAAJ&hl=en&oi=ao){:target="\_blank"} 를 통해 확인가능합니다. 

***
#### <a name="wp"></a>Working topics

{% for post in site.working reversed %}
  {% include archive-double.html %}
{% endfor %}


***


#### <a name="pr"></a>Peer-reviewed papers

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}