### Project Title

Author: Abhinav Dagur

#### Executive summary
The objective of this project was to develop predictive models capable of accurately identifying potential loan defaults. This is crucial for financial institutions to mitigate risks associated with lending and to make informed decisions.

#### Rationale
Understanding the factors that contribute to loan defaults can help financial institutions improve risk assessment models, minimize losses, and offer better terms to low-risk applicants. This analysis is crucial for anyone involved in the lending industry or interested in credit risk assessment.

#### Research Question
Which features are most indicative of a loan's likelihood to default, and how can financial institutions use these insights to improve their lending models?

#### Data Sources
The analysis was conducted using loan data, which includes both applicant features (e.g., occupation, employment details) and loan features (e.g., rate, amount, purpose).

#### Methodology
The methodology involved:
Filtering the dataset for relevant features.
Encoding categorical variables for correlation analysis.
Visualizing distributions and correlations between loan status and numerical features.
Summarizing key insights regarding the impact of various features on loan defaults.
#### Model Selection and Development
Multiple models were evaluated to address the prediction task, including Random Forest, Logistic Regression, and Gradient Boosting Machines (XGBoost). These models were chosen for their proven track record in handling binary classification problems effectively.

#### Baseline Models: 
Initial models were trained with default hyperparameters to establish a performance baseline.
#### Optimized Models: 
Following baseline model evaluation, we employed RandomizedSearchCV for hyperparameter tuning, seeking to improve model performance by exploring a wide range of parameter configurations.
#### Model Evaluation
Model performance was rigorously evaluated using several key metrics: Accuracy, Precision, Recall, F1 Score, and ROC-AUC. These metrics provided a comprehensive view of each model's strengths and weaknesses, particularly in terms of their ability to balance the trade-off between sensitivity and specificity.


#### Results
The GBM (XGBoost) models, both baseline and optimized, outperformed other models across all evaluation metrics, with the optimized version showing slight improvements over the baseline. The Random Forest model saw a decrease in performance upon optimization, indicating possible overfitting with the default parameters. Logistic Regression models demonstrated modest performance, with minimal differences between the baseline and optimized versions.

#### Next steps
Further research could explore more advanced feature engineering techniques, alternative ensemble methods, and deep learning models to assess their potential for improving prediction accuracy. Additionally, investigating model interpretability tools can provide valuable insights into the decision-making process, enhancing transparency and trust in the predictive models.


#### Outline of project

- [Link to [notebook](https://github.com/dagura111/ucb_capstone_20_1/blob/main/try-it-20.1.ipynb)]
- [Link to [data](https://github.com/dagura111/ucb_capstone_20_1/blob/main/data/loan.csv)]

(Because of the size of data, I uploaded the partial data to the git repo. Link to the kaggle(https://www.kaggle.com/datasets/adarshsng/lending-club-loan-data-csv) for complete set of data)

##### Contact and Further Information
