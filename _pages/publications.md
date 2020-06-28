---
layout: archive
title: "Publications New"
permalink: /publications/
author_profile: true
entries_layouts: grid
type: grid
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
