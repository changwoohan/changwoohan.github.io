---
layout: page
title: Publications
permalink: /publications/
---

***
[Working topics](#wp) | [Peer-reviewed papers](#pr) 
<br>
Updated: 30 September 2024

The papers listed here are those for which I am either the first author or the corresponding author. You can find my full publication list on [Google Scholar](https://scholar.google.com/citations?user=0brjiRcAAAAJ&hl=en&oi=ao) profile. † represents equal contribution.


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