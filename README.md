# Data-Science-Interview-Questions

I have written some of the most frequesnt data science questions that are asked in the interviews and my answers to those questions. The questions have been divided into the follwing categories:

* Statistics
* Machine Learning
* SQL
* Python


## Statistics

### Hypothesis Testing ?
It is a practice of testing a null hypothesis against a null hypothesis. The null hypothesis is only rejected if its probability falls below a significance level, in which case the hypothesis being tested is said to have that level of significance

###  P-value?
When you perform a hypothesis test in statistics, a p-value can help you determine the strength of your results. 
Low p-value (≤ 0.05) indicates strength against the null hypothesis which means we can reject the null Hypothesis. High p-value (≥ 0.05) indicates strength for the null hypothesis which means we can accept the null Hypothesis p-value of 0.05 indicates the Hypothesis could go either way.

### Basic assumptions of Linear regression
1. Homoscedasticity: The variance of erros/residual is the same for any value of X. 
2. linear regression assumes that there is little or no multicollinearity in the data.
3. A linear relationship exists between the independent variable (X) and dependent variable (y).

### Confidence level ?
it is expressed as a percentage and represents how often the true % of the population lies within the confidence level. The 95% CI means you can be 95% certain.
Confidence interval is the range of values in which the true parameter is likely to fall. If confidence level is 95% then the confidence interval will contain values that are 95% certain.

### Type I and Type II error
Type I error aka False positive, is the rejection of a true null hypothesis while a Type II error aka False negative, is the non-rejection of a false null hypothesis 

### Chi- Square test
Compares two categorical variables to see if they are related. That is if there is any relationship between the variables.
Null hypothesis: Assumes that there is no relationship between the two variables

### Central Limit Theorem
The central limit theorem states that if you have a population and take sufficiently large random samples from the population with replacement , then the distribution of the sample means will be approximately normally distributed. 
While data collection we can never have data for the entire opulation, therefore we take random sample of the population that represents the entire population.

### Selection Bias
Selection bias is a kind of error that occurs when the researcher decides who is going to be studied. It is usually associated with research where the selection of participants isn’t random. It is sometimes referred to as the selection effect. It is the distortion of statistical analysis, resulting from the method of collecting samples. If the selection bias is not taken into account, then some conclusions of the study may not be accurate


### Linear Regression:
Linear regression attempts to model the relationship between two variables by fitting a linear equation to observed data. One variable is considered to be an explanatory variable, and the other is considered to be a dependent variable.

### Logistic Regression:
Logistic regression is a statistical model that in its basic form uses a logistic function to model a binary dependent variable. It uses sigmoid function to output the probabilities of a certain class.

## Machine Learning

### Regularization
Regularisation is the process of adding penalty to the cost function to reduce the complexity of the model. Regularization helps to prevent overfitting in the model.
The penalty is often the L1(lasso) and L2(ridge)  
