# <span style="color:blue">Hypothesis Testing</span>

Hypothesis testing is a statistical method used to make decisions about the population based on sample data. It involves the following steps:

## <span style="color:green">Files</span>

- **Data/house_price_increase.csv**: Contains the data of house price increases with columns `house_id` and `price_increase_pct`.
- **Hypothesis_Testing.ipynb**: Jupyter notebook that contains the code and explanations for hypothesis testing.
- **README.md**: This file, providing an overview of the project.

## <span style="color:green">Hypothesis Testing</span>

Hypothesis testing is a statistical method used to make decisions about the population based on sample data. It involves the following steps:

1. **Define the Null Hypothesis (H0)**: The baseline claim that there is no effect or no difference.
2. **Define the Alternative Hypothesis (H1)**: The claim that we are testing, which is contrary to the null hypothesis.
3. **Select a Significance Level (α)**: Commonly used significance levels are 0.05, 0.01, and 0.10.
4. **Choose the Appropriate Test**: Depending on the data and hypothesis, choose between Z-test, T-test, Chi-Square test, or ANOVA test.
5. **Calculate the Test Statistic**: Compute the test statistic using the sample data.
6. **Make a Decision**: Compare the test statistic to the critical value or use the p-value to decide whether to reject or fail to reject the null hypothesis.

### <span style="color:orange">Types of Tests</span>

- **Z-Test**: Used when the sample size is large (n > 30) and the population standard deviation is known.
- **T-Test**: Used when the sample size is small (n ≤ 30) and the population standard deviation is unknown.
- **Chi-Square Test**: Used for comparing categorical variables.
- **ANOVA Test**: Used for comparing means of three or more groups.

### <span style="color:orange">One-Tailed vs Two-Tailed Tests</span>

- **One-Tailed Test**: Tests the hypothesis in one direction (e.g., greater than or less than a certain value).
- **Two-Tailed Test**: Tests the hypothesis in both directions (e.g., not equal to a certain value).

### <span style="color:orange">Decision Rule</span>

- If the test statistic falls in the rejection region, reject the null hypothesis.
- If the test statistic falls in the acceptance region, fail to reject the null hypothesis.

## <span style="color:green">Example</span>

The dataset `house_price_increase.csv` contains the percentage increase in house prices. We can use hypothesis testing to determine if the average price increase is significantly different from a certain value.

## <span style="color:green">Additional Notes</span>

##### Any Claim that can be tested is called Hypothesis Testing, Null Hypothesis is the Baseline Claim, Alternative Hypothesis is the Claim that we are testing.
##### If the Null Hypothesis is True, then the Alternative Hypothesis is False and Vice Versa.

##### Steps for Hypothesis Testing
1. Define the Null Hypothesis
2. Define the Alternative Hypothesis
#### Once Hypothesis is defined, we need to test the Hypothesis and Finalize the Hypothesis with Z-Test or T-Test or Chi-Square Test or Anova Test.
### Once this is done we arrive at a conclusion.

#### Z test is used when the sample size is large and the population standard deviation is known. 30 is a good sample size.
#### T test is used when the sample size is small and the population standard deviation is unknown.
#### Chi-Square Test is used when we are comparing the Categorical Variables.

#### We can also have one-tailed test and two-tailed test. In one-tailed test we are only interested in one side of the distribution, in two-tailed test we are interested in both sides of the distribution.
#### Example: if we say Inflation is > 5% then we call it one-tailed test and if it's not 5% meaning it can be 6% or 4% then we call it two-tailed test.

##### If Z score falls in rejection region then we reject the Null Hypothesis, if Z score falls in acceptance region then we accept the Null Hypothesis.
##### If Z score is greater than 1.96 or less than -1.96 then we reject the Null Hypothesis, if Z score is between -1.96 and 1.96 then we accept the Null Hypothesis.

##### Type one and Type two errors
- Type 1 error is when we reject the Null Hypothesis when it is True.
- Type 2 error is when we fail to reject the Null Hypothesis when it is False.
- Statistical power is the probability of rejecting the Null Hypothesis when it is False.
- False Positive is Type 1 error and False Negative is Type 2 error.
- Statistical Power is 1 - Type 2 error.

##### AB Testing is used to compare the two versions of the same product. We have control group and test group.
### This test is used to compare the two versions of the same product most times to check for improvements.

## <span style="color:green">Requirements</span>

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn

## <span style="color:green">Usage</span>

1. Clone the repository.
2. Open `Hypothesis_Testing.ipynb` in Jupyter Notebook.
3. Run the cells to see the hypothesis testing in action.

## <span style="color:green">Conclusion</span>

This project provides a comprehensive overview of hypothesis testing and demonstrates how to apply various statistical tests using Python.