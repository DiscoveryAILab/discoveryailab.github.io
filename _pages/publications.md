---
title: "Publications"
layout: single
permalink: /publications/
author_profile: true
---

Here are selected recent publications:

{% for pub in site.data.publications %}
- **{{ pub.authors }}** ({{ pub.year }}). *{{ pub.title }}*. {{ pub.journal }}.
{% endfor %}
