# 🛍️ Customer Shopping Behavior Analysis

An end-to-end **Exploratory Data Analysis (EDA)** project exploring customer shopping behavior — uncovering purchasing patterns, customer preferences, and providing data-driven business recommendations.

## 📌 Objective

Analyze customer shopping behavior using EDA techniques to:
- Clean and understand the dataset
- Explore purchasing patterns through univariate, bivariate, and multivariate analysis
- Extract meaningful insights about customer preferences
- Provide actionable business recommendations

## 📂 Dataset

The dataset contains information about customers, their purchases, preferences, and shopping habits, including:
- Demographics (Age, Gender)
- Purchase details (Category, Purchase Amount, Payment Method)
- Customer behavior (Subscription Status, Previous Purchases, Frequency of Purchases, Review Rating)
- Seasonal information

## 🛠️ Tools & Technologies

- **Python**
- **Pandas** – data manipulation and cleaning
- **Matplotlib** & **Seaborn** – data visualization
- **Jupyter Notebook**

## 🔍 Project Workflow

### 1. Data Understanding & Cleaning
- Loaded and inspected the dataset (shape, data types, statistical summary)
- Checked for missing values and duplicates
- Verified unique values across categorical columns
- Removed non-analytical columns (e.g., Customer ID)
- Checked for outliers using boxplots

### 2. Exploratory Data Analysis (EDA)

**Univariate Analysis**
- Age distribution
- Most common product categories
- Purchase amount distribution
- Most common payment methods
- Subscription status distribution

**Bivariate Analysis**
- Gender vs. product category purchases
- Product categories vs. purchase amount
- Subscription status vs. spending
- Review rating vs. purchase amount
- Season vs. purchasing behavior

**Multivariate Analysis**
- Correlation matrix between numerical features
- Customer characteristics vs. purchasing behavior (pairplot)
- Demographic patterns vs. spending

### 3. Data Storytelling & Insights

## 💡 Key Insights

- Customer ages are nearly uniformly distributed between **18–70**, reflecting a broad and diverse customer base.
- **Clothing** is the top-performing category, followed by Accessories, while Outerwear has the smallest share.
- Average purchase amount remains remarkably stable at **~$60** across all categories, genders, seasons, and subscription statuses.
- Male customers account for roughly double the number of purchases compared to female customers across all categories.
- Subscription status has **no significant impact** on spending (subscribers: $59.49 vs. non-subscribers: $59.87).
- Review ratings show a **negligible correlation** (~0.03) with purchase amount.
- No demographic factor (age, gender, subscription, season) shows a meaningful correlation with spending — the strongest pairwise correlation in the whole dataset is only 0.04 (Age vs. Previous Purchases).

## 📊 Conclusion

Customer spending patterns remain highly consistent across demographic groups, product categories, and seasons. Clothing is the most frequently purchased category, while purchase amounts remain relatively stable regardless of customer characteristics. This suggests that **broad-based marketing strategies** and **consistent, demographic-agnostic inventory planning** may be more effective than narrow, targeted approaches.

## 🚀 Recommendations

- Deploy broad-scale marketing rather than niche demographic targeting
- Maintain the ~$60 pricing sweet spot across categories
- Keep inventory levels stable year-round rather than adjusting heavily by season

## 📁 Repository Contents

```
├── Customer Shopping Behavior Analysis.ipynb               # Main Jupyter notebook with full EDA
├── shopping_behavior_updated.csv                           # Dataset used in the analysis
└── README.md                                               # Project documentation
```

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/AlaaSoudy/Customer-Shopping-Behavior-Analysis.git
   ```
2. Install the required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
3. Open and run `analysis.ipynb` in Jupyter Notebook / JupyterLab.

## 👤 Author

**Alaa Soudy**
[GitHub](https://github.com/AlaaSoudy)
