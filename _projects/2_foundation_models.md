---
layout: page
title: Foundation models as context
description: Using foundation models as flexible priors and contextual memory for downstream inference.
img: assets/img/bridge.jpeg
importance: 2
category: methods
related_publications: true
---

<div class="row">
  <div class="col-md-6 mx-auto">
{% include figure.liquid loading="eager" path="assets/img/bridge.jpeg" title="bridge" class="img-fluid rounded z-depth-1" %}
</div>
</div>

Prior knowledge is a powerful form of context in statistical inference. Traditionally, applying such knowledge required expert intervention on each new problem. Today, foundation models encode broad domain knowledge in a reusable, black-box format. Our work focuses on extracting and operationalizing this implicit knowledge by connecting foundation models to structured, parametric statistical models.

<p>
We are building a bi-directional bridge between foundation models and structured statistical estimation:
<ul>
    <li>Using FMs to improve statistical inference {% cite mahbub2024one %}</li>
    <li>Using FMs to automatically understand statistical models {% cite bordt2024data %} {% cite lengerich2023llms %} </li>
</ul>
Our work on <a href="https://incontext.ml">InContextML</a> supports this integration with structured prompting and retrieval-augmented inference.
</p>

<br/><br/>
