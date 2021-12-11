---
layout: page
title: 'Mini-Conference: Recent Advances on SLOPE'
---

<style>
    .schedule th:nth-child(1)  {white-space: nowrap;}
    .schedule td:nth-child(1)  {white-space: nowrap;}
    .schedule {padding-bottom: 2ex;}
    img {margin: 1.5ex; float: right; align: right; padding-top: 2.5ex;}
</style>

On **December 13, 08:00 to 12:00 CET**, we will be running a mini-conference on
recent advances in Sorted L-One Penalized Estimation (SLOPE), featuring speakers
from across the world.

We will use [zoom](https://zoom.us/) for the conference and the link for the
conference is <https://lu-se.zoom.us/j/65067339175>. Upon joining, you will be
placed in a waiting room; please wait for the host to let you in to the meeting.

## Schedule

<table class = "schedule">
  <thead>
    <tr>
      <th style="text-align: left">Start Time</th>
      <th style="text-align: left">Speaker</th>
      <th style="text-align: left">Title</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align: left"><a
      href="https://dateful.com/convert/stockholm-sweden?t=0800">08:00 CET</a></td>
      <td style="text-align: left">Kentaro Minami</td>
      <td style="text-align: left">
        Degrees of freedom in submodular regularization: A computational perspective of Stein’s unbiased risk estimate
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td style="text-align: left"><a
      href="https://dateful.com/convert/stockholm-sweden?t=0845">08:45 CET</a></td>
      <td style="text-align: left">Ziyan Luo</td>
      <td style="text-align: left">
        Solving the OSCAR and SLOPE Models Using a Semismooth Newton-Based Augmented Lagrangian Method
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td style="text-align: left"><a
      href="https://dateful.com/convert/stockholm-sweden?t=0945">09:45 CET</a></td>
      <td style="text-align: left">Małgorzata Bogdan</td>
      <td style="text-align: left">On the statistical properties of SLOPE and adaptive SLOPE</td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td style="text-align: left"><a
      href="https://dateful.com/convert/stockholm-sweden?t=1030">10:30 CET</a></td>
      <td style="text-align: left">Clément Elvira</td>
      <td style="text-align: left">
        Safe Rules for the Identification of Zeros in the Solutions of the SLOPE Problem
      </td>
    </tr>
  </tbody>
</table>

## Speakers

### Kentaro Minami

<img src="/slope-conference/minami.jpg" align="right" width="200px">

Kentaro Minami is a researcher at Preferred Networks Inc in Tokyo, Japan,
specializing in machine learning researching for estimation and prediction
problems.

#### Title

Degrees of freedom in submodular regularization: A computational perspective
of Stein’s unbiased risk estimate

#### Abstract

Degrees of freedom (DF) is a quantity that can be interpreted as the effective
number of model parameters. DF of some popular estimators are calculated by
surprizingly simple formulae: For example, DF of Lasso is the number of non-zero
coefficients, and DF of Fused Lasso is the number of distinct values in
coefficients. In this talk, I will introduce a unified degrees-of-freedom
formula for a class of convex regularization estimators, which we call
submodular regularization. Submodular regularization can represent various
structured sparsity related to combinatorial objects (e.g., directed/undirected
graphs, hypergraphs), and contains many existing penalized estimators, such as
Lasso, Fused Lasso, nearly-isotonic regression, and SLOPE. Our DF formula is
simple and easily implemented, and the formula does not depend on the underlying
combinatorial object.

#### Links

- [Related Article: Degrees of freedom in submodular regularization: A
  computational perspective of Stein’s unbiased risk
  estimate](https://doi.org/10.1016/j.jmva.2019.104546)
- [Personal Website](https://sites.google.com/site/ktrmnm1991/home)

### Ziyan Luo

Ziyan Luo is a professor at Beijing Jiaotong University, China.

#### Title

Solving the OSCAR and SLOPE Models Using a Semismooth Newton-Based Augmented
Lagrangian Method

#### Abstract

The octagonal shrinkage and clustering algorithm for regression (OSCAR),
equipped with the l1-norm and a pair-wise l1-norm regularizer, is a useful tool
for feature selection and grouping in high-dimensional data analysis. The
computational challenge posed by OSCAR, for high dimensional and/or large sample
size data, has not yet been well resolved due to the non-smoothness and
non-separability of the regularizer involved. In this talk, we will resolve this
numerical challenge by proposing a sparse semismooth Newton based augmented
Lagrangian method to solve the more general SLOPE (the sorted L-one penalized
estimation) model. By appropriately exploiting the inherent sparse and low-rank
property of the generalized Jacobian of the semismooth Newton system in the
augmented Lagrangian subproblem, we show how the computational complexity can be
substantially reduced. Our algorithm offers a notable computational advantage in
the high-dimensional statistical regression settings. Numerical experiments are
conducted on real data sets, and the results demonstrate that our algorithm is
far superior, in both speed and robustness, to the existing state-of-the-art
algorithms based on first-order iterative schemes, including the widely used
accelerated proximal gradient (APG) method and the alternating direction method
of multipliers (ADMM).

#### Links

- [Related Article: Solving the OSCAR and SLOPE Models Using a Semismooth
  Newton-Based Augmented Lagrangian Method](https://arxiv.org/abs/1803.10740)

### Małgorzata Bogdan

<img src="/slope-conference/bogdan.jpg" width="150px">

Małgorzata Bogdan is a professor at the Department of Mathematics at Wrocław
University, Poland and a guest professor at the Department of Statistics,
Lund University.

#### Title

On the statistical properties of SLOPE and adaptive SLOPE

#### Abstract

In this talk we will present some theoretical and empirical results on the
statistical properties of SLOPE and adaptive SLOPE, including the False
Discovery Control and averaging of the similar regression coefficients. If time
permits, we will also discuss the application of SLOPE in the context of
portfolio optimization.

#### Links

- [Personal Website](http://www.math.uni.wroc.pl/~mbogdan/)

### Clément Elvira

<img src="/slope-conference/elvira.jpg" width="125px">

Clément Elvira is a _Maître de Conférences_ at CentraleSupélec in Rennes,
France, working with the SSEE team of the IETR laboratory. His talk
represents join work with Cédric Herzet.

#### Title

Safe Rules for the Identification of Zeros in the Solutions of the SLOPE Problem

#### Abstract

In this talk we present a methodology to accelerate the resolution of the
so-called “Sorted L-One Penalized Estimation” (SLOPE) problem. Our method is
based on the concept of “safe screening” and aims at identifying the zeros in
the solution of SLOPE. More specifically, we introduce a new family of safe
screening rules and derive a polynomial-time procedure to verify if one of these
tests is passed. We illustrate on several numerical benchmarks that the proposed
method can lead to significant computational savings.

#### Links

- [Personal Website](https://c-elvira.github.io/)
- [Related Article: Safe Rules for the Identification of Zeros in the Solutions
  of the SLOPE Problem](https://arxiv.org/abs/2110.11784)

