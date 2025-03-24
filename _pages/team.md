---
title: "Our Team"
layout: single
permalink: /team/
author_profile: false
---

{% for member in site.data.team %}
<div class="member-card">
  <img src="{{ member.photo }}" alt="Photo of {{ member.name }}" class="member-photo" />
  <div class="member-info">
    <h3>{{ member.name }}</h3>
    <p><strong>Role:</strong> {{ member.role }}</p>
    <p><strong>Email:</strong> <a href="mailto:{{ member.email }}">{{ member.email }}</a></p>
    <p><strong>Bio:</strong> {{ member.bio }}</p>
  </div>
</div>
{% endfor %}

