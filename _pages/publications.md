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
  margin-right: -6em;
  margin-left: 2em;
  margin-bottom: 2em;
  padding-left: 0;
  text-indent: -1.5em;
}
</style>
</head>

<body>
<ol>
    <li>Self-Sampling Preference Optimization for Diffusion Model Alignment. <br />
        <font color="#778899">{Reinforcement Fine-Tuning, Diffusion Model, Text-to-Visual Generation}</font> <br />
        Daoan Zhang*, <strong>Guangchen Lan*</strong>, Dong-Jun Han, Wenlin Yao, Xiaoman Pan, Hongming Zhang, Mingxiao Li, Pengcheng Chen, Dong Yu, Christopher Brinton, Jiebo Luo. <br />
        Submitted to <i>IEEE/CVF Conference on Computer Vision and Pattern Recognition</i> (<font color="#CD5C5C"><strong>CVPR'25</strong></font>). February 26, 2025. <br />
        <a href="https://huggingface.co/papers/2410.05255">[paper]</a>
    </li>
    <br />
    <li>Asynchronous Federated Reinforcement Learning with Policy Gradient Updates: Algorithm Design and Convergence Analysis. <br />
        <font color="#778899">{Reinforcement Learning, Asynchronous System, Distributed Training}</font> <br />
        <strong>Guangchen Lan</strong>, Dong-Jun Han, Abolfazl Hashemi, Vaneet Aggarwal, Christopher Brinton. <br />
        <i>International Conference on Learning Representations</i> (<font color="#CD5C5C"><strong>ICLR'25</strong></font>). January 22, 2025. <br />
        <a href="https://arxiv.org/abs/2404.08003">[paper]</a>
    </li>
    <br />
    <li>Improved Communication Efficiency in Federated Natural Policy Gradient via ADMM-based Gradient Updates. <br />
        <font color="#778899">{Reinforcement Learning, Distributed Training, Optimization}</font> <br />
        <strong>Guangchen Lan</strong>, Han Wang, James Anderson, Christopher Brinton, Vaneet Aggarwal. <br />
        <i>Advances in Neural Information Processing Systems</i> (<font color="#CD5C5C"><strong>NeurIPS'23</strong></font>). September 21, 2023. <br />
        <a href="https://proceedings.neurips.cc/paper_files/paper/2023/hash/bc6a1f968f8b1dae3e880f3f723d7d46-Abstract-Conference.html">[paper]</a>
    </li>
    <br />
    <li>Communication-Efficient Federated Learning for Resource-Constrained Edge Devices. <br />
        <font color="#778899">{Federated Learning, Model Compression, Tensor Decomposition, Zeroth-order Optimization}</font> <br />
        <strong>Guangchen Lan</strong>, Xiao-Yang Liu, Yijing Zhang, Xiaodong Wang. <br />
        <font color="#8B0000"><strong>IEEE Transactions on Machine Learning in Communications and Networking</strong></font>. August 23, 2023. <br />
        <a href="https://ieeexplore.ieee.org/abstract/document/10233897">[paper]</a>
    </li>
</ol>
</body>
</html>
