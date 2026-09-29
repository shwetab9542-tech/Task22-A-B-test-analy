Task22-A/B Test Analysis

## Project Overview

This project analyzes an A/B test comparing a Control group and a
Treatment group.

The objective is to determine whether the observed difference in
Purchase Amount is statistically significant.

## Dataset

The dataset contains:

- User_ID
- Group
- Purchase_Amount

The two groups are:

- Control
- Treatment

## Tools and Technologies

- Python
- Pandas
- NumPy
- SciPy
- Matplotlib
- Jupyter Notebook

## Analysis Performed

1. Loaded and inspected the dataset
2. Checked missing values and duplicates
3. Defined Control and Treatment groups
4. Calculated descriptive statistics
5. Compared group means
6. Calculated percentage change
7. Visualized the groups
8. Formulated statistical hypotheses
9. Performed Welch's independent two-sample t-test
10. Calculated p-value
11. Calculated Cohen's d effect size
12. Calculated 95% confidence interval
13. Prepared the final recommendation

## Statistical Test

Welch's independent two-sample t-test was used to compare the
average Purchase Amount between the two independent groups.

Significance level:

α = 0.05

## Conclusion

The analysis evaluates both statistical significance and effect size
to support an evidence-based A/B test conclusion.
