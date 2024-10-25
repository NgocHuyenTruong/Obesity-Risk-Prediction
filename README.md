# **Obesity Risk Prediction**

## **Project Overview**
This project aims to develop a predictive model that identifies an individual's risk of obesity, a significant health concern linked to cardiovascular disease.

## **Stakeholders**
- **Individuals:** Understanding obesity risk empowers informed health choices, potentially preventing complications.
- **Healthcare Providers:** The model serves as a screening tool for early intervention in at-risk individuals.
- **Public Health Initiatives:** The model can inform programs promoting healthy weight management and reducing obesity rates in the target population.

## **Dataset**
The dataset includes 20,758 records and 17 attributes, estimating obesity levels in people aged 14 to 61 from Mexico, Peru, and Colombia.
The target variable is `Obesity risk (NObeyesdad)`, which is a categorical variable with several levels:
- 0 - Insufficient_Weight
- 1 - Normal
- 2 - Overweight_Level_I
- 3 - Overweight_Level_II
- 4 - Obesity_Type_I
- 5 - Obesity_Type_II
- 6 - Obesity_Type_III

Dataset source: [Kaggle] https://www.kaggle.com/competitions/playground-series-s4e2/data

## **Problem Approach**
This is a classic supervised multiclass classification problem. The process involves:
1. Inspecting and visualizing the data.
2. Cleaning and transforming the dataset.
3. Building and testing 29 models, including XGBoost, LightGBM, and RandomForest.
4. Evaluating models using metrics such as accuracy and cross-validation scores to select the top 3 models (RandomForest, XGBoost, LightGBM).
5. Performing hyperparameter tuning on the selected models.
6. Constructing a Voting Classifier ensemble model from the top models.
7. Comparing the ensemble model's performance against its individual components to find the best final model.
8. Making predictions and assessing the performance of the best-tuned model.

## **Getting Started**
To run this project:
1. Clone the repository: https://github.com/NgocHuyenTruong/Obesity-Risk-Prediction
2. Open the Jupyter Notebook for data analysis and model development.

## **Contributions**
Contributions are welcome! Please open an issue or submit a pull request for any enhancements or suggestions.

## **Acknowledgments**
I would like to acknowledge the collaborative efforts of my team members, Ngoc Anh Nguyen and Thanh Dung Nguyen, in completing this project.

