# Lead Scoring: Predictive Modeling of Lead Conversion

### CONTENTS:

1. Lead Scoring Problem Statement (.pdf)

2. Final Report (.pdf)

3. Lead Scoring Slide Deck (.pdf) *presentation notes not included

4. Python Code (.ipynb):

	01 Data Wrangling

	02 EDA

	03 Preprocessing and Modeling

5. Data Files (.csv):

	Leads_X_Education - original dataset

	leads_cleaned - first pass of cleaned data

	leads_cleaned_2 - second pass of cleaned data

	baseline_scores - profile and activity scores from original data, saved for future comparison

	model_data - final preprocessed data for modeling

6. Model Files:

	model.pickle

	Capstone 2 Model Metrics File.pdf - details re: model tuning and performance

### Overview:

In this project, I created a model that uses sales data to assign a numerical score to incoming
leads, indicating the probability of conversion for each lead. The data contained several
categorical and numerical features to describe lead characteristics, behaviors, and perceived
quality. The best performance was achieved with an XGBoost model, optimizing log loss to
emphasize the importance of accurate predicted probabilities. The area under the ROC curve
for the final model was 0.94, with recall for converted leads at 50% probability threshold of 0.81.

Using this model, the company can increase their lead conversion rate by adapting sales
strategies to an individual lead’s score. The model also identified the most important features
predicting conversion, which the company can use to update their marketing strategies to focus
on attracting leads that are more likely to convert.
