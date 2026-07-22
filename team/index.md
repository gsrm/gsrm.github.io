---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Conoce al maravilloso equipo.

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}
ㅤ
{% include list.html data="members" component="portrait" filter="role != 'principal-investigator'" %}


<!-- 
{% include list.html data="members" component="portrait" filter="ref == 'psl'" %}
{% include list.html data="members" component="portrait" filter="ref == 'amm'" %}-->
{% include section.html background="images/background-gemini-1.png" dark=true %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include section.html %}

# Foto de grupo

{% include figure.html image="images/group-photo-nocoat.jpg" %}
