---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D. in Computer Science, Hong Kong University of Science and Technology, 2024 (in progress)
* B.Eng. in Computer Science, Shanghai Jiao Tong University, 2020–2024 (graduated June 2024)

Work experience
======
* Research Intern, MINIMAX, 2025–present
* Research Intern, Tencent WXG, June 2024 – September 2024
* Research Intern, Shanghai AI Lab, June 2023 – December 2023

Skills
======
* Natural language processing, machine learning, large language models, LLM reasoning
* PyTorch, Python, Git, LaTeX

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
