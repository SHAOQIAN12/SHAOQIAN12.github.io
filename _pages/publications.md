---
layout: archive
title: "Projects"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

<!-- {% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %} -->

## ⭐ Imitating Cost Constrained Behaviors in Reinforcement Learning

We explore imitation learning in scenarios where expert behavior is influenced by both rewards and constraints, introducing methods such as Lagrangian, meta-gradient, and cost violation-based approaches to address trajectory cost constraints, with empirical results showing that the meta-gradient-based approach outperforms existing methods in accurately imitating cost-constrained behaviors

▶ **Key Components**

<div class="row">
  <div class="col-md-12">
    <img src="/images/Imitation Learning.png" alt="Imitation Learning Framework" class="img-responsive">
  </div>
</div>

## ⭐ Preference-Aware Delivery Planning for Last-Mile Logistics

Our research addresses the challenge of optimizing last-mile logistics delivery routes, proposing a hierarchical route optimizer with learnable parameters that integrates op- timization and machine learning to bridge the gap between optimized routes and practitioner-preferred routes, which often arise from differing priorities.
▶ **System Architecture**

<div class="row">
  <div class="col-md-12">
    <img src="/images/Last Mile.png" alt="Delivery System Architecture" class="img-responsive">
  </div>
</div>

## ⭐ LLM-based Early Rumor Detection with Imitation Agent


Our research tackles Early Rumor Detection (EARD) by predicting the earliest point to assess a claim’s truthfulness from social media. A lightweight agent analyzes time-series data while an LLM detects rumors, using a Markov Decision Process (MDP) with expert trajectories. 

▶ **System Architecture**

<div class="row">
  <div class="col-md-12">
    <img src="/images/Example.png" alt="Delivery System Architecture" class="img-responsive">
  </div>
</div>
