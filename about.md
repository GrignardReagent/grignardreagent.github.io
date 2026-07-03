---
layout: page
title: About
description: About Xi Yang (Ian) AMRSC, PhD student in computational biology at the University of Edinburgh.
permalink: /about.html
kicker: About
hero_title: Computational biology grounded in chemistry, modelling, and research software.
hero_image: assets/ian-yang-headshot.jpg
hero_image_alt: Xi Yang (Ian) headshot
---

## Profile

I am Xi Yang (Ian), AMRSC, a PhD student in computational biology at the University of Edinburgh. My current research focuses on characterising and mathematically modelling metabolic oscillations in single cells, especially using yeast time-lapse microscopy, stochastic simulation, and machine-learning representations of biological time series.

Before starting the PhD, I trained across medicinal and biological chemistry, bioinformatics, drug discovery, and computational modelling. That background shapes how I work: I care about biological mechanism, reproducible software, and models that can be tested against experimental data.

## Research Direction

My current project asks whether simulation-trained models can learn useful representations of noisy experimental traces. Recent work uses SimCLR, synthetic telegraph-model trajectories, and downstream classifiers to transfer from stochastic simulations to real transcription-factor localisation data.

Longer term, I am interested in interpretable and useful machine-learning workflows for single-cell biology, early-stage drug discovery, and robust scientific software.

## Timeline

{% for item in site.data.timeline %}
### {{ item.period }} · {{ item.title }}

{{ item.description }}
{% endfor %}
