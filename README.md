# Project_2_coding_dojo
# Income Prediction Project

## Business Problem and Stakeholders

### Problem Statement
The goal of this project is to predict whether an individual earns more than $50,000 per year or less. This prediction can be valuable for various purposes, including targeted marketing, resource allocation, and financial planning.

### Stakeholders
- Marketing teams: They can use the predictions to target high-income individuals with relevant advertisements and offers.
- Non-profit organizations: They can identify potential donors for fundraising campaigns.
- Financial planners: They can use the predictions to offer tailored financial advice.

## Data Source

### Dataset
The dataset used for this project is the [Adult Income Dataset](https://www.kaggle.com/datasets/wenruliu/adult-income-dataset) from the UCI Machine Learning Repository. This dataset contains various attributes of individuals, including age, education, occupation, and more, along with their income level (<=50K or >50K).

### Data Description
- **age**: Age of the individual (numeric)
- **workclass**: Type of employment (categorical)
- **education**: Highest level of education (categorical)
- **marital-status**: Marital status (categorical)
- **occupation**: Occupation of the individual (categorical)
- **relationship**: Relationship status (categorical)
- **race**: Race of the individual (categorical)
- **gender**: Gender of the individual (categorical)
- **hours-per-week**: Average number of working hours per week (numeric)
- **native-country**: Native country of the individual (categorical)
- **income**: Income level, either <=50K or >50K (binary)


## Getting Started

### Analytical insights from my data analysis.

 I choose two visualizations from the analysis that demonstrate key trends and insights for stakeholders. These visuals will be reporting-quality with titles, labels, and explanations for a non-technical audience.

### Visualization 1: Bar Chart - Education Level and Income

  ## Title: Education Level vs. Income

<p align = "center"> 
  <img src = "https://github.com/Magui2912/Project_2_coding_dojo/assets/135860668/9b5c6594-f9a5-4663-9c9f-82087ccc65ca">
</p>

## Explanation: 

This bar chart shows how education level relates to income. Each bar represents a different education level, and the height of the bar tells us the percentage of people with high income (earning over $50,000) in each education group.

## Insight:

As you move from left to right on the chart (from "Some High School" to "Doctorate"), you can see that more education generally leads to a higher percentage of people earning a high income. It's like climbing a ladder: the higher you go in education, the more likely you are to earn more money.

#### Visualization 2: Stacked Bar Chart - Marital Status and Income


  ## Title: Marital Status vs. Income

<p align = "center"> 
  <img src = "https://github.com/Magui2912/Project_2_coding_dojo/assets/135860668/340e4e45-08b4-4ccc-b52f-f21dcf719007">
</p>

## Explanation:

This stacked bar chart shows the relationship between marital status and income. Each colored segment represents a different marital status group, and within each group, the height of the segments shows the percentage of people with high income (earning over $50,000) and low income.

## Insight: 

If you look at the tallest segments in each group, you'll see that married people tend to have a higher percentage of high income compared to divorced or never-married individuals. Being married often means a higher chance of earning more money.

## Conclusion:
***These two visualizations provide clear insights into the relationship between education level and income, as well as the impact of marital status on income distribution***



### Metrics
We evaluate our models using the following metrics:
- Accuracy
- Precision
- Recall
- F1 Score
- ROC AUC Score

### Best Model
Our best-performing model is the Random Forest Classifier, which achieved an accuracy of approximately 79% on the test data.

## Future Work
- Fine-tuning hyperparameters for better model performance.
- Deploying the model for real-time predictions.
- Collecting more data to improve model accuracy.
