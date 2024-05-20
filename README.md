
# Bank Loan Dashboard

### Dashboard Link : https://app.powerbi.com/view?r=eyJrIjoiNjdiZTg2YzctNTcxOS00YTJjLTg3ZmEtZjBjODFhNDNmYmZhIiwidCI6ImIzMzczYTViLWY5ZmEtNDcyNC1iMmE3LWFjZTFiYThjMThhMSJ9

## PROBLEM STATEMENT

### DASHBOARD 1: OVERVIEW
This dashboard is created in order to monitor and assess our bank's lending activities and performance, I need to create a comprehensive Bank Loan Report. This report aims to provide insights into key loan-related metrics and our changes over time. The report will help us make data-driven decisions, track their loan portfolio's health, and identify trends that can inform their lending strategies.


### Key Performance Indicators (KPIs) Requirements:

- Total Loan Applications: We need to calculate the total number of loan applications received during a specified period. Additionally, it is essential to monitor the Month-to-Date (MTD) Loan Applications and track changes Month-over-Month (MoM).
- Total Funded Amount: Understanding the total amount of funds disbursed as loans is crucial. We also want to keep an eye on the MTD Total Funded Amount and analyse the Month-over-Month (MoM) changes in this metric.
- Total Amount Received: Tracking the total amount received from borrowers is essential for assessing the bank's cash flow and loan repayment. We should analyse the Month-to-Date (MTD) Total Amount Received and observe the Month-over-Month (MoM) changes.
- Average Interest Rate: Calculating the average interest rate across all loans, MTD, and monitoring the Month-over-Month (MoM) variations in interest rates will provide insights into our lending portfolio's overall cost.
- Average Debt-to-Income Ratio (DTI): Evaluating the average DTI for our borrowers helps us gauge their financial health. We need to compute the average DTI for all loans, MTD, and track Month-over-Month (MoM) fluctuations.

### Good Loan v Bad Loan KPI’s
In order to evaluate the performance of their lending activities and assess the quality of their loan portfolio, I need to create a comprehensive report that distinguishes between 'Good Loans' and 'Bad Loans' based on specific loan status criteria.

#### Good Loan KPIs:
- Good Loan Application Percentage: We need to calculate the percentage of loan applications classified as 'Good Loans.' This category includes loans with a loan status of 'Fully Paid' and 'Current.'
- Good Loan Applications: Identifying the total number of loan applications falling under the 'Good Loan' category, which consists of loans with a loan status of 'Fully Paid' and 'Current.'
- Good Loan Funded Amount: Determining the total amount of funds disbursed as 'Good Loans.' This includes the principal amounts of loans with a loan status of 'Fully Paid' and 'Current.'
- Good Loan Total Received Amount: Tracking the total amount received from borrowers for 'Good Loans,' which encompasses all payments made on loans with a loan status of 'Fully Paid' and 'Current.'

#### Bad Loan KPIs:
- Bad Loan Application Percentage: Calculating the percentage of loan applications categorized as 'Bad Loans.' This category specifically includes loans with a loan status of 'Charged Off.'
- Bad Loan Applications: Identifying the total number of loan applications categorized as 'Bad Loans,' which consists of loans with a loan status of 'Charged Off.'
- Bad Loan Funded Amount: Determining the total amount of funds disbursed as 'Bad Loans.' This comprises the principal amounts of loans with a loan status of 'Charged Off.'
- Bad Loan Total Received Amount: Tracking the total amount received from borrowers for 'Bad Loans,' which includes all payments made on loans with a loan status of 'Charged Off.'

#### Loan Status Grid View
In order to gain a comprehensive overview of our lending operations and monitor the performance of loans, we aim to create a grid view report categorized by 'Loan Status.' This report will serve as a valuable tool for analysing and understanding the key indicators associated with different loan statuses. By providing insights into metrics such as 'Total Loan Applications,' 'Total Funded Amount,' 'Total Amount Received,' 'Month-to-Date (MTD) Funded Amount,' 'MTD Amount Received,' 'Average Interest Rate,' and 'Average Debt-to-Income Ratio (DTI),' this grid view will empower us to make data-driven decisions and assess the health of our loan portfolio.

### DASHBOARD 2: OVERVIEW

In our Bank Loan Report project, we aim to visually represent critical loan-related metrics and trends using a variety of chart types. These charts will provide a clear and insightful view of our lending operations, facilitating data-driven decision-making and enabling us to gain valuable insights into various loan parameters. Below are the specific chart requirements:

- Monthly Trends by Issue Date (Line Chart):
Chart Type: Line Chart

Metrics: 'Total Loan Applications,' 'Total Funded Amount,' and 'Total Amount Received'

X-Axis: Month (based on 'Issue Date')
Y-Axis: Metrics' Values

Objective: This line chart will showcase how 'Total Loan Applications,' 'Total Funded Amount,' and 'Total Amount Received' vary over time, allowing me to identify seasonality and long-term trends in lending activities.

- Regional Analysis by State (Filled Map):

Chart Type: Filled Map

Metrics: 'Total Loan Applications,' 'Total Funded Amount,' and 'Total Amount Received'
Geographic Regions: States

Objective: This filled map will visually represent lending metrics categorized by state, enabling me to identify regions with significant lending activity and assess regional disparities.

- Loan Term Analysis (Donut Chart):

Chart Type: Donut Chart

Metrics: 'Total Loan Applications,' 'Total Funded Amount,' and 'Total Amount Received'

Segments: Loan Terms (e.g., 36 months, 60 months)

Objective: This donut chart will depict loan statistics based on different loan terms, allowing us to understand the distribution of loans across various term lengths.

- Employee Length Analysis (Bar Chart):

Chart Type: Bar Chart

Metrics: 'Total Loan Applications,' 'Total Funded Amount,' and 'Total Amount Received'

X-Axis: Employee Length Categories (e.g., 1 year, 5 years, 10+ years)

Y-Axis: Metrics' Values

Objective: This bar chart will illustrate how lending metrics are distributed among borrowers with different employment lengths, helping us assess the impact of employment history on loan applications.

-  Loan Purpose Breakdown (Bar Chart):

Chart Type: Bar Chart

Metrics: 'Total Loan Applications,' 'Total Funded Amount,' and 'Total Amount Received'

X-Axis: Loan Purpose Categories (e.g., debt consolidation, credit card refinancing)

Y-Axis: Metrics' Values

Objective: This bar chart will provide a visual breakdown of loan metrics based on the stated purposes of loans, aiding in the understanding of the primary reasons borrowers seek financing.

- Home Ownership Analysis (Tree Map):
Chart Type: Tree Map

Metrics: 'Total Loan Applications,' 'Total Funded Amount,' and 'Total Amount Received'

Hierarchy: Home Ownership Categories (e.g., own, rent, mortgage)

Objective: This tree map will display loan metrics categorized by different home ownership statuses, allowing for a hierarchical view of how home ownership impacts loan applications and disbursements.

#### These diverse chart types will enhance our ability to visualize and communicate loan-related insights effectively, supporting data-driven decisions and strategic planning within our lending operations."

### DASHBOARD 3: DETAILS
In our Bank Loan Report project, we recognize the need for a comprehensive 'Details Dashboard' that provides a consolidated view of all the essential information within our loan data. This Details Dashboard aims to offer a holistic snapshot of key loan-related metrics and data points, enabling users to access critical information efficiently.

#### Objective:

The primary objective of the Details Dashboard is to provide a comprehensive and user-friendly interface for accessing vital loan data. It will serve as a one-stop solution for users seeking detailed insights into our loan portfolio, borrower profiles, and loan performance.

### STEPS FOLLOWED

- Step 1 : Load data into SQL Server, dataset is a csv file.
- Step 2 : Preview Data

      SELECT * FROM bank_loan_data
 ![F 1](https://github.com/Charles-Opitoke/Bank-Loan-Analysis-/assets/164562500/ad210d16-b004-41b4-9e2c-3a57b032ede0)
 

- Step 3 : Calculate the total number of loan applications received during a specified period.
#### Total Loan Applications
      SELECT COUNT(id) AS Total_Applications FROM bank_loan_data
![F2](https://github.com/Charles-Opitoke/Bank-Loan-Analysis-/assets/164562500/5047bb9d-5b24-461f-9e5d-a43b5f2533c7)
#### Month To Date (MTD) Loan Applications
      SELECT COUNT(id) AS Total_Applications FROM bank_loan_data
      WHERE MONTH(issue_date) = 12

![F30](https://github.com/Charles-Opitoke/Bank-Loan-Analysis-/assets/164562500/640ceceb-4ba9-4561-86f3-35b049ff48e5)


#### Previous Month To Date (PMTD) Loan Applications
      SELECT COUNT(id) AS Total_Applications FROM bank_loan_data
      WHERE MONTH(issue_date) = 11

![F3](https://github.com/Charles-Opitoke/Bank-Loan-Analysis-/assets/164562500/2eb8d8f2-ae0a-4241-9e19-0c9b735652d2)

- Step 4 : Calculate the total amount of funds disbursed as loans during a specific period.
#### Total Funded Amount

      SELECT SUM(loan_amount) AS Total_Funded_Amount FROM bank_loan_data

![F31](https://github.com/Charles-Opitoke/Bank-Loan-Analysis-/assets/164562500/34a9c361-f4cb-4eea-8431-7cf86f28faa2)

#### MTD Total Funded Amount
      SELECT SUM(loan_amount) AS Total_Funded_Amount FROM bank_loan_data
      WHERE MONTH(issue_date) = 12

![F4](https://github.com/Charles-Opitoke/Bank-Loan-Analysis-/assets/164562500/d1b7fca8-5823-47ae-ba2f-860f02f10e48)

#### PMTD Total Funded Amount
      SELECT SUM(loan_amount) AS Total_Funded_Amount FROM bank_loan_data
      WHERE MONTH(issue_date) = 11

![F5](https://github.com/Charles-Opitoke/Bank-Loan-Analysis-/assets/164562500/0f3f16de-80ef-4dec-aff1-03bc14d440c0)

- Step 5 : calculate the total amount received from borrowers
#### Total Amount Received
      SELECT SUM(total_payment) AS Total_Amount_Collected FROM bank_loan_data

![F32](https://github.com/Charles-Opitoke/Bank-Loan-Analysis-/assets/164562500/be379235-09cb-4cd5-850f-64d3de9105ae)

#### MTD Total Amount Received
      SELECT SUM(total_payment) AS Total_Amount_Collected FROM bank_loan_data
      WHERE MONTH(issue_date) = 12

![F6](https://github.com/Charles-Opitoke/Bank-Loan-Analysis-/assets/164562500/0427da9b-15bb-4ad6-ac63-cb96b17fbbde)

#### PMTD Total Amount Received
      SELECT SUM(total_payment) AS Total_Amount_Collected FROM bank_loan_data
      WHERE MONTH(issue_date) = 11

![F7](https://github.com/Charles-Opitoke/Bank-Loan-Analysis-/assets/164562500/c97df08a-6a93-42c7-9821-056a207c869d)


- Step 6 : Calculate the average interest rate across all loans.
#### Average Interest Rate
      SELECT AVG(int_rate)*100 AS Avg_Int_Rate FROM bank_loan_data

![F33](https://github.com/Charles-Opitoke/Bank-Loan-Analysis-/assets/164562500/2d7696f5-3b78-47d8-b676-d1a52e9ee1d4)

#### MTD Average Interest
      SELECT AVG(int_rate)*100 AS MTD_Avg_Int_Rate FROM bank_loan_data
      WHERE MONTH(issue_date) = 12

![F8](https://github.com/Charles-Opitoke/Bank-Loan-Analysis-/assets/164562500/b2138690-47b3-4079-8e49-f40e26ee6545)

#### PMTD Average Interest
      SELECT AVG(int_rate)*100 AS PMTD_Avg_Int_Rate FROM bank_loan_data
      WHERE MONTH(issue_date) = 11

![F9](https://github.com/Charles-Opitoke/Bank-Loan-Analysis-/assets/164562500/cb319f91-9488-4f6c-ac1b-5a502ae1b8bd)

- Step 7 : Evaluating the average DTI
#### Avg DTI

      SELECT AVG(dti)*100 AS Avg_DTI FROM bank_loan_data

![F34](https://github.com/Charles-Opitoke/Bank-Loan-Analysis-/assets/164562500/c2b00aca-1ae7-4327-a7e2-f6959a869a7e)

#### MTD Avg DTI

      SELECT AVG(dti)*100 AS MTD_Avg_DTI FROM bank_loan_data
      WHERE MONTH(issue_date) = 12

![F10](https://github.com/Charles-Opitoke/Bank-Loan-Analysis-/assets/164562500/1d977175-80a0-4d32-94a8-e3a354c32dbb)

#### PMTD Avg DTI

      SELECT AVG(dti)*100 AS PMTD_Avg_DTI FROM bank_loan_data
      WHERE MONTH(issue_date) = 11

![F11](https://github.com/Charles-Opitoke/Bank-Loan-Analysis-/assets/164562500/154a0a42-467f-4195-98d9-70cda63df74d)

- Step 8 : Preview Loan Status 

      SELECT loan_status FROM bank_loan_data

![F12](https://github.com/Charles-Opitoke/Bank-Loan-Analysis-/assets/164562500/267c1bf6-7e0d-43b4-ba0d-080babd5d60e)

#### Good Loan Percentage
      SELECT
    (COUNT(CASE WHEN loan_status = 'Fully Paid' OR loan_status = 'Current' THEN id END) * 100.0) / 
	COUNT(id) AS Good_Loan_Percentage
    FROM bank_loan_data

![F13](https://github.com/Charles-Opitoke/Bank-Loan-Analysis-/assets/164562500/a949e69b-e421-45eb-83cf-60deddd66a10)

#### Good Loan Applications
     SELECT COUNT(id) AS Good_Loan_Applications FROM bank_loan_data
     WHERE loan_status = 'Fully Paid' OR loan_status = 'Current'

![F14](https://github.com/Charles-Opitoke/Bank-Loan-Analysis-/assets/164562500/cbf57ec4-0882-45e5-a642-2764d2864b2d)

#### Good Loan Funded Amount
     SELECT SUM(loan_amount) AS Good_Loan_Funded_amount FROM bank_loan_data
     WHERE loan_status = 'Fully Paid' OR loan_status = 'Current'

![F15](https://github.com/Charles-Opitoke/Bank-Loan-Analysis-/assets/164562500/aa17d94b-5919-465a-a1d6-963c219bee8e)

#### Good Loan Amount Received
     SELECT SUM(total_payment) AS Good_Loan_amount_received FROM bank_loan_data
     WHERE loan_status = 'Fully Paid' OR loan_status = 'Current'

![F16](https://github.com/Charles-Opitoke/Bank-Loan-Analysis-/assets/164562500/2841f8bd-74a6-4363-9870-2643edf81267)

### BAD LOAN ISSUED
#### Bad Loan Percentage
     SELECT
    (COUNT(CASE WHEN loan_status = 'Charged Off' THEN id END) * 100.0) / 
	COUNT(id) AS Bad_Loan_Percentage
     FROM bank_loan_data

![F17](https://github.com/Charles-Opitoke/Bank-Loan-Analysis-/assets/164562500/cdcffcf7-8240-4321-b43e-8f425843ca54)

#### Bad Loan Applications
     SELECT COUNT(id) AS Bad_Loan_Applications FROM bank_loan_data
     WHERE loan_status = 'Charged Off'

![F18](https://github.com/Charles-Opitoke/Bank-Loan-Analysis-/assets/164562500/ef02f0ed-f09d-402d-bcfb-76744231aa9f)

#### Bad Loan Funded Amount
     SELECT SUM(loan_amount) AS Bad_Loan_Funded_amount FROM bank_loan_data
     WHERE loan_status = 'Charged Off'

![F19](https://github.com/Charles-Opitoke/Bank-Loan-Analysis-/assets/164562500/419137ee-b35b-4102-97ad-daa831cf23dc)

#### Bad Loan Amount Received
     SELECT SUM(total_payment) AS Bad_Loan_amount_received FROM bank_loan_data
     WHERE loan_status = 'Charged Off'

![F20](https://github.com/Charles-Opitoke/Bank-Loan-Analysis-/assets/164562500/c8f4bd3e-6f37-422e-a96a-d15a131ec5ad)

#### LOAN STATUS
     	SELECT
        loan_status,
        COUNT(id) AS Total_Loan_Application,
        SUM(total_payment) AS Total_Amount_Received,
        SUM(loan_amount) AS Total_Funded_Amount,
        AVG(int_rate * 100) AS Interest_Rate,
        AVG(dti * 100) AS DTI
    FROM
        bank_loan_data
    GROUP BY
        loan_status

![F21](https://github.com/Charles-Opitoke/Bank-Loan-Analysis-/assets/164562500/e8192ff9-13f2-48d0-a66a-bb986c6bb534)

#### MTD Total Amount Recieved
     	SELECT 
	loan_status, 
	SUM(total_payment) AS MTD_Total_Amount_Received, 
	SUM(loan_amount) AS MTD_Total_Funded_Amount 

     	FROM bank_loan_data

     	WHERE MONTH(issue_date) = 12 

     	GROUP BY loan_status

![F22](https://github.com/Charles-Opitoke/Bank-Loan-Analysis-/assets/164562500/534547f8-3129-438c-a1d4-ebf3996ff1ad)

- Step 9 : Calculate for Monthly Trends based on Issue Date

#### MONTHLY TREND BASED ON ISSUE DATE
     	SELECT 
	MONTH(issue_date) AS Month_Munber, 
	DATENAME(MONTH, issue_date) AS Month_name, 
	COUNT(id) AS Total_Loan_Applications,
	SUM(loan_amount) AS Total_Funded_Amount,
	SUM(total_payment) AS Total_Amount_Received
     FROM bank_loan_data
     GROUP BY MONTH(issue_date), DATENAME(MONTH, issue_date)
     ORDER BY MONTH(issue_date)

![F23](https://github.com/Charles-Opitoke/Bank-Loan-Analysis-/assets/164562500/b9f34116-6e66-46ca-a5b2-25452c4e3ca5)

- Step 10 : Calculate 'Total Loan Applications,' 'Total Funded Amount,' and 'Total Amount Received' based on Geographic Regions: States

#### TOTAL LOAN APPLICATIONS BASED ON REGIONS "STATE"
     	SELECT 
	address_state AS State, 
	COUNT(id) AS Total_Loan_Applications,
	SUM(loan_amount) AS Total_Funded_Amount,
	SUM(total_payment) AS Total_Amount_Received
     FROM bank_loan_data
     GROUP BY address_state
     ORDER BY address_state
![F35](https://github.com/Charles-Opitoke/Bank-Loan-Analysis-/assets/164562500/70f34ee4-fa41-4af1-bc21-0389451e92de)

- Step 11 : Calculate 'Total Loan Applications,' 'Total Funded Amount,' and 'Total Amount Received' based on Loan Terms (e.g., 36 months, 60 months)
#### TOTAL LOAN APPLICATIONS BASED ON LOAN TERM
     SELECT 
	term AS Term, 
	COUNT(id) AS Total_Loan_Applications,
	SUM(loan_amount) AS Total_Funded_Amount,
	SUM(total_payment) AS Total_Amount_Received
	FROM bank_loan_data
	GROUP BY term
	ORDER BY term

![F25](https://github.com/Charles-Opitoke/Bank-Loan-Analysis-/assets/164562500/e63f5890-8ab4-477b-a8a0-83b66744a01c)

- Step 12 : Calculate 'Total Loan Applications,' 'Total Funded Amount,' and 'Total Amount Received' based on Employee Length Categories
#### TOTAL LOAN APPLICATIONS BASED ON EMPLOYEE LENGTH
     SELECT 
	emp_length AS Employee_Length, 
	COUNT(id) AS Total_Loan_Applications,
	SUM(loan_amount) AS Total_Funded_Amount,
	SUM(total_payment) AS Total_Amount_Received
     FROM bank_loan_data
     GROUP BY emp_length
     ORDER BY emp_length

![F26](https://github.com/Charles-Opitoke/Bank-Loan-Analysis-/assets/164562500/dc31c60a-be8e-4201-bf33-a014fa95d49e)

- Step 13 : Calculate  'Total Loan Applications,' 'Total Funded Amount,' and 'Total Amount Received' based on Loan Purpose Categories
#### TOTAL LOAN APPLICATIONS ON BASED LOAN PURPOSE
     SELECT 
	purpose AS PURPOSE, 
	COUNT(id) AS Total_Loan_Applications,
	SUM(loan_amount) AS Total_Funded_Amount,
	SUM(total_payment) AS Total_Amount_Received
     FROM bank_loan_data
     GROUP BY purpose
     ORDER BY purpose

![F27](https://github.com/Charles-Opitoke/Bank-Loan-Analysis-/assets/164562500/9dd7bab1-2ea6-4388-9057-dd5f3a3bdd5b)

- Step 14 : Calculate 'Total Loan Applications,' 'Total Funded Amount,' and 'Total Amount Received' based on Home Ownership Categories
#### TOTAL LOAN APPLICATIONS BASED ON HOME OWNERSHIP
     SELECT 
	home_ownership AS Home_Ownership, 
	COUNT(id) AS Total_Loan_Applications,
	SUM(loan_amount) AS Total_Funded_Amount,
	SUM(total_payment) AS Total_Amount_Received
     FROM bank_loan_data
     GROUP BY home_ownership
     ORDER BY home_ownership

![F28](https://github.com/Charles-Opitoke/Bank-Loan-Analysis-/assets/164562500/292012c2-d28c-412f-851c-c143a877882e)

- Step 15 : Connect SQL Server to Power BI
Designed the Summary Dashboard, Overview Dashboard and Details Dashboard
#### SUMMARY DASHBOARD 
![F36](https://github.com/Charles-Opitoke/Bank-Loan-Analysis-/assets/164562500/e590bc3b-191b-4324-a11c-03b8290e1109)
#### OVERVIEW DASHBOARD
![F37](https://github.com/Charles-Opitoke/Bank-Loan-Analysis-/assets/164562500/52464f89-273c-4c18-8d61-8291280f298f)

#### DETAILS DASHBOARD
![F38](https://github.com/Charles-Opitoke/Bank-Loan-Analysis-/assets/164562500/a7c02d2f-b201-4eba-8ffe-26d4bed9ade7)




