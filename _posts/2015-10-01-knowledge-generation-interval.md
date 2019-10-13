---
title: 'What is a Generation Interval?'
date: 2015-10-01
permalink: /posts/knowledge/generation-interval/
tags:
  - generation interval
  - definition
  - serial interval
---

The generation interval is simply the interval between the time when an individual is infected, and the time her/his infector was infected. 

For example, Alice was infected on day 3. Alice infects Bob on day 9. The generation interval for this transmission event is 9 - 3 = 6 days. 

There are two ways to observe the generation interval:

* *Forward* in time, from the *infector*'s perspective (Alice)
* *Backward* in time, from the *infectee*'s perspective (Bob)

![gi](/images/gi-definition.png)

Usually, as an epidemic unfolds, we observe _backward_ generation intervals, simply because we cannot look into the future. We can only observe the transmissions events that have occurred in the past. 

This distinction between forward and backward generation intervals may seem trivial. After all, there is only one single value for a given transmission event: there are 6 days between the time Alice and Bob were infected, whatever direction you look at it. 
But, as the epidemic progresses, the backward generation intervals observed are "right-censored": at a given observation time, we haven't yet observed the longest generation intervals (they haven't happened yet at the time we are observing the epidemic). Making the distinction between forward and backward generation intervals allows taking into account this censoring effect. 

As an epidemic outfolds, many transmission events occur. If we know all transmission times, we can calculate the generation interval associated with every transmission. The collection of all the generation intervals forms the generation interval distribution. This distribution is fundamental when modelling the disease transmission process, as illustrated by the renewal equation. Something peculiar happens during an outbreak: the observed generation interval distribution change as time progresses. [This paper](/publication/2015-gi-prsb) explains why this is happening and how to incorporate this phenomenon when using contact-tracing data. 




There is one practical issue with generation interval: we usually cannot observe *directly* the actual infection times. However, the time of symptoms onset is often easier to observe (for example, when fever starts). The interval between the onset of the symptoms of the newly infected individual and her/his infector is called the *serial* interval, and it is often used as a proxy for the generation interval.  
