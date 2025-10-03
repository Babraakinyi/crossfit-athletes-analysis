# CrossFit Athlete Performance Prediction

## Project Overview
This project analyzes a dataset of 423k CrossFit athletes collected from competitions and training profiles worldwide.  
The goal is to explore and predict athletes strength performance, with a focus on deadlift weights, by understanding characteristics (age, gender, body size, background, training habits) and link them to performance metrics (strength lifts, benchmark workouts). 

---

## Dataset
Source: [CrossFit Athletes Dataset on Kaggle](https://www.kaggle.com/datasets/ulrikthygepedersen/crossfit-athletes?select=athletes.csv)  

- Includes age, gender, height, weight, training background.  
- Records of benchmark workouts (Fran, Grace, Helen, Filthy50, etc.) and lifts (deadlift, squat, snatch, C&J).  

Dataset is too large for GitHub → download from Kaggle and place in `/data`.  

---

## Project Structure
crossfit-project/
│── data/ # Local storage for dataset (ignored in GitHub)
│── notebooks/ # Jupyter notebooks (analysis + modeling steps)
│── README.md # Project overview (this file)
│── .gitignore # Ignore large files (data/.csv, data/.xlsx)

---

### Workflow
- **Data Cleaning & EDA**: Handled missing values, explored demographics, lifts, and WOD performance.  
- **Feature Engineering**: Created strength ratios, total strength, and encoded categorical data.  
- **Modeling**: Compared Linear Regression, Ridge, and Random Forest.  
- **Best Model**: Random Forest Regressor (Test R² = **0.85**).  

---

### Key Insights
- **Back squat** is the strongest predictor of deadlift.  
- **Gender** plays a major role in strength outcomes.  
- Random Forest captured relationships much better than linear models.

### Prediction Example
- Athlete 1 predicted deadlift: **373 lbs**  
- Athlete 2 predicted deadlift: **259 lbs**

---

## Tech Stack
- **Python** – Core programming language.  
- **Pandas, NumPy** – Data cleaning, manipulation, and feature engineering.  
- **Matplotlib, Seaborn** – Data visualization.  
- **Scikit-learn** – Machine learning models (Linear Regression, Ridge, Random Forest) and preprocessing pipelines.  
- **Jupyter Notebook** – Interactive development environment.  
- **Git & GitHub** – Version control and project sharing.  

---

## License
This project is for educational and research purposes.  
Dataset belongs to its original creators/sources.    
