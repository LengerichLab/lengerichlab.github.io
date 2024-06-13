---
layout: page
title: Context-adaptive systems
description: Training models to reveal heterogeneity by automatically adapting to context
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
    Rather than using a single population model which operates identically for all contexts, context-adaptive systems estimate models which adapt to each local context. {% cite lengerich2023contextualized %}
</p>

<p>
We've built a Python package {% cite ellington2024contextualized %} and applied this paradigm to extend several biomedical tools:
    <ul>
        <li>Indivdual treatment effects {% cite lengerich2022automated %}</li>
        <li>Policy Recovery {% cite deuschel2024contextualized %}</li>
    </ul>
and are continuing to build more tools with context-adaptive modeling.
</p>
