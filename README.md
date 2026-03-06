# Student Success Data Analytics Project

## Exploratory Data Analysis of Student Skills, Academic Performance, and Career Expectations

---

##  Project Overview

This project performs **Exploratory Data Analysis (EDA)** on a dataset containing information about students, including their academic performance, programming experience, leadership skills, event participation, and expected salary.

The goal of this project is to analyze patterns in student skills and background data to generate meaningful insights using Python-based data analytics techniques.

---

## Objectives

- Analyze academic performance (CGPA) of students
- Study the relationship between **CGPA, Python experience, and expected salary**
- Understand **student demographics (cities, colleges)**
- Identify popular technical events
- Detect patterns between **leadership skills and academic performance**
- Visualize trends using charts and statistical methods

---

## Dataset Description

The dataset contains the following attributes:

| Column | Description |
|------|-------------|
| Email ID | Unique identifier for students |
| College Name | Name of the student's college |
| City | City of the student |
| CGPA | Academic performance indicator |
| Family Income | Income category of the student's family |
| Experience with Python | Python programming experience (in months) |
| Leadership Skills | Whether the student has leadership experience |
| Events | Technical events attended |
| Year of Graduation | Expected graduation year |
| Expected Salary | Salary expectation after graduation |

---

## Data Cleaning

The following preprocessing steps were performed:

- Removed duplicate records
- Trimmed column name spaces
- Converted numeric columns such as CGPA, salary, and Python experience
- Handled missing values
- Converted **family income ranges into numeric values** for statistical analysis

Example conversion:
0-2 Lakh → 1
2-5 Lakh → 3.5
5-7 Lakh → 6
7 Lakh+ → 8

---

## Analysis Performed

### Basic Analysis

- Number of unique students
- Average CGPA
- Graduation year distribution
- Python experience distribution
- Average family income
- CGPA comparison across colleges
- Outlier detection
- Average CGPA by city
- Correlation between income and CGPA

---

### Moderate Analysis

- Student distribution across cities
- Expected salary vs CGPA analysis
- Event popularity analysis
- Leadership skills vs GPA comparison
- Students graduating before 2024
- Most effective promotion channels
- Participation in Data Science events
- Salary expectations of highly skilled students

---

## Visualizations

The following visualizations were created:

- Student distribution by city (Bar Chart)
- CGPA vs Expected Salary (Scatter Plot)
- Correlation Heatmap
- Event participation chart
- Income distribution graph

These visualizations help identify trends and relationships within the dataset.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab
- Power BI

---

## 📁 Project Structure
Student_Success_Data_Analysis
│
├── Code
│ └── dataset
│    └── Power BI Updated Data analyst Data.xlsx
│    └── processesd_student_data.xlsx
│ └── project.ipynb
│
├── Documentation
│
├── Demo Video
│ └── demo.mp4
│
└── README.md

---

## Key Insights

- The **average CGPA of students is around 8**, indicating strong academic performance.
- Students with **more Python experience tend to expect higher salaries**.
- **WhatsApp and Email promotions** are the most effective channels for event outreach.
- Leadership skills show a **small positive relationship with academic performance**.
- Most students belong to **lower income categories but still maintain strong CGPA**.

---

## Learning Outcomes

Through this project I learned:

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Statistical correlation analysis
- Data visualization techniques
- Real-world data interpretation

---

## Author

**Gopalkrishna Siddabattula**

This project was completed as part of an **Industry Internship Program at Cloud Counselage**, focusing on **Data Analytics**.

---

## Future Improvements

- Apply machine learning models for salary prediction
- Build an interactive **Power BI dashboard**
- Perform advanced skill clustering
- Deploy analysis using cloud platforms