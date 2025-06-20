# Superstore Sales Data Analysis

## Project Overview
This project is an Exploratory Data Analysis (EDA) of the popular Superstore dataset. The goal of this analysis is to identify key trends, discover top-performing products and categories, and uncover actionable business insights to improve sales efficiency and profitability.

**Dataset:** [Superstore Sales Dataset on Kaggle](https://www.kaggle.com/datasets/safalpreeth/super-store-dataset)

---

## Analysis Performed
In this project, I sought to answer several key business questions:
1.  **Which Products Are the Most Profitable?** - Analyzing profit by product sub-category to identify which products are the biggest drivers of profit and which are underperforming or causing losses.
2.  **Which Products Are the Best Sellers?** - Analyzing sales quantity by sub-category to determine which products are most popular among customers.
3.  **Which Cities Have the Highest Sales?** - Identifying the top 10 cities by total sales to uncover potential geographic focus areas for marketing.
4.  **What Are the Sales Trends Over Time?** - Analyzing monthly sales data to understand seasonal patterns and long-term growth trends.

---

## Key Findings & Recommendations
* **Finding 1 (Profitability):** Products in the `Copiers` and `Phones` sub-categories are highly profitable. Conversely, `Tables` and `Bookcases` consistently result in financial losses.
    * **Recommendation:** The company could increase promotional efforts for high-profit items. A re-evaluation of the pricing and discount strategy for unprofitable products is necessary.

* **Finding 2 (Sales Trends):** There is a significant sales peak at the end of the year, particularly in September, November, and December.
    * **Recommendation:** The marketing and inventory management teams should prepare for this high demand by planning targeted campaigns and increasing stock for the fourth quarter (Q4).

---

## Key Visualizations


**1. Total Profit by Product Sub-Category**
![Question1](images/Question1.png)

**2. Total Units Sold by Product Sub-Category**
![Question2](images/Question2.png)

**3. Top 10 Cities by Total Sales**
![Question3](images/Question3.png)

**4. Monthly Sales Trend (2014-2017)**
![Question4](images/Question4.png)

---

## Tech Stack
* **Python**
* **Pandas** (for data cleaning and manipulation)
* **Matplotlib** & **Seaborn** (for data visualization)
* **Google Colab** (as the work environment)

---

## How to Run This Project
1.  Ensure you have Python and the libraries listed above installed.
2.  Clone or download this repository.
3.  Open the `.ipynb` file (e.g., `analisis_superstore.ipynb`) in Jupyter Notebook or Google Colab.
4.  Make sure the dataset file `superstore.csv` is in the same directory as the notebook.
5.  Run the code cells sequentially from top to bottom.
