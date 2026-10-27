# Food Waste Prediction Using Machine Learning

## 1. Project Overview
This project uses Machine Learning to predict the amount of food waste in kilograms. It analyzes factors such as meals served, staff experience, and waste category to identify patterns and estimate food waste.

The main goal is to support better food management and help reduce food wastage.

## 2. Objectives
- Predict food waste in kilograms.
- Analyze factors affecting food waste.
- Perform Exploratory Data Analysis (EDA).
- Compare different Machine Learning models.
- Support better food management and waste reduction.

## 3. Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook / Google Colab

## 4. Machine Learning Models
The following regression models are used:
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

## 5. Project Workflow
1. Load the dataset.
2. Clean and preprocess the data.
3. Perform Exploratory Data Analysis (EDA).
4. Handle missing values and encode categorical features.
5. Split the dataset into training and testing sets.
6. Train and evaluate Machine Learning models.
7. Compare model performance.
8. Predict food waste using the best-performing model.

## 6. Model Performance
The Random Forest Regressor achieved the following results on the test dataset:

- **MAE:** 4.694 kg
- **RMSE:** 6.928 kg
- **R² Score:** 0.906

These results describe the model's performance on the available test data.

## 7. Installation
Install the required libraries using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn joblib
```

## 8. How to Run
1. Clone or download this repository.
2. Open the notebook `Food_Waste_Prediction.ipynb` in Jupyter Notebook or Google Colab.
3. Upload the required dataset.
4. Run the notebook cells in order.
5. Review the model evaluation results and predictions.

## 9. Expected Outcome
The project estimates food waste in kilograms based on the available input features. These predictions may help identify food waste patterns and support more efficient food planning.

## 10. Future Improvements
- Test the model on more diverse datasets.
- Improve prediction accuracy through feature engineering and model tuning.
- Develop a simple web application for food waste prediction.

## 11. Author
**Alok Kumar Swami**

B.Tech – Computer Science and Engineering (AI & Data Science)

## 12. Disclaimer
The predictions are estimates based on the dataset used for training and testing. Actual food waste may vary depending on real-world conditions.
