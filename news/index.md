---
title: News
nav:
  order: 4
  tooltip: Musings and miscellany
---

# {% include icon.html icon="fa-solid fa-feather-pointed" %}News

Latest news from our group - both science and social.

{% include section.html %}

{% include search-box.html %}

{% include tags.html tags=site.tags %}

{% include search-info.html %}

{% include list.html data="resources" component="post-excerpt" filter="tags: ^(?!meme$)" %}
