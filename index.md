---
layout: home
title: Mónica Arango | Data Analyst
---

# Hi, I’m Mónica 👋

Experienced Psychologist and Data Analyst combining deep understanding of human behavior with strong analytical skills. I transform complex datasets into actionable insights that improve decision-making, optimize processes, and drive strategic results. Skilled in both behavioral research and modern data analytics tools.

Technical Skills: Excel | SQL | Python | Power BI | Tableau
Soft Skills: Analytical Thinking | Behavioral Insights | Communication | Collaboration | Results-Focused | Organization | Initiative | Attention to Detail

---

## Projects

{% for project in site.data.projects %}
### {{ project.title }}

{{ project.description }}

**Tools:** {{ project.tools }}

[View project →]({{ project.link }})

---
{% endfor %}
