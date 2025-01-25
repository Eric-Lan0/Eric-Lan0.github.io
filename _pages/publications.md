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
  counter-reset: num 5;
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
    <li>Self-Sampling Preference Optimization for Diffusion Model Alignment. <br />
        - Reinforcement Fine-Tuning, Diffusion Model, Text-to-Visual Generation. <br />
        Daoan Zhang\*, **Guangchen Lan\***, Dong-Jun Han, Wenlin Yao, Xiaoman Pan, Hongming Zhang, Mingxiao Li, Pengcheng Chen, Dong Yu, Christopher Brinton, Jiebo Luo. <br />
        Submitted to CVPR 2025. February 26, 2025.
    </li>
    <li>华为手机</li>
    <li>魅族手机</li>
    <li>魅族手机</li>
</ol>
</body>
</html>

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
