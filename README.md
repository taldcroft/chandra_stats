Statistics and fitting for the real world
==========================================

Goal:

  Use practical Chandra operations examples to illustrate the use and
  limitations of classical gaussian statistics, probability distributions,
  and linear and nonlinear fitting.  Introduce the idea of simulating from
  probability distributions to make robust predictions.  Keep it all simple and
  minimize distracting lingo (e.g. histogram vs. probability
distribution function).

  Illustrate all content interactively and graphically in Python.

Topics:

* Refresher on classical statistics
  * Standard deviation and 1-sigma error bars
  * Estimating likelihood of an event given errors

* Real world: non-gaussian errors
  * Visualizing distributions: histograms
  * Comparing to gaussian distribution
  * Using percentiles to estimate event likeliood

* Fitting data
  * Linear data fitting
    - Matrix inversion
    - Outliers: sigma-clipping, Theil-Sen estimator
  * Nonlinear data fitting
    - Fit methods (Simplex, Levenberg-Marquardt, etc)
    - Fit statistic chi**2 (least squares), likelihood (Cash)
  * Understanding the errors on the fitted parameters

* Using model fits to make predictions
  * The problem of correlated errors
  * The solution of using simulations
  * Example: predicting when some MSID could exceed a limit

* Maximum likelihood estimation and fitting
  * Why do we need this, why not just chi**2
  * Example: Fitting ACA acquisition statistics

