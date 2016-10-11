---
layout: page
title: publications
permalink: /publications/
---

***
***
<br>

### Cool stuff

{% for pub in site.data.publications %}
- {{ pub.authors }}. *{{ pub.title }}*. <u>{{ pub.journal }}</u>. {{ pub.year }}. [doi:{{ pub.doi }}](https://doi.org/{{ pub.doi }})
{% endfor %}

***
***
