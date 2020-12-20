# Work Experience

My work experience is as follows:

{% for item in site.data.variablefile %}

{{ item.name }}{{ item.place }}

{% endfor %}
