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

ol {
      reversed: 1;
    }

ol li::before {
      content: \[counter(index)\];
}

<ol reversed=1>
    <li>小米手机</li>
    <li>华为手机</li>
    <li>魅族手机</li>
</ol>

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
