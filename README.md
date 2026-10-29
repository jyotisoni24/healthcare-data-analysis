# 🏥 Healthcare Appointment Data Analysis — EDA

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on a healthcare appointment dataset to understand appointment scheduling patterns and identify factors associated with different appointment outcomes.

The analysis focuses on **appointment trends, visit reasons, doctors, appointment hours, cancellations, completed appointments, and no-shows**.

The goal is to transform raw appointment data into meaningful insights that can support better appointment management and scheduling decisions.

---

## 🎯 Objectives

The key objectives of this project are to:

* Analyze appointment volume across different months and days
* Understand appointment outcomes and their distribution
* Identify the most common reasons for medical visits
* Analyze appointment outcomes across different visit reasons
* Compare appointment patterns across doctors
* Analyze appointment volume by hour
* Identify patterns in cancellations and no-show appointments
* Generate actionable insights from healthcare appointment data

---

## 📂 Dataset

The dataset contains healthcare appointment records with information related to:

* Appointment dates
* Appointment times
* Doctors
* Reasons for visits
* Appointment status
* Other appointment-related attributes

The dataset was cleaned and transformed before performing exploratory analysis.

---

## 🛠️ Technologies Used

| Technology       | Purpose                        |
| ---------------- | ------------------------------ |
| Python           | Data analysis                  |
| Pandas           | Data manipulation and analysis |
| NumPy            | Numerical operations           |
| Matplotlib       | Data visualization             |
| Seaborn          | Statistical visualization      |
| Jupyter Notebook | EDA environment                |
| Git & GitHub     | Version control                |

---

## 🔄 Project Workflow

```text
Raw Dataset
     ↓
Data Loading
     ↓
Data Inspection
     ↓
Data Quality Checks
     ↓
Data Cleaning
     ↓
Date & Time Feature Engineering
     ↓
Exploratory Data Analysis
     ↓
Visualizations
     ↓
Key Insights
     ↓
Conclusion
```

---

## 🔍 Data Preparation

The dataset was inspected and prepared before analysis.

The following checks and transformations were performed:

* Dataset structure inspection
* Data type validation
* Missing value checks
* Duplicate record checks
* Unique value analysis
* Descriptive statistics
* Date/time conversion
* Extraction of useful time-based features

### Feature Engineering

Additional features were created from appointment date/time information, including:

* Appointment Year
* Appointment Month
* Month Name
* Day of Week
* Appointment Hour

These features were used to identify temporal patterns in appointment activity.

---

# 📊 Exploratory Data Analysis

## 1. Monthly Appointment Analysis

Appointment volume was analyzed across different months to identify seasonal patterns and months with relatively higher or lower appointment activity.

---

## 2. Appointment Analysis by Day of Week

Appointments were analyzed across the days of the week to understand which weekdays experience higher appointment activity.

---

## 3. Appointment Status Analysis

The distribution of appointment outcomes was analyzed to understand the proportion of:

* Completed appointments
* Cancelled appointments
* No-show appointments
* Scheduled appointments

This helps identify the overall appointment outcome pattern.

---

## 4. Analysis by Reason for Visit

Different medical visit reasons were compared to identify the most frequently occurring appointment types.

This provides an understanding of the demand for different healthcare services.

---

## 5. Visit Reason vs Appointment Status

A cross-tabulation was performed between **visit reason and appointment status**.

Row-wise percentages were calculated to make appointment outcomes comparable across different visit types.

A heatmap was also used to visually identify patterns in cancellations, completions, and no-shows.

---

## 6. Doctor-wise Appointment Analysis

Appointments were analyzed across different doctors to understand:

* Appointment volume
* Appointment outcomes
* No-show patterns
* Completion patterns
* Cancellation patterns

Doctor-level comparisons can help identify differences in appointment behavior.

---

## 7. Appointment Hour Analysis

Appointment volume was analyzed across different hours of the day.

This helps identify:

* Busiest appointment hours
* Least busy hours
* Hour-wise appointment patterns
* Differences in appointment outcomes by time

---

## 8. Doctor vs Reason for Visit

A cross-tabulation was performed between doctors and reasons for visits to understand how different appointment types are distributed across doctors.

---

# 💡 Key Insights

The analysis produced several interesting observations:

* **April** recorded the highest number of appointments, while **September** recorded the lowest.
* **Tuesday and Wednesday** had the highest appointment volume among the days of the week.
* **Cancelled and no-show appointments together accounted for 51.5%** of all recorded appointments.
* Only **23% of appointments were completed**.
* **Therapy** had the highest observed no-show proportion at **35.71%**.
* **Emergency appointments** had a no-show proportion of **34.48%**.
* **Consultation** had the highest cancellation proportion at **34.88%** and the lowest completion proportion at **9.30%**.
* **3 PM** was the busiest appointment hour with **28 appointments**.
* **4 PM** had the lowest appointment volume with **15 appointments**.
* **D004** had the highest observed doctor-level no-show proportion at **35.71%**.
* **D007** had the highest observed completion proportion at **38.46%**.

> These insights are based on the analyzed dataset and represent patterns observed within this dataset.

---

# 📈 Visualizations

The EDA notebook contains visualizations covering:

* Monthly appointment trends
* Day-of-week appointment distribution
* Appointment status distribution
* Visit reason distribution
* Visit reason vs appointment status
* Doctor-wise appointment analysis
* Appointment hour distribution
* Doctor vs visit reason
* Heatmaps and comparative percentage analysis

---

# 📁 Project Structure

```text
Healthcare-Appointment-EDA/
│
├── data/
│   └── healthcare_appointments.csv
│
├── Healthcare_Appointment_EDA.ipynb
│
├── images/
│   └── visualizations/
│
├── README.md
│
└── requirements.txt
```

---

# ▶️ How to Run the Project

### 1. Clone the repository

```bash
git clone <your-repository-link>
```

### 2. Navigate to the project

```bash
cd Healthcare-Appointment-EDA
```

### 3. Install required libraries

```bash
pip install -r requirements.txt
```

Or install them directly:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 5. Open the notebook

```text
Healthcare_Appointment_EDA.ipynb
```

Run the notebook cells sequentially to reproduce the analysis.

---

# 📦 Requirements

```text
pandas
numpy
matplotlib
seaborn
jupyter
```

---

# 🚀 Future Improvements

This project can be extended further by:

* Building an interactive **Power BI healthcare dashboard**
* Performing deeper analysis using **SQL JOINs**
* Performing statistical hypothesis testing
* Building a machine learning model to predict appointment no-shows
* Creating an automated healthcare appointment reporting system
* Adding interactive filters and KPIs to the dashboard

---

# 🧠 Skills Demonstrated

Through this project, the following Data Analytics skills were demonstrated:

`Python`
`Pandas`
`NumPy`
`Data Cleaning`
`Exploratory Data Analysis`
`Feature Engineering`
`Data Visualization`
`Matplotlib`
`Seaborn`
`Statistical Analysis`
`Git`
`GitHub`

---

# 👨‍💻 Author

**Adabala Satya Sai**

B.Tech — Electronics & Communication Engineering

---

## ⭐ Conclusion

The analysis demonstrates how healthcare appointment data can be explored to identify meaningful patterns in **appointment volume, timing, visit reasons, doctors, cancellations, completions, and no-shows**.

The findings can help healthcare organizations better understand appointment behavior and identify areas where scheduling strategies, attendance monitoring, or patient follow-up may be improved.

This project demonstrates an end-to-end **Python-based Exploratory Data Analysis workflow** using a real-world-style healthcare dataset.
