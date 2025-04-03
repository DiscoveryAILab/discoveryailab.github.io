---
title: "Our Team"
layout: single
permalink: /team/
author_profile: false
---

<style>
.site-title {
  font-size: 2.5rem !important;
  font-weight: 800 !important;
  color: #005BAC !important;
}
</style>



{% for member in site.data.team %}
<div class="member-card" style="margin-bottom: 1rem;">
  <div class="member-info">
    {% if member.name %}
      <h3 style="margin: 0 0 0.3rem 0;">{{ member.name }}</h3>
    {% endif %}
    
    {% if member.role %}
      <p style="margin: 0.2rem 0;"><strong>Role:</strong> {{ member.role }}</p>
    {% endif %}
    
    {% if member.email %}
      <p style="margin: 0.2rem 0;"><strong>Email:</strong> <a href="mailto:{{ member.email }}">{{ member.email }}</a></p>
    {% endif %}
    
    {% if member.bio %}
      <p style="margin: 0.2rem 0;"><strong>Bio:</strong> {{ member.bio }}</p>
    {% endif %}
  </div>

  {% if member.photo %}
    <img src="{{ member.photo }}" alt="Photo of {{ member.name }}" width="150" height="150" />
  {% endif %}
</div>
{% endfor %}



{% comment %}
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
{% endcomment %}


<div style="margin-top: 4rem;"></div>
# Collaborators
{% for member in site.data.collaborators %}
<div class="member-card" style="margin-bottom: 2rem;">
  <div class="member-info">
    {% if member.name %}
      <h3 style="margin: 0 0 0.3rem 0;">{{ member.name }}</h3>
    {% endif %}
    
    {% if member.role %}
      <p style="margin: 0.2rem 0;"><strong>Role:</strong> {{ member.role }}</p>
    {% endif %}
    
    {% if member.email %}
      <p style="margin: 0.2rem 0;"><strong>Email:</strong> <a href="mailto:{{ member.email }}">{{ member.email }}</a></p>
    {% endif %}
    
    {% if member.bio %}
      <p style="margin: 0.2rem 0;"><strong>Bio:</strong> {{ member.bio }}</p>
    {% endif %}
  </div>

  {% if member.photo %}
    <img src="{{ member.photo }}" alt="Photo of {{ member.name }}" width="150" height="150" />
  {% endif %}
</div>
{% endfor %}


