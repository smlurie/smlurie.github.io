---
layout: archive
title: "Other projects"
permalink: /software/
author_profile: true
---
{% for post in site.portfolio reversed %}
 {% include archive-single.html %}
{% endfor %}
