---
title: Team
nav:
  order: 2
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

We are a friendly group!  Current research group members:

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$), group: ^(?!alum$)" %}

{% include section.html background="images/background.jpg" dark=true %}

If you are interested in joining us, please get in touch with Conrad.  
  
Previous group members:

{% include section.html %}

{% include list.html data="members" component="portrait" style="small" filters="role: ^(?!pi$), group: alum" %}
