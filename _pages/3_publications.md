---
layout: page
title: Publications
permalink: /publications/
---

***
[Working topics](#wp) | [Peer-reviewed papers](#pr) 
<br>
Updated: 30 September 2024

First or corresponding author articles only. You can find my full publication list on [Google Scholar](https://scholar.google.com/citations?user=0brjiRcAAAAJ&hl=en&oi=ao) profile.<br>† represents the equal contribution.

<br>
#### <a name="wp"></a>Working topics

***


{% for post in site.preprints reversed %}
  {% include archive-single.html %}
{% endfor %}

#### <a name="pr"></a>Peer-reviewed papers
***

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}