


## Files

- **Data/house_price_increase.csv**: Contains the data of house price increases with columns `house_id` and `price_increase_pct`.
- **Hypothesis_Testing.ipynb**: Jupyter notebook that contains the code and explanations for hypothesis testing.
- **README.md**: This file, providing an overview of the project.

## Hypothesis Testing

Hypothesis testing is a statistical method used to make decisions about the population based on sample data. It involves the following steps:

1. **Define the Null Hypothesis (H0)**: The baseline claim that there is no effect or no difference.
2. **Define the Alternative Hypothesis (H1)**: The claim that we are testing, which is contrary to the null hypothesis.
3. **Select a Significance Level (α)**: Commonly used significance levels are 0.05, 0.01, and 0.10.
4. **Choose the Appropriate Test**: Depending on the data and hypothesis, choose between Z-test, T-test, Chi-Square test, or ANOVA test.
5. **Calculate the Test Statistic**: Compute the test statistic using the sample data.
6. **Make a Decision**: Compare the test statistic to the critical value or use the p-value to decide whether to reject or fail to reject the null hypothesis.

### Types of Tests

- **Z-Test**: Used when the sample size is large (n > 30) and the population standard deviation is known.
- **T-Test**: Used when the sample size is small (n ≤ 30) and the population standard deviation is unknown.
- **Chi-Square Test**: Used for comparing categorical variables.
- **ANOVA Test**: Used for comparing means of three or more groups.

### One-Tailed vs Two-Tailed Tests

- **One-Tailed Test**: Tests the hypothesis in one direction (e.g., greater than or less than a certain value).
- **Two-Tailed Test**: Tests the hypothesis in both directions (e.g., not equal to a certain value).

### Decision Rule

- If the test statistic falls in the rejection region, reject the null hypothesis.
- If the test statistic falls in the acceptance region, fail to reject the null hypothesis.

## Example

The dataset `house_price_increase.csv` contains the percentage increase in house prices. We can use hypothesis testing to determine if the average price increase is significantly different from a certain value.

## Requirements

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Usage

1. Clone the repository.
2. Open `Hypothesis_Testing.ipynb` in Jupyter Notebook.
3. Run the cells to see the hypothesis testing in action.

## Conclusion

This project provides a comprehensive overview of hypothesis testing and demonstrates how to apply various statistical tests using Python.
