# Retail Sales Demographic Analysis

## Project Overview
This project explores how **customer age and gender influence spending patterns across different product categories** in a retail environment. Using a Kaggle retail dataset, the analysis applies descriptive analytics techniques to uncover trends and insights that can support business decision-making.

---

## Objectives of this project
- Analyze how spending varies across different **age groups**
- Compare purchasing behavior between **male and female customers**
- Identify the most popular **product categories**
- Discover patterns that can help improve **targeted marketing strategies**

---

## Analysis Questions
- **How do customer age and gender influence spending patterns across retail product categories?**
- **Which product categories show the most significant differences in spending between male and female customers across various age groups?**
- **What spending trends can be observed among different age groups within each product category?**

## Benefit from the Analysis Questions
- This helps the marketing team to create targeted advertisements. for example if the data shows that men aged 25-30 spend most on Electronics, the company can allocate more of its budget on social media ads for specific group"
- Also helps businesses create products for specific age groups

## Challenges during the project
- During loading data from excel to Tableau, the price per unit and total spending columns were read as String while they are number
- **How was fixed**
- The file in excel was saved as *csv* file resulting to covert numeric data to TEXT
- Therefore, i changed and saved the file as *xlsx* and the value were read as numeric.
---

## Dataset
- Source: Kaggle Retail Sales Dataset  
- Features include:
  -Customer Demographics: age and gender
  -Product information: product category
  -Sales metrics: quantity and price per quantity

*https://www.kaggle.com/code/ahmdayman/retail-sales-dataset*

---

## Tools & Technologies
In this project, i used the following tools
- Microsoft Excel for Data Cleaning & Pivot Tables
- Tableau for Data Visualization
- GitHub for Project Hosting

---

## Analysis Process

### 1. Data Cleaning
- Added missing dollar sign to price per unit and total spending columns  
- Standardized age groups and categories  

### 2. Data Transformation
- Grouped customers into:
  - Youth (<25)
  - Adults (25–45)
  - Seniors (>45)

### 3. Data Analysis
- Compared spending by:
  - Age group
  - Gender
  - Product category  

### 4. Visualization
- Horizontal Bar charts for category spending
- Heatmaps for product category vs age group spending
- Highlight table for product category vs gender spending
- Side by side bar chart for gender vs product category
- Dashboard summaries  

---

##  Key Insights
- Younger customers tend to spend more on **beauty products**, Adults spend more on **Clothing products** and Senior customers spend more on **Electronic products**
- Female customers show higher spending in **clothing categories**
- Adult customers contribute the highest **overall spending**
- Certain product categories perform better with specific demographic groups
- Electronics Product category contibute the highest **overall spending**

---

##  Dashboard Preview
*<img width="933" height="486" alt="image" src="https://github.com/user-attachments/assets/1b129e12-569b-4452-898c-2fd28d08d005" />
*
*<img width="916" height="285" alt="image" src="https://github.com/user-attachments/assets/e4044a02-45eb-4b28-88a4-881094239fc0" />
*

---

##  Live Demo
 *[A link to Tableau](https://public.tableau.com/views/RetailSalesAnalysis_17773852582870/RetailSalesAnalysis?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)*
 
---

##  How to Use This Project
1. Download the dataset or clone this repository  
2. Open the dataset in Excel / Tableau  
3. Explore the dashboard or recreate the analysis  
4. Modify visualizations to gain additional insights  

---

##  Recommendations
- Retailers should target **specific age groups** with tailored promotions  
- Marketing campaigns should consider **gender-based preferences**  
- Focus on high-performing categories to maximize revenue  

---

##  Future Improvements
- Include more demographic factors (income, location)  
- Apply predictive analytics  
- Automate dashboard updates  

---

##  Author
**Deus Masanja**  

---

##  Acknowledgements
- Kaggle for providing the dataset  
- Open-source tools for analysis and visualization  

