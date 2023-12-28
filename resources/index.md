---
title: Resources
nav:
  order: 5
  tooltip: Software, datasets, and more
---

## Lab resources

Various group resources.


{% include section.html %}

{% include search-box.html %}

{% include tags.html tags="Database, Software, Outreach" %}

{% include search-info.html %}

{% include list.html data="resources" component="post-excerpt" filter="tags: ^(?!meme$)" %}

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
