---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


<script src="http://bibbase.org/show?bib=http%3A%2F%2Fscience.mq.edu.au%2F%7Efcassez%2Fbib%2Ffranck-bib.bib&jsonp=1&group0=year&css=true&show=true"></script>


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
