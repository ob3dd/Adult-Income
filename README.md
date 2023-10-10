![Header-38-800x450](https://github.com/ob3dd/Adult-Income-and-Wine-Quality-/assets/133266342/ad2e403c-b8ea-4422-9edf-619d0d03b5dc)
# Adult Income
This is where I will be exploring, analyzing, and gaining valuable insights from two diverse and fascinating datasets: "Adult Income" and "Wine Quality.", and also pick one to work with.
I chose to work on the "Adult Income"
# Business Description and Stakeholders
This dataset is about the income made by adults from all kinds of demographic. Giving an individual's annual income from various factors, but also influenced by their paths across life.
# Source of Data: 
Adult income dataset https://www.kaggle.com/datasets/wenruliu/adult-income-dataset. For this dataset, there are 48842 rows and 15 columns.
# Analytical Insights
- During the exploratory data analysis, a boxplot, barplot and countplot were visualized for each categorical column. 
- Also, a boxplot was visualized for my numerical column.
- And a heatmap was used to find correlations between my features and the target.
- This gave a good baseline for all of the numeric and categorical columns for univariate EDA.
![download (6)](https://github.com/ob3dd/Adult-Income-and-Wine-Quality-/assets/133266342/410c5b1c-b54b-4a0f-978a-565a1fed8f23)

    - From the above plot, we can deduce that;
      
        - Occupations most individuals covered were the ones with specialities
          
        - The least was a Private house server.

     
![download (7)](https://github.com/ob3dd/Adult-Income-and-Wine-Quality-/assets/133266342/665119de-5962-42a0-8b4f-d18ecea048c8)

    - The most relationship status of individuals who have incomes are known to be husbands.
 
    - Wives(excluding "Others") were the least ones to have incomes in a household.
 
# Best Model Metrics
The best model for predicting our adult's incomes was built using a KNN Classification algorithm. The following metrics were achieved on the test set:

## CLASS 0:

  - Accuracy: 84%

  - Precision: 87%

  - Recall: 93%

  - F1-score: 90%

## CLASS 1:

  - Accuracy: 84%

  - Precision: 72%

  - Recall: 54%

  - F1-score: 62%

# Model's Effectiveness
The KNN classification model demonstrated an accuracy of 84%, which means it can accurately predict which customer makes less than $50k and which makes more. This predictive power allows the marketing and customer retention teams to proactively identify every adult's income in the database.

# Summary
The KNN classification model provides valuable insights into an adult's income. The analysis revealed that most adults in their late 20s to late 40s have less than $50k income and most adults in their mid 30s to early 50s have more than $50k income.

# Recommendation

I would recommend  boosting the models to find a much better accuracy, probably using the SMOTHE technique. 
