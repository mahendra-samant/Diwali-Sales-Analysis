# Diwali Sales Analysis

An exploratory data analysis project focused on understanding customer purchasing behaviour, sales performance, and product trends during the Diwali sales period.

The analysis uses Python and the Pandas, NumPy, Matplotlib, and Seaborn libraries to transform raw transactional data into meaningful business insights.

---

## Project Overview

Understanding customer behaviour is important for improving product targeting, inventory planning, and sales strategies.

This project analyzes Diwali sales data to identify:

- High-performing customer segments
- Revenue and order patterns
- Geographic sales performance
- Customer demographics
- Occupation-wise purchasing behaviour
- Product category performance
- High-value products
- Relationships between customer and sales variables

The goal is not only to visualize the data, but to translate the analysis into **actionable business insights**.

---

## Business Questions

The analysis focuses on questions such as:

1. Which customer segments contribute the most to sales?
2. Which age groups generate the highest revenue?
3. How does purchasing behaviour differ between male and female customers?
4. Which states contribute the most to revenue and orders?
5. Which occupations generate the highest sales?
6. Which product categories perform best?
7. Which products contribute significantly to revenue?
8. Which customer segments should receive greater marketing attention?
9. Are revenue and order volume driven by the same customer segments?
10. What business opportunities can be identified from the data?

---

## Dataset

The project uses the **Diwali Sales Data** dataset containing customer, demographic, geographic, and transaction-level information.

### Main Attributes

| Column | Description |
|---|---|
| User_ID | Unique customer identifier |
| Cust_name | Customer name |
| Product_ID | Product identifier |
| Gender | Customer gender |
| Age | Customer age |
| Age Group | Customer age segment |
| Marital_Status | Marital status |
| State | Customer's state |
| Zone | Geographic zone |
| Occupation | Customer occupation |
| Product_Category | Product category |
| Orders | Number of orders |
| Amount | Transaction amount |

The dataset is stored in:

```text
data/Diwali Sales Data.csv
```

---

## Tools & Technologies

- **Python**
- **Pandas** — data manipulation and analysis
- **NumPy** — numerical analysis
- **Matplotlib** — data visualization
- **Seaborn** — statistical visualization
- **Jupyter Notebook** — interactive analysis environment

---

## Analysis Workflow

The project follows a structured data-analysis workflow.

### 1. Data Understanding

- Loaded the raw sales dataset
- Examined dataset dimensions
- Reviewed data types
- Inspected sample records
- Identified relevant analytical variables

### 2. Data Cleaning

The dataset was prepared for analysis by:

- Removing irrelevant columns
- Identifying missing values
- Handling incomplete transaction records
- Checking duplicate records
- Correcting data types
- Standardizing categorical values where required

### 3. Exploratory Data Analysis

The analysis investigates multiple dimensions of sales performance:

#### Customer Demographics

- Gender distribution
- Age-group distribution
- Age and gender combinations
- Marital-status distribution

#### Geographic Analysis

- State-wise revenue
- State-wise order volume
- Zone-level performance
- Comparison of high-performing regions

#### Customer Occupation

- Occupation-wise revenue
- Order contribution by occupation
- Gender and occupation patterns

#### Product Performance

- Product-category revenue
- Product-category order volume
- Top-performing products
- Revenue concentration among products

#### Customer Analysis

- Customer-level purchase contribution
- High-value customers
- Customer purchasing patterns

### 4. Statistical Analysis

Numerical variables are also examined using correlation analysis to understand relationships between variables such as:

- Age
- Orders
- Amount

---

## Key Performance Indicators

The notebook includes an executive-level summary of important sales metrics, including:

- Total Revenue
- Total Orders
- Average Order Value
- Unique Customers
- Number of Product Categories
- Geographic Coverage

These metrics provide a high-level overview before moving into detailed analysis.

---

## Key Insights

The analysis identifies several important patterns in the Diwali sales data, including:

- Differences in purchasing behaviour across customer demographics
- Strong revenue contribution from specific age groups
- Variation in revenue and order volume across states
- Significant contribution from particular occupational groups
- Uneven performance across product categories
- Concentration of revenue among selected products and customer segments

The notebook provides detailed visualizations and supporting analysis for each finding rather than relying only on aggregate conclusions.

---

## Business Recommendations

Based on the analysis, potential business actions include:

### 1. Target High-Value Customer Segments

Focus marketing campaigns on customer segments that demonstrate strong revenue contribution and purchasing activity.

### 2. Strengthen Regional Marketing

Prioritize high-performing states and regions while investigating opportunities to improve performance in lower-contributing markets.

### 3. Optimize Product Promotion

Increase visibility and promotional activity for high-performing product categories while evaluating underperforming categories for pricing, positioning, or inventory decisions.

### 4. Use Occupation-Based Segmentation

Customer occupation can be used as an additional segmentation variable for targeted campaigns and personalized offers.

### 5. Improve Inventory Planning

Historical product and category performance can support better inventory allocation during high-demand sales periods.

---

## Project Structure

```text
Diwali-Sales-Analysis/
│
├── data/
│   └── Diwali Sales Data.csv
│
├── Diwali_Sales_Analysis.ipynb
│
├── README.md
│
└── .gitignore
```

### File Description

| File | Description |
|---|---|
| `data/Diwali Sales Data.csv` | Raw dataset used for analysis |
| `Diwali_Sales_Analysis.ipynb` | Complete data cleaning, analysis, visualization, and insights |
| `README.md` | Project documentation |
| `.gitignore` | Prevents temporary and unnecessary files from being committed |

---

## How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/Diwali-Sales-Analysis.git
```

### 2. Navigate to the project

```bash
cd Diwali-Sales-Analysis
```

### 3. Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 4. Start Jupyter Notebook

```bash
jupyter notebook
```

### 5. Open the notebook

Open:

```text
Diwali_Sales_Analysis.ipynb
```

Make sure the dataset remains at:

```text
data/Diwali Sales Data.csv
```

before running the notebook.

---

## Reproducibility

The analysis is designed to run from the project directory using the included dataset.

The notebook reads the dataset using a relative path, allowing the project to be cloned and executed on another system without changing local file paths.

---

## Limitations

This analysis is based on the available Diwali sales dataset and should be interpreted within the scope of the data.

Some limitations include:

- The dataset represents a specific sales period rather than a complete year.
- Customer behaviour outside the available period is not represented.
- The analysis identifies relationships and patterns but does not establish causal relationships.
- Demographic findings should be interpreted as observations from the dataset rather than general population behaviour.
- Additional business variables such as marketing spend, discounts, inventory levels, profit margins, and customer acquisition cost are not available.

---

## Future Improvements

Possible extensions to this project include:

- Building an interactive Power BI dashboard
- Adding profit and margin analysis if financial data becomes available
- Creating customer segmentation using clustering techniques
- Developing customer lifetime value analysis
- Performing predictive sales analysis
- Adding time-series analysis with transaction dates
- Building an automated reporting pipeline
- Connecting the analysis to a live database
- Creating an interactive Streamlit dashboard

---

## Conclusion

This project demonstrates a complete exploratory data-analysis workflow, from raw data preparation and quality checks to statistical exploration, visualization, business interpretation, and recommendations.

The analysis highlights how customer demographics, geography, occupation, and product characteristics can be examined together to understand sales performance and identify opportunities for more targeted business decisions.

---

## Author

**Mahendra**

GitHub: `https://github.com/mahendra-samant`

---

## License

This project is intended for educational and portfolio purposes.