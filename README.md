# PolynomialRegression

## Polynomial Curve Fitting Problem Statement

Polynomial curve fitting is an example of regression. Here you will apply the concepts of linear regression for
polynomial curve fitting. In regression, the objective is to learn a function that maps an input variablexto a
continuous target variabley.
For this part, you will be provided a personalised input file that contains data of the form (xi,yi) fori=
1 ,...,100. The relationship between x and y is of the form:

```
y=w0 +w1*x+···+wM*(x^M)+e
```
where the noise e is drawn from a Gaussian distribution with zero mean and unknown (but fixed, for a given
input file) variance.M is also unknown. The goal is to identify the underlying polynomial (both the degree and the coefficients), as well
as obtain an estimate of the noise variance.
Specifically, the following tasks are to be accomplished:

- To begin with, use only the first 20 data points in your file. Solve the polynomial curve fitting regression
    problem using error function minimisation. Define your own error function other than the sum-of-squares
    error. Try different error formulations and report the results.
- Use a goodness-of-fit measure for polynomials of different order. Can you distinguish overfitting, underfitting,
    and the best fit?
- Obtain an estimate for the noise variance.
- Introduce regularisation and observe the changes. For quadratic regularisation, can you obtain an estimate
    of the optimal value for the regularisation parameterλ? What is your corresponding best guess for the
    underlying polynomial? And the noise variance?
- Now repeat all of the above using the full data set of 100 data points. How are your results affected by
    adding more data? Comment on the differences.
- What is your final estimate of the underlying polynomial? Why?

In addition, present visualisations of the data and results in meaningful ways.
