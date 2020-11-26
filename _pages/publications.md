---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Old one:

<script src="https://bibbase.org/show?bib=https%3A%2F%2Ffranck44.github.io%2Fpublications%2Ffranck-pubs.bib&jsonp=1&group0=year&css=true&show=true"></script>


New one:

<div>
<script src="http://bibbase.org/show?bib=http%3A%2F%2Fscience.mq.edu.au%2F%7Efcassez%2Fbib%2Ffranck-bib.bib&jsonp=1&group0=year&css=true&show=true"></script>
</div>

yet another one:

 <script src="https://bibbase.org/show?bib=https://franck44.github.io/franck-pubs.bib&jsonp=1"></script>



try include from the pub folder:

 <script src="https://bibbase.org/show?bib=https://franck44.github.io/publications/franck-pubs.bib&jsonp=1"></script>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
