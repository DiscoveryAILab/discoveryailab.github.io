---
title: "Events"
layout: single
permalink: /events/
author_profile: false
---

<style>
.site-title {
  font-size: 2.5rem !important;
  font-weight: 800 !important;
  color: #005BAC !important;
}
</style>


## Upcoming Events
{% for event in site.data.events.current_events %}
### {{ event.title }} 
- **Date**: {{ event.date }}
- **Description**: {{ event.description }}
- **Venue**: {{ event.venue }}
{% endfor %}

