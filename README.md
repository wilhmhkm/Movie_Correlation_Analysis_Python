# 🎬 Movie Correlation Analysis

## 📌 Executive Summary
 
In this project, I analyze a movie industry dataset to uncover the key factors that drive box office success. I use Python to explore relationships between variables such as budget, votes, and revenue.  

From the analysis, I find that **budget and audience engagement (votes)** are the strongest predictors of gross revenue, while factors like company show minimal impact.

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

I start by downloading the movie dataset from Kaggle and loading it into Python using `pandas.read_csv()`.  

I then explore the data by checking the first few rows with `.head()`, reviewing data types using `.dtypes`, and identifying missing values through loops and `isnull()`.  

Next, I clean the dataset by converting key columns like budget and gross into integers, creating a corrected year column from the release date, sorting the data by gross revenue, removing duplicates, and standardizing the overall structure for analysis.  

After that, I perform feature engineering by converting categorical variables such as company and genre into numeric format using category encoding.  

For the exploratory analysis, I build scatter plots to examine the relationship between budget and revenue, apply regression plots to identify trends, and generate a correlation matrix using the Pearson method.  

Finally, I create heatmaps to visualize the correlations clearly and highlight the strength of relationships between variables.

---

## 📊 Key Insights

From the analysis, I observe that **budget and gross revenue** have a strong positive correlation of around 0.71, indicating that higher investment generally leads to higher returns.  

I also find that **votes and gross revenue** show a significant relationship, suggesting that audience engagement plays a key role in a movie’s success.  

On the other hand, **company and gross revenue** have a weak correlation, meaning that the production company alone does not strongly determine performance.  

Other features like runtime show only minimal to moderate influence on revenue.

---

## 💡 Recommendations
 
Based on these insights, I focus on several key takeaways. I emphasize the importance of **strategic budget allocation** to maximize returns. I also prioritize **audience engagement and marketing efforts** to drive visibility and increase votes.  

At the same time, I avoid over-relying on production company reputation as a success factor, and instead advocate for **data-driven decision making** when planning film investments.
