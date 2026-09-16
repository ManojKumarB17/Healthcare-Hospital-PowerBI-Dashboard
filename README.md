# 🏥 Healthcare & Hospital Dashboard

Interactive Power BI dashboard analyzing patient admissions, treatment costs, hospital outcomes, patient demographics, and hospital performance.

---

## 🎯 Project Objectives

The objective of this project is to analyze healthcare and hospital data using Power BI to identify trends in patient admissions, treatment costs, patient outcomes, age groups, gender distribution, cities, departments, and admission types.

The dashboard provides an interactive way to monitor hospital performance and generate meaningful healthcare insights.

---

## 📁 Dataset Used
<a  href="https://github.com/ManojKumarB17/Healthcare-Hospital-PowerBI-Dashboard/blob/main/Healthcare_Hospital_Dashboard_Dataset.xlsx">dataset</a>

---

## 📌 Dashboard KPIs

The dashboard contains the following key performance indicators:

### 1. Total Patients — **31**
Represents the total number of patients included in the dataset.

### 2. Total Admissions — **31**
Represents the total number of patient admissions.

### 3. Total Treatment Cost — **3.27M**
Represents the total treatment cost associated with the patients.

### 4. Average Length of Stay — **5.97**
Represents the average number of days patients stayed in the hospital.

### 5. Successful Outcomes — **24**
Represents the number of patients with successful/discharged outcomes.

---

## 📊 Dashboard Visualizations

### 1. Monthly Patient Admissions Trend

**Chart Type:** Line Chart

**Fields:**
- **X-axis:** `Month`
- **Y-axis:** Count of `Patient_ID`

**Purpose:**

Shows the monthly trend in patient admissions and helps identify months with higher or lower patient activity.

---

### 2. Successful Outcomes by City

**Chart Type:** Horizontal Bar Chart

**Fields:**
- **Y-axis:** `City`
- **X-axis:** Count of `Patient_ID`

**Purpose:**

Compares successful patient outcomes across different cities and helps understand the distribution of successful outcomes geographically.

---

### 3. Total Treatment Cost by Gender

**Chart Type:** Donut Chart

**Fields:**
- **Legend:** `Gender`
- **Values:** `Treatment_Cost`

**Purpose:**

Shows the distribution of total treatment costs between male and female patients.

The dashboard displays:

- **Male:** 56.04%
- **Female:** 43.96%

---

### 4. Patient Distribution by Age Group

**Chart Type:** Column Chart

**Fields:**
- **X-axis:** `Age_Group`
- **Y-axis:** Count of `Patient_ID`

**Purpose:**

Shows the distribution of patients across different age groups.

Age groups include:

- 0–18
- 19–35
- 36–50
- 51–65
- 66+

This helps identify which age groups have the highest number of patients.

---

### 5. Patient Outcomes & Treatment Cost

**Chart Type:** Matrix/Table

**Fields:**
- `Outcome`
- Count of `Patient_ID`
- Average `Length_of_Stay`
- Sum of `Treatment_Cost`

**Purpose:**

Provides a detailed comparison of patient outcomes, average hospital stay, and treatment costs.

The dashboard includes outcomes such as:

- Discharged
- Referred
- Under Treatment

---

## 🎛️ Interactive Filters

The dashboard contains interactive slicers for:

### Admission Date
Allows users to analyze patient admissions based on admission dates.

### City
Allows comparison of hospital/patient activity across different cities.

### Department
Allows users to analyze patients based on hospital departments.

### Gender
Allows analysis of patient data based on gender.

### Admission Type
Allows users to analyze patients based on admission types such as referral.

---

## 💡 Project Insights

The analysis provides insights into:

- Patient admission trends over time
- Successful outcomes across different cities
- Treatment cost distribution by gender
- Patient distribution across age groups
- Average length of hospital stay
- Treatment costs associated with different patient outcomes
- Patient activity across departments and admission types

These insights can help understand hospital activity, patient demographics, treatment costs, and patient outcomes.

---

## 🏁 Conclusion

The Healthcare & Hospital Dashboard provides an interactive view of patient admissions, treatment costs, hospital stay duration, patient demographics, and outcomes using Power BI.

The dashboard transforms healthcare data into meaningful visual insights and demonstrates practical skills in data cleaning, data analysis, DAX, Power Query, and Power BI dashboard development.

---

## 🛠️ Tools & Technologies

- **Power BI**
- **Power Query**
- **DAX**
- **Data Cleaning**
- **Data Analysis**
- **Data Visualization**
- **Dashboard Development**

---

## 🖼️ Dashboard Preview

![Healthcare & Hospital Dashboard](Dashboard.png)
