
# Prodigy Infotech Internship Task 03

This repository contains the work completed for Task 3 of my Prodigy Infotech internship, which focuses on a Decision Tree Classifier to analyze and predict customer responses to a bank's term deposit marketing campaign. The dataset, sourced from the Bank Marketing Dataset, explores the impact of various customer demographics, financial attributes, and campaign details on subscription decisions. The project involves extensive data preprocessing, exploratory data analysis, correlation analysis, and model building.


## Tools and Libraries:

* Jupyter notebook 
* pandas, numpy for data manipulation.
* scikit-learn for machine learning model training and evaluation.
* matplotlib, seaborn for visualizations.
## Key Steps

1. Data Preprocessing:

* Handling missing values and renaming columns for clarity.
* Detection and removal of outliers using the Interquartile Range (IQR) method.
* Label encoding for categorical variables to prepare data for modeling.

2. Exploratory Data Analysis:

* Histograms for numeric features to analyze data distribution.
* Bar Plots for categorical variables to visualize counts.
* Box Plots for identifying and handling outliers.

3. Correlation Analysis:

* Highly correlated features (emp.var.rate, euribor3m, nr.employed) were dropped to avoid multicollinearity.
* Visualized with a heatmap.

4. Model Building:

* A Decision Tree Classifier was implemented with: 
    * Gini Index as the splitting criterion.
    * Hyperparameters like max_depth=5 and min_samples_split=10.
* The model was evaluated on training and test datasets.

5. Model Evaluation:

* Metrics used:
    * Accuracy Score to measure model performance.
    * Confusion Matrix and Classification Report for detailed evaluation of predictions.
* Visualization:
    * Decision Tree visualization using plot_tree to understand the decision-making process.
## Conclusion

The Bank Marketing Campaign Analysis and Decision Tree Classifier project successfully demonstrates the application of machine learning to predict customer behavior in a marketing context. By leveraging data preprocessing, exploratory analysis, and classification techniques, the project offers valuable insights into the factors influencing customer decisions to subscribe to a term deposit.

Thank you for reviewing my submission!