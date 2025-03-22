---
title: "PhD Projects"
layout: single
permalink: /phd-projects/
author_profile: true
---

We supervise the following PhD projects:

{% for project in site.data.phd_projects %}
### {{ project.title }}
- **Student**: {{ project.student }}
- **Supervisor**: {{ project.supervisor }}
- **Research Focus**: {{ project.description }}
{% endfor %}
