# Instacart Marketing Analysis
## Project Overview: This project delivers a comprehensive Marketing Analysis using a structured, end-to-end analytics workflow. The analysis evaluates customer engagement, campaign performance, retention behavior, and regional trends to identify actionable opportunities for improving marketing ROI and operational decision-making.

![download](https://github.com/bazi-imran/Python-Instacart-Analysis/assets/160747644/16dea413-270e-44ea-8c4e-5a0eb7f4fbef)

Instacart, an online grocery store app, seeks to enhance its understanding of sales patterns through exploratory data analysis. With a focus on customer segmentation and purchasing behaviors, the goal is to inform targeted marketing strategies for continued growth and optimization.

Using a combination of data wrangling, validation checks, derived marketing indicators, and visualizations, this project provides a complete, insight-driven interpretation of customer behavior across multiple segments.

## Project Objectives: 
- Clean, validate, and standardize raw marketing activity data 
- Build derived features to segment customers by loyalty, spending, and frequency
- Visualize marketing performance trends across product categories and customer groups
- Identify high-value customer segments for targeted engagement
- Provide strategic recommendations based on observed patterns

## Key Business Questions: 
#### Customer Timing & Behavior: 
- What are the busiest days of the week and hours of the day?
- At what times of day do customers spend the most money?
#### Product Strategy:
- How can product prices be grouped into simpler ranges to guide targeted promotions?
- Which product types or departments are the most popular?
#### Customer Segments:
- How is customer loyalty distributed?
- Do ordering habits vary by loyalty status?
- Are there behavioral differences across customer regions?
- Is there a connection between age, income, and family status?
- What demographic classifications naturally emerge?
- How do ordering habits differ across customer profiles?

## Data Preparation & Quality Checks
#### Population Flow: 
A step-by-step mapping of how raw datasets were merged and filtered to produce a clean analytical dataset.
This included:
- Removing incomplete records
- Standardizing formats (dates, categorical fields)
- Verifying record counts after each transformation
- Ensuring customer and order IDs matched across tables
<img width="1092" height="375" alt="Screenshot 2025-11-21 at 11 03 58 AM" src="https://github.com/user-attachments/assets/0ec7b22e-b47a-4556-9937-5c4004bbd621" />

#### Consistency Checks:
To protect data integrity, several validation checks were applied:
- Duplicate customer and order ID detection
- Consistency between order counts and customer activity
- Outlier checks for unusually high/low spending
- Logical validation of date fields and age ranges

These checks ensured that the final dataset was reliable for downstream analysis.




## Tools
This analysis was performed using:

#### Programming & Analytics:
- Python
  - Pandas – Data cleaning and analysis
  - NumPy – Calculations and transformations
  - Matplotlib – Visualizations
  - Seaborn – Statistical plotting
  - SciPy – Mathematical/statistical functions

#### Documentation & Reporting: 
- Excel
- Jupyter Notebook
- Visualization exports

### Datasets: 
- orders
- products
- departments
- orders_products
- customers

The Data dictionary can be accesed [here.](https://github.com/bazi-imran/Python-Instacart-Analysis/blob/main/01%20Project%20Management/Data%20Dictionary.pdf)

## Repository Structure
The project files are divided between the following folders:

- Project Management: Project Brief & Data Dictionary.
- Data: Separated into two subfolders Original and Prepared Data.
  - These contain the original data frames and the data frames after they have been cleaned and prepared for analysis respectively. (Data files not uploaded to GitHub due to size.)
- Scripts: The Jupyter notebooks containing the coding for the analysis.
- Analysis: Separated into two subfolders Reports and Visualizations. The Reports subfolder contains crosstabs and the Visualizations subfolder contains the visualizations used for developing and explaining insights.
- Sent to Client: The final report presented in Excel
