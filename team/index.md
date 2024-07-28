---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# <i class="fas fa-person-chalkboard"></i> Principal Investigator

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}

{% include section.html %}

# <i class="fas fa-users"></i> Researchers

{% include list.html data="members" component="portrait" filters="role: postdoc" %}
{% include list.html data="members" component="portrait" filters="role: phd2020" %}
{% include list.html data="members" component="portrait" filters="role: ms2020" %}
{% include list.html data="members" component="portrait" filters="role: phd2021" %}
{% include list.html data="members" component="portrait" filters="role: ms2021" %}
{% include list.html data="members" component="portrait" filters="role: phd2022" %}
{% include list.html data="members" component="portrait" filters="role: ms2022" %}
{% include list.html data="members" component="portrait" filters="role: phd2023" %}
{% include list.html data="members" component="portrait" filters="role: ms2023" %}
{% include list.html data="members" component="portrait" filters="role: phd2024" %}
{% include list.html data="members" component="portrait" filters="role: ms2024" %}
{% include list.html data="members" component="portrait" filters="role: phd2025" %}
{% include list.html data="members" component="portrait" filters="role: ms2025" %}
{% include list.html data="members" component="portrait" filters="role: undergrad" %}

# Alumni

<p style="text-align:center">“ Just as we dread parting when we meet, we believe that we’ll meet again when we part. ”</p>
{% include list.html data="members" component="portrait" filters="role: ^(alum-)" %}
