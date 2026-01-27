---
layout: page
title: Projects
permalink: /projects/
sidebar: false
---

{% for project in site.data.projects %}

### {{ project.title }}

{% if project.image %}
![{{ project.title }}]({{ project.image }}){: style="max-width:100%; height:auto; margin-bottom:10px;" }
{% endif %}

{{ project.description }}

**Tools:** {{ project.tools }}

[View project →]({{ project.link }})

---
{% endfor %}
