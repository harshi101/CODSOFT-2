# CODSOFT-2
Movie Rating Prediction- CODSOFT Internship

This project is a part of the CodSoft Data Science Internship (Task 2).

Obective:

To build a machine learning model that predicts the IMDb rating of a movie based on features like genre, director, and actors using regression techniques.
The goal is to analyze historical movie data and develop a model that can accurately estimate the rating given to a movie by users or critics.

Technologies Used:
 - Python
 - Pandas, NumPy (Data Handling)
 - Matplotlib, Seaborn (Data Visualization)
 - Scikit-learn (Model Building & Evaluation)

Steps Followed:

  Step 1: Data Preprocessing
   - Handled missing values
   - Extracted Year and cleaned Duration
   - Encoded Genre using one-hot encoding
   - Encoded Director and top 20 frequent actors
   - Created final feature set

  Step 2: Model Building
   - Used Linear Regression (baseline)
   - Tested Random Forest Regressor for improvement
   - Trained and evaluated model using regression metrics

  Step 3: Evaluation
   - Used the following metrics to evaluate performance:
   - MAE – Mean Absolute Error
   - RMSE – Root Mean Squared Error
   - R² Score – Goodness of Fit

Results:

 - MAE :          ~1.00
 - RMSE :         ~1.25
 -  R²  :        ~0.14 to 0.18

Conclusion:

   The model performs moderately well with the given dataset. Accuracy may improve with additional features like user reviews or cast popularity.

Dataset
- Source: [Kaggle Dataset Link](https://www.kaggle.com/datasets/adrianmcmahon/imdb-india-movies)

Author:

T Harshitha

Codsoft Data Science Intern

#codsoft #datascience #internship

   
