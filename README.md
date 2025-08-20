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

Airtime was the most frequently purchased product on the Xente App, making fairly good sales of about UGX 4M, however retail outperformed it with total sales of 70.12M. This is expected because retail services are generally pricier than airtime services. 
For Xente, majority of it's e-commerce sales come from retail, a good signal that the market has great potential to be explored. On the otherhand, services such as payment of utility bills, movie subscriptions, etc, which are not yet popular among users should be given marketing focus.


<img width="665" height="371" alt="Screenshot 2025-08-08 211940" src="https://github.com/user-attachments/assets/719595b7-abee-44d4-b3e2-eb5449cb87d9" />

Xente Loans were classified under "Basic", "Premium", and "Platinum". 

Basic loans - less than 10,000

Premium loans - between 10,000 and 50,000

Platinum loans - more than 50,000

From the distributions, about 74% of loan takers fall in the basic category, and 96% of these borrowers repay their debt, showing a good performance for basic loans. Defaulters are usually found in the premium and platinum categories, indicating the likelihood of inaccurate/insufficient credit worthiness and behaviour analysis checks in the loan process.

A steady increase in loan activity over the months indicates a regular expansion in customer base. Further investigation is to be made into the unusual peak in the month of February.

A correlation was spotted between loan defaulters and retail services, implying that at least half of retail services users default on their loans. This correlation will be further explored for deeper insights. 




