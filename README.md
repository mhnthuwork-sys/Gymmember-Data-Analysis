
# 🏋️ Gym Members Exercise & Health Data Analysis
**Google Data Analytics Capstone — Style Project**

![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat-square)
![Pandas](https://img.shields.io/badge/Pandas-green?style=flat-square)
![Seaborn](https://img.shields.io/badge/Seaborn-teal?style=flat-square)
![Kaggle](https://img.shields.io/badge/Dataset-Kaggle-orange?style=flat-square)

---

## 📌 Overview

An end-to-end data analysis project following the **Google Data Analytics 6-step framework**, applied to a gym members exercise dataset from Kaggle. The analysis simulates a business scenario for a fictional fitness app (*FitTrack*) seeking to improve member engagement and product features.

> ⚠️ This uses a **simulated dataset**. Findings are for learning purposes only.

---

## 🔄 Framework

| Step | Phase | Description |
|------|-------|-------------|
| 1 | **Ask** | Define business questions around workout behavior and health outcomes |
| 2 | **Prepare** | Load and assess the dataset (ROCCC check) |
| 3 | **Process** | Clean data, handle nulls/duplicates, engineer new features |
| 4 | **Analyze** | Answer each business question with aggregations and groupby analysis |
| 5 | **Share** | Build 7 visualizations to communicate findings |
| 6 | **Act** | Summarize insights and recommend next steps |

---

## 📦 Dataset

- **Source:** [Kaggle — Gym Members Exercise Dataset](https://www.kaggle.com/datasets/valakhorasani/gym-members-exercise-dataset)
- **File:** `gym_members_exercise_tracking.csv`
- **Size:** 973 rows × 15 columns
- **Key variables:** Age, Gender, BMI, Workout Type, Session Duration, Calories Burned, Experience Level, Water Intake, Heart Rate

---

## 📊 Charts Included

1. Most popular workout types — bar chart
2. Workout frequency vs. average calories burned — line chart
3. Gender comparison (calories, fat %, session duration) — box plots
4. BMI category distribution — bar + pie chart
5. Experience level vs. calories burned & fat % — grouped bar charts
6. Correlation heatmap of fitness variables
7. Calories burned vs. session duration by workout type — scatter plot

---

## 💡 Key Findings

1. All 4 workout types (Cardio, Strength, Yoga, HIIT) are equally popular at ~25% each
2. Members who work out 5 days/week burn significantly more calories than those who work out 2 days/week
3. Male members burn slightly more calories on average; female members show lower fat % at higher experience levels
4. ~60% of members fall in the Normal or Overweight BMI range — room for targeted health programs
5. Expert-level members burn far more calories and have much lower body fat than beginners
6. Session duration, workout frequency, and water intake all positively correlate with calorie burn

---

## 🛠️ Requirements

```bash
pip install pandas numpy matplotlib seaborn
```

---

## ▶️ How to Run

1. Download the dataset CSV from the Kaggle link above
2. Place it in the same folder as the notebook
3. Open `gym_analysis.ipynb` in Jupyter or VS Code
4. Run all cells in order

---

## 📁 Project Structure
