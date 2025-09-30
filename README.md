# CrossFit Athletes Performance Analysis

## Project Overview
This project analyzes a dataset of **CrossFit athletes** collected from competitions and training profiles worldwide.  
The goal is to understand athlete characteristics (age, gender, body size, background, training habits) and link them to performance metrics (strength lifts, benchmark workouts).   

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

## Progress So Far
- ✅ Set up project structure  
- ✅ Data inspection (shape, columns, dtypes)  
- ✅ Data consistency check (missingness, min/max values)  
- 🔜 Define cleaning rules  
- 🔜 Perform EDA  
- 🔜 Build predictive models  

---

## Next Steps
- Clean dataset (remove unrealistic values, handle missing values).  
- Explore correlations between demographics, habits, and performance.  
- Train regression models to predict **deadlift** and **back squat**.  
- Evaluate model accuracy and feature importance.  

---

## Tech Stack
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

## Glossary
- **WOD (Workout of the Day):** Standardized CrossFit workouts used worldwide.  
- **Fran:** 21-15-9 thrusters & pull-ups (time).  
- **Grace:** 30 clean & jerks (time).  
- **Helen:** Run + kettlebell swings + pull-ups (time).  
- **Filthy50:** 50 reps of 10 movements (time).  
- **Deadlift, Back Squat, Snatch, C&J:** Strength lifts (weight in lbs).  

---

## License
This project is for educational and research purposes.  
Dataset belongs to its original creators/sources.  
