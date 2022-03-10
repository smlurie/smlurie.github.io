---
layout: archive
title: "Software"
permalink: /software/
author_profile: true
---
Other projects:
{% for post in site.portfolio reversed %}
 { include archive-single.html %}
{% endfor %}
