---
layout: page
title: publications
permalink: /publications/
---

***
***
<br>

This is a personally curated list of my peer-reviewed publications. Other sources include [PubMed query](http://www.ncbi.nlm.nih.gov/pubmed?term=((((Bot%20B%5BAuthor%5D)%20OR%20Bot%20BM%5BAuthor%5D)%20OR%20Bot%2C%20Brian%5BAuthor%5D)%20OR%20Bot%2C%20Brian%20M%5BAuthor%5D)%20NOT%20Le%20Bot%20B%5BAuthor%5D), [Google Scholar](https://scholar.google.com/citations?user=uL8iPIMAAAAJ&hl=en), and [ORCID](http://orcid.org/0000-0002-2412-6826).

### Personal top 10 list (rev. chronological order)

{% for pub in site.data.pubTop10 %}
- {{ pub.authors }}. *{{ pub.title }}*. <u>{{ pub.journal }}</u>. {{ pub.year }}. [doi{{ pub.doi }}](https://doi.org/{{ pub.doi }})
{% endfor %}

***
***
<br>

### The rest of the best (rev. chronological order)

{% for pub in site.data.pubRest %}
- {{ pub.authors }}. *{{ pub.title }}*. <u>{{ pub.journal }}</u>. {{ pub.year }}. [doi{{ pub.doi }}](https://doi.org/{{ pub.doi }})
{% endfor %}

***
***
