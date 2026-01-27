---
layout: single
title: Projects
permalink: /projects/
---

{% for project in site.data.projects %}
### {{ project.title }}

{{ project.description }}

**Tools:** {{ project.tools }}

[View project →]({{ project.link }})

---
{% endfor %}
