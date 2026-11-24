# Customer Sales Data Analysis

## 1. Project Aim

To analyse customer sales data to identify purchasing patterns and customer behaviour, and derive meaningful business insights through systematic data preprocessing, exploratory analysis and data visualization.

### Why I Chose This Project

I chose this project to explore how customer information and sales data can be transformed into meaningful business insights. This project belongs to the **Customer Relationship Management (CRM) and Sales Analytics** domain, focusing on customer demographics, purchasing behaviour, spending patterns and customer feedback to support better business decisions.

## 2. Tools and Techniques

### Tools and Libraries
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly (Express and Graph Objects)

### Techniques
- Data Inspection and Exploration
- Data Cleaning and Preprocessing
- Missing Value and Duplicate Handling
- Text Standardization
- Data Type Conversion
- Feature Engineering
- Outlier Detection and Handling
- Statistical Analysis
- Grouping and Aggregation
- Correlation Analysis
- Pivot Table Analysis
- Data Visualization

## 3. Project Pipeline / Workflow

| Workflow Stage | Activities Performed |
|---|---|
| **1. Data Loading and Initial Operations** | Loaded the Messy Customer Sales Dataset using Pandas. Examined the first and last records using `head()` and `tail()`. Checked dataset dimensions using `shape`, total elements using `size`, column information using `info()`, data types, unique values and statistical summaries using `describe()`. |
| **2. Data Cleaning and Preprocessing** | Created a working copy of the dataset; standardized text and corrected inconsistent entries; checked and handled missing/null values; removed unnecessary columns; converted columns into appropriate data types; identified and removed duplicate records; performed numerical, categorical and date-based feature engineering; detected and handled outliers using descriptive statistics, boxplots and the IQR method; performed filtering, sorting, grouping and aggregation; exported the cleaned dataset. |
| **3. Exploratory Data Analysis (EDA)** | **Without Visualization:** Performed univariate, bivariate and multivariate analysis; analysed numerical and categorical variables; conducted correlation analysis, pivot table analysis, grouping, aggregation, sorting and ranking to identify patterns and relationships. **With Visualization:** Created histograms, count plots, pie charts, bar charts, line charts, scatter plots, violin plots, bubble charts, stacked bar charts, swarm plots, treemaps, heatmaps and regression plots to analyse customer demographics, purchasing behaviour, customer segments, feedback and sales trends. |
| **4. Key Insights and Recommendations** | **Key Insights:** Identified city-wise customer and purchase patterns, gender distribution, spending segments, monthly and annual trends, customer feedback patterns, engagement levels and high-value customers. **Recommendations:** Implement city-specific marketing campaigns, personalized offers, loyalty incentives and targeted promotions; re-engage inactive customers; plan seasonal campaigns based on purchasing trends; and regularly monitor customer feedback to improve satisfaction and retention. |

## 4. Repository Structure

    Customer-Sales-Data-Analysis/
    │
    ├── data/
    │   ├── raw/
    │   │   └── messy_customer_sales_data.csv
    │   │
    │   └── processed/
    │       └── Clean_Customer_Sales_Data.csv
    │
    ├── instructions/
    │   └── Project_Instructions.pdf
    │
    ├── notebooks/
    │   └── Customer Sales data(9).ipynb
    │
    ├── presentations/
    │   └── Customer_Sales_Data_Analysis_Seminar_Presentation_Revised.pptx
    │
    └── README.md

## 5. What I Gained from This Project

Through this project, I gained practical, hands-on experience in working with messy datasets and understanding the complete data analytics workflow, from raw data loading to deriving meaningful business insights.

I developed my skills in:

- **Data Handling:** Loading, inspecting and understanding datasets using Pandas and NumPy.
- **Data Cleaning:** Identifying and handling missing values, duplicates, inconsistent text, incorrect data types and outliers.
- **Feature Engineering:** Creating meaningful numerical, categorical and date-based features to support deeper analysis.
- **Exploratory Data Analysis:** Performing univariate, bivariate and multivariate analysis to identify patterns, trends and relationships.
- **Statistical Analysis:** Applying descriptive statistics, correlation analysis, grouping, aggregation, pivot tables and ranking techniques.
- **Data Visualization:** Creating and interpreting different charts using Matplotlib, Seaborn and Plotly.
- **Business Understanding:** Translating analytical findings into meaningful insights and actionable business recommendations.

Overall, this project strengthened my Python-based data analytics skills and helped me understand how raw data can be transformed into structured information, meaningful insights and data-driven business decisions.
