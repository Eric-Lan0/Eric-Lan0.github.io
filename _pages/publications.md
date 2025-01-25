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

<html>
<head>
<style>
ol {
  counter-reset: num;
  list-style: none;
  li::before{
  counter-increment: num 1;
  content: '第' counter(num) '条:';
  }
  padding-left: 0;
}
</style>
</head>

<body>
<ol reversed=1>
    <li>小米手机</li>
    <li>华为手机</li>
    <li>魅族手机</li>
</ol>
</body>
</html>

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
