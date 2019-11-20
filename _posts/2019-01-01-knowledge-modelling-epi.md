---
title: 'How are epidemics modeled? A Gentle introduction'
date: 2019-01-01
permalink: /posts/knowledge/modelling-epidemics/
tags:
  - model introduction
  - definition
---


We can try to translate the disease transmission process into mathematical equations.
After all, the basic mechanism of disease transmission between individuals in a population is relatively simple.
 
It usually starts with a few individuals being initially infected. 
They become infectious after some time, and during their infectious period, contact other individuals who are susceptible to the pathogen. 
Some of these contacts will be successful in transmitting the disease to those susceptible individuals. 
And the cycle goes on, until the pool of susceptible is exhausted.

This transmission process was modelled with mathematical equations in the 1910s by the Nobel prize winner [Ronald Ross](https://en.wikipedia.org/wiki/Ronald_Ross){:target="_blank"} during his work on malaria, and was further developed in the late 1920s by [Kermack and McKendrick](https://en.wikipedia.org/wiki/Kermack%E2%80%93McKendrick_theory){:target="_blank"}.

To actually translate the transmission process into equations, we will step into the infector's shoes and keep track of when s/he transmits the pathogen to other individuals. 






Epidemic models aim to understand the mechanisms driving  outbreaks. 
Hence, we often try to shape epidemic models as close to reality and incorporate observational data. 
But it is usually difficult to observe perfectly an epidemic, so a lot of statistics is involved to take into account this uncertainty.
As more realistic features are incorporated in the model, its complexity increases and we have no other choice than to ask computers for help to solve the equations. 


