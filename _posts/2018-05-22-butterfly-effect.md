---
layout: single
title:  "Embrace the butterfly effect"
date:   2018-05-22 10:00:00 -0400
categories: misc
author_profile: false
---

By Surge Biswas

TL;DR: The most interconnected cogs of a complex system are often the most critical to its well-being. But they are also few in number and offer the most leverage. Aggressively search for those key non-trivial changes to these cogs in order to find a superior reconfiguration of the system.

We often quote the butterfly effect when some seemingly small, insignificant thing has an _unpredictable_, yet large effect on the outcome; a butterfly flapping its wings here and causing a typhoon half way around the world is the example often used. However, in Greg Egan's sci-fi novel [Permutation City](https://en.wikipedia.org/wiki/Permutation_City), technology and science in the future are so advanced that people are able to use the butterfly effect to their advantage -- particularly, for weather control. By making minimal changes to the atmosphere -- an interdependent, seemingly chaotic system -- they can exact large beneficial weather outcomes disproportionate to their effort.

... large beneficial outomes, disproportionate to effort. Sounds awesome.

Here's maybe another way to think about it; the cogs that are most interconnected and most difficult to change without disrupting the whole system are precisely the cogs that afford the most leverage over the whole system.  This more optimistic interpretation of the butterfly effect is potentially important for drug development, bioengineering, and I imagine for lots of applications where we have to deal with messy interconnected systems (e.g. life generally). 

For example, the product of every gene in every cell of our body influences the product (how much and kind) of many other genes, and some genes are more interconnected than others.  All diseases in some way or another disturb the harmony of this complex, interdependent regulatory network. The optimist's butterfly effect suggests to figure out how to drug the hub genes (possibly in combination), so that changes to them can reach the rest of the network efficiently. This is risky business though since most of the time heavily connected genes are heavily connected for a reason -- they are critical for life! 

Take another example (disclaimer: this is some shameless self-promotion). My colleagues and I wrote a [paper](https://www.biorxiv.org/content/early/2018/06/02/337154) on how machine learning can assist protein engineering. One of the important lessons we learned was that the most important mutations an ML model should learn to make are those that are non-trivial in nature; mutations to amino acids that are heavily structural involved and often vital to the protein's function. We learned that if we can find the right combinations of these non-trivial changes we can find meaningfully and efficiently reconfigured protein variants with improved protein function. 

The theme in both of these examples is as follows: when you make changes to interconnected cogs of a complex, interdependent system, on average you will break the system. However, as these cogs are points of leverage, some significant minority of the time you will reconfigure the system to be better. Therefore it's useful to "chase this variance," especially if you have a cheap way of testing many system configurations _en masse_. The figure below illustrates this thought.

![My helpful screenshot]({{ "/assets/butterfly_effect_fig.jpg" | absolute_url }})

\*



