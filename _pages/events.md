---
title: "Events"
layout: single
permalink: /events/
author_profile: true
---

### Upcoming Events
{% for event in site.data.events %}
#### {{ event.title }} ({{ event.date }})
{{ event.description }}
{% endfor %}

---

### Archived Events
{% for event in site.data.archived_events %}
#### {{ event.title }} ({{ event.date }})
{{ event.description }}
{% endfor %}
