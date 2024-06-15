---
layout: page
permalink: /resources/
title: Resources
description: We value reproducible and open science.
nav: true
nav_order: 4
---

### Internal resources
- [Lengerich Lab user guide](https://docs.google.com/document/d/1HMHeX9qSOq6PFn_cW47b3tzdJKK6QZGE39u25vsA9QA/edit?usp=sharing)

### Compilations

- [Reading List](https://github.com/LengerichLab/ReadingList)
- [CompBio Datasets for ML](https://github.com/LengerichLab/CompBioDatasetsForMachineLearning)
- [Clinical ML Zoo](https://github.com/LengerichLab/ClinicalMLZoo)

### Advice

- [Thoughts from my Faculty Application Experience](https://benlengerich.medium.com/38f1a29c715e)

### Templates

- [Latex templates for faculty applications](https://www.overleaf.com/read/qdrzkgjkmzqc#b3bdcc)

### Software tools

{% if site.data.repositories.github_repos %}

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.github_repos %}
    {% include repository/repo.liquid repository=repo %}
  {% endfor %}
</div>
{% endif %}

### GitHub users

{% if site.data.repositories.github_users %}

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for user in site.data.repositories.github_users %}
    {% include repository/repo_user.liquid username=user %}
  {% endfor %}
</div>

---

{% if site.repo_trophies.enabled %}
{% for user in site.data.repositories.github_users %}
{% if site.data.repositories.github_users.size > 1 %}

  <h4>{{ user }}</h4>
  {% endif %}
  <div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% include repository/repo_trophies.liquid username=user %}
  </div>

---

{% endfor %}
{% endif %}
{% endif %}
