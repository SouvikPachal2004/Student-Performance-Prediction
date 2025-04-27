# Student-Performance-Prediction

## Project Overview
This project aims to analyze the "StudentsPerformance.csv" dataset and predict students' math scores using Machine Learning algorithms. The main objective is to compare different models and find the best-performing one.

---

## Dataset Description
- **Dataset:** StudentsPerformance.csv
- **Features:**
  - Gender
  - Race/Ethnicity
  - Parental level of education
  - Lunch
  - Test preparation course
  - Reading score
  - Writing score
- **Target Variable:**
  - Math score

---

## Libraries Used
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

---

## Project Workflow

1. **Data Preprocessing**
   - Encoding categorical variables using Label Encoding.
   - Splitting the dataset into features (X) and target (y).

2. **Model Training**
   - Linear Regression
   - Random Forest Regressor

3. **Evaluation Metrics**
   - MAE (Mean Absolute Error)
   - MSE (Mean Squared Error)
   - RMSE (Root Mean Squared Error)
   - R2 Score

4. **Visualization**
   - Scatter plots of actual vs. predicted math scores for both models.

5. **Presentation**
   - Created a PowerPoint presentation summarizing the analysis, evaluation, and conclusion.

---

## Results

| Model                   |        MAE      |        MSE         |        RMSE       |      R2 Score      | 
|-------------------------|-----------------|--------------------|-------------------|--------------------|
| Linear Regression       |4.130145078004054| 28.275284506327317 | 5.317450940660131 | 0.8838026201112225 |
| Random Forest Regressor |4.70082380952381 | 36.79422162429139  | 6.065824068029948 | 0.8487940184356789 |

- **Best Model:** Linear Regression Model performed better for predicting Math Scores! (based on R2 score)
