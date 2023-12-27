---
title: Projects
nav:
  order: 2
  tooltip: Software, datasets, and more
---

## Research projects

{% capture text %}


*From intitiation, to forks and termination*
We have developed a series of innovative genomic technolgies to determine DNA replication dyanmics. Both population-level and single molecule approaches have allowed discovery of sites of replication initiation and subsequent replication dynamics.

{% endcapture %}

{%
  include feature.html
  image="https://media.springernature.com/m312/springer-static/image/art%3A10.1038%2Fs41592-019-0394-y/MediaObjects/41592_2019_394_Fig3_HTML.png"
  title="DNA replication dynamics"
  text=text
%}


# {% include icon.html icon="fa-solid fa-wrench" %}Projects

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include tags.html tags="publication, resource, website" %}

{% include search-info.html %}

{% include section.html %}

## Featured

{% include list.html component="card" data="projects" filters="group: featured" %}

{% include section.html %}

## More

{% include list.html component="card" data="projects" filters="group: " style="small" %}
