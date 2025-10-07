---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<!-- Google Scholar link will be added when available -->

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
