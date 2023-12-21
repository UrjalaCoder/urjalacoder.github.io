---
layout: page
title: ArXiv Visualization notebook
description: Visualization notebook for ArXiv data.
img:
importance: 4
category: personal
---

{::nomarkdown}
{% assign jupyter_path = "assets/jupyter/arxiv_visualization.ipynb" | relative_url %}
{% capture notebook_exists %}{% file_exists assets/jupyter/blog.ipynb %}{% endcapture %}
{% if notebook_exists == "true" %}
    {% jupyter_notebook jupyter_path %}
{% else %}
    <p>Sorry, the notebook you are looking for does not exist.</p>
{% endif %}
{:/nomarkdown}