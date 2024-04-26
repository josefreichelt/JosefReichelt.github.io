
# {{include.project.title}}


{% if include.project.image %}
![ {{include.project.title}} ]({{include.project.image}})
{% endif %}

{{include.project.description}}

{% if include.project.link %}
[{{include.project.link_text}}]({{include.project.link}})
{% endif %}


{% if include.project.tech %}

### Technologies used

<ul>
{% assign techlist = include.project.tech | split: ", " %}
{% for tech in techlist %}
  <li>{{tech}}</li>
{% endfor %}
</ul>
{% endif %}


----------
