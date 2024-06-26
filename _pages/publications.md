---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a> or <a href="{{site.author.researchgate}}">my researchgate profile</a>.</div>
{% endif %}

<?php $contents = file_get_contents("https://bibbase.org/show?bib=https://dblp.org/pid/136/6770.bib&noBootstrap=1"); print_r($contents); ?>

<script src="https://bibbase.org/show?bib=https://dblp.org/pid/136/6770.bib&noBootstrap=1&jsonp=1"></script>



<iframe src="https://bibbase.org/show?bib=https://dblp.org/pid/136/6770.bib&noBootstrap=1"></iframe>

<!-- {% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %} -->
