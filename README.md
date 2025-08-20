# LOANS-AND-E-COMMERCE-ANALYSIS

### OBJECTIVE
This project analyzes data from Xente, a Ugandan e-commerce and financial services company, to uncover trends across its offerings, with a particular emphasis on evaluating and enhancing loan performance.

### TOOLS
Data Cleaning & EDA - Jupyter Notebook
Visualization - Power BI

## Project Workflow
Source of Data - Kaggle

### Data cleaning 

-The dataset didn't contain any duplicates

-2 nulls in an ID column were identified and removed

-Columns were given the right data types 

### Data Analysis

<img width="593" height="334" alt="Screenshot 2025-08-20 110712" src="https://github.com/user-attachments/assets/b7725139-32d4-465c-9ff4-8d3af8cf631f" />

### Key Insights

#### Revenue Concentration:

Total Revenue: 77.45M UGX

Retail dominates with 70.12M UGX (~90% of revenue), while other products (airtime, utility bills, data bundles, TV, movies, financial services) contribute minimally.

Airtime is the most frequently purchased service (922 purchases) but generates only 4.26M UGX, showing low unit price but high volume.

Retail has fewer purchases (237) but generates disproportionately high revenue, indicating high-value transactions.

#### Customer Base:

Only 239 customers generated this revenue.

Revenue is heavily skewed: the Top 5 customers contribute ~28% (25M UGX) of total revenue, with one customer (ID 305) alone contributing 10M UGX (~13%).

#### Loan Default Link:

Retail accounts for 85.96% of loan defaults, suggesting a strong link between retail purchases and loan repayment struggles.


<img width="665" height="371" alt="Screenshot 2025-08-08 211940" src="https://github.com/user-attachments/assets/719595b7-abee-44d4-b3e2-eb5449cb87d9" />

Xente Loans were classified under "Basic", "Premium", and "Platinum". 

Basic loans - less than 10,000

Premium loans - between 10,000 and 50,000

Platinum loans - more than 50,000

From the distributions, about 74% of loan takers fall in the basic category, and 96% of these borrowers repay their debt, showing a good performance for basic loans. Defaulters are usually found in the premium and platinum categories, indicating the likelihood of inaccurate/insufficient credit worthiness and behaviour analysis checks in the loan process.

A steady increase in loan activity over the months indicates a regular expansion in customer base. Further investigation is to be made into the unusual peak in the month of February.

A correlation was spotted between loan defaulters and retail services, implying that at least half of retail services users default on their loans. This correlation will be further explored for deeper insights. 

### Areas to Probe

Why do Premium loans default at such high rates (39%)? Is it due to larger loan sizes, weaker credit assessments, or misuse of funds?

Why is retail linked so strongly to defaults? Are customers borrowing for consumption rather than income-generating activities?

Was the dip in March 2019 loans due to seasonality, tighter credit policies, or reduced customer demand?

### Recommendations

Diversify Revenue Streams: Promote airtime, data bundles, and utility payments (already high-volume categories) with bundles or discounts to reduce over-dependence on retail.

Customer Segmentation: Analyze high-value vs. frequent low-value customers to tailor marketing (e.g., loyalty programs for airtime buyers, premium offers for retail buyers).

Risk Management: Monitor retail-related loans more closely, possibly setting stricter credit checks or lower loan limits for retail purchases.

Cross-Selling: Encourage airtime/data customers to explore retail through promotions tied to frequent services.

Refocus Loan Strategy: Scale back or restructure Premium loans (tighter eligibility, smaller loan caps, higher interest buffer). Promote Basic loans, which have high repayment reliability.

Strengthen Credit Risk Management: Introduce credit scoring models using customer transaction history and set stricter controls on retail-related loans to reduce default risks.

Customer Education: Offer financial literacy programs to customers, especially around loan use for retail consumption.
