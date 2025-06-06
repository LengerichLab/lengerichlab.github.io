---
layout: page
title: Foundation models as context
description: Using foundation models as flexible priors and contextual memory for downstream inference tasks.
img: assets/img/bridge.jpeg
importance: 2
category: methods
related_publications: true
---

{% include figure.liquid loading="eager" path="assets/img/bridge.jpeg" title="bridge" class="img-fluid rounded z-depth-1" %}

Prior knowledge is a powerful form of context in statistical inference. Traditionally, applying such knowledge required expert intervention on each new problem. Today, foundation models encode broad domain knowledge in a reusable, black-box format. Our work focuses on extracting and operationalizing this implicit knowledge by connecting foundation models to structured, parametric statistical models.

We are building a bi-directional bridge between the two paradigms:

- *Inference from Foundation Models*: Using foundation models to inform and regularize statistical estimators {% cite mahbub2024one %}.
- *Understanding with Foundation Models*: Using foundation models to interpret, summarize, or explain structured models automatically {% cite bordt2024data %} {% cite lengerich2023llms %}.
  
<br/><br/>
