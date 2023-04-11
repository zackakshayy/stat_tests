# stat_tests
This code will perform parametric and non parametric tests automatically


The ParametricTests class defines two methods for performing parametric tests: a two-sample t-test and a one-way analysis of variance (ANOVA). The NonParametricTests class defines two methods for performing non-parametric tests: a Wilcoxon signed-rank test and a Kruskal-Wallis test.

Each class takes in the control and test groups as arguments, and the methods perform the desired statistical significance test on the data. The methods return the p-value and whether or not the null hypothesis was rejected, using the specified alpha value (default 0.05).

To use these classes, you would first need to define your control and test groups as NumPy arrays, and then create instances of the ParametricTests and NonParametricTests classes, passing in the control and test groups as arguments. Here's an example usage:
