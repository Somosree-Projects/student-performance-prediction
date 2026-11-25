# Student Performance Prediction and Academic Risk Analysis

## 1. Project Introduction

The **Student Performance Prediction and Academic Risk Analysis** project uses Machine Learning techniques to analyze students' academic performance and identify students who may be at risk of poor academic results.

The project studies different academic and personal factors, such as study time, previous examination grades, past failures, and absences. It applies Machine Learning algorithms to predict final examination marks, classify students into Pass or Fail categories, and group students according to their academic performance.

The main goal is to understand student performance through data analysis and provide useful insights that can support early identification of academically at-risk students.

## 2. Project Objectives

The main objectives of this project are:

- To analyze students' academic performance using a real-world dataset.
- To identify important factors that influence final examination marks.
- To predict students' final examination marks using Linear Regression.
- To classify students into Pass and Fail categories using Logistic Regression and K-Nearest Neighbors.
- To group students into different academic performance categories using K-Means Clustering.
- To identify students with high, medium, and low academic risk.
- To visualize academic trends and present meaningful insights.

## 3. Dataset Information

**Dataset Name:** Student Performance Dataset (Portuguese Language Course)

**Dataset Source:** UCI Machine Learning Repository

**Dataset File:** `student-por.csv`

**Dataset Link:** https://archive.ics.uci.edu/dataset/320/student+performance

The dataset contains information about students' personal backgrounds, family circumstances, study habits, school-related activities, and academic grades.

| Dataset Information | Details |
|---|---|
| Total Records | 649 students |
| Total Original Attributes | 33 |
| File Format | CSV |
| Separator | Semicolon (`;`) |
| Target Variable | G3 (Final Grade) |
| Missing Values | 0 |
| Duplicate Records | 0 |

### Important Dataset Attributes

- `studytime` – Weekly study time.
- `absences` – Number of school absences.
- `failures` – Number of previous class failures.
- `G1` – First-period grade.
- `G2` – Second-period grade.
- `G3` – Final-period grade.

**Note:** The project uses `G3` as the final grade for prediction and Pass/Fail classification. A grade of 10 or above is considered Pass, while a grade below 10 is considered Fail.

## 4. Technologies Used

The project is developed using the following technologies and libraries:

- **Python** – Main programming language.
- **Google Colab / Jupyter Notebook** – Development environment.
- **Pandas** – Data loading and manipulation.
- **NumPy** – Numerical calculations.
- **Matplotlib** – Data visualization.
- **Seaborn** – Statistical visualization.
- **Scikit-learn** – Machine Learning model development and evaluation.

## 5. Machine Learning Algorithms

The project uses four Machine Learning algorithms:

### 1. Linear Regression
Used to predict students' final examination marks (`G3`) based on academic and personal features.

### 2. Logistic Regression
Used to classify students into two categories: Pass and Fail.

### 3. K-Nearest Neighbors (KNN)
Used to classify students based on the academic patterns of similar students.

### 4. K-Means Clustering
Used to group students into three academic performance categories:

- High Performing
- Average
- Academically At-Risk

The project also applies parameter tuning to improve the performance of the classification models.

## 6. Project Workflow

The project follows these major steps:

1. **Dataset Loading:** Import the student dataset using Pandas.
2. **Data Preprocessing:** Check missing values, duplicate records, data types, and outliers.
3. **Data Encoding:** Convert categorical data into numerical form.
4. **Exploratory Data Analysis:** Calculate statistical measures and examine relationships between academic factors.
5. **Data Visualization:** Generate graphs to understand grade distributions, study habits, absences, and correlations.
6. **Model Development:** Implement Linear Regression, Logistic Regression, KNN, and K-Means.
7. **Model Optimization:** Apply parameter tuning to the classification models.
8. **Model Evaluation:** Evaluate predictions using suitable performance metrics.
9. **Academic Risk Analysis:** Identify students' academic risk levels.
10. **Final Visualization and Export:** Display project results and save the generated analysis files.

## 7. Results and Evaluation

The project evaluates each algorithm using suitable evaluation techniques.

| Algorithm | Evaluation Method | Purpose |
|---|---|---|
| Linear Regression | MAE, MSE, RMSE, R² Score | Final grade prediction |
| Logistic Regression | Accuracy, Confusion Matrix, Classification Report | Pass/Fail classification |
| KNN | Accuracy, Confusion Matrix, Classification Report | Similarity-based classification |
| K-Means | Silhouette Score and Cluster Analysis | Student grouping |

### Project Outputs

The project generates the following outputs:

- Predicted final examination marks.
- Pass/Fail classification results.
- Pass probability for students.
- Academic risk categories.
- Student performance groups.
- Important factors related to academic performance.
- Model performance comparison.

**Final model scores will be added after the models have been tested and their results verified.**

## 8. Graphs and Visualizations

The project includes visualizations to make the analysis easier to understand.

The following graphs are generated:

1. Distribution of Student Final Grades.
2. Study Time vs Final Examination Performance.
3. Student Absences vs Final Grades.
4. Correlation Heatmap of Student Performance.
5. Actual vs Predicted Final Examination Marks.
6. Classification Model Accuracy Comparison.
7. Distribution of Students by Academic Risk Level.
8. Student Performance Segmentation Using K-Means.
9. Important Factors Affecting Student Performance.

## 9. How to Run the Project

### Requirements

- Python 3.x
- Google Colab or Jupyter Notebook
- Required Python libraries

### Step 1: Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY-NAME.git
```

### Step 2: Open the Project

Open `Student_Performance_Analysis.ipynb` using Google Colab or Jupyter Notebook.

### Step 3: Upload the Dataset

Upload the `student-por.csv` file to the notebook environment.

### Step 4: Install Required Libraries

```python
!pip install pandas numpy matplotlib seaborn scikit-learn
```

### Step 5: Run the Notebook

Execute the notebook cells in sequential order, starting from the first cell.

The notebook will perform data preprocessing, exploratory data analysis, model training, prediction, evaluation, and visualization.

## 10. Generated Output Files

After successful execution, the project saves the following CSV files:

| File Name | Description |
|---|---|
| `student_prediction_results.csv` | Actual marks, predicted marks, and academic risk |
| `model_comparison.csv` | Comparison of Machine Learning model performance |
| `student_performance_analysis.csv` | Student data with performance groups |

## 11. Conclusion

This project demonstrates how Machine Learning can be applied to student academic data to predict examination performance, classify students based on their results, and identify different academic risk levels.

By combining data analysis, prediction, classification, and clustering techniques, the project provides useful insights into student performance and supports the identification of students who may need additional academic attention.

---

## Author

**Project:** Student Performance Prediction and Academic Risk Analysis

**Course:** Master of Computer Applications (MCA)

**Section:** C

**Academic Year:** 2025–2026

**Tools:** Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

---

*This project is developed for academic and educational purposes.*
