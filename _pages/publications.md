---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

The complete list is on my *[Google Scholar profile](https://scholar.google.com/citations?user=0OkYBPQAAAAJ&hl=en&authuser=1)*.

{% include base_path %}

<style>
ol.ref li::before{content: '\['counter(num)'\]';}
</style>

<ol reversed=1, class="ref">
    <li>小米手机</li>
    <li>华为手机</li>
    <li>魅族手机</li>
</ol>


{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
