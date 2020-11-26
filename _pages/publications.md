---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


<script src="https://bibbase.org/show?bib=https%3A%2F%2Ffranck44.github.io%2Fpublications%2Ffranck-pubs.bib&jsonp=1&group0=year&css=true&show=true"></script>


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
