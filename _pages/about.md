---
permalink: /
title: Junteng Liu
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a first-year Ph.D. candidate at the **HKUST NLP Group**, advised by **Prof. Junxian He**. I graduated from **Shanghai Jiao Tong University (SJTU)** in June 2024. My research focuses on **natural language processing** and **machine learning**.

## Academic Background

- **Ph.D. in Computer Science**, Hong Kong University of Science and Technology, 2024-Present.
- **B.Eng.**, Shanghai Jiao Tong University, 2020-2024 (graduated in June 2024).
- **Honors:** Zhiyuan Honor Scholarship, Shanghai Jiao Tong University.

## Research Experience

- **Research Intern**, MINIMAX, February 2025-Present.
- **Research Intern**, Tencent WXG, June 2024-September 2024. Advisor: Zifei Shan.
- **Research Intern**, Shanghai AI Lab, June 2023-December 2023. Advisor: Prof. Yu Cheng.
- **Ph.D. Supervisor:** Prof. Junxian He, HKUST NLP Group. Prof. He previously advised Junteng Liu during his undergraduate studies at Shanghai Jiao Tong University.

## Publications

A full list is also maintained on the [Publications]({{ "/publications/" | relative_url }}) page and on [Google Scholar](https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate).

{% include base_path %}

{% if site.publication_category %}
  {% for category in site.publication_category %}
    {% assign title_shown = false %}
    {% for post in site.publications reversed %}
      {% if post.category != category[0] %}
        {% continue %}
      {% endif %}
      {% unless title_shown %}
        <h3>{{ category[1].title }}</h3>
        {% assign title_shown = true %}
      {% endunless %}
      {% include archive-single.html %}
    {% endfor %}
  {% endfor %}
{% else %}
  {% for post in site.publications reversed %}
    {% include archive-single.html %}
  {% endfor %}
{% endif %}

## Skills & Research Interests

- **Core areas:** Natural Language Processing; Machine Learning.
- **Research interests:**
  - LLM Reasoning and Reinforcement Learning
  - Hallucination in Vision-Language Models (VLMs)
  - LLM Truthfulness and Interpretability

## Contact

- **Email:** [jliugi@connect.ust.hk](mailto:jliugi@connect.ust.hk)
- **GitHub:** [github.com/Vicent0205](https://github.com/Vicent0205)
- **Google Scholar:** [Junteng Liu - Google Scholar](https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate)
- **X (Twitter):** [@junteng88716710](https://twitter.com/junteng88716710)
