💠 Business Case Study - Healthcare Analytics: Implement Data Governance through multiple Login Users Creation, Role Based Access Control (RBAC), Dynamic Data Masking, Row Level Security (RLS) based on Region of the patients at SQL Server Data Source to adhere with HIPPA regulations to analyse data on Power BI.



🛑 Business Rule: Adhering to the HIPPA rules, the Patient Name, DOB, Insurance IDs from the insurance policy must be masked while sharing the data with vendors. 



🔆 Data Availability validation on PowerBI: What is the impact of SQL Server Dynamic Data Masking on Power BI Data Import mode?



Answer:

🎯 To ensure the data masking changes remain intact, direct query ensures business team to view latest changes without refresh. 



🎯 If data is ingested through Import, any changes with masking policy would not reflect on the dashboard until report is refreshed.
