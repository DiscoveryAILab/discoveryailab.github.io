---
title: "Our Team"
layout: single
permalink: /team/
author_profile: false
---


{% for member in site.data.team %}
<div class="member-card" style="margin-bottom: 5rem;">
  <div class="member-info">
    <h3 style="margin: 0 0 0.3rem 0;">{{ member.name }}</h3>
    <p style="margin: 0.2rem 0;"><strong>Role:</strong> {{ member.role }}</p>
    <p style="margin: 0.2rem 0;"><strong>Email:</strong> <a href="mailto:{{ member.email }}">{{ member.email }}</a></p>
    <p style="margin: 0.2rem 0;"><strong>Bio:</strong> {{ member.bio }}</p>
  </div>
  <img src="{{ member.photo }}" alt="Photo of {{ member.name }}" width="150" height="150" />
</div>
{% endfor %}


# Collaborators
{% for member in site.data.collaborators %}
<div class="member-card" style="margin-bottom: 2rem;">
  <div class="member-info">
    <h3 style="margin: 0 0 0.3rem 0;">{{ member.name }}</h3>
    <p style="margin: 0.2rem 0;"><strong>Role:</strong> {{ member.role }}</p>
    <p style="margin: 0.2rem 0;"><strong>Email:</strong> <a href="mailto:{{ member.email }}">{{ member.email }}</a></p>
    <p style="margin: 0.2rem 0;"><strong>Bio:</strong> {{ member.bio }}</p>
  </div>
  <img src="{{ member.photo }}" alt="Photo of {{ member.name }}" width="150" height="150" />
</div>
{% endfor %}


