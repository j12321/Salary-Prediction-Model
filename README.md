# Salary Prediction Model 

## Project Overview
This project aims to predict job salaries in Taiwan using machine learning techniques. The dataset was obtained through web scraping from Taiwan's largest job search website,[104 Job Search](https://www.104.com.tw). Various models were implemented, including Random Forest, Gradient Boosting, and K-Nearest Neighbors, to optimize prediction accuracy.

## Dataset
- **Source:** Web scraped job listings from 104 job search website
- **Features:** Job title, company, location, industry, required experience, education level, and salary range
- **Target Variable:** Salary

## Technologies Used
- **Programming Languages:** Python
- **Libraries & Frameworks:** pandas, NumPy, scikit-learn, BeautifulSoup
- **Tools:** Jupyter Notebook, Git, Excel

## Methodology
1. **Data Collection:**
   - Used BeautifulSoup to extract job listings
   - Cleaned and preprocessed raw data
   - Feature engineering to improve predictive power

2. **Exploratory Data Analysis (EDA):**
   - Visualized salary distributions
   - Identified feature correlations
   - Handled missing values and outliers

3. **Model Training & Evaluation:**
   - Applied multiple machine learning models: Random Forest, Gradient Boosting, KNN, Linear Regression, Lasso, Ridge, SGD, 
   - Hyperparameter tuning 
   - Evaluated performance using Mean Absolute Error (MAE) and R Mean Squared Error (RMSE)
