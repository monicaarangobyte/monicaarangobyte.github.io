---
layout: home
title: Mónica Arango | Data Analyst
sidebar: false
---

# Hi, I’m Mónica 👋

I’m a Psychologist and Data Analyst with experience combining human behavior insights with data analysis to generate actionable insights. I specialize in turning complex data into actionable insights to support better decision-making and strategic outcomes.

## Projects

{% for project in site.data.projects %}
<div style="margin-bottom: 30px; padding: 15px; border: 1px solid #ddd; border-radius: 8px;">
### {{ project.title }}

{% if project.image %}
![{{ project.title }}]({{ project.image}}){: style="max-width:100%; height:auto; margin-bottom:10px;" }
{% endif %}

{{ project.description }}

**Tools:** {{ project.tools }}

[View project →]({{ project.link }})

</div>
{% endfor %}
