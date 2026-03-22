---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

For a complete and up-to-date list of publications, see my  
**[Google Scholar profile](https://scholar.google.com/citations?hl=en&user=BurWbwoAAAAJ)**  
(2470+ citations · h-index: 14 · i10-index: 14 · 24 publications)
{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
