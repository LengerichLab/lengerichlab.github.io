---
layout: page
title: Intelligible ML
description: Building glass-box models that are both predictive and interpretable
img: assets/img/glass.jpeg
importance: 3
category: methods
related_publications: true
---

{% include figure.liquid loading="eager" path="assets/img/glass.jpeg" title="glass" class="img-fluid rounded z-depth-1" %}

For many reasons (e.g. scientific inquiry, high-stakes decision making), we need AI systems that are both _accurate_ and _intelligible_.

We find that _interaction effects_ are often a useful lens through which to view intelligibility. Interaction effects {% cite lengerich2020purifying %} are effects which require two input components to know anything about the output (one component alone tells you nothing). Since humans reason by chunking and hierarchical logic, we struggle to understand interactions of multiple variables. If we can instead represent effects as additive (non-interactive) combinations of components, we can understand the components independently and reason about even very complex concepts.

Toward this end, we have designed new architectures including deep additive models {% cite agarwal2022neural %} and contextualized additive models {% cite lengerich2022automated %}, studied deep learning theory through the lens of interaction effects {% cite lengerich2022dropout %}, studied additive models and identifiability {% cite chang2021how %}, {% cite lengerich2020purifying %}, and applied intelligible models to real-world evidence {% cite lengerich2024interpretable %}.

<br/><br/>
