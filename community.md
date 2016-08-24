---
layout: page
title: community
permalink: /community/
---

***
***
<br>

I am committed to being an active participants in the open science community. Here is a list of general community activities I have been involved in:

{% for comm in site.data.community %}
- **{{ comm.role }}**. *{{ comm.activity }}*. {{ comm.date }}
{% endfor %}

***
***
