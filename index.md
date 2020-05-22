<script type="text/x-mathjax-config">
  MathJax.Hub.Config({
    tex2jax: {
      inlineMath: [ ['$','$'], ["\\(","\\)"] ],
      processEscapes: true
    }
  });
</script>
<script
  type="text/javascript"
  charset="utf-8"
  src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML"
>
</script>
<script
  type="text/javascript"
  charset="utf-8"
  src="https://vincenttam.github.io/javascripts/MathJaxLocal.js"
>
</script>

# One World

The effects of CoViD-19 pervades through research communities across the globe,
causing cancelled conferences, post-poned research visits, and suspended
projects. Like [many others](#other-one-world-seminars), we have sought 
other opportunities for collaboration in spite of the current state of
affairs and have therefore organized this online seminar 
series in statistical learning.

# Format

We are going to use [zoom](https://zoom.us/). The seminar will be 1 hour
long, with 45 minutes allocated to the presentation itself and 15 minutes to
discussions afterwards. 

Here are some ground rules for these seminars:

- Please use your real name as a handle.
- Please mute your microphone whenever you are not speaking.
- If you wish to ask a question, use the **raise hand** button in the
  **participants** window.

# Zoom link

<https://lu-se.zoom.us/j/65067339175>

# Program

The seminar is held on a weekly basis on **fridays** and will run
at least until June 12. Each seminar starts at
[16:30 CEST](https://www.thetimezoneconverter.com/?t=16%3A30%20pm&tz=Warsaw&).

[Link to calendar event](https://lu-se.zoom.us/meeting/u5Etce6rrTIrHdGmDxIUKT33_HsILcrt6Tui/ics?icsToken=98tyKu-trj0tGdecsR6CR_MMAo_oKOnztlhcgqd6kTv9KhV4VlClCcpRG558AsyG)

## Upcoming talk

### Friday, May 29, 16:30 CEST

- **Speaker**: Wojciech Rejchel
- **Title**: Fast and robust procedures in high-dimensional variable selection
- **Abstract**: We investigate the variable selection problem in the single 
   index model $Y=g(\beta'X,\epsilon)$, where $g$ is unknown function. Moreover,
   we make no assumptions on the distribution of errors, existence of their
   moments etc. We propose a computationally fast variable selection procedure,
   which is based on standard Lasso with response variables replaced by their
   ranks. If response variables are binary, our approach is  even simpler: we 
   just treat their class labels as they were numbers and apply standard Lasso. 
   We present theoretical and numerical results describing variable selection 
   properties of the methods.

### Friday, June 12, 16:30 CEST

- **Speaker**: Aaron Molstad
- **Title**: Insights and algorithms for the multivariate square-root lasso
- **Abstract**: We study the multivariate square-root lasso, a method for 
  fitting the multivariate response (i.e., multi-task) linear regression 
  model with dependent errors. This estimator minimizes the nuclear norm of the 
  residual matrix plus a convex penalty. Unlike some existing methods for 
  multivariate response linear regression, which require explicit estimates of
  the error co- variance matrix or its inverse, the multivariate square-root 
  lasso criterion implicitly adapts to dependent errors and is convex. To
  justify the use of this estimator, we establish an error bound which 
  illustrates that like the univariate square-root lasso, the multivariate
  square-root lasso is pivotal with respect to the unknown error covariance
  matrix. Based on our theory, we propose a simple tuning approach which 
  requires fitting the model for only a single value of the tuning parameter,
  e.g., does not require cross-validation. We propose two algorithms to compute
  the estimator: a prox-linear alternating direction method of multipliers 
  algorithm, and an accelerated first order algorithm which can be applied in
  certain cases. In both simulation studies and a genomic data application, we 
  show that the multivariate square-root lasso can outperform more 
  computationally intensive methods which estimate both the regression 
  coefficient matrix and error precision matrix.Aaron Molstad

## Previous talks

| Date   | Speaker           | Title                                                                        | Resources                                                                                                                       |
| :----- | :---------------- | :--------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------ |
| May 22 | Jaroslaw Harezlak | Brain Connectivity-Informed Adaptive Regularization for Generalized Outcomes | [presentation](https://vimeo.com/421641945)                                                                                     |
| May 22 | Jaroslaw Harezlak | Wearable Devices - Statistical Learning to the Rescue                        | [presentation](https://vimeo.com/421640615)                                                                                     |
| May 8  | Johan Larsson     | The strong screening rule for SLOPE                                          | [slides](slides\200508-johanlarsson.pdf), [presentation](https://vimeo.com/416633997), [paper](http://arxiv.org/abs/2005.03730) |
| May 8  | Patrick Tardivel  | Screening rules for the lasso                                                | [presentation](https://vimeo.com/416630058)                                                                                     |

# Recordings

Recordings of the talks on this seminar are hosted at
<https://vimeo.com/channels/statlearnseminar>.

# Organization

This seminar series is organized by 
[The Department of Mathematics, Wrocław University](https://www.math.uni.wroc.pl) and 
[The Department of Statistics, Lund University](https://stat.lu.se).

# Other Online Seminars

- [One World Probability Seminar](https://www.wim.uni-mannheim.de/doering/one-world/)
- [One World Optimization Seminar](https://owos.univie.ac.at/)
- [One World ABC (Approximate Bayesian Computation) Seminar](https://warwick.ac.uk/fac/sci/statistics/news/upcoming-seminars/abcworldseminar)
- [One World Mathematics of INformation, Data, and Signals (MINDS) Seminar](https://sites.google.com/view/minds-seminar/home)
- [One World Stochastic Numerics and Inverse Problems (SNIP) Seminar](https://www.icms.org.uk/V_SNIPS.php)
- [One World PDE Seminar](https://people.bath.ac.uk/mw2319/owpde/)
- [One World Mathematical Game Theory Seminar](https://gametheorynetwork.com/one-world-game-theory-seminar/)
- [One World Seminar: Mathematical Methods for Arbitrary Data Sources](http://www.nonlocal-methods.eu/oneworld/)
- [One World Cognitive Psychologie Seminar](https://www.sowi.uni-mannheim.de/en/erdfelder/research/one-world-cps/)
- [International Seminar on Selective Inference](https://www.selectiveinferenceseminar.com)
- [Online Causal Inference Seminar](https://sites.google.com/view/ocis/home)

