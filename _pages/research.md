---
layout: single
permalink: /research/
title: "Research"
excerpt: "Flow--structure interaction; Viscoelasticity, from discrete to the continuum"
header:
  overlay_image: /assets/images/flag_flap.gif
  overlay_filter: rgba(255, 255, 255, 0.5)
  image_description: "elasticflagflow"
  caption: "Elastic flag flapping in the wake of a rigid heated cylinder at Re=200"
#last_modified_at: 2018-05-17T08:41:35-04:00
---

Currently a member of <a href="https://mattia-lab.com/">Gazzola Lab</a>, I am deeply
passionate about exploring and understanding, using computational and theoretical tools,
the physics involving flow--structure interaction (FSI), multiphase phenomena,
interplay between elasticity and fluid dynamics of FSI systems and continuum viscoelasticity.
Below, you can find brief descriptions of the research domains I'm involved in:
{: style="text-align: justify;"}

## Soft/rigid body flow-structure interaction

Accurate and versatile solvers are the key to shed light on and dissect underlying physics in
FSI systems presenting body elasticity/compliance, with potential applications in medicine, soft
robotics, flow control and inertial microfluidics. With that in mind, my recent venture at
[Gazzola Lab](https://mattia-lab.com/) with the help of my colleague
[Tejaswin Parthasarathy](https://parthas1.github.io/) has led to the development of a robust, 
flexible numerical algorithm for solving incompressible flow–structure interaction problems
for mixed rigid/soft body representations, within a consistent framework based on the
remeshed vortex method. The preprint detailing our study with the algorithm, benchmarks and
illustrations can be found here [here](https://arxiv.org/pdf/2011.09669.pdf) with one of the
illustration cases shown below: a rigid cylinder falling on an elastic trampoline, with both
bodies submerged in a viscous fluid.
{: style="text-align: justify;"}

<figure class="align-center">
  <img src="{{site.url}}{{site.baseurl}}/assets/images/tramp.gif" alt="">
  <figcaption>A rigid cylinder falling under gravity on a soft trampoline, with orange/blue
representing positive/negative vorticity.</figcaption>
</figure>

## Viscous streaming

Viscous streaming refers to the time-averaged steady flow that arises when an immersed body
of characteristic length scale *D* undergoes small-amplitude oscillations (compared to *D)*
in a viscous fluid. With the broad range of applications of viscous streaming in microfluidic
flow manipulation, particle trapping, scalar transport and passive swimming, our understanding
of how streaming flow features and topology are affected by multiple body length scales remains
largely incomplete. In my Master's thesis work, we attempted to elucidate the mechanisms
at play, when streaming flow topology is manipulated via regulated variations of shape geometry,
thus providing a rational design approach for microfluidic applications. Our work, which can be
found [here](/assets/paps/curv.pdf) has been published recently in ***Journal of Fluid Mechanics***,
with a glimpse of the effects of geometric variation on streaming flows shown below:
{: style="text-align: justify;"}

<figure class="align-center">
  <img src="{{site.url}}{{site.baseurl}}/assets/images/stream.gif" alt="">
  <figcaption>Streaming flow visualization for a circular cylinder and a bullet
  shaped cylinder.</figcaption>
</figure>

## Dynamics of a leaf upon raindrop impact

Dynamics of drop impact on soft surfaces has drawn a lot of attention for its applications and
is motivated by natural examples like raindrop impact on a leaf. Previous studies have focused
on categorizing the bending motion observed, using cantilever beam theory, but the complex dynamic
response shown by a leaf involving other degrees of motions like torsion about the petiole,
remains yet to be understood. In a recent study, that can be found [here](/assets/paps/leaf.pdf),
published in ***Bioinspiration & Biomimetics***, we decompose the leaf's motion as a superposition
of multiple modes modeled as damped harmonic oscillators. Our results, that are in good agreement with
experimental results, shed light on the design of potential raindrop energy harvesting devices
mimicking a leaf’s structure. A video capturing the dynamics of a leaf's response upon raindrop
impact is shown below:
{: style="text-align: justify;"}

<figure class="align-center">
  <img src="{{site.url}}{{site.baseurl}}/assets/images/leaf.gif" alt="">
  <figcaption>Raindrop impact on a Katsura leaf.</figcaption>
</figure>

## Emergent mechanics of a "bird nest" system

Systems of randomly packed, macroscopic elements, from jammed spherical grains to tangled
long filaments, represent a broad class of disordered meta-materials with a wide range
of applications and manifestations in nature. A *bird nest* presents itself at an interface
between hard round grains described by granular physics to long soft filaments, the center
of textile material science. In a recent **Research Highlight** published in
***Journal of Applied Physics*** (found [here](/assets/paps/nest.pdf)), while reviewing packing
statistics, mechanical response characterization, and consideration of boundary effects,
we present a perspective that attempts to establish a link between the bulk and local behavior
of a pile of sand and a wad of cotton, demonstrating the nest’s relationship with each.
Our research, in collaboration with [Prof King](http://www.mbod-lab.com/), has been covered in
***New York Times*** ([article link](https://www.nytimes.com/2020/03/17/science/why-birds-are-the-worlds-best-engineers.html)),
with a characteristic compression cycle response of the computational *bird nest* systems shown below:
{: style="text-align: justify;"}

<figure class="align-center">
  <img src="{{site.url}}{{site.baseurl}}/assets/images/nest.gif" alt="">
  <figcaption>Compression cycles of different computational bird nest systems.</figcaption>
</figure>

## Natural convection characterization over a heated cylinder

Natural convection is widely used as a conventional method for cooling in various applications
such as shell tube heat exchangers, electronic cooling, heat transfer through submerged pipelines,
steam pipes in power plants and cooler pipes in nuclear reactors, due to its high reliability and
low costs in design and maintenance. In my work with
[Prof K. C. Lin](https://sites.google.com/site/kuangclin/home), we proposed a 3D-CFD model to predict
the existing experimental data and heat transfer characterization for a natural convection flow
over a heated horizontal cylinder, published in ***Applied Thermal Engineering*** (details can be
found [here](/assets/paps/plume.pdf)). Our work has been covered in ***Advances in Engineering***
([article link](https://advanceseng.com/3d-cfd-investigation-free-convection-flow-above-heated-horizontal-cylinder-comparisons-experimental-data/)),
with a glimpse of the research shown below:
{: style="text-align: justify;"}

<figure class="align-center">
  <img src="{{site.url}}{{site.baseurl}}/assets/images/plume.png" alt="">
  <figcaption>Variations of the velocity and temperature profiles over a heated cylinder.</figcaption>
</figure>

Due credits to Prof. Gazzola for developing the core of the FSI-remeshed vortex method code,
which I have used to simulate some of the results shown in this website.
{: .notice--info}
