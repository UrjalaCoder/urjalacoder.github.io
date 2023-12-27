---
layout: page
title: ArXiv analysis notebook
description: Analysis and modeling notebook for ArXiv data.
img: assets/img/arxiv_logo.jpg
importance: 1
category: personal
---

**NOTE:**  The visualization of the embeddings and clusters is in a separate [notebook](https://urjalacoder.github.io/assets/html/arxiv_visualization.html). 

Built with Azure Databricks.

{::nomarkdown}
{% assign jupyter_path = "assets/jupyter/arxiv_analysis.ipynb" | relative_url %}
{% capture notebook_exists %}{% file_exists assets/jupyter/arxiv_analysis.ipynb %}{% endcapture %}
{% if notebook_exists == "true" %}
    {% jupyter_notebook jupyter_path %}
{% else %}
    <p>Sorry, the notebook you are looking for does not exist.</p>
{% endif %}
{:/nomarkdown}

