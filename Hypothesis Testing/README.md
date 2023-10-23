## Hypothesis Testing Hands-On Practices

[hypo]: https://drive.google.com/file/d/1zmdWy9JxULHNLj6S00BpVHo0ttUIG5n0/view?usp=sharing

>[!NOTE]
**For a comprehensive analysis, please refer to the [Full Report][hypo] document.**

### 1. Introduction

In the research and data analysis, hypothesis testing serves as a fundamental tool to draw conclusion about the populations based on sample data. This structure approach ensures that interpretations and decisions are grounded in evidence, reducing the chances of random or biased conclusions. Hypothesis testing provides a framework for researchers to verify theories or assess business practices.

The underlying principle of hypothesis testing is to set an initial assumption (null hypothesis) and then determine whether the collected data provides enough evidence to challenge this assumption in favor of an alternative hypothesis.

This report aims not only to provide a comprehensive understanding of the fundamental concepts of hypothesis testing but also to offer a hands-on guide to implementing these tests using various tools by demonstrating the traditional formula-based approach, which provides a deep understanding of the computation involves. Showcasing step-by-step procedures in Excel and IBM SPSS, these software practices simplify the testing process, automate calculations, and allow for handling larger datasets. 

### 2. Definition of Hypothesis Testing

Hypothesis testing is a fundamental statistical method used to determine if there is enough evidence in a sample of data to infer that a particular condition is true for the entire population. It involves comparing two datasets or evaluating a sample from a dataset to draw conclusions about the entire population based on sample data or a limited set of data. 

#### 2.1 Types of Hypothesis Testing

2.1.1 Z-test: compare means to determine if there is a significant difference, specifically when the data meets certain criteria, primarily related to the sample size and known variance.

2.1.2 T-test: determine if there is a significant difference between the means of two groups. The test results of T-test are derived from a T-distribution, which is similar to a normal distribution but slightly more spread out, especially when sample sizes are small. 

  - One-sample T-test: Compare the mean of a single sample to a known population mean. It determines if the sample mean is significantly different from the known value.
  -	Two-sample independent T-test (or paired T-test): Compare the means of two independent samples.
  -	Paired T-test: Used when the samples are related in some way.
  -	Equal variance (or pooled) T-test: Assumes that the two samples might have the same variance.
  -	Unequal variance (or Welch’s) T-test: Used when the two samples might have different variances.

2.1.3 Chi-square test: compare the means of more than two groups.

  -	One-way ANOVA: Compare means across three or more independent groups.
  -	Two-way ANOVA: Compare means across groups considering two independent variables.

2.1.4 ANOVA: compare the means of more than two groups.

  -	One-way ANOVA: Compare means across three or more independent groups.
  -	Two-way ANOVA: Compare means across groups considering two independent variables.

2.1.5 F-test: compare the variance of two population.

### 3. The Process of Hypothesis Testing

#### 3.1 Define the problem

#### 3.2 Define the hypotheses

  - Null hypothesis (H0): A statement that there is no effect or difference. 
  - Alternative hypothesis (H1): Represents what need to prove or the presence if an effect.
    
#### 3.3 Choose the Level of Significance:

The probability of rejecting the null hypothesis when it is actually true. It normally selects 0.05.

#### 3.4 Select the appropriate statistical test: 

Based on the nature of the data and research question. Common tests include z-test, t-test, chi-square, f-test, and ANOVA.
	
#### 3.5 Collect and prepare data: 

Gather the necessary data for the test, ensuring it meets the assumption required for the chosen statistical test.
	
 #### 3.6 Calculate the test statistic: 
 
 Use the collected data to compute the test statistic.

#### 3.7 Determine the critical value or p-value: 
	
  - Compare the test statistic to a critical value (based on the significance level and the chosen test). If the test statistic is more than the critical value, reject the null hypothesis.
  - Alternatively, compute p-value based on the test statistic. If p-value is less than significance value, reject the null hypothesis.
	
#### 3.8 Draw a conclusion: 

Based on the previous step, conclude whether or not there is enough evidence to reject the null hypothesis based on the sample data.






