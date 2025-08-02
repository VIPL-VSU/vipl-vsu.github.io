---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

VIPL-VSU group belongs to the Visual Information Processing and Learning (VIPL) research group, affiliated with Intelligent Information Processing, Institute of Computing Technology, CAS.

{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="VIPL"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="https://www.ict.ac.cn/jssgk/ysfm/201811/W020181102796499224879.jpg"
  caption="Institute of Computing Technology, CAS"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}
