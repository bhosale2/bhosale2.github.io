---
layout: single
permalink: /coursework/
title: "Coursework"
excerpt: "Details of the coursework (course projects and recommendations) related to my research interests"
header:
  overlay_image: /assets/images/swimmer.png
  overlay_filter: rgba(0, 0, 0, 0.25)
  image_description: "swimmer"
  caption: "Elastic swimmer school"
#last_modified_at: 2018-05-17T08:41:35-04:00
---

At UIUC, I ended up taking a number of interesting courses that covered a range of topics,
computational and theoretical tools and methods, that are helpful and insightful for
generic as well as specific topics in computational physics. My take
on some of these courses, the coursework involved as well as some other recommendations are
given below:
{: style="text-align: justify;"}

## Fast Algorithms and Integral Equation Methods ([CS598APK](https://relate.cs.illinois.edu/course/cs598apk-f19/)): [Prof Andreas Kloeckner](https://andreask.cs.illinois.edu/aboutme/)

This course teaches a unique flavour of techniques and tools (including the famed *Fast
Multipole Method*) for solving PDE boundary value problems, particularly in the *integral
equations* formulation, where a significant reduction in the algorithmic cost can be
achieved for problems that show super-linear runtime scaling. As a course project, I
implemented a 2D Helmholtz PDE solver based on Combined Field Integral Equation
(CFIE) formulation for acoustic scattering from a surface in a half-space domain with
different boundaries conditions on the boundary wall. Details can be found in this
[report](/assets/paps/cs598rep.pdf) with the `Python` implementation of the algorithm
in the following [repo](https://github.com/bhosale2/2d_helmholtz_solver_CFIE).
Shown below is a scattering phenomenon from a body (details in caption):

<figure class="align-center">
  <img src="{{site.url}}{{site.baseurl}}/assets/images/apk_project.png" alt="">
  <figcaption>Wave displacement field for (a) the incident field from a point source and (b) scattered field from a star shaped sound-soft body.</figcaption>
</figure>

## Numerical Methods for Partial Differential Equations: ([CS555](https://relate.cs.illinois.edu/course/cs555-s19/)): [Prof Paul Fischer](http://fischerp.cs.illinois.edu/)

This course builds a strong wide foundation of numerical analysis and computational
physics by covering the basics of finite differences, volumes and elements (mostly),
followed by advanced topics such as discontinuous Galerkin and spectral methods. As a course
project, we solved the incompressible unsteady Navier--Stokes (UNS) equations using the
spectral element method. Shown below is a result generated from our solver for a lid
driven cavity (details in caption).

<button onclick="/assets/paps/cs555_poster.pdf" class="btn btn-info">Poster</button>
<button onclick="https://drive.google.com/file/d/14qgRxqOVArN_cDVdZ7Fpx0r6mWgg22rD/view?usp=sharing" class="btn btn-info">Notes</button>

<figure class="align-center">
  <img src="{{site.url}}{{site.baseurl}}/assets/images/ldc.png" alt="">
  <figcaption>Lid driven cavity simulation using spectral element method: Contours of velocity magnitude for Re=400.</figcaption>
</figure>

## Theoretical courses

Besides the above numerical theme courses, I would also recommend (with my notes for reference) 
some theoretical courses offered at UIUC, that greatly enhance the understanding of physics
and mechanics of the systems seen around us:

- ***Asymptotic Methods*** ([TAM549](https://mechanical.illinois.edu/courses/profile/TAM549)):
[Prof Moshe Matalon](https://mechanical.illinois.edu/directory/profile/matalon)

- ***Wave Motion***: ([TAM518](https://mechanical.illinois.edu/courses/profile/TAM518)):
[Prof Sascha Hilgenfeldt](https://mechanical.illinois.edu/directory/faculty/sascha)

<button onclick="https://drive.google.com/file/d/1uRSo8UAPgLmO41X_x39maCNKUI0-WOkg/view?usp=sharing" class="btn btn-info">Notes</button>
