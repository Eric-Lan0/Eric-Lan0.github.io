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
  counter-reset: num 4;
  list-style: none;
  li::before{
  counter-increment: num -1;
  content: '['counter(num)'] ';
  }
  padding-left: 0;
}
</style>
</head>

<body>
<ol>
    <li>小米 <br>
      手机</li>
    <li>华为手机</li>
    <li>魅族手机</li>
</ol>
</body>
</html>

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
