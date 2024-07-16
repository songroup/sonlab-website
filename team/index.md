---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# <i class="fas fa-person-chalkboard"></i> Principal Investigators

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}

{% include section.html %}

# <i class="fas fa-users"></i> Researchers

{% include list.html data="members" component="portrait" filters="role: postdoc" %}
{% include list.html data="members" component="portrait" filters="role: phd" %}
{% include list.html data="members" component="portrait" filters="role: ms" %}
{% include list.html data="members" component="portrait" filters="role: undergrad" %}

# Formal Researchers

<p style="text-align:center">“ Just as we dread parting when we meet, we believe that we’ll meet again when we part. ”</p>
{% include list.html data="members" component="portrait" filters="role: ^(alum-)" %}
