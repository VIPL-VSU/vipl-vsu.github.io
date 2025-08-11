---
title: Team
nav:
  order: 3
  tooltip: About our team
---

We are a diverse and dynamic group of researchers driven by curiosity and collaboration. Our team includes members at different career stages, working together to advance research in scene understanding.

# {% include icon.html icon="fa-solid fa-users" %}Current Members

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}
{% include list.html data="members" component="portrait" filter="role == 'postdoc'" %}
{% include list.html data="members" component="portrait" filter="role == 'programmer'" %}
{% include list.html data="members" component="portrait" filter="role == 'phd'" %}
{% include list.html data="members" component="portrait" filter="role == 'master'" %}

{% include section.html %}

# {% include icon.html icon="fa-solid fa-users" %}Alumni

{% include list.html data="members" component="portrait" filter="role == 'alumni'" %}

{% include section.html background="images/background.jpg" dark=true %}

{% include section.html %}

{% capture content %}

# {% include icon.html icon="fa-solid fa-users" %}Group Photos

{% include figure.html image="images/mmexport1754108074984.jpg" %}
{% include figure.html image="images/group_dinner.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
