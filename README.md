# Used Car Price Prediction

## Project Overview
This project focuses on analyzing and predicting the prices of used cars using machine learning techniques. A real-world dataset collected from an online car marketplace is used to understand the factors influencing used car prices and to build predictive models based on historical data.

## Dataset
**The Quikr Used Car Price Dataset was used for this project.**
The dataset contains information about used cars, including:
- Car name and company
- Manufacturing year
- Kilometers driven
- Fuel type
- Selling price

After cleaning, the dataset consists of 819 records used for model training and evaluation.

## Project Workflow
1. **Exploratory Data Analysis (EDA)**  
   - Analyzed price distribution, car age, mileage, fuel type, and brand trends  
   - Identified missing values and inconsistencies  

2. **Data Cleaning & Preprocessing**  
   - Converted textual price and mileage values into numeric format  
   - Removed invalid and missing entries  
   - Created a new feature `Age` to represent vehicle depreciation  

3. **Feature Engineering**  
   - Selected numerical features (year, kilometers driven, age)  
   - Selected categorical features (company, fuel type, car name)  

4. **Preprocessing Pipeline**  
   - Handled missing values using imputation  
   - Scaled numerical features  
   - Encoded categorical features using one-hot encoding  

5. **Machine Learning Models**
   - **Linear Regression** (baseline model)
   - **Random Forest Regressor** (non-linear ensemble model)

6. **Model Evaluation**
   - Models were evaluated using:
     - R² Score
     - Root Mean Squared Error (RMSE)
   - Linear Regression achieved better predictive performance on this dataset.

7. **Feature Importance Analysis**
   - Random Forest was used to identify key factors influencing car prices.
   - Important features included car age, year, mileage, brand, and specific car models.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Results
- Linear Regression achieved an R² score of approximately 0.72.
- Car age, mileage, brand, and model significantly affect resale prices.
- The project demonstrates a complete end-to-end machine learning workflow for price prediction.

## How to Run
1. Clone the repository  
2. Open the Jupyter Notebook  
3. Install required libraries  
4. Run cells sequentially

## Conclusion
This project successfully combines data analysis, preprocessing, and machine learning to predict used car prices and extract meaningful insights about price-driving factors.

