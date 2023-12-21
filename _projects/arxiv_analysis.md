---
layout: page
title: ArXiv analysis notebook
description: Analysis and modeling notebook for ArXiv data.
img:
importance: 5
category: personal
---

{::nomarkdown}
{% assign jupyter_path = "assets/jupyter/arxiv_analysis.ipynb" | relative_url %}
{% capture notebook_exists %}{% file_exists assets/jupyter/arxiv_analysis.ipynb %}{% endcapture %}
{% if notebook_exists == "true" %}
    {% jupyter_notebook jupyter_path %}
{% else %}
    <p>Sorry, the notebook you are looking for does not exist.</p>
{% endif %}
{:/nomarkdown}