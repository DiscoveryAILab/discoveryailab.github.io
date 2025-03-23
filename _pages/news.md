---
title: "News"
layout: single
permalink: /news/
author_profile: false
---

## News from the Discovery AI Lab
{% for item in site.data.news.items %}
### {{ item.title }} 
- **Date**: {{ item.date }}
- **Description**: {{ item.description }}
{% endfor %}

