---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Meet the remarkable minds behind the RIIPL lab — a diverse team of multi-disciplinary talents dedicated to research and development in medical imaging. Each member brings a unique set of skills and insights, driving innovation and excellence in our work.

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

{% include section.html background="images/background.jpg" dark=true %}

<blockquote>
"The strength of the team is each individual member. The strength of each member is the team." <br>
- Phil Jackson
</blockquote>

{% include section.html %}

{% capture content %}

{% include figure.html image="images/staff_photos/RIIPL_lab_04142023.jpg" %}
{% include figure.html image="images/staff_photos/RIIPL_lab_08042022.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
