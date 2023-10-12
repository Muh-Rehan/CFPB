# CFPB COMPLAINT EXPLORATORY DATA ANALYSIS
## By Muhammad Raihan

According to the [official website](https://www.consumerfinance.gov/), Consumer Financial Protection Bureau (CFPB) is a United States bureau agency that implements and enforces federal consumer financial law and ensures that markets for consumer financial products are fair, transparent, and competitive. Some of the functions and responsibilites of the CFPB are as follows:
- Consumer education,
- Rulemaking and enforcement,
- Supervision and examination,
- Complaint handling,
- Research and data analysis.

As part of the responsibilities, CFPB receives complaints submitted by consumers of federal financial products regarding the issues they encountered with financial products and services, which then would be handled by CFPB to be investigated and solved. CFPB stored these complaints into a database which are made publically available to be accessed.

CFPB conducts data analysis of the complaints to gain insights upon the markets and trends within the financial space in order to better understand and continuously improve in addressing issues affecting the consumers. As handling and processing complaints takes a lot of time and resources from both CFPB and the respective financial company, getting to know the trend and typical complaints being filed is vital to streamline and improve the overall process.

This jupyter notebook contains an Exploratory Data Analysis (EDA) on CFPB consumer complaint database filtered from 01 July 2018 up to 30 June 2023. The purpose of the EDA is to understand problems consumers' experienced within financial markets that would result in complaint filling, this includes:
- What types of products and issues are being complained,
- Trend between states and over a period of time,
- How do the complaints being handled by CFPB and the companies,
- Other insights that could be discovered.

Summary of findings are as follows:
- Credit reporting being number one product complaints, with most issues are incorrect credit report; investigation problem; and misuse reporting.
- High increase complaints during pandemic, which skyrocketed from 2022.
- As for banking products, deposits/withdrawals and credit card purchase disputes are among the most filled complaints
- Complaints between the major players are similar, with few exception of company major event like the Wells Fargo scandal
- Relief rate remains mid to low between the major players.
- South east states remains the highest in complaint counts.
- Household with more wealth are more likely to submit complaints.

Therefore, here are some proposals suggested for improvement of CFPB and financial company as a whole:
- Credit reporting improvements:
    - Improve credit input and scoring process, especially to further regulate the data furnishers to properly validate informations that would end up in the consumers credit reports.
    - Through FCRA (Fair Credit Reporting Act) CFPB shall watch closely against the agencies to make sure proper code of ethics are in place regarding internal complaint handling and uses of consumers' report.
    - As for the agencies, proper team of consumers' complaints needed to be assembled and trained accordingly to handle massive amount of complaints entering. The agencies should not expect to lightly process many complaints that deemed without any basis.
- Banking products improvements:
   - Proper educations are needed for the consumers to know exactly how deposits and withdrawals work to avoid misunderstandings, and to also investigate fraud checks that could happened.
   - Improve securities on credit account information and educate consumers how to securely manage their credit accounts.

**IMPORTANT NOTE REGARDING COMPLAINT DATA**
The complete .csv data has the size of 1.8GB with 2.4 million of rows, which are way too big to be saved inside GitHub repository. Data is available publically in both the [CFPB official website](https://www.consumerfinance.gov/data-research/consumer-complaints/#download-the-data) and [Google Public Dataset](https://console.cloud.google.com/marketplace/product/cfpb/complaint-database). The data is open and can be redistributed appropriately and legally according to the Google Terms of Service. The data contains complaints from 01 July 2018 to 30 June 2023, and contains the following 18 columns:
 1.   Date received
 2.   Product
 3.   Sub-product
 4.   Issue
 5.   Sub-issue
 6.  Consumer complaint narrative
 7.   Company public response
 8.   Company
 9.   State
 10.   ZIP code
 11.  Tags
 12.  Consumer consent provided?
 13.  Submitted via
 14.  Date sent to company
 15.  Company response to consumer
 16.  Timely response?
 17.  Consumer disputed?
 18.  Complaint ID
