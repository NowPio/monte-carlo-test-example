# monte-carlo-test-example
An example of the Monte Carlo test with the Kolmogorov Smirnov test

The Kolmogorv-Smirnov (KS) test, along with other goodness-of-fit tests, assumes that the parameters of a distribution are provided a priori. However, these parameters are often estimated in practice. When parameters are estimated, the calculated p-values from the KS test may be innacurate. To obtain correct p-values, we can conduct a Monte Carlo test. This involves drawing samples from an assumed distribution and obtaining the distribution of the KS statistic or p-value under parameter estimation. This work provides an example of using the Monte Carlo test to correct the KS test.

See the results below together with calculated error rates.

![MC_test_plot](https://github.com/user-attachments/assets/9e2281fc-fd08-4e22-ba93-5cb7864fee7f)
