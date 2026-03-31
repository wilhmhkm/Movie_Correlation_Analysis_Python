# 🎬 Movie Correlation Analysis (Python Portfolio Project)

## 📌 Executive Summary
This project analyzes a movie industry dataset to uncover the key factors influencing box office success. Using Python, the analysis focuses on identifying correlations between variables such as budget, votes, and revenue.  

The findings reveal that **budget and audience engagement (votes)** are the strongest predictors of gross revenue, while factors like company have minimal impact.

---

## 🛠️ Tools & Technologies
- **Python**
- **Jupyter Notebook (Anaconda)**
- **Pandas** – Data manipulation & cleaning  
- **NumPy** – Numerical operations  
- **Matplotlib** – Data visualization  
- **Seaborn** – Advanced statistical visualization  

---

## 🚀 Data Processing Steps

### 1. Data Acquisition
- Downloaded movie dataset from Kaggle
- Loaded dataset using `pandas.read_csv()`

### 2. Data Exploration
- Inspected dataset using `.head()`
- Reviewed column types with `.dtypes`
- Checked for missing values using loops and `isnull()`

### 3. Data Cleaning
- Converted data types (e.g., budget & gross → integers)
- Created a **corrected year column** from release date
- Sorted data by gross revenue
- Checked and handled duplicates
- Standardized dataset structure for analysis

### 4. Feature Engineering
- Converted categorical variables (company, genre, etc.) into numeric format using **category encoding**

### 5. Exploratory Data Analysis (EDA)
- Built **scatter plots** to compare budget vs revenue
- Used **regression plots** to identify trends
- Generated **correlation matrix** using Pearson method

### 6. Visualization
- Created **heatmaps** to easily interpret correlations
- Highlighted strong vs weak relationships visually

---

## 📊 Key Insights

- **Budget vs Gross Revenue**
  - Strong positive correlation (~0.71)
  - Higher investment generally leads to higher returns

- **Votes vs Gross Revenue**
  - Significant correlation
  - Audience engagement is a strong success indicator

- **Company vs Gross Revenue**
  - Weak correlation
  - Production company does not strongly determine success

- **Runtime & Other Features**
  - Minimal to moderate impact on revenue

---

## 💡 Recommendations

- 🎯 Focus on **strategic budget allocation** to maximize returns  
- 📣 Prioritize **audience engagement and marketing** to increase votes and visibility  
- 🏢 Avoid over-reliance on production company reputation as a success factor  
- 📊 Use **data-driven decision making** when planning film investments  
