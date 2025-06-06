---
layout: page
title: Contextualized Models
description: Models with parameters that adapt to patient, task, or environmental context to support personalized inference.
img: assets/img/heterogeneity.jpeg
importance: 1
category: methods
related_publications: true
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/heterogeneity.jpeg" title="heterogeneity" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<p>
Rather than relying on a one-size-fits-all model, contextualized systems learn parameters that adapt to the local environment — patient characteristics, tasks, or domain shifts. These models improve both accuracy and generalization in heterogeneous data settings.
</p>

<p>
We’ve developed theory and methods to support this framework, including:
<ul>
    <li>Contextualized Machine Learning {% cite lengerich2023contextualized %}</li>
    <li>Contextualiezd Policy Recovery {% cite deuschel2024contextualized %}</li>
    <li>Personalized treatment effects {% cite lengerich2022automated %}</li>
    <li>Personalized Gene Regulatory Networks {% cite ellington2025learning %}</li>
</ul>
Our open-source toolkit, <a href="https://contextualized.ml">
      <img src="/assets/img/contextualized_logo.png" alt="ContextualizedML" width="30%"/>
    </a>, supports model development and application across domains.
</p>

<br/><br/>
