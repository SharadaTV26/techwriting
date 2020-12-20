---
layout: template
---

# Work Experience

My work experience is as follows:

{% for item in site.data.variablefile %}

{{ item.company }} during {{ item.from }} - {{ item.to }}

{% endfor %}
