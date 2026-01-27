---
layout: home
title: Mónica Arango | Data Analyst
---

# Hi, I’m Mónica 👋

I’m a Data Analyst with a background in Psychology. I specialize in combining data analysis with psychological insights to support strategic decisions and generate actionable insights.

---

## Projects

{% for project in site.data.projects %}
### {{ project.title }}

{{ project.description }}

**Tools:** {{ project.tools }}

[View project →]({{ project.link }})

---
{% endfor %}
