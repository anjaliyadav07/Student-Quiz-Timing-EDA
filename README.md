# Student Online Learning Quiz Attempt Timing Analysis

# 📌Project Overview -

This project analyzes quiz attempt timing behavior of students in an online learning environment.
The main goal is to understand how early, on-time, and late submissions affect student performance using Exploratory Data Analysis (EDA).

The analysis is performed using Python, focusing on time difference calculations, visualizations, and correlation analysis.

# 🎯 Objectives -

1. To analyze how early or late students attempt online quizzes

2. To categorize attempts as Early, On Time, or Late

3. To study the relationship between attempt timing and quiz scores

4. To identify patterns using visualizations and statistics

# 🧰 Technologies Used -

1. Python

2. Pandas – data handling and analysis

3. Matplotlib – data visualization

## 📁 Project Structure 
```text
project/
│
├── quiz_attempts.csv      # Dataset 
├── project.ipynb          # Python notebook (EDA code)
└── README.md              # Project documentation
```

# 📊 Dataset Description

The dataset contains quiz attempt information of students.

### 📑 Column Details

| Column Name       | Description                                      |
|-------------------|--------------------------------------------------|
| `student_id`      | Unique student identifier                        |
| `quiz_id`         | Quiz identifier                                  |
| `scheduled_time`  | Official quiz start time                         |
| `attempt_time`    | Time when student attempted the quiz             |
| `score`           | Marks obtained by the student                    |

### 

- Dataset is realistic and manually created

- Dates belong to December 2025

- Includes early, on-time, late attempts and some failures

# 🔍 Analysis Performed -

- Time difference calculation between scheduled and attempt time

- Classification of attempt behavior (Early / On Time / Late)

- Descriptive statistics of scores

- Visualizations:

1. Bar chart (attempt distribution)

2. Scatter plot (timing vs score)

3. Box plot (score comparison)

-  Correlation analysis between timing and score

# 📈 Key Findings

- Students attempting quizzes early or on time generally score higher

- Late submissions show lower average scores

- A negative correlation exists between delay in attempt and quiz score

- Time management plays an important role in online assessments

# 🧠 Conclusion

The study highlights that quiz attempt timing has a noticeable impact on student performance.
Early and on-time attempts are associated with better outcomes, while late submissions often lead to lower scores.
This analysis emphasizes the importance of effective time management in online learning environments.

# ▶️ How to Run the Project

1. Make sure Python is installed

2. Install required libraries:

    pip install pandas matplotlib


3. Open project.ipynb

4. Run all cells from top to bottom

# 👤 Author

Student Name: Anjali yadav
Course: BTECH CSE AI 

College: RISU Bhilai





