---
title: Projects
nav:
  order: 2
  tooltip: Software, datasets, and more
---

## Research projects

{% capture text %}

*From intitiation, to forks and termination*

We have developed a series of innovative genomic technolgies to determine DNA replication dynamics. Both population-level and single molecule approaches have allowed discovery of sites of replication initiation and subsequent replication dynamics.

{%
  include citation.html
  lookup="doi:10.1016/j.csbj.2020.05.017"
  style="rich"
%}

{% endcapture %}

{%
  include feature.html
  image="images/mosaic_detail.png"
  title="DNA replication dynamics"
  text=text
%}

## Lab resources

### Databases

Database resources

{% include list.html component="card" data="projects" filters="group: database" %}

{% include section.html %}

### Computer scripts and packages

{% include list.html component="card" data="projects" filters="group: script" %}

{% include section.html %}

### Data visualisation

{% include list.html component="card" data="projects" filters="group: visualisation" %}

{% include section.html %}

### Outreach

{% include list.html component="card" data="projects" filters="group: outreach" %}

{% include section.html %}


### More

{% include list.html component="card" data="projects" filters="group: " style="small" %}
