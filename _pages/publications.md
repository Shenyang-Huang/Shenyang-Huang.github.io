---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on [Google Scholar](https://scholar.google.com/citations?user=BZZ1XE4AAAAJ).


{% include base_path %}

{% for post in site.publications reversed %}
  ---
  {% include archive-single.html %}
{% endfor %}

---
<sup>*</sup> Equal authorship
