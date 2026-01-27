---
layout: single
title: Projects
permalink: /projects/
sidebar: false
---

{% for project in site.data.projects %}

<div style="margin-bottom: 40px; padding: 20px; border: 1px solid #e5e5e5; border-radius: 10px;">

### {{ project.title }}

{% if project.image %}
![{{ project.title }}]({{ project.image }}){: style="max-width:100%; height:auto; margin:15px 0; border-radius:8px;" }
{% endif %}

{{ project.description }}

**Tools:** {{ project.tools }}

[View project →]({{ project.link }})

</div>

{% endfor %}
