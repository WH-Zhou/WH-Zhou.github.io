---
layout: archive
title: "Solar system small bodies"
permalink: /solar_system/
author_profile: true
---

My research includes:
* [Binary Yarkovsky effect on binary asteroids](#binary-yarkovsky-effect) 
* [Crater-indcued YORP effect on main belt asteroids](#crater-induced-yorp-cyorp-effect)
* [Rotational evolution of main belt asteroids](#rotational-evolution-of-main-belt-asteroids)

## Binary Yarkovsky effect on binary asteroids ([Zhou et al. 2024a](https://iopscience.iop.org/article/10.3847/2041-8213/ad4f7f); [Zhou, 2024](https://www.aanda.org/articles/aa/abs/2024/12/aa52146-24/aa52146-24.html))
-----
We discovered how the Yarkovsky effect affects the binary asteroids.

(1) The eclipse-induced thermal perturbation produces a net thermal force that moves the component towards the synchronous orbit where the spin period equals the orbital period.

(2) The radiation from the other component produces a net thermal force moves the component towards the opposite direction of the synchronous orbit.

For nearly co-planar binaries, for which the mutual orbit aligns with the heliocentric orbit, the (1) always dominates over (2). We propose this effect could account for the synchronization process of small binary asteroids in main belt asteroids and near Earth asteroids. 


<figure>
  <img src="/images/binary_YK.jpg" alt="This is the caption for the image">
  <figcaption>Schematics of binary Yarkovsky effect.</figcaption>
</figure>

<figure style="max-width: 400px; margin: auto;">
  <img src="/images/binary_temperature.gif" alt="This is the caption for the image" style="width: 100%; height: auto;">
  <figcaption style="text-align: center;">The temperature distribution of binary asteroids.</figcaption>
</figure>


With this newly discovered effect, more discoveries on binary asteroid dynamics to come soon...



## Crater-induced YORP (CYORP) effect on main belt asteroids ([Zhou et al. 2022](https://www.aanda.org/articles/aa/abs/2022/12/aa44386-22/aa44386-22.html); [Zhou & Michel 2024](https://www.aanda.org/articles/aa/abs/2024/02/aa46970-23/aa46970-23.html))
-----
We developed a semi-analytical method to calculate the temperature distribution of a crater and the produced thermal torque, namely the CYORP torque. We found that roughly speaking, a crater with the size 1/3 of the asteroid could produce a CYORP torque comparable to the YORP torque. Based on this tool, we can estimate the YORP torque change brought by a sub-catastrophic impact, and study the asteroid rotational evolution under collisions and YORP. 


<div style="display: flex; justify-content: space-between;">
  <div style="margin-right: 10px;">
    <img src="/images/ryugu.gif" alt="Image 1" style="width: 100%;">
    <figcaption style="text-align: center;">Temperature of Bennu's surface over a day (numerical).</figcaption>
  </div>
  <div style="margin-left: 10px;">
    <img src="/images/no_scatter_selfheating.gif" alt="Image 2" style="width: 100%;">
    <figcaption style="text-align: center;">Temperature of a crater over a day (analytical).</figcaption>
  </div>
</div>

<figure>
  <img src="/images/Exm_spin_evolution.jpg" alt="This is the caption for the image">
  <figcaption>Evolution of the spin rate (left panel) and the obliquity (right panel) of a 10 km synthetic asteroid. In the presence of the static YORP torque (blue line), the asteroid gradually decelerates until it reaches a quasi-non-rotational state. Subsequently, we impose a new rotational state on the asteroid by assigning random values of rotational speed and obliquity. Conversely, when incorporating the CYORP torque (red line), the asteroid follows a different path, exhibiting random fluctuations in its spin rate due to the occurrence of impacts, creating new craters that lead to changes in the CYORP torque. As a result, the asteroid experiences intermittent transitions between spin up and spin down.</figcaption>
</figure>

With CYORP, it's time to estimate the stochastic YORP and Yarkovsky effect...


## Rotational evolution of main belt asteroids ([Zhou et al. 2025](https://www.nature.com/articles/s41550-025-02489-8))
-----


There are three mysteries regarding the slowly rotating asteroids in the main belt:

1. Excess of slow rotators. The overabundance of asteroids rotating slowly was realized about 40 years ago. Collisions typically produce a Maxwell distribution in the spin rate and the classic YORP theory produces a uniform distribution. The existing theory cannot explain the excess of slow rotators.

2. Gap. Recent Gaia observation reveals a visible gap in the period-diameter distribution of asteroids, which separates the slow rotators from faster rotators. Classic theory only predicts smooth distributions without any kind of gap.

3. Tumbler distribution. The distribution of tumbling asteroids in the period-diameter is not well explained.

This paper attempted to solve the above three problems by constructing a novel comprehensive rotation evolution model and fitting it to Gaia observation.

<figure>
  <img src="/images/spin_evolution.gif" alt="This is the caption for the image">
  <figcaption>Period-diameter distribution of main belt asteroids from Gaia data (left) and simulation (right).</figcaption>
</figure>



