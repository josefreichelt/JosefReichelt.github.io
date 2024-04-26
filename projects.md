---
layout: page
title: My Projects
permalink: /projects/
---

{% for project in site.data.projects %}
{%include project.md project=project %}
{% endfor %}
