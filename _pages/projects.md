---
title: "Research Projects"
layout: single
permalink: /projects/
author_profile: false
---

<style>
.site-title {
  font-size: 2.5rem !important;
  font-weight: 800 !important;
  color: #005BAC !important;
}
</style>


## **Funded research projects**:

{% for project in site.data.funded_projects %}
### {% if project.url %}[{{ project.title }}]({{ project.url }}){% else %}{{ project.title }}{% endif %}
- **Funder**: {{ project.funder }}
- **Duration**: {{ project.duration }}
- **Summary**: {{ project.description }}
{% endfor %}

## PhD projects:

{% for project in site.data.phd_projects %}
### {{ project.title }}
- **Student**: {{ project.student }}
- **Supervisor**: {{ project.supervisor }}
- **Research Focus**: {{ project.description }}
{% endfor %}
