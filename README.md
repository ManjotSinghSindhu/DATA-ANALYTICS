# DATA-ANALYTICS

Data analytics (DA) is the process of examining data sets in order to find trends and draw conclusions about the information they contain. Increasingly data analytics is used with the aid of specialized systems and software. Data analytics technologies and techniques are widely used in commercial industries to enable organizations to make more-informed business decisions. It is also used scientists and researchers to verify or disprove scientific models, theories and hypotheses.

Data analytics initiatives can help businesses increase revenues, improve operational efficiency, optimize marketing campaigns and customer service efforts. It can also be used to respond quickly to emerging market trends and gain a competitive edge over rivals. The ultimate goal of data analytics, however, is boosting business performance. Depending on the particular application, the data that's analyzed can consist of either historical records or new information that have been processed for real-time analytics. In addition, it can come from a mix of internal systems and external data sources.

************************************************************************************************************************************************************

DA-1(GENERAL FUNCTIONS)(CSV FILE USED: sales.csv)
The File Contains the Introduction to Data Analytics and Basic Fumctions Used While Analysing the Data. Some General Functions are:
1. Head : The head () method in python contains only one parameter, which is n. It is an optional parameter. By setting it, we fix the number of rows we want from the DataFrame. The head () function returns n rows from the DataFrame. 

2. Shape : shape() is use in pandas to give number of row/column.

3. Columns : columns is used to display the Columns in the data.

4. dtypes : dtypes is used to Print Data Type of the Columns in the Data.

5. info : info() function is used to get a concise summary of the dataframe. It comes really handy when doing exploratory analysis of the data.

6. iLoc : iloc is used to extract an element based upon the position.

************************************************************************************************************************************************************

DA-2(CENTRAL TENDENCY AND DISPERSION)(CSV FILE USED: sales.csv)
This File Contains the Central Tendency and Dispersion Functions such as:
1. Mean : For a data set, the arithmetic mean, also called the expected value or average, is the central value of a discrete set of numbers: specifically, the sum of the values divided by the number of values. 

2. Median : The median is well-defined for any ordered (one-dimensional) data, and is independent of any distance metric. The median can thus be applied to classes which are ranked but not numerical (e.g. working out a median grade when students are graded from A to F), although the result might be halfway between classes if there is an even number of cases.

3. Mode : Mode is the value which occurs most frequently in a set of observations. For example, {6, 3, 9, 6, 6, 5, 9, 3} the Mode is 6, as it occurs most often.

4. Percentile : A percentile (or a centile) is a measure used in statistics indicating the value below which a given percentage of observations in a group of observations falls.

5. Quartile : A quartile is a type of quantile which divides the number of data points into four more or less equal parts, or quarters. The first quartile (Q1) is defined as the middle number between the smallest number and the median of the data set.

6. Inter Quartile Range : Interquartile range (IQR), also called the midspread, middle 50%, or H‑spread, is a measure of statistical dispersion, being equal to the difference between 75th and 25th percentiles, or between upper and lower quartiles, IQR = Q3 − Q1.

7. Variance : Variance (σ 2) in statistics is a measurement of the spread between numbers in a data set.

8. Standard Deviation : Standard Deviation is a measure which shows how much variation (such as spread, dispersion, spread,) from the mean exists. The standard deviation indicates a “typical” deviation from the mean.

9. Population Standard Deviation : The population standard deviation is the square root of the variance.

10. Skewness : Skewness refers to distortion or asymmetry in a symmetrical bell curve, or normal distribution, in a set of data. If the curve is shifted to the left or to the right, it is said to be skewed.

11. Box Plot : A Box plot or boxplot is a method for graphically depicting groups of numerical data through their quartiles. Box plots may also have lines extending from the boxes indicating variability outside the upper and lower quartiles, hence the terms box-and-whisker plot and box-and-whisker diagram. Outliers may be plotted as individual points.

************************************************************************************************************************************************************

DA-3(DISTRIBUTION)

This File Contains the Most Commonly used Distribution Functions such as:
1. Binomial Distribution : Binomial distribution with parameters n and p is the discrete probability distribution of the number of successes in a sequence of n independent experiments, each asking a yes–no question, and each with its own boolean -valued outcome: success / yes / true / one (with probability p) or failure / no / false / zero (with probability q = 1 − p).
Binomial Distribution Formula
The binomial distribution formula is for any random variable X, given by;
P(x:n,p) = nCx px (1-p)n-x
Or
P(x:n,p) = nCx px (q)n-x
Where,
n = the number of experiments,
x = 0, 1, 2, 3, 4, …,
p = Probability of Success in a single experiment,
q = Probability of Failure in a single experiment = 1 – p,
The binomial distribution formula can also be written in the form of n-Bernoulli trials, where nCx = n!/x!(n-x)!. Hence,
P(x:n,p) = n!/[x!(n-x)!].px.(q)n-x

2. Poisson Distribution:
A Poisson distribution is a probability distribution which results from the Poisson experiment. A Poisson experiment is a statistical experiment that classifies the experiment into two categories, such as success or failure. Poisson distribution is a limiting process of the binomial distribution. A Poisson random variable “x” defines the number of successes in the experiment. This distribution occurs when there are events that do not occur as the outcomes of a definite number of outcomes. Poisson distribution is used under certain conditions. They are:
Number of trials “n” tends to infinity
Probability of success “p” tends to zero
np = 1 is finite
Poisson Distribution Formula
The formula for the Poisson distribution function is given by:
f(x) =(e– λ λx)/x!
Where,
e is the base of the logarithm,
x is a Poisson random variable,
λ is an average rate of value.

3. Uniform Distribution : A continuous probability distribution is a Uniform distribution and is related to the events which are equally likely to occur. It is defined by two parameters, x and y, where x = minimum value and y = maximum value. It is generally denoted by u(x, y).

4. Normal Distribution : A normal distribution is an arrangement of a data set in which most values cluster in the middle of the range and the rest taper off symmetrically toward either extreme.

5. Cumulative Distribution Function : The Cumulative Distribution Function (CDF), of a real-valued random variable X, evaluated at x, is the probability function that X will take a value less than or equal to x. It is used to describe the probability distribution of random variables in a table. And with the help of these data, we can create a CDF plot in excel sheet easily.

6. Hypergeometric Distribution : The hypergeometric distribution is a discrete probability distribution that describes the probability of successes (random draws for which the object drawn has a specified feature) in draws, without replacement, from a finite population of size that contains exactly objects with that feature, wherein each draw is either a success or a failure.

7. Exponential Distribution : The exponential distribution graph is a graph of the probability density function which shows the distribution of distance or time taken between events. The two terms used in the exponential distribution graph is lambda (λ)and x. Here, lambda represents the events per unit time and x represents the time.

************************************************************************************************************************************************************

DA-4(HYPOTHESIS TESTING)

WHAT IS HYPOTHESIS?
A hypothesis is a proposition that attempts to explain a set of facts in a unified way. It generally forms the basis of experiments designed to establish its plausibility. Simplicity, elegance, and consistency with previously established hypotheses or laws are also major factors in determining the acceptance of a hypothesis.


WHAT IS HYPOTHESIS TESTING?
Hypothesis testing is a form of statistical inference that uses data from a sample to draw conclusions about a population parameter or a population probability distribution.

P VALUE APPROACH : 
In statistics, the p-value is the probability of obtaining results at least as extreme as the observed results of a statistical hypothesis test, assuming that the null hypothesis is correct. The p-value is used as an alternative to rejection points to provide the smallest level of significance at which the null hypothesis would be rejected. A smaller p-value means that there is stronger evidence in favor of the alternative hypothesis.

t TEST : 
A t-test is a type of inferential statistic used to determine if there is a significant difference between the means of two groups, which may be related in certain features. It is mostly used when the data sets, like the data set recorded as the outcome from flipping a coin 100 times, would follow a normal distribution and may have unknown variances. A t-test is used as a hypothesis testing tool, which allows testing of an assumption applicable to a population. A t-test looks at the t-statistic, the t-distribution values, and the degrees of freedom to determine the statistical significance. To conduct a test with three or more means, one must use an analysis of variance.

************************************************************************************************************************************************************

DA-5(ANOVA)

What is Analysis of Variance (ANOVA)?
Analysis of variance (ANOVA) is an analysis tool used in statistics that splits an observed aggregate variability found inside a data set into two parts: systematic factors and random factors. The systematic factors have a statistical influence on the given data set, while the random factors do not. Analysts use the ANOVA test to determine the influence that independent variables have on the dependent variable in a regression study.

The Formula for ANOVA is:
F= MSE/MST
where:
F=ANOVA coefficient,
MST=Mean sum of squares due to treatment,
MSE=Mean sum of squares due to error


************************************************************************************************************************************************************

