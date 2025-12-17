# adult_census_dataset
The objective of this project is to apply Data Science concepts to the Adult Census Income dataset from the UCI Machine Learning Repository. The main goal is to predict whether an individual's annual income exceeds $50K per year based on demographic and socioeconomic attributes.

The main tasks include:
• Exploratory Data Analysis (EDA):
• Preprocessing and preparation of the dataset
• Training three different classification models
• Evaluating model performance through multiple metrics
• Performing two statistical hypothesis tests related to income proportions

The exploratory data analysis (EDA) section includes descriptive statistics for numerical and categorical variables, handled missing values and identified outliers, explored feature distributions and class imbalance, and relevant visualizations to support insights.

Regarding the data preparation, it covers the encoding of categorical variables, the normalization/standardization of numerical features, and the train/test split, along with a brief justification for these preprocessing decisions.

In the modeling phase, three classifiers were tested, with detailed justification of the selected hyperparameters and a comparison of their performance. Evaluation was conducted using standard classification metrics - Accuracy, Confusion Matrix, Precision, Recall, F1-score, and ROC-AUC - and included an analysis of model behavior under class imbalance as well as the consequences of false positives and false negatives.

Furthermore, two statistical hypothesis tests were performed to investigate differences between groups with respect to the income variable. The first test compared proportions to determine whether the proportion of women earning more than 50K is equal to that of men. The second test was an A/B test to investigate whether the proportion of individuals earning more than 50K differs between those who work more than 40 hours per week and those who work 40 hours or fewer.

Workflow: Data science pipeline from EDA to modeling and statistical testing, with insights guiding preprocessing and model decisions.
