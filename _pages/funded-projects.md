---
title: "Funded Projects"
layout: single
permalink: /projects/
author_profile: true
---

Here are some of our key funded research projects:

{% for project in site.data.funded_projects %}
### {{ project.title }}
- **Funder**: {{ project.funder }}
- **Duration**: {{ project.duration }}
- **Summary**: {{ project.description }}
{% endfor %}
