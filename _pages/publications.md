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
  margin-right: -4em;
  margin-left: 2em;
  padding-left: 0;
  text-indent: -1.5em;
}
</style>
</head>

<body>
<ol>
    <li>Self-Sampling Preference Optimization for Diffusion Model Alignment. <br />
        - Reinforcement Fine-Tuning, Diffusion Model, Text-to-Visual Generation. <br />
        Daoan Zhang*, <strong>Guangchen Lan*</strong>, Dong-Jun Han, Wenlin Yao, Xiaoman Pan, Hongming Zhang, Mingxiao Li, Pengcheng Chen, Dong Yu, Christopher Brinton, Jiebo Luo. <br />
        Submitted to <font color="#CD5C5C"><strong>CVPR</strong></font> 2025. February 26, 2025. <br />
        <a href="https://huggingface.co/papers/2410.05255">[paper]</a>
    </li>
    <br />
    <li>Asynchronous Federated Reinforcement Learning with Policy Gradient Updates: Algorithm Design and Convergence Analysis. <br />
        - Reinforcement Learning, Asynchronous System, Distributed Training. <br />
        <strong>Guangchen Lan</strong>, Dong-Jun Han, Abolfazl Hashemi, Vaneet Aggarwal, Christopher Brinton. <br />
        <font color="#CD5C5C"><strong>ICLR</strong></font> 2025. January 22, 2025. <br />
        <a href="https://arxiv.org/abs/2404.08003">[paper]</a>
    </li>
    <br />
    <li>Improved Communication Efficiency in Federated Natural Policy Gradient via ADMM-based Gradient Updates. <br />
        - Reinforcement Learning, Distributed Training, Optimization. <br />
        <strong>Guangchen Lan</strong>, Han Wang, James Anderson, Christopher Brinton, Vaneet Aggarwal. <br />
        <font color="#CD5C5C"><strong>NeurIPS</strong></font> 2023. September 21, 2023. <br />
        <a href="https://proceedings.neurips.cc/paper_files/paper/2023/hash/bc6a1f968f8b1dae3e880f3f723d7d46-Abstract-Conference.html">[paper]</a>
    </li>
    <br />
    <li>Communication-Efficient Federated Learning for Resource-Constrained Edge Devices. <br />
        - Federated Learning, Model Compression, Tensor Decomposition, Zeroth-order Optimization. <br />
        <strong>Guangchen Lan</strong>, Xiao-Yang Liu, Yijing Zhang, Xiaodong Wang. <br />
        <font color="#000080"><strong>IEEE Transactions on Machine Learning in Communications and Networking</strong></font>. August 23, 2023. <br />
        <a href="https://ieeexplore.ieee.org/abstract/document/10233897">[paper]</a>
    </li>
</ol>
</body>
</html>

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
