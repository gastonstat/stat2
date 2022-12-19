# STAT 2 - Introduction to Statistics

- __Description__: This course is designed primarily as a basic introductory course for statistical thinking. We'll start with descriptive statistics that allows us to summarize important features of data we've collected without requiring much in the way of mathematical theory or assumptions. Then we'll move on to probability and inference. Probability gives us a language for talking about how random variability arises in the data we collect. Inference uses the language of probability to help us determine what we can learn from our data despite the presence of that random variability.

- __Note__: This course is not very mathematical; the emphasis of the course is critical thinking about quantitative evidence. Neither linear algebra nor calculus is required, although some concepts seem more natural if you've taken these courses. You do need to be comfortable with math at the level of high-school algebra (e.g., the equation of a straight line, plotting points, taking powers and roots, percentages).

- __Instructor__: [Gaston Sanchez](https://www.gastonsanchez.com)

- __Lecture__: 3 hours of lecture per week

- __Lab__: 2 hours of laboratory per week

- __Assignments__: weekly HW assignments

- __Exams__: one midterm exam, and final test

- __Textbook__: Statistics, 4th edition by Freedman, Pisani, and Purves (FPP)

- __LMS__: the specific learning resources of a given semester are shared in the Learning Management Sysment (LMS) approved by Campus authorities (e.g. bCourses, Canvas)


-----


## 1.1 What is Data?

:card_index: __ABOUT__:

We begin by talking about "Data". For the scope of this course, we'll think of "Data" as a set of individuals and variables that give us information about those individuals. An individual can be an object or a person. A variable is an attribute, such as a measurement or a label.

<br>

:book: __READING__:

- FPP, chap 1: Introduction

<br>

:pencil2: __TOPICS__:

+ __Variables__
    - Understand the concept of "data" for statistical analysis
    - Explain what is a "variable"
    - Difference between qualitative and quantitative variables



## 1.2 Summarizing Data Graphically

:card_index: __ABOUT__:

One of the first steps in data analysis is to explore each variable in a data set (i.e. univariate analysis). A common tool used for such exploration is to create a graph of the distribution of the variable. One kind of graph is the so-called __histogram__ which is a visual display of the distribution of a quantitative variable. Histograms are particularly useful for large data sets. A histogram divides the variable values into equal-sized intervals. We can see the number of individuals in each interval.

<br>

:book: __READING__:

- FPP, chap 3: The Histogram

<br>

:pencil2: __TOPICS__:

+ __Graphing distributions__
	- 3+1 things to pay attention to: shape, center, spread, and outliers
	- The shape of a distribution (e.g. left-skewed, right-skewed, symmetric)
	- The center of a distribution is a typical value that represents the group.
	- The spread of a distribution is a description of how the data varies.
+ __About histograms__
	- What is a histogram?
    - Learn how to read and interpret a histogram
    - Learn how to graph a histogram
	- Descriptions of shape, center, and spread are affected by how the bins are defined.


-----


## 2.1 Measures of Center: Mean and Median

:card_index: __ABOUT__: 

Recall that when we describe the distribution of a quantitative variable, we describe the overall pattern (shape, center, and spread) in the data and deviations from the pattern (outliers). In this section, we expand our discussion about the notion of __center__. The idea is to determine, in a mathematical way, a typical value in the distribution, with the goal of using such a single value to represent the entire group.
<br>

:book: __READING__: 

- FPP, chap 4: The Average and the Standard Deviation

<br>

:pencil2: __TOPICS__:

+ __Mean__
	- What does it represent?
	- How to compute it?
	- When to use it?
+ __Median__
	- What does it represent?
	- How to compute it?
	- When to use it?


## 2.2 Measures of Spread

:card_index: __ABOUT__: 

In this section, we expand our discussion about the notion of __spread__. To be more precise, we'll focus on one kind of spread: __standard deviation__. This is a measure of variability when we use the mean as a measure of center.

<br>

:book: __READING__: 

- FPP, chap 4: The Average and the Standard Deviation

<br>

:pencil2: __TOPICS__:

+ __Standard Deviation__
	- How to measure spread around the mean.
	- What does standard deviation it represent?
	- Properties of standard deviation
	- How standard deviation is affected by outliers and skew in the data.


-----


## 3.1 Normal Approximation for Data

:card_index: __ABOUT__: 

In this section, we discuss how to use the Normal distribution which allows us to approximate the distribution of variables that have a fairly bell-shaped histogram.

<br>

:book: __READING__: 

- FPP, chap 5: The Normal Approximation for Data

<br>

:pencil2: __TOPICS__:

+ __Standard Deviation__
    - Getting to know the Normal Curve
    - Understanding the Standard Normal Curve
    - How to find areas under the normal curve
    - Normal approximation for symmetric distributions


## 3.2 Scatter Diagrams

:card_index: __ABOUT__: 

In this section, we describe how to use a scatterplot to display the relationship between two quantitative variables. We focus on the overall pattern (form, direction, and strength) and striking deviations from the pattern.

<br>

:book: __READING__: 

- FPP, chap 7: Plotting Points and Lines

<br>

:pencil2: __TOPICS__:

+ __Scatterplots__
    - Studying relationships between two variables
    - Scatter plots of two variables
    - Football-shaped "clouds"
    - Visualizing scatter diagrams
    - Understanding correlation
    - How to compute the correlation coefficient


-----


## 4.1 Correlation

:card_index: __ABOUT__: 

In this section, we discuss the notion of __correlation__ and the correlation coefficient which is a numerical measure that assesses the strength of a linear relationship.

<br>

:book: __READING__: 

- FPP, chap 8: Correlation
- FPP, chap 9: More about Correlation

<br>

:pencil2: __TOPICS__:

+ __Correlation__
    - How to compute correlation coefficient
    - How to interpret the value of a correlation coefficient
    - Properties of correlation
    - Ecological Correlations
    - Correlation and causation


## 4.2 Regression

:card_index: __ABOUT__: 

So far we have used a scatterplot to describe the relationship between two quantitative variables. We then focused on linear relationships and the use of correlation as a measure of the direction and strength of the linear relationship. Our focus on linear relationships continues here. We will 1) use lines to make predictions, and 2) develop a measurement for identifying the best line to summarize the data.

<br>

:book: __READING__: 

- FPP, chap 10: Regression

<br>

:pencil2: __TOPICS__:

+ __Linear Regression__
    - Understand the Graph of Averages
    - Understand the Regression line
    - Regression line as the line that smooths out the bumps of the graph of averages
    - Understand the regression effect


-----


## 5.1 Prediction Errors

:card_index: __ABOUT__: 

We need to look at how the predictions from a given line compare to observed data. This involves defining a residual to be the amount of error in a prediction. Next, we create residual plots. A residual plot with no pattern reassures us that our linear model is a good summary of the data.

<br>

:book: __READING__: 

- FPP, chap 11: The R.M.S. Error for Regression

<br>

:pencil2: __TOPICS__:

+ __Prediction Errors__
    - Understanding the concept of prediction errors (i.e. _residuals_)
    - Understanding the _Root Mean Squared Error_ of the regression line
    - Learn the formula of the r.m.s. error
    - Graphing the residuals with the _residual plot_
    - Understanding the concept of __homoscedastic__ (similar spread)
    - Understanding the concept of __heteroscedastic__ (different spread)


## 5.2 The Regression Line

:card_index: __ABOUT__: 

For a linear relationship, we use the least squares regression line to model the pattern in the data and to make predictions. This method gives us the line of "best fit".

<br>

:book: __READING__: 

- FPP, chap 12: The Regression Line

<br>

:pencil2: __TOPICS__:

+ __Regression Line__
    - Computing the slope and y-intercept of the regression line
    - Learn how to interepret the coefficients of a regression line
    - Tools to assess the fit of the regression line


-----


## 6.1 Probability Rules (part 1)

:card_index: __ABOUT__: 

Probability is a measure of how likely an event is to occur. When we say that an event is random or due to chance, we mean that the event is unpredictable in the short run but has a regular and predictable behavior in the long run.

<br>

:book: __READING__: 

- FPP, chap 13: What Are the Chances?
- FPP, chap 14: More about Chance


<br>

:pencil2: __TOPICS__:

+ __Probability Rules 1__
    - Concept of chance (under frequency theory)
    - Chances are between 0% and 100%
    - Complement rule: the chance of something equals 100% minus the chance of the opposite thing
    - Conditional probabilities


## 6.1 Probability Rules (part 2)

:card_index: __ABOUT__: 

We continue the discussion of probability rules.

<br>

:book: __READING__: 

- FPP, chap 13: What Are the Chances?
- FPP, chap 14: More about Chance


<br>

:pencil2: __TOPICS__:

+ __Probability Rules 2__
    - Multiplication rule
    - Independence (independent events)
    - Addition Rule


-----


## 7.1 Binomial Distribution

:card_index: __ABOUT__: 

In probability theory and statistics, the binomial distribution with parameters _n_ and _p_ is the discrete probability distribution of the number of successes in a sequence of _n_ independent trials. The binomial distribution is frequently used to model the number of successes in a sample of size _n_ drawn with replacement from a population of size _N_. 

<br>

:book: __READING__: 

- FPP, chap 15: The Binomial Formula

<br>

:pencil2: __TOPICS__:

+ __Binomal Probability__
    - Binomial coefficients
    - Binomial Formula
    - Calculate the chance that an even t will occur exactly _k_ times out of _n_


## 7.2 The Law of Averages

:card_index: __ABOUT__: 

In this section, the idea is to talk about chance processes; simply put, this can be approached by considering a list of numbers each of which is associated with a given probability. Interestingly, we can use a so-called _box model_ to represent a population, as well as to study sampling procedures.

<br>

:book: __READING__: 

- FPP, chap 16: The Law of Averages

<br>

:pencil2: __TOPICS__:

+ __Chance Error__
	- Chance error is likely to be large in absolute terms
	- Chance error will tend to be small relative to the number of draws
+ __Law of Averages__
+ __Making a box model__
	- Which numbers go into the box?
	- How many of each kind?
	- How many draws?


-----


## 8.1 Expected Value and Standard Error

:card_index: __ABOUT__: 

We now focus on the mean and standard deviation of a discrete random variable. We discuss how to calculate these measures of center and spread for this type of probability distribution, but in practice we will use software to do these calculations.

<br>

:book: __READING__: 

- FPP, chap 17: The Expected Value and Standard Error

<br>

:pencil2: __TOPICS__:

+ __Probability Rules 1__
    - Understand the concept of Expected Value
    - Understand the concept of Chance Error
    - Understand the concept of Standard Error
    - Drawing at random with replacement from a box of numbered tickets
    - Formula of Expected Value
    - Formula of Standard Error


## 8.2 Probability Histograms

:card_index: __ABOUT__: 

When a chance process generates a number, the expected value and standar error are a guide to where the number will be. But the probability histogram gives a complete picture. This visual display is not supposed to represent data, instead it represents chance. 

<br>

:book: __READING__: 

- FPP, chap 18: The Normal Approximation for Probability Histograms

<br>

:pencil2: __TOPICS__:

+ __Probability Histograms__
    - Understanding the concept of Probability Histogram
    - Probability histogram for the sum of draws at random with replacement from a box
    - Use the normal approximation for probability histograms
    - Probability histograms for sums converge to the normal curve
    - How to use the continuity correction


-----


## 9.1 Population and Samples

:card_index: __ABOUT__: 

We now focus on the mean and standard deviation of a discrete random variable. We discuss how to calculate these measures of center and spread for this type of probability distribution, but in practice we will use software to do these calculations.

<br>

:book: __READING__: 

- FPP, chap 19: Sample Surveys

<br>

:pencil2: __TOPICS__:

+ __Sampling__
    - Population and samples
    - A _parameter_ is a numerical description about a population.
    - A _statistic_ is a numerical description about a sample
    - Discussion of methods for choosing samples.
    - Understanding Bias selection.
    - Understanding non-response bias.


## 9.2 Sampling Distributions

:card_index: __ABOUT__: 

We know that a parameter is a number that describes a population. In turn, a statistic is a number that describes a sample. Obviously, random samples vary, so we need to understand how much they vary and how they relate to the population. Our ultimate goal is to create a probability model that describes the long-run behavior of sample measurements. We use this model to make inferences about the population.

<br>

:book: __READING__: 

- FPP, chap 20: Chance Errors in Sampling

<br>

:pencil2: __TOPICS__:

+ __Sampling Distributions__
    - Develop a probability model of how sample statistics behave
    - Describing the long-run behavior of statistics from random samples
    - Usually a parameter cannot be determined exactly, but can only be __estimated__ by a statistic
    - When estimating a parameter, one major issue is accuracy: how close is the estimate close to be?


-----


## 10.1 Estimating a Population Proportion

:card_index: __ABOUT__: 

When our goal is to estimate a population proportion, we select a random sample from the population and use the sample proportion as an estimate. Of course, random samples vary, so we want to include a statement about the amount of error that may be present. Because sample proportions vary in a predictable way, we can also make a probability statement about how confident we are in the process we used to estimate the population proportion.

<br>

:book: __READING__: 

- FPP, chap 21: The Accuracy of Percentages

<br>

:pencil2: __TOPICS__:

+ __Estimating Proportions__
    - Describe the sampling distribution for sample proportions
    - Sample statistics vary, so there is always error in our estimate
    - We use the standard error, which is the average error in our sample estimates, to create a margin of error
    - In turn, we use a margin of error to build a confidence interval to estimate a population proportion


-----


## 11.1 Estimating a Population Mean

:card_index: __ABOUT__: 

We now focus on how to use a sample mean to estimate a population mean.

<br>

:book: __READING__: 

- FPP, chap 23: The Accuracy of Averages

<br>

:pencil2: __TOPICS__:

+ __Estimating Means__
    - Construct a confidence interval to estimate a population mean
    - Interpret the confidence interval in context.
    - Interpret the meaning of a confidence level associated with a confidence interval.
    - Adjust the margin of error by making changes to the confidence level or sample size.


-----


## 12.1 Hypothesis Tests

:card_index: __ABOUT__: 

In inference, we use a sample to draw a conclusion about a population. Two types of inference are the focus of our work in this course: 1) Estimate a population parameter with a confidence interval; 2) Test a claim about a population parameter with a hypothesis test.

Now we look at how to test a claim with a hypothesis test. Statistical investigations begin with research questions. We begin our discussion of hypothesis tests with research questions that require us to test a claim. Later we look at how a claim becomes a hypothesis.

<br>

:book: __READING__: 

- FPP, chap 26: Test of Significance

<br>

:pencil2: __TOPICS__:

+ __Hypothesis Testing__
    - Cooking recipe for hypothesis testing
    - Step 1: Determine the hypotheses
    - Step 2: Collect the data
    - Step 3: Assess the evidence
    - Step 4: Give the conclusion


## 12.2 Hypothesis Test for a Population Proportion

:card_index: __ABOUT__: 

In this section we discuss how to conduct a hypothesis test for a population proportion. 

<br>

:book: __READING__: 

- FPP, chap 26: Test of Significance

<br>

:pencil2: __TOPICS__:

+ __Hypothesis Testing__
    - Recognize when a situation calls for testing a hypothesis about a population proportion.
    - How to interpret the P-value
    - Distinguish statistical significance from practical importance


-----


## 13.1 Hypothesis Test for a Population Mean

:card_index: __ABOUT__: 

In this section we learn to use a sample mean to test a hypothesis about a population mean.

<br>

:book: __READING__: 

- FPP, chap 26: Test of Significance
- FPP, chap 27: More Test for Averages

<br>

:pencil2: __TOPICS__:

+ __Hypothesis Testing__
    - Recognize when a situation calls for testing a hypothesis about a population mean.
    - Identify the type of test statistic
    - How to interpret the P-value
    - Distinguish statistical significance from practical importance


## 13.2 Tests for Comparing Two Samples

:card_index: __ABOUT__: 

In this section we learn how to conduct tests for comparing two samples (i.e. compare two sample averages).

<br>

:book: __READING__: 

- FPP, chap 27: More Test for Averages

<br>

:pencil2: __TOPICS__:

+ __Hypothesis Testing__
    - Formula of the standard error for the difference of two independent quantities.
    - Difference between averages of two samples are tested with a _two-sample z-test_.
    - The two-sample z-test can handle situations which involve classifying and counting.


-----


## 14.1 Chi-Square Test

:card_index: __ABOUT__: 

In this module, we focus on inference with categorical variables. We learn three new hypothesis tests, two of which are an extension of hypothesis tests about proportions.

<br>

:book: __READING__: 

- FPP, chap 28: The Chi-Square Test

<br>

:pencil2: __TOPICS__:

+ __Hypothesis Testing__
    - Test a claim about the distribution of a categorical variable in a population.
    - Test a claim about the relationship between two categorical variables in a population.


