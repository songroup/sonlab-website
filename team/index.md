---
title: Team
nav:
  order: 3
  tooltip: Our Team!
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include section.html %}

## Current Members
{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: postdoc" %}
{% include list.html data="members" component="portrait" filters="role: phd" %}
{% include list.html data="members" component="portrait" filters="role: ms" %}
{% include list.html data="members" component="portrait" filters="role: undergrad" %}

## Alumni
Just as we dread parting when we meet, we believe that we’ll meet again when we part.  
{% include list.html data="members" component="portrait" filters="role: ^(alum-)" %}
