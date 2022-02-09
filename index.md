---
title: Statistical Learning Seminars
layout: page
feature_image:
feature_text:
---

<style>
    img {margin: 1.5ex; float: right; align: right; padding-top: 2.5ex;}
    h4 {margin-bottom: 0.5ex; padding-bottom: 1.3ex;}
</style>

The effects of CoViD-19 pervade through research communities across the
globe, causing canceled conferences, postponed research visits, and suspended
projects. Like [many others](/links), we have sought other opportunities for
collaboration in spite of the current state of affairs and have therefore
organized this online seminar series in statistical learning.

## Format

We use [zoom](https://zoom.us/) for all the sessions. Upon joining the seminar,
you will be placed in a waiting room; please wait for the host to let you in to
the meeting.

The seminars are approximately an hour long with anywhere between 20 and 40
minutes allocated to the presentation and the rest for discussion. Sessions
are held on a regular basis on Fridays at [15:30
CET](https://www.thetimezoneconverter.com/?t=15%3A30%20pm&tz=Stockholm&). See
[Previous Talks](/previous-talks) for recordings, slides, and resources from
previous seminars.

### Zoom Link

<https://lu-se.zoom.us/j/65067339175>

### Mailing List

To receive announcements for upcoming seminars, please join the group at
<https://groups.google.com/g/statlearnsem>.

### Calendar Event

[Link to calendar event](https://lu-se.zoom.us/meeting/u5Etce6rrTIrHdGmDxIUKT33_HsILcrt6Tui/ics?icsToken=98tyKu-trj0tGdecsR6CR_MMAo_oKOnztlhcgqd6kTv9KhV4VlClCcpRG558AsyG)

## Upcoming Talks

### Friday, February 11 [15:00 CET](tz_mod)

#### Magali Champion (IUT de Paris – Rives de Seine, University of Paris)

Title
: l1-spectral clustering algorithm: a spectral clustering method using
l1-regularization

Abstract
: Detecting cluster structure is a fundamental task to understand and visualize
functional characteristics of a graph. Among the different clustering methods
available, spectral clustering is one of the most widely used due to its speed
and simplicity, while still being sensitive to high perturbations imposed on the
graph. In this work, we present a variant of the spectral clustering, called
l_1-spectral clustering, based on Lasso regularization and adapted to perturbed
graph models. By promoting sparse eigenbases solutions of specific
l_1-minimization problems, it detects the hidden natural cluster structure of
the graph. The effectiveness and robustness to noise perturbations is confirmed
through a collection of simulated and real biological data.
Joint work with C. Champion, M. Blazère, R. Burcelin and JM. Loubes.

<img src="/assets/pictures/megali-champion.jpg" align="right" width="200px">

Related Work
: [l1-spectral clustering algorithm: a spectral clustering method using
l1-regularization](https://hal.archives-ouvertes.fr/hal-03095805/document)

About
: Magali Champion is an assistant professor in statistics at the
department STID of IUT de Paris – Rives de Seine at the University of Paris.
She is also part of the MAP5 lab and currently a visiting reacher
at the Seminar for Statistics of the ETH Zürich. Her interests are
primarily in the fields on statistical learning
and computational biology.

### Friday, February 25 [15:30 CET][tz]

#### Wojciech Rejchel (Nicolaus Copernicus University, Torun)

Title
: Selection consistency for high-dimensional categorical data

Abstract
: Selection with categorical data is challenging even for a moderate number of
variables, because one parameter is roughly needed to encode one category or
level. The group lasso is a well known and efficient algorithm for selection
continuous or categorical variables, but all estimates related to a selected
factor usually differ, so a fitted model may not be sparse. To make a group
lasso solution sparse, we pro- pose to merge levels of the selected factor, if a
difference between its corresponding estimates is less than some predetermined
threshold. We prove that under weak conditions our algorithm recovers the true,
sparse linear or logistic model even for the high-dimensional scenario, that is
when a number of parameters is greater than a sample size. To our knowledge,
selection consistency has been proven many times for different algorithms
fitting sparse models with categorical variables, but our result is the first
for the high-dimensional scenario.

Related Work
: [Group Lasso merger for sparse prediction with high-dimensional categorical
data](https://arxiv.org/abs/2112.11114)

<!-- <img src="/assets/profilepic-nghia-tran.png" align="right" width="200px"> -->

About
: Wojciech Rejchel is an assistant professor at the Department of
Mathematics and Computer Science at Copernicus University in Torun, Poland.

### Friday, March 4 [15:30 CET][tz]

#### Nghia Tran (Oakland University)

Title
: Sharp, strong, and unique minimizers for low complexity robust recovery

Abstract
: In this talk, we show the important roles of sharp minima and
strong minima for robust recovery. We also obtain several characterizations
of sharp minima for convex regularized optimization problems. Our
characterizations are quantitative and verifiable especially for the case
of decomposable norm regularized problems including sparsity,
group-sparsity, and low-rank convex problems. For group-sparsity
optimization problems, we show that a unique solution is a strong solution
and obtain quantitative characterizations for solution uniqueness.

<img src="/assets/profilepic-nghia-tran.png" align="right" width="200px">

Related Work
: [Sharp, strong and unique minimizers
for low complexity robust recovery](https://arxiv.org/abs/2111.05444)

About
: Nghia Tran is an associate professor at the Department of Mathematics
and Statistics at Oakland University, Rochester, Michigan, USA. His primary
research focus has been non-smooth optimization, variational analysis, and
applications thereof.

[tz]: https://dateful.com/convert/stockholm-sweden?t=3pm

## Organization

This seminar series is a joint effort organized by
[The Department of Mathematics, Wrocław University](https://www.math.uni.wroc.pl),
[The Department of Mathematics, University of Burgundy](https://math.u-bourgogne.fr/), and
[The Department of Statistics, Lund University](https://stat.lu.se).

<div class="row">
  <div class="column">
    <img src="assets/logo-lu.svg" alt="Lund University" style="height:170px">
  </div>
  <div class="column">
    <img src="assets/logo-burgundy.png" alt="University of Burgundy" style="width:auto height:170px">
  </div>
  <div class="column">
    <img src="assets/logo-wroclaw.svg" alt="Wroclaw University" style="height:170px">
  </div>
</div>
