---
layout: archive
title: "Projects"
author_profile: false
permalink: /projects/
---

{% for project in site.data.projects %}
## [{{ project.title }}](/projects/{{ project.page }}/)

**Lead:** {{ project.lead }}  
{{ project.description }}  
[GitHub]({{ project.github }})

---
{% endfor %}
