---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
redirect_from:
  - /research
---
You can find a pdf version of my Research Statement [here](https://ivanrazu.github.io/files/Research_statement_Ivan.pdf).

I am interested in developing mathematical models to study the dynamics of inflammation and immune response. In particular, I am interested in understanding the role of energetics in the acute immune response during sepsis.  In general we use ordinary differential equations to develop such models, although it is also common to use partial and stochastic differential equations. 

Once a model is well tuned, we conduct analytic and numerical explorations such as bifurcation analysis of these models which provide a rich inside of the biology of the problem. In optimal situations these models can be used to predict patient outcome and help to reduce mortality by introducing therapy at the right moment. As part of the model tunning, we perform parameter space reduction, like structural and practical identifiability, sensitivity analysis, parameter correlation with the end goal of obtaining parameter estimates through different techniques such as Ordinary Least Squares, Monte Carlo Markov Chains (MCMC) algorithms, and variations of these like Delayed Rejection Adaptive Metropolis (DRAM).  
I am also interested in implementing optimal control to our models to find best treatment strategies to fight an infection.  

## Projects

### Mathematical Modeling of Energy Consumption in the Acute Inflammatory Response.

* Several studies have found a relation between sepsis and low levels of adenosine triphosphate (ATP) combined with overproduction of lactate and nitric oxide (NO). In this project we developed a system of ordinary differential equations to study the dynamics of the acute inflammatory response and its interactions with the production and demand of ATP. 
We also explored some altered metabolic states such as hypoglycemia, hyperglycemia, and hypoxia in the presence of sepsis obtaining consistent resuts with the literture.

### A Data-driven Mathematical Study of the Role of Energy in Sepsis.

* Building up on our previous model, we are currently working on determining main diferences across survivors and non-survivors on a study done on thirty-two baboons that were sedated, and 2 ×10^9 colony forming units per kilogram of Escherichia coli were infused IV into each subject over 2 hours. Our main goal is to identify the role of energetics in each of the groups and to determine cause of death for the non-survivor cohort.  

{% include base_path %}
