---
permalink: /
title: "About"
excerpt: "About me"
author_profile: true
redirect_from: 
  - "/wordpress/"
  - "/wordpress/index.html"
---

{% include base_path %}

I am a first year Ph.D. student in Computer Science at <a href="https://www.gatech.edu/">Georgia Tech</a>, advised by Professor <a href="https://cocoxu.github.io/">Wei Xu</a> and Professor <a href="https://aritter.github.io/">Alan Ritter</a>. Before that, I was an AI Research Engineer at <a href="https://www.vinai.io/">VinAI Research, Vietnam</a>. I also spent two wonderful years at VinAI as an AI Research Resident under the supervision of Professor <a href="https://ix.cs.uoregon.edu/~thien/">Thien Huu Nguyen</a>. I obtained my B.S. degree in Computer Science from <a href="https://en.hust.edu.vn/">Hanoi University of Science and Technology</a>.

## My work and research
My research interest lies in the intersection of Natural Language Processing and Machine Learning. Recently, I focus on the following topics: Dialog system, Controllable text generation.

## Selected papers
{% for post in site.selectedarticles reversed %}
  {% include archive-single.html %}
{% endfor %}
