---
title: Statistical Learning Seminars
layout: page
feature_image:
feature_text:
---

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

### June 18, [15:30 CET](https://www.thetimezoneconverter.com/?t=15%3A30%20pm&tz=Stockholm&)

#### Patrick Tardivel (University of Burgundy)

Title
: Geometry of Model Pattern Recovery by Penalized and Thresholded Estimators

Abstract
: LASSO, SLOPE, OSCAR, Fused LASSO, Clustered LASSO, generalized
  LASSO... are popular penalized estimators for which the penalty term is a
  polyhedral gauge. This presentation focuses on the model pattern recovery of
  $\beta$; namely recovering the subdifferential of a polyhedral gauge at
  $\beta$, where $\beta$ is an unknown parameter of regression coefficients. For
  LASSO, when the penalty term is the $\ell_1$ norm, the model pattern of $\beta$
  only depends on the sign of $\beta$ and sign recovery via LASSO estimator is
  actually a well known topic in the literature. Furthermore, this presentation
  shows that the notion of model pattern recovery is relevant for many examples
  of polyhedral gauge penalty. Specifically, we introduce the "path condition":
  a necessary condition for model pattern recovery, via a penalized least
  squares estimator, with a probability larger than $1/2$. One may relax this
  later condition using "thresholded" penalized least squares estimators; a
  new class of estimators generalizing thresholded LASSO. Indeed, we show that
  the "accessibility condition", a condition weaker than the "path
  condition", is asymptotically sufficient for model pattern recovery. It is
  well known that penalized estimators can be not uniquely defined and, actually,
  the theory of model pattern recovery is closely related to the important issue
  of uniqueness. In this presentation we also introduce a necessary and
  sufficient condition for the uniform uniqueness of penalized least squares
  estimators. 

Paper
: [The Geometry of Model Recovery by Penalized and Thresholded Estimators][1]


## Upcoming Talks

### June 18, [15:30 CET][tz]

#### Zhiqi Bu (University of Pennsylvania)

Title
: Characterizing the SLOPE Trade-off: A Variational Perspective and the 
Donoho--Tanner Limit

Abstract
: Sorted l1 regularization has been incorporated into many methods for solving
high-dimensional statistical estimation problems, including the SLOPE estimator
in linear regression. In this paper, we study how this relatively new
regularization technique improves variable selection by characterizing the
optimal SLOPE trade-off between the false discovery proportion (FDP) and true
positive proportion (TPP) or, equivalently, between measures of type I error and
power. Assuming a regime of linear sparsity and working under Gaussian random
designs, we obtain an upper bound on the optimal trade-off for SLOPE, showing
its capability of breaking the Donoho-Tanner power limit. To put it into
perspective, this limit is the highest possible power that the Lasso, which is
perhaps the most popular l1-based method, can achieve even with arbitrarily
strong effect sizes. Next, we derive a tight lower bound that delineates the
fundamental limit of sorted l1 regularization in optimally trading the FDP off
for the TPP. Finally, we show that on any problem instance, SLOPE with a certain
regularization sequence outperforms the Lasso, in the sense of having a
smaller FDP, larger TPP and smaller l2 estimation risk simultaneously. Our
proofs are based on a novel technique that reduces a variational calculus
problem to a class of infinite-dimensional convex optimization problems and a
very recent result from approximate message passing theory.
    
Paper
: [Characterizing the SLOPE Trade-off: A Variational 
   Perspective and the Donoho--Tanner Limit][2]

[1]: https://hal.archives-ouvertes.fr/hal-03262087
[2]: https://arxiv.org/abs/2105.13302
[tz]: https://www.thetimezoneconverter.com/?t=15%3A30%20pm&tz=Stockholm&

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

