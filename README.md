# applied-statistics-assessment
Assessment for the module Applied Statistics

As per the README in the applied statistics Github account by Dr Ian McLoughlan the aim of the module is:

- Describe the stochastic nature of real-world measurements.
- Source documentation to programmatically perform a statistical test.
- Select an appropriate statistical test to investigate a claim.
- Perform a statistical test on a data set.

# Problem 1: Lady Tasting Tea.
The first problem in the notebook is based on the origional experiment by Ronald Fisher and reported in his book The Design of Experiments (1935). The original experiment containes 8 cups of tea. For this problem I expanded the problem to analyse 12 cups of tea. 8 with tea first and 4 milk first.

# Problem 2: Normal Distribution.
This problem in the notebook centred around flipping coins. I looked at first at one coin and the chance of heads or tails being returned when it was flipped. I then looked at the probability when two coins were flipped. The problem then required 100,000 samples of size 10 to be generated.  For each sample, compute the standard deviation with ddof=1 (sample SD) and with ddof=0 (population SD). Plot histograms of both sets of values on the same axes with transparency. In the analysis differences were identified and how we would expect those differences to change if the sample size increased.

# Problem 3: t-Tests,
William Sealy Gosset (13 June 1876 – 16 October 1937) was an English statistician, chemist and brewer who worked for Guinness. In statistics, he pioneered small sample experimental design known as the t-Test or students t-Test. in this problem I identified the differences between type I and type II errors. I drew two samples of size 100, one from the standard normal distribution and one from the normal distribution with mean d and standard deviation 1. t-Tests were run on these samples and analysis done.

# Problem 4: ANOVA.
ANOVA (Analysis of Variance) extends hypothesis testing beyond two groups to compare means across multiple groups simultaneously. Instead of conducting multiple t-tests (which increases Type I error risk), ANOVA tests whether at least one group mean differs significantly from the others. For this problem three independant samples of size 30 were generated. ANOVA tests were performed and during this notebook it was explined why ANOVA was perferable over several t_Tests.


# References used in the notebook
Markdown formatting:
https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax

Imports:
https://docs.python.org/3/library/math.html
https://docs.python.org/3/library/itertools.html
https://docs.python.org/3/library/random.html
https://numpy.org/doc/stable/user/absolute_beginners.html
https://matplotlib.org/stable/contents.html
https://docs.scipy.org/doc/scipy/reference/stats.html
https://www.statsmodels.org/stable/index.html
https://seaborn.pydata.org/
https://pandas.pydata.org/docs/user_guide/index.html#user-guide

Problem 1: Lady Tasting Tea.
https://cdn.pixabay.com/animation/2022/12/05/07/21/07-21-38-732_512.gif
https://en.wikipedia.org/wiki/Lady_tasting_tea
https://en.wikipedia.org/wiki/Combination
https://docs.python.org/3/library/math.html#math.comb
https://www.geeksforgeeks.org/python/python-itertools-combinations-function/
https://docs.python.org/3/library/random.html
https://docs.python.org/3/tutorial/datastructures.html#sets
https://en.wikipedia.org/wiki/Pascal%27s_triangle
https://www.britannica.com/science/statistics/Hypothesis-testing
https://owl.excelsior.edu/research/research-hypotheses/formulating-strong-hypotheses/
https://owl.excelsior.edu/research/research-hypotheses/types-of-research-hypotheses/#:~:text=Simple%20Hypothesis,more%20independent%20and%20dependent%20variables.
https://owl.excelsior.edu/research/research-hypotheses/types-of-research-hypotheses/#:~:text=Simple%20Hypothesis,more%20independent%20and%20dependent%20variables.
https://en.wikipedia.org/wiki/Type_I_and_type_II_errors
https://www.scribbr.com/statistics/statistical-power/#:~:text=Statistical%20power%2C%20or%20sensitivity%2C%20is,sample%20size%20for%20a%20study

Problem 2: Normal Distribution.
https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExYXg3NWoxbmlidzg3dnp6bGRpM2g2aDBlaDVpd3JxNHk4NWZtanV3MCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/a8TIlyVS7JixO/giphy.gif
https://en.wikipedia.org/wiki/Bessel%27s_correction
https://numpy.org/doc/2.1/reference/random/generated/numpy.random.binomial.html
https://www.datacamp.com/doc/numpy/sum
https://www.geeksforgeeks.org/pandas/bar-plot-in-matplotlib/
https://en.wikipedia.org/wiki/Probability_distribution
https://numpy.org/doc/stable/reference/generated/numpy.unique.html#main-content
https://en.wikipedia.org/wiki/Normal_distribution
https://en.wikipedia.org/wiki/Probability_density_function
https://numpy.org/doc/2.2/reference/generated/numpy.sqrt.html
https://numpy.org/doc/stable/reference/generated/numpy.ndarray.html
https://numpy.org/doc/2.2/reference/generated/numpy.sqrt.html
https://numpy.org/doc/stable/reference/generated/numpy.exp.html
https://numpy.org/doc/stable/reference/generated/numpy.pi.html
https://numpy.org/doc/2.1/reference/random/generated/numpy.random.normal.html
https://numpy.org/doc/2.2/reference/generated/numpy.histogram.html
https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.hist.html
https://en.wikipedia.org/wiki/Sampling_distribution
https://stats.libretexts.org/Bookshelves/Introductory_Statistics/Introductory_Statistics_(Shafer_and_Zhang)/06%3A_Sampling_Distributions/6.01%3A_The_Mean_and_Standard_Deviation_of_the_Sample_Mean
https://www.datacamp.com/tutorial/sample-standard-deviation
https://en.wikipedia.org/wiki/Shapiro%E2%80%93Wilk_test
https://www.spss-tutorials.com/spss-shapiro-wilk-test-for-normality/
https://docs.scipy.org/doc/scipy-1.16.2/tutorial/stats/hypothesis_shapiro.html

Problem 3: Type II error.
https://media1.tenor.com/m/Z8bTkI7qkVUAAAAC/guinness-real.gif" alt="Guinness GIF" style="display: block; margin: 0 auto; max-width: 100%;
https://en.wikipedia.org/wiki/Type_I_and_type_II_errors
https://en.wikipedia.org/wiki/William_Sealy_Gosset
https://en.wikipedia.org/wiki/Student%27s_t-test
https://numpy.org/devdocs/reference/random/generated/numpy.random.normal.html
https://matplotlib.org/stable/gallery/statistics/histogram_multihist.html#sphx-glr-gallery-statistics-histogram-multihist-py
https://seaborn.pydata.org/generated/seaborn.stripplot.html
https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.ttest_ind.html
https://seaborn.pydata.org/generated/seaborn.stripplot.html
https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.ttest_1samp.html
https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.ttest_rel.html
https://numpy.org/doc/stable/reference/random/generated/numpy.random.default_rng.html
https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.ttest_ind.html

Problem 4: ANOVA.
https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExOHRuZ2I4cGcxbHVib21od3E2bGJkb3M0enYzdWF6aWp1ZG8yY2ppbSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/JrGYQZWou5Z51vNRob/giphy.gif
https://en.wikipedia.org/wiki/Analysis_of_variance
https://en.wikipedia.org/wiki/F-test
https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.ttest_ind.html
https://docs.python.org/3/library/math.html
https://en.wikipedia.org/wiki/Type_I_and_type_II_errors
https://docs.python.org/3/library/itertools.html
https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.f_oneway.html
https://statistics.laerd.com/spss-tutorials/one-way-anova-using-spss-statistics.php
https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.tukey_hsd.html
https://en.wikipedia.org/wiki/Tukey%27s_range_test
https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.tukey_hsd.html
https://numpy.org/devdocs/reference/generated/numpy.concatenate.html
https://en.wikipedia.org/wiki/One-way_analysis_of_variance
https://numpy.org/devdocs/reference/generated/numpy.isnan.html
https://media.giphy.com/media/3o7btPCcdNniyf0ArS/giphy.gif