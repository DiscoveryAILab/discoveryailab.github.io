---
title: "Events"
layout: single
permalink: /events/
author_profile: false
---


## Upcoming Events
{% for event in site.data.events.current_events %}
### {{ event.title }} 
- **Date**: {{ event.date }}
- **Description**: {{ event.description }}
- **Venue**: {{ event.venue }}
{% endfor %}

