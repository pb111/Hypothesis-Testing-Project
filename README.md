# Hypothesis Testing Project

**Hypothesis testing** is a statistical tool to test an assumption regarding the population parameter. This project is dedicated towards `hypothesis testing`. In this project, I have discussed `hypothesis testing`, `p-value`, `significance level`, `types of errors in hypothesis testing`, `one-tailed test` and `two-tailed test`. 

===============================================================================

## Table of contents

1.	Introduction to hypothesis testing
2.	Null and alternate hypothesis
3.	p value
4.	Significance level
5.	Confidence interval
6.	Type I and Type II errors
7.	One-tailed and two-tailed test
8.	Decision criteria
9.  Applications of hypothesis testing
10.	References

===============================================================================

## 1. Introduction to hypothesis testing

-	**Hypothesis** is basically an assumption that we make about the population parameter. 
-	**Hypothesis testing** is a statistical tool whereby we can test the above assumption regarding the population parameter.
-	This technique was first introduced by Ronald Fisher, Jerzy Neyman, Karl Pearson and his son Egon Pearson.
-	The methodology employed in statistical testing depends on the nature of dataset used and the reason for the analysis. 
-	So, hypothesis testing is used to infer the result of a hypothesis performed on sample data from a larger population.


### Steps to perform hypothesis testing

There are various steps in performing hypothesis testing. These are as follows:-

**1. Choose a sample statistic**

-	The first step in hypothesis testing is to choose a sample test statistic.
-	Hypothesis testing allow us to check the sample statistic against a population statistic or statistic of another sample.

**2. Define hypothesis (NULL and Alternate)**

-	The next step is to define hypothesis to be tested. 
-	Hypothesis is defined in two ways - **Null hypothesis** and **Alternate hypothesis**.

**3. Set the decision criteria**

-	The third step is to set the decision criteria to be used in hypothesis testing. 
-	To set the decision criteria, we state the pre-determined significance level for a test.

**4. Evaluate and interpret the result**

-	Every test produces the significance value for that particular test.
-	Based on the significance level, we make a decision to reject or not reject the null hypothesis (Ho).
-	If the significance value is less than the predetermined significance value, then we should reject the null hypothesis. 
-	If the significance value is greater than the predetermined significance value, then we should not reject the null hypothesis. 


- The diagram below demonstrates how hypothesis testing works.

![Hypothesis testing mechanism](https://github.com/pb111/Hypothesis-Testing-Project/blob/master/Images/Hypothesis%20testing%20works.jpg)

===============================================================================


## 2. Null and alternate hypothesis

-	While carry out hypothesis testing, we define hypothesis.
-	A hypothesis is an assumption about the population parameter. 
-	We define two types of hypothesis – **Null hypothesis** and **Alternate hypothesis**.

### Null Hypothesis (Ho)

-	Null hypothesis is a statistical hypothesis which assumes that the difference in observations is due to a random factor. 
-	It is denoted by **Ho**. 
-	Suppose the null hypothesis is **HO : µ1 = µ2**. 
-	It says that there is no difference between the two population means.

### Alternate Hypothesis (H1)

-	Alternate hypothesis is the opposite of null hypothesis. 
-	It is denoted by H1. 
-	The alternate hypothesis assumes that difference in observations are the result of a real effect.

===============================================================================

## 3. p-value

-	The p-value is the probability value within a hypothesis test representing the probability of the occurrence of a given event.
-	The p-value is the probability that a given result would occur under the null hypothesis. 
-	It is the probability of finding the observed results when the null hypothesis (H0) is true.
-	The p-value does not provide the probability that either hypothesis is correct.
-	A p value is used to help you support or reject the null hypothesis. 
-	The p value is the evidence against a null hypothesis. 
-	The smaller the p-value, the stronger the evidence that you should reject the null hypothesis.
-	In a hypothesis test, we compare the p value from the test to the alpha level.
-	p-values are calculated using p-value tables.

===============================================================================

## 4. Significance level

-	Significance level is the probability of rejecting the null hypothesis (Ho), when it is true.
-	It is denoted by alpha or α.
-	The most practical value of significance level (α), accepted across all business cases is 5%. Other values of significance level could be 1% or 0.5%.
-	This 5% is called **Significance level** also known as alpha level (symbolized as α). 
-	It means that if random chance probability is less than 5% then we can conclude that there is difference in behaviour of two different population means.

===============================================================================

## 5. Confidence interval

-	Confidence intervals were introduced in statistics by Jerzy Neyman in a paper published in 1937.
-	A confidence interval is a range of values within which our true value may lie. 
-	It is a type of interval estimate, computed from the observed statistics of the distribution. 
-	This interval estimate gives us a range of values in which the population statistic may lie.
-	So, confidence intervals consist of a range of potential values of the unknown population parameter.
-	The confidence interval has an associated confidence level that quantifies the level of confidence that the parameter lies in the interval.
-	The confidence level is designated prior to examining the data. Most commonly the 95% confidence level is used. However, other confidence levels like 90% and 99% can also be used.
-	There are various factors which affect the width of the confidence interval. They include the size of the sample, the confidence level and the variability in the sample.
-	A larger sample will tend to produce a better estimate of the population parameter, when all other factors being equal.
-	A higher confidence level will tend to produce a higher confidence interval.

===============================================================================

## 6. Type I and Type II errors

-	Two types of errors occur when we conduct hypothesis testing.
-	These are Type I error and Type II error.

### Type I error

-	A **Type I error** is a statistical term that describes the error that occurs when we reject the null hypothesis that is actually true. 
-	So, we reject the null hypothesis (Ho), when it is true.
-	Then this type of error is called **Type I error**.
-	It is denoted by α.


### Type II error

-	A **Type II error** is a statistical term used within the context of hypothesis testing that describes the error that occurs when one fails to reject a null hypothesis that is actually false. 
-	So, we accept the null hypothesis (Ho), when it is false.
-	Then this type of error is called **Type II error**.
-	It is denoted by β.
-	This type of error produces a false positive. 


- The below diagram demonstrates Type I and Type II errors.

![Type I and Type II error](https://github.com/pb111/Hypothesis-Testing-Project/blob/master/Images/Type%20I%20and%20II%20errors.png)

===============================================================================

## 7. One-tailed and two-tailed test

-	We can break down the hypothesis test into one-tailed and two-tailed test.

### One-tailed test

-	When the given statistical hypothesis tests only one value like Ho: µ1 = µ2, it is called the **one-tailed test**.
-	A one-tailed test is a statistical test in which the critical area of a distribution is one-sided so that it is either greater than or less than a certain value, but not both. 
-	If the sample being tested falls into the one-sided critical area, the alternate hypothesis will be accepted instead of the null hypothesis.
-	One-tailed test is also known as a directional hypothesis or directional test.


### Two-tailed test

-	When the given hypothesis assumes a less than or greater than value, it is called the **two-tailed test**.
-	In statistics, a two-tailed test is a method in which the critical area of a distribution is two-sided and tests whether a sample is greater than or less than a certain range of values.
-	It is used in null-hypothesis testing and testing for statistical significance.
-	If the sample being tested falls into either of the critical areas, the alternative hypothesis is accepted instead of the null hypothesis.
-	By convention two-tailed tests are used to determine significance at the 5% level, meaning each side of the distribution is cut at 2.5%.


- The diagram below shows the difference between one-tailed and two-tailed test.

![One-tailed and two-tailed test](https://github.com/pb111/Hypothesis-Testing-Project/blob/master/Images/One-tailed%20and%20two-tailed%20test.jpg)


===============================================================================

## 8. Decision criteria

We have carried out a hypothesis test. Now, it is time for decision-making. The decision-making means to decide whether to reject or do not reject the null hypothesis (Ho). There are two ways to decide whether we should reject or do not reject the null hypothesis (Ho). These ways are discussed below:-


### Decision criteria – first method

-	Decide which test is appropriate and calculate the test statistic.
-	Derive the distribution of the test statistic under the null hypothesis from the assumptions.
-	Select a significance level (α), a probability threshold below which the null hypothesis will be rejected. 
- Common values are 5% and 1%.
-	Compute from the observations the observed value tobs of the test statistic.
-	The decision rule is to reject the null hypothesis H0 if the observed value tobs is in the critical region or fail to reject the hypothesis otherwise.
-	If tobs > tcritical  => Reject Ho  and accept H1
-	If tobs < tcritical  => Accept Ho  


This is clearly explained with the following diagram-


# ! [Ho rejection condition](https://github.com/pb111/Hypothesis-Testing-Project/blob/master/Images/Reject%20Ho%20condition.png)


### Decision criteria – second method

An alternative decision process which is commonly used is as follows:-

-	Compute from the observations the observed value tobs of the test statistic. 
-	Calculate the p-value. This is the probability, under the null hypothesis, of sampling a test statistic at least as extreme as that which was observed. 
-	Reject the null hypothesis (Ho), in favour of the alternative hypothesis, if and only if the p-value is less than the significance level (the selected probability) threshold.
-	p-value < significance-level (α) => Reject Ho and accept H1.
-	p-value > significance-level (α) => Accept Ho


### Important points about decision criteria

-	We will never say that we accept the null hypothesis (Ho).
-	Instead, we should say that we do not have sufficient evidence to reject the null hypothesis (Ho). 
-	So, our null hypothesis (Ho) is true, or
-	We should say that we have sufficient evidence to reject the null hypothesis (Ho). 
-	So, our null hypothesis (Ho) is false and alternate hypothesis is true (H1).

===============================================================================

## 9. Applications of hypothesis testing

The real world applications of hypothesis testing are listed below:-

1.	Testing whether more men than women suffer from diabetes or other disease.

2.	Establishing authorship of documents.

3.	Deciding whether hospital carpeting results in more infections.

4.	Selecting the best means to stop smoking.

5.	Testing the claims of handwriting analysts.


===============================================================================

## 10. References

The work done in this project is inspired from the following books and websites:-

1.	Think Stats – Exploratory Data Analysis in Python by Allen B. Downey 

2.	Udemy course – Statistics for Data Science and Business Analysis

3.	https://www.analyticsvidhya.com/blog/2015/09/hypothesis-testing-explained/

4.	https://en.wikipedia.org/wiki/Statistical_hypothesis_testing

5.	https://www.statisticssolutions.com/hypothesis-testing/

6.	https://www.statisticshowto.datasciencecentral.com/probability-and-statistics/hypothesis-testing/





