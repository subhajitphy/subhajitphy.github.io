---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}

{% endif %}
See my [up-to-date publication list in NASA ADS]([https://ui.adsabs.harvard.edu/search/q=%20author%3A%22susobhanan%2C%20abhimanyu%22&sort=date%20desc%2C%20bibcode%20desc&p_=0](https://ui.adsabs.harvard.edu/search/filter_database_fq_database=NOT&filter_database_fq_database=*%3A*&filter_database_fq_database=database%3A%22earthscience%22&fq=%7B!type%3Daqp%20v%3D%24fq_database%7D&fq_database=(*%3A*%20NOT%20database%3A%22earthscience%22)&p_=0&q=-docs(96a02eebd55d5cc44bd661bffa806bfc)%20-docs(8d4bf16d1a1e0177ab26217f25375eb9)%20%20author%3A%22dandapat%2C%20subhajit%22&sort=date%20desc%2C%20bibcode%20desc)https://ui.adsabs.harvard.edu/search/filter_database_fq_database=NOT&filter_database_fq_database=*%3A*&filter_database_fq_database=database%3A%22earthscience%22&fq=%7B!type%3Daqp%20v%3D%24fq_database%7D&fq_database=(*%3A*%20NOT%20database%3A%22earthscience%22)&p_=0&q=-docs(96a02eebd55d5cc44bd661bffa806bfc)%20-docs(8d4bf16d1a1e0177ab26217f25375eb9)%20%20author%3A%22dandapat%2C%20subhajit%22&sort=date%20desc%2C%20bibcode%20desc).
{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
