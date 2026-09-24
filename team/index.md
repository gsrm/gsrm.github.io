---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Meet the team!

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}
ㅤ
{% include list.html data="members" component="portrait" filter="role != 'principal-investigator'" %}


<!-- 
{% include list.html data="members" component="portrait" filter="ref == 'psl'" %}
{% include list.html data="members" component="portrait" filter="ref == 'amm'" %}-->
{% include section.html background="images/background-gemini-1.png" dark=true %}

Discovery consists of seeing what everybody has seen and thinking what nobody has thought.
- *Albert Szent-Györgyi* (Nobel Prize laureate in Medicine, 1937)

{% include section.html %}

# The whole team united

{% include figure.html image="images/group-photo-nocoat.jpg" %}

{% include section.html background="images/background-gemini-1.png" dark=true %}

# Collaborators

{% capture col1 %}
{% include figure.html image="images/collaborators/coll_1.png" link="https://cima.cun.es/" %}
{% endcapture %}

{% capture col2 %}
{% include figure.html image="images/collaborators/coll_2.png" link="https://www.pcuv.es/es/empresas/biotecnologia/MENDEL-S-BRAIN" %}
{% endcapture %}

{% capture col3 %}
{% include figure.html image="images/collaborators/coll_3.png" link="https://procesoterapeutico.com/" %}
{% endcapture %}


{% include cols.html col1=col1 col2=col2 col3=col3 %}


{% capture col1 %}
{% include figure.html image="images/collaborators/coll_4.png" link="https://www.ucsf.edu/" %}
{% endcapture %}

{% capture col2 %}
{% include figure.html image="images/collaborators/coll_5.png" link="https://www.uv.es/" %}
{% endcapture %}

{% capture col3 %}
{% include figure.html image="images/collaborators/coll_6.png" link="https://www.umcutrecht.nl/en" %}
{% endcapture %}


{% include cols.html col1=col1 col2=col2 col3=col3 %}

{% capture col1 %}
{% include figure.html image="images/collaborators/coll_7.png" link="https://www.nibrt.ie/" %}
{% endcapture %}

{% capture col2 %}
{% include figure.html image="images/collaborators/coll_8.png" link="https://www.uoc.gr/en/home/" %}
{% endcapture %}

{% capture col3 %}
{% include figure.html image="images/collaborators/coll_9.png" link="https://celvia.ee/en/" %}
{% endcapture %}


{% include cols.html col1=col1 col2=col2 col3=col3 %}

{% capture col1 %}
{% include figure.html image="images/collaborators/coll_10.png" link="https://www.ugr.es/" %}
{% endcapture %}

{% capture col2 %}
{% include figure.html image="images/collaborators/coll_11.png" link="https://www.maynoothuniversity.ie/" %}
{% endcapture %}

{% capture col3 %}
{% include figure.html image="images/collaborators/coll_12.png" link="https://ut.ee/en" %}
{% endcapture %}


{% include cols.html col1=col1 col2=col2 col3=col3 %}