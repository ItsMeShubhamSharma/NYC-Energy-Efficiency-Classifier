# NYC Building Energy Efficiency Prediction

## Project Objective

Predict whether a building in NYC is energy-efficient based on energy usage metrics and building characteristics using machine learning.

## Dataset

Data source: NYC Benchmarking Disclosure Data Reported in 2016  
Dataset includes building energy usage, physical characteristics, and ENERGY STAR scores.

## Key Steps

- Data cleaning and preprocessing  
- Feature selection and encoding  
- Model building with Decision Tree, Random Forest, Logistic Regression, and SVM  
- Model evaluation using accuracy, precision, recall, and F1-score  
- Hyperparameter tuning using GridSearchCV  
- Handling class imbalance  

## Results

- Random Forest gave the best accuracy (~88%) and balanced precision/recall for both classes  
- Logistic Regression and Decision Tree performed reasonably well  
- SVM underperformed due to class imbalance  

## Tools Used

- Python  
- Pandas  
- Scikit-learn  
- Jupyter Notebook  

## Project Structure

- `nyc_energy_efficiency.ipynb` — Jupyter Notebook with analysis and modeling  
- `data/nyc_benchmarking_data_2016.xlsx` — Dataset  
- `requirements.txt` — Project dependencies  
- `images/` — Important charts and visuals  

## How to Run

1. Install dependencies with `pip install -r requirements.txt`  
2. Open the Jupyter Notebook and run all cells  
3. Explore the results and visuals
