---
title: Projects
nav:
  order: 2
  tooltip: Software, datasets, and more
---

# {% include icon.html icon="fa-solid fa-wrench" %}Projects

This page showcases the datasets, systems, and other resources developed by our group.

{% include tags.html tags="publication, dataset, website" %}

{% include search-info.html %}

{% include section.html %}


## Dataset

{% include list.html component="card" data="projects" filter="group == 'dataset'" %}

{% include section.html %}

## More

{% include list.html component="card" data="projects" filter="!group" style="small" %}
