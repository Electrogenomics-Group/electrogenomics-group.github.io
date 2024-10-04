---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

{% include section.html %}

## {% include icon.html icon="fa-solid fa-university" %} Affiliations

{% capture content %}

{% include figure.html image="images/logo-qmul.png" link="https://www.qmul.ac.uk/whri/research-centres/centre-for-clinical-pharmacology-and-precision-medicine/" style="width:100%" %}
{% include figure.html image="images/logo-ucl.png" link="https://www.ucl.ac.uk/cardiovascular/research/research-department-clinical-science" %}
{% include figure.html image="images/logo-zaragoza.png" link="https://bsicos.i3a.es/" %}
{% include figure.html image="images/logo-brc.png" link="https://www.qmul.ac.uk/nihr-bartsbrc" %}
{% include figure.html image="images/logo-kcl.png" link="https://www.kcl.ac.uk/bmeis/our-centres" %}
{% include figure.html image="images/logo-bdi.png" link="https://www.bdi.ox.ac.uk/research/werables-group" %}

{% endcapture %}

{% include grid.html content=content %}



