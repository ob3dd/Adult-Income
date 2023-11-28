![Header-38-800x450](https://github.com/ob3dd/Adult-Income-and-Wine-Quality-/assets/133266342/ad2e403c-b8ea-4422-9edf-619d0d03b5dc)
# Adult Income
This is where I will be exploring, analyzing, and gaining valuable insights from a diverse and fascinating dataset: "Adult Income".

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
The insights gotten from our prediction was, those with degrees like the prof-speciality occupations. These include occupations that requires highly specialized training or experience. Also jobs one can get with a bachelor’s degree. Being a private house server or waiter didn't make that much income.

# Recommendation
I would recommend government increasing the minimum wage of individuals, make housing affordable for people to buy and live in, promote financial literacy and promote entrepreneurship. Thus would help in the increase of individual's income and help them live better financially. 
