---
layout: page
title: Publications
permalink: /publications/
---

***
***
<br>

### Peer-reviewed publications

{% for pub in site.data.publications %}
- {{ pub.authors }}. *{{ pub.title }}*. <u>{{ pub.journal }}</u>. {{ pub.year }}. [doi:{{ pub.doi }}](https://doi.org/{{ pub.doi }})
{% endfor %}

***
***
