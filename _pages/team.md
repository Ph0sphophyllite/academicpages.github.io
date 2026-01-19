---
layout: archive
title: "Team"
permalink: /team/
---

{% for member in site.data.team %}
### [{{ member.name }}](/team/{{ member.page }}/)

**{{ member.role }}**  
Email: {{ member.email }}  
[GitHub]({{ member.github }})

---
{% endfor %}
