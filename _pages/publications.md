---
title: "Publications"
layout: single
permalink: /publications/
author_profile: false
---

## Featured publications:

{% for pub in site.data.publications %}
- **{{ pub.authors }}** ({{ pub.year }}). *{{ pub.title }}*. {{ pub.journal }}.{% if pub.link %} [View paper]({{ pub.link }}){% endif %}
{% endfor %}


## Full list of publications can be found at: [PURE Portal](https://pure.qub.ac.uk/en/persons/h-wang/publications/)

