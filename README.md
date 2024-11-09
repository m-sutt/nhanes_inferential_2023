# nhanes_inferential_2023
NHANES 2021-2023 Inferential Analytics


## Objective

- Use NHANES data to perform basic inferential statistics using Python in Google Colab.
- Explore relationships and differences in health metrics and demographic variables, utilizing the skills learned in class to answer key questions about the dataset.

## Results and Interpretation

- **Question 1** : "Is there an association between marital status (married or not married) and education level (bachelor’s degree or higher vs. less than a bachelor’s degree)?"
  - Test Used: Chi-square test of independence.
  - Findings: There was no significant association between marital status and education level, indicating that being married or not married does not appear to have a     strong relationship with the level of education attained (bachelor's degree or higher vs. less than a bachelor's degree).
    
- **Question 2** : "Is there a difference in the mean sedentary behavior time between those who are married and those who are not married?"
  - Test Used: Independent samples t-test.
  - Findings: There was no significant difference in sedentary behavior time between married and not married individuals. This suggests that marital status does not       play a significant role in determining the amount of sedentary behavior in the sample.
    
- **Question 3**: "How do age and marital status affect systolic blood pressure?"
  - Test Used: OLS Regression.
  - Findings: Age was found to have a significant positive effect on systolic blood pressure, meaning that as age increases, systolic blood pressure tends to           increase. However, marital status (whether married or not) did not show a significant effect on systolic blood pressure in this dataset.
    
- **Question 4**: "Is there a correlation between self-reported weight and minutes of sedentary behavior?"
  - Test Used: Pearson correlation.
  - Findings: The analysis found no significant correlation between self-reported weight and sedentary behavior time. This means that in this dataset, there is no strong relationship between a person’s weight and their time spent in sedentary activities.

- **Question 5** (Creative Analysis): "Does age influence sedentary behavior time?"
  - Test Used: Pearson correlation.
  - Findings: There was no significant correlation between age and sedentary behavior time. This suggests that age does not have a direct relationship with how much time individuals spend in sedentary behavior, at least based on the data from this dataset.

- Errors encountered:
    - While cleaning data and merging them, I forgot I did it to one dataframe and then when I went to go and try to extract a different set of data I found that I couldn't
    - Also when I stop and came back to this assignment I would forget to load some data or sometimes purposefully didn't load it so I can clean up again because it seemed easier to just start from scratched.
    - For the regression question I wanted to have a way for my code to automatically extract the interpretation but ran into multiple errors while in the process and I know where my errors are but haven't really found a solution to it.
