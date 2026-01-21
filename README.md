# 🎮 Video Games Sales – Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project focuses on **Exploratory Data Analysis (EDA)** of a global video games sales dataset.  
The aim is to understand **game trends, platform popularity, sales behavior over time, and regional contributions** using data cleaning and visualization techniques.

This project is **strictly EDA-based** and does not involve any machine learning or predictive modeling.

---

## 🎯 Objective
The objectives of this project are to:
- Clean and preprocess the video games sales dataset
- Handle missing values and duplicates
- Analyze game distribution across genres and platforms
- Study global sales trends over time
- Compare regional sales contributions
- Extract meaningful insights using data visualization

---

## 📂 Dataset Description
- **Dataset Name:** `Video_Games_Sales_as_at_22_Dec_2016.csv`
- **Number of Records:** ~16,000+
- **Time Period Covered:** Up to 2016
- **Sales Unit:** Millions

### Key Columns Used
- `Name`
- `Platform`
- `Genre`
- `Publisher`
- `Year_of_Release`
- `NA_Sales`
- `EU_Sales`
- `JP_Sales`
- `Other_Sales`
- `Global_Sales`

---

## 🔄 Project Workflow

### 1️⃣ Data Loading
- Loaded the dataset using Pandas
- Inspected dataset shape, structure, and data types

---

### 2️⃣ Data Preprocessing

#### 🔹 Handling Missing Values
- **Year_of_Release:** Filled missing values using the median
- **Publisher:** Missing values labeled as `"Unknown"`
- **Dropped columns with high missing values:**
  - `Critic_Score`
  - `Critic_Count`
  - `User_Score`
  - `User_Count`
  - `Developer`
  - `Rating`
- Removed a very small number of rows with missing `Name` or `Genre`

After these steps, the dataset contained **no missing values**.

---

### 3️⃣ Handling Duplicates
- Checked for duplicate records
- Ensured dataset integrity before visualization

---

## 📊 Exploratory Data Analysis & Visualizations

### 1️⃣ Most Common Game Genres
- Visualized the distribution of games across genres
- **Insight:** Action and Sports genres contain the highest number of games compared to other genres

---

### 2️⃣ Number of Games Released per Platform
- Analyzed platform-wise game releases
- **Insight:** PS2 and DS have the highest number of game releases, indicating longer platform life cycles and strong developer support

---

### 3️⃣ Global Video Game Sales Trend Over Time
- Analyzed year-wise aggregated global sales
- **Insight:** Global video game sales increased steadily from early years, peaked in the late 2000s, and declined in later years, indicating market saturation

---

### 4️⃣ Regional Sales Comparison
- Compared sales across regions (NA, EU, JP, Others)
- **Insight:** North America contributes the largest share of global video game sales

---

## 🛠️ Tools & Libraries Used
- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**

---

##  Scope of the Project
- This project focuses on **EDA-only**
- Focus is purely on understanding data and extracting insights.

---

---

## ✅ Conclusion
This exploratory data analysis provides a clear understanding of the video game industry’s evolution over time.  
By analyzing platforms, genres, regional sales, and historical trends, this project highlights key patterns and market dynamics in the global gaming industry.

---

## 👤 Author
**Maaz Patel**  
BSc IT | Aspiring Data Analyst

