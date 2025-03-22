---
title: "Our Team"
layout: single
permalink: /team/
author_profile: true
---

{% for member in site.data.team %}
### {{ member.name }}
- **Role**: {{ member.role }}
- **Email**: [{{ member.email }}](mailto:{{ member.email }})
- **Bio**: {{ member.bio }}

![Photo of {{ member.name }}]({{ member.photo }})
{% endfor %}
