---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if 1 %}
  You can also find my articles on <a href="https://scholar.google.com.hk/citations?hl=en&pli=1&user=80uJ64gAAAAJ">my Google Scholar profile</a>.
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
