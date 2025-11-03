# GitHub-Workbook-Repository
Projects from Data Bootcamp
Day 1: Excel
**Name:** Kieran Parkin  
**Course Date:** 22/09/2025
## Day 1: Task 1
### Common Data Laws and Regulations
| Regulation | Description | Importance | Real-world Example | Impact on Data Work | Consequences of Breach |
|-------------|--------------|-------------|---------------------|----------------------|------------------------|
| **Data Protection Act (DPA)** | Controls how personal information is used by organisations. | Ensures fair and secure data handling. | Staying vigilant against phishing and malicious data gathering. | Requires careful compliance to prevent breaches. | Example: Yahoo! fined £250,000 for 2014 breach exposing 500M users. |
| **GDPR** | EU regulation protecting personal data and privacy. | Strengthens consumer rights and data correction/deletion. | Checking company data usage and signing GDPR compliance forms. | Enforces lawful handling and storage of personal data. | Fines up to €20M or 4% of global turnover. |
| **Freedom of Information Act (FOI)** | Provides access to recorded information held by UK public authorities. | Promotes transparency and accountability. | Used to reveal police costs for a football match (£2M). | Public bodies must provide requested info in 20 days. | Fines or contempt of court for blocking or altering info. |
| **Computer Misuse Act** | Illegal to access or modify computer data without permission. | Protects systems from hacking and malware. | 2017: Two men arrested for attempting to hack Microsoft. | Ensures ethical IT use. | Offences can lead to fines or imprisonment. |
## Day 2: Task 1

Tasks to complete within `retail_sales_dataset.xlsx`:

1. Convert data (A–J) into a **Table**.  
2. Sort the **Age** column (largest → smallest).  
3. Use **SUM** in `M10` to calculate total commission.  
4. Use **AVERAGE** in `M11` to calculate average commission.
## Day 3: Task 1

Dataset: `Day_3_Task_1_Bike_Sales_Pivot_Lab.xlsx`  
Create a Pivot Table and answer reflection questions:

- **Markets for Germany:** Adults aged 35–64 (13 orders)  
- **Country with sales in all markets:** United Kingdom  
- **Most profitable:**
  - Country: United States (66)
  - Age Group: Adults 35–64 (99)
  - Gender: Female (108)
- **Findings:** Data shows increasing sales with age — older demographics order more bikes.
## Day 3: Task 2
### Dataset

| County | Product | Sales Volume |
|---------|----------|--------------|
| Yorkshire | Laptops | 500 |
| Yorkshire | Smartphones | 200 |
| Cornwall | Laptops | 700 |
| Cornwall | Printers | 400 |
| Lancashire | Smartphones | 150 |
| Lancashire | Laptops | 600 |
| Essex | Printers | 800 |
| Essex | Smartphones | 300 |
| Durham | Laptops | 250 |
| Durham | Printers | 300 |
| Greater Manchester | Smartphones | 600 |
| Greater Manchester | Laptops | 400 |

### Steps

1. **Pivot Table:** Summarise by County (rows) and Product (columns) with Sales Volume as value.  
2. **SWITCH Function:** Categorise products based on Sales Volume:

```excel
=SWITCH(TRUE, C2 > 600, "High", C2 >= 300, "Medium", "Low")
