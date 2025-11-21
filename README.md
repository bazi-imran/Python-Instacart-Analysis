# Instacart Marketing Analysis
## Project Backgroud: This project delivers a comprehensive Marketing Analysis with an aim to better understand customer purchasing behavior, peak shopping windows, and high-value customer segments to improve marketing ROI.

![download](https://github.com/bazi-imran/Python-Instacart-Analysis/assets/160747644/16dea413-270e-44ea-8c4e-5a0eb7f4fbef)

Instacart, an online grocery store app, seeks to enhance its understanding of sales patterns through exploratory data analysis. With a focus on customer segmentation and purchasing behaviors, the goal is to inform targeted marketing strategies for continued growth and optimization.

I conducted an exploratory analysis to uncover when people shop, what they buy, and which customer groups drive revenue, using real-world business framing and actionable recommendations.

## Executive Summary: 
This analysis reveals clear patterns in Instacart’s customer behavior that directly support marketing strategy, product prioritization, and loyalty growth:
- Weekend traffic surges create costly ad competition, while Tues/Wed mornings and late afternoons offer high-value, low-traffic ad windows.
- Mid-range products dominate engagement, but both low and high-price items still account for 37% of orders and deserve balanced campaigns.
- Just a few departments — Produce, Dairy & Eggs, Snacks, Beverages, Frozen — drive the majority of sales.
- Regular customers (51%) outnumber loyal customers (33.2%), revealing a major opportunity to increase retention.
- Demographics and regions display distinct shopping patterns that support more tailored targeting.
- Below are visuals and insights that summarize the business problems Instacart needs to solve — and how this analysis supports those solutions.

## Data Preparation & Quality Checks
#### Population Flow: 
A step-by-step mapping of how raw datasets were merged and filtered to produce a clean analytical dataset.
This included:
- Removing incomplete records
- Standardizing formats (dates, categorical fields)
- Verifying record counts after each transformation
- Ensuring customer and order IDs matched across tables
<img width="1392" height="575" alt="Screenshot 2025-11-21 at 11 03 58 AM" src="https://github.com/user-attachments/assets/0ec7b22e-b47a-4556-9937-5c4004bbd621" />

#### Consistency Checks:
To protect data integrity, several validation checks were applied:
- Duplicate customer and order ID detection
- Consistency between order counts and customer activity
- Outlier checks for unusually high/low spending
- Logical validation of date fields and age ranges

These checks ensured that the final dataset was reliable for downstream analysis.

## Key Insights: 

#### Optimize Ad Timing Around Traffic Patterns
Weekend orders peak on Saturdays and Sundays between 9 a.m.–4 p.m., so ads should be prioritized during low-traffic periods like Tuesdays and Wednesdays before 9 a.m. and after 4 p.m.

<img width="739" height="256" alt="Screenshot 2025-11-21 at 12 49 17 PM" src="https://github.com/user-attachments/assets/e90f390a-c9ca-4890-be2d-c9f12a6a2114" />

#### Mid-Range Products Lead Overall Engagement
Mid-range items make up 61% of inventory and should be the primary marketing focus, while low- and high-range products still account for 37% of orders and require balanced targeting.
#### A Few Departments Drive Most Demand
Produce and Dairy & Eggs dominate with 42% and 24% of all orders, making them top priorities alongside Snacks, Beverages, and Frozen for targeted promotions.

<img width="500" alt="Screenshot 2025-11-21 at 12 55 40 PM" src="https://github.com/user-attachments/assets/ef1565cb-c566-46c6-9f2e-aedc24b79d4c" />

#### Converting Regular Customers Into Loyal Ones Is a Major Opportunity
With regular customers at 51% and loyal customers at 33.2%, loyalty programs, delivery perks, and personalized offers can significantly expand the loyal customer base.
#### Engagement Strategies Should Match Order Frequency
Frequent loyal customers need personalized incentives, while less active customers benefit more from targeted re-engagement campaigns and regular customers should be encouraged into loyalty tiers.
#### Regional Patterns Require Tailored Marketing
Regional strategies should address cultural differences in the Northeast, Midwest, and West, while the South should maintain strong performance and focus ads during peak responsiveness from 5 a.m.–10 a.m.

<img width="739" height="256" alt="Screenshot 2025-11-21 at 12 52 38 PM" src="https://github.com/user-attachments/assets/5f6433ca-ebbf-4bd8-92be-eb343af30f59" />

#### Demographic Segments Have Distinct Marketing Needs
Marketing should focus on married adults and seniors, while offering tailored campaigns for young adults, dependents, and single or widowed customers to increase relevance and satisfaction.
#### Age and Income Strongly Influence Buying Behavior
High-income customers over 40 respond well to premium offerings, while customers earning under 200k across age groups engage more with savings-focused promotions.

<img width="500" alt="Screenshot 2025-11-21 at 12 55 08 PM" src="https://github.com/user-attachments/assets/2ac9f122-8012-4fa4-a310-701119dcae78" />

#### Households With Dependents Generate the Most Sales
Middle- and high-income customers with dependents drive frequent orders and respond well to bulk deals and reward programs, while high-income young adults without dependents require targeted lifestyle-oriented marketing.

## Tools Used: 

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

## Datasets: 
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

## Contact
Feel free to contact me on [LinkedIn](https://www.linkedin.com/in/bazilla-imran-aa5ab0237/)!
