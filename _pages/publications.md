---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---



You can also find my articles on <a href="https://scholar.google.com/citations?hl=en&user=kZxMlEQAAAAJ">my Google Scholar profile</a>.


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
