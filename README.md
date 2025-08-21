# LOANS-AND-E-COMMERCE-ANALYSIS

## 📑 TABLE OF CONTENTS  

- [OVERVIEW](#overview)  
- [DATA SOURCE](#data-source)  
- [DATA PROCESSING](#data-processing)  
- [SKILLS DEMONSTRATED](#skills-demonstrated)  
- [OBJECTIVES/PROBLEM STATEMENT](#objectivesproblem-statement)  
- [DATA ANALYSIS AND VISUALIZATION](#data-analysis-and-visualization)  
- [INSIGHTS](#insights)  
- [RECOMMENDATIONS](#recommendations)  

## OVERVIEW
Xente is a Ugandan e-commerce and financial services company that provides a platform for individuals and organizations to make and receive payments, shop and pay for goods and services online, and access loans and credit facilities.
This project seeks to improve the efficiency, profitability, and sustainability of Xente's services, especially loan products. It analyzes loan performance to uncover repayment patterns, default risks, and customer behavior, identifies key trends across Xente’s services, and generates actionable insights to improve loan recovery and support data-driven decision making. 

## DATA SOURCE
Blossom Academy, final project

## TOOLS
Microsoft Power Query – Utilized for data cleaning, transformation, and structuring to prepare the dataset for analysis.

Microsoft Power BI – Employed for exploratory data analysis (EDA) and to create visualizations

## DATA PROCESSING

Duplicate Check – Verified the dataset contained no duplicate records, ensuring data integrity.

Handling Missing Values – Identified and removed 2 null entries in the ID column to maintain consistency and accuracy.

Data Type Optimization – Converted columns to their appropriate data types (e.g., dates, numerical values, categorical fields) to enable accurate analysis and efficient processing.

Feature Engineering (Loan Classification) – Created a new categorical feature to classify loans into Basic, Premium, and Platinum, based on loan amount thresholds, for deeper insights into customer segments and repayment behavior.

Data Validation – Conducted preliminary checks to confirm data consistency, eg, no negative loan values, valid date ranges, and reasonable loan amounts.

## SKILLS DEMONSTRATED
Data Cleaning and Preparation – handling missing values, correcting inconsistencies, and ensuring data quality for accurate analysis.

Exploratory Data Analysis (EDA) – using descriptive statistics and visualizations to uncover trends, patterns, and anomalies in Xente’s financial and transactional data.

Business and Domain Understanding – framing the analysis around fintech challenges (loan performance, repayments, customer behavior) and aligning insights with Xente’s business model.

Data Visualization – building clear, insightful charts and dashboards to communicate findings effectively.

Insight Generation and Storytelling – translating raw data into meaningful business insights and actionable recommendations for reducing defaults and improving services.

Problem-Solving and Critical Thinking – identifying inefficiencies and proposing solutions to optimize financial services.

## OBJECTIVES/PROBLEM STATEMENT

Understand revenue streams across Xente’s e-commerce products to see which ones drive growth and which ones underperform.

Assess loan performance by looking at repayment trends and default patterns to gauge financial risk.

Break down loans into categories (basic, premium, platinum) to compare repayment behavior across different loan sizes.

Examine customer contributions to revenue to identify reliance on key clients.

Explore connections between loan activity and product usage, such as how retail services may be linked to loan defaults.


## DATA ANALYSIS AND VISUALIZATION

<img width="593" height="334" alt="Screenshot 2025-08-20 110712" src="https://github.com/user-attachments/assets/b7725139-32d4-465c-9ff4-8d3af8cf631f" />


Xente offers 7 e-commerce products to a customer base of 239 and generates 77.45M UGX 

Retail dominates with 70.12M UGX (90% of revenue), while other products (airtime, utility bills, data bundles, TV, movies, financial services) contribute minimally.

Airtime is the most frequently purchased service (922 purchases) but generates only 4.26M UGX, showing low unit price but high volume.

Retail has fewer purchases (237) but generates disproportionately high revenue, indicating high-value transactions.

Revenue is heavily skewed. The Top 5 customers contribute 28% (25M UGX) of total revenue, with one customer (ID 305) alone contributing 10M UGX (13%).

Retail accounts for 85.96% of loan defaults, suggesting a strong link between retail purchases and loan repayment struggles.



<img width="665" height="371" alt="Screenshot 2025-08-08 211940" src="https://github.com/user-attachments/assets/719595b7-abee-44d4-b3e2-eb5449cb87d9" />

Over a 6-month period, Xente issued 1,483 loans, generating an income of 17.58M UGX. However, 178 of these loans defaulted, leading to a financial loss of 3.25M UGX.

Xente Loans were classified under "Basic", "Premium", and "Platinum". 

Basic loans - less than 10,000

Premium loans - between 10,000 and 50,000

Platinum loans - more than 50,000

From the distributions, about 74% of loan takers fall in the basic category, and 96% of these borrowers repay their debt, showing a good performance for basic loans. Defaulters are usually found in the premium and platinum categories, indicating the likelihood of inaccurate/insufficient credit worthiness and behaviour analysis checks in the loan process.

A steady increase in loan activity over the months indicates a regular expansion in customer base, with an unusual peak in the month of February.

A correlation is observed between loan defaulters and retail services, implying that at least half of retail services users default on their loans. 

## INSIGHTS
#### Revenue Concentration in Retail

Retail dominates Xente’s e-commerce portfolio, contributing 90% of total revenue (70.12M UGX) despite only 237 purchases.

Other products (airtime, utility bills, data bundles, TV, movies, financial services) generate minimal revenue, highlighting low product diversification.

Retail transactions are high-value but low-frequency, while airtime is low-value but high-volume (922 purchases, 4.26M UGX).

#### Revenue Dependency on a Few Customers

Revenue is heavily skewed, with the top 5 customers contributing 28% (25M UGX), and one customer (ID 305) alone contributing 13% (10M UGX).This concentration exposes Xente to revenue risk if key customers churn.

#### Loan Portfolio Performance

In 6 months, Xente issued 1,483 loans, earning 17.58M UGX, but 178 defaults caused a 3.25M UGX loss, which is 18% of loan income.

Loans in the basic category have a strong repayment rate of 96%.

Defaults are concentrated in Premium (10K–50K) and Platinum (>50K) loans, suggesting weaknesses in creditworthiness assessment for higher-value loans.

#### Loans & Retail Linkage

A strong correlation exists between loan defaults and retail services, with 85.96% of defaults tied to retail purchases. This suggests that customers relying on credit for retail transactions may face repayment struggles, increasing credit risk.

## RECOMMENDATIONS

Diversify Revenue Streams: Promote airtime, data bundles, and utility payments with bundles or discounts to reduce over-dependence on retail.

Customer Segmentation: Analyze high-value vs. frequent low-value customers to tailor marketing (e.g., loyalty programs for airtime buyers, premium offers for retail buyers).

Risk Management: Monitor retail-related loans more closely, possibly setting stricter credit checks or lower loan limits for retail purchases.

Cross-Selling: Encourage airtime/data customers to explore retail through promotions tied to frequent services.

Refocus Loan Strategy: Scale back or restructure Premium loans (tighter eligibility, smaller loan caps, higher interest buffer). Promote Basic loans, which have high repayment reliability.

Strengthen Credit Risk Management: Introduce credit scoring models using customer transaction history and set stricter controls on retail-related loans to reduce default risks.

Customer Education: Offer financial literacy programs to customers, especially around loan use for retail consumption.
