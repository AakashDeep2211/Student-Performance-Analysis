# 🎓 Student Performance Analysis

This project analyzes student performance data by exploring various factors such as **teacher quality, parental education level, distance from home, and study hours**. The analysis involves **data wrangling, cleaning, visualization, and statistical insights**.

---

## 📊 Dataset Information
- **Total Records:** 6,607 rows  
- **Columns:** 20  
- **Data Types:** 
  - 13 **Object** (categorical) columns  
  - 7 **Integer** (numerical) columns  
- **Null Values:** 
  - `Teacher_Quality`, `Parental_Education_Level`, and `Distance_from_Home` contain **null values**

---

## 🛠️ Libraries Used
- `pandas` → Data manipulation and cleaning  
- `numpy` → Numerical operations  
- `seaborn` → Data visualization  
- `matplotlib` → Plotting charts  

---

## 🔍 Exploratory Data Analysis (EDA)

### 1️⃣ **Data Exploration**
- **Index:** Starts from `0` to `6606` (total 6,607 entries).  
- **Categorized Variables:**
  - **Continuous Variables:** 4  
  - **Discrete Count Variables:** 3  
  - **Discrete Categorical Variables:** 13  

### 2️⃣ **Continuous Variables Insights**
- **Hours_Studied:**  
    - Mean: **19.97** hours/week (~3 hours/day)  
    - Mode: **20** hours/week (most common)  
- **Test_Score:**  
    - Mean: **75.41**  
    - Mode: **80**  
- **Distance_from_Home:**  
    - Mean: **8.52** km  
    - Mode: **5** km  

### 3️⃣ **Teacher Quality Analysis**
- **Teacher_Quality** column contains **null values**.  
- Mode: `Average`  

### 4️⃣ **Parental Education Level**
- **Parental_Education_Level** contains **null values**.  
- Mode: `Bachelor's Degree`  

### 5️⃣ **Distance from Home**
- Contains **null values** with most common value being **5 km**.  

---

## 📈 Data Wrangling & Cleaning
- Handled **null values** by replacing them with mode values for categorical columns.  
- Checked for **duplicates** and ensured data consistency.  
- Separated columns into **continuous, discrete count, and discrete categorical** variables.  

---

## 🔥 Key Takeaways
✅ Students **study an average of 20 hours** per week.  
✅ **Teacher quality** and **parental education** significantly impact performance.  
✅ **Distance from home** does not show a strong correlation with performance.  
✅ Majority of students scored around **75-80** on their tests.  

---
## 🛠️ Future Enhancements
- Use **machine learning models** to predict student performance.  
- Apply **hypothesis testing** to validate statistical observations.  
- Add more **visualizations** for better insights.  

---
