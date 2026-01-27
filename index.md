---
layout: home
title: Mónica Arango | Data Analyst
sidebar: false
---

# Hi, I’m Mónica 👋

I’m a Psychologist and Data Analyst with experience combining human behavior insights with data analysis to generate actionable insights. I specialize in turning complex data into actionable insights to support better decision-making and strategic outcomes.

## Projects

{% for project in site.data.projects %}

<div style="border:1px solid #ddd; border-radius:8px; padding:1rem; margin-bottom:1.5rem; box-shadow: 2px 2px 6px rgba(0,0,0,0.05);">

### {{ project.title }}

{% if project.image %}
<img src="{{ project.image }}" alt="{{ project.title }}" style="width:100%; border-radius:6px; margin-bottom:10px;">
{% endif %}

{{ project.description }}

**Tools:** {{ project.tools }}

<p>
<a href="{{ project.link }}" style="display:inline-block; margin-top:10px; padding:0.5rem 1rem; background-color:#3b82f6; color:white; border-radius:6px; text-decoration:none;">
View project →
</a>
</p>

</div>

{% endfor %}
