---
layout: page
title: About me
permalink: /about/
css: /assets/css/styles.css
---
{% include me.md %}


## 📖 My Spellbook

### Main languages I use

<ul>
{% for language in site.data.techlist.languages.main %}
  <li>{{language}}</li>
{% endfor %}
</ul>

### Others I use occasionally

<ul>
{% for language in site.data.techlist.languages.secondary %}
  <li>{{ language }}</li>
{% endfor %}
</ul>

----------

### Web Frameworks

<ul>
{% for framework in site.data.techlist.frameworks.web %}
  <li>{{framework}}</li>
{% endfor %}
</ul>


### Game Frameworks

<ul>
{% for framework in site.data.techlist.frameworks.game %}
  <li>{{framework}}</li>
{% endfor %}
</ul>


### Other tools I use

<ul>
{% for tool in site.data.techlist.tools %}
  <li>{{tool}}</li>
{% endfor %}
</ul>
