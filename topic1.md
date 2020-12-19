---
layout: template
---
# Documentation Process in Agile

This article provides a time-tested documentation process that you can follow in agile. Are you a technical writer working in an agile environment? Then read on.
Documentation in agile means that writers are involved in the project right from the initial stage, which brings an excellent opportunity for writers to contribute towards user experience. 

To add local variable from config.yml, use site to call the variables.

To add global variable, add it to template

I am calling it here: {{ site.product_name }}

Am adding data variables here

{ % for item in site.data.variablefile % }

The animals are {{ item.name }} and places are {{ item.place }}

{% endfor %}
