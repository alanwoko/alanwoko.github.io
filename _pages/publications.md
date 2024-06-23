---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can check <a href="https://scholar.google.com/citations?user=gIQOYDYAAAAJ&hl=en">my Google Scholar profile</a> for an updated list.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
