HR Attrition Analysis – Microsoft Fabric & Power BI
An end-to-end HR Analytics project built using Microsoft Fabric and Power BI to understand employee attrition and identify the key factors behind employee turnover.
Tools Used:
•	Microsoft Fabric
•	Fabric Lakehouse
•	OneLake Security
•	Power BI
•	DAX
•	Direct Lake
•	Column-Level Security (CLS)
Microsoft Fabric Workflow:
•	Created a Microsoft Fabric Workspace for the project.
•	Created a Lakehouse (lh_HR) to store the HR dataset.
•	Loaded the employee data into the hr_employees table, containing 1,470 employees and 37 columns.
•	Created a Power BI Semantic Model from the Lakehouse data.
•	Used Direct Lake to connect the analytical layer with the Fabric data.
•	Built an interactive Power BI HR Attrition Dashboard with Overview and Deep Dive pages.
Data Security with CLS:
•	One of the important parts of this project was implementing Column-Level Security (CLS) for the MonthlyIncome column.
•	Since salary information is sensitive, CLS helps restrict access to this column while allowing users to work with other HR data.
•	This is useful in real-world organizations where different users may need different levels of access to employee information. The Fabric security configuration confirms that CLS was applied to the hr_employees table.
Dashboard Highlights:
The dashboard provides insights into:
•	Overall attrition rate
•	Attrition by department and job role
•	Salary-wise attrition
•	Age and gender patterns
•	Business travel
•	Overtime
•	Education field
•	Marital status
Key Insights:
•	Overall attrition is 16.1%, with 237 employees leaving out of 1,470. 
•	Sales has the highest department attrition (20.63%), followed by HR (19.05%). 
•	Younger employees have higher attrition — the 18–25 age group has the highest rate at 35.77%. 
•	Overtime is a major factor — employees working overtime have 30.53% attrition, compared with 10.44% for those who don't. 
•	Frequent business travellers have higher attrition (24.91%) compared with non-travellers (8.09%). 
•	Lower-income employees show higher attrition — the Under 3K salary band has 28.61% attrition, while Above 10K has only 8.90%. 
•	Single employees have the highest marital-status attrition (25.53%). 
•	Male employees have slightly higher attrition (17.01%) than female employees (14.80%). 
•	Human Resources and Technical Degree education fields show relatively high attrition, at 25.93% and 24.24% respectively. 
Attrition is particularly high among younger, lower-income, single employees and those working overtime or travelling frequently. This suggests that compensation, workload, career stage, and work-life balance could be important areas for HR to investigate further. 

Key Takeaway:
•	This project helped me understand that a good BI solution isn't just about creating visuals. It also involves data management, modeling, security, and governance.
•	Implementing CLS on MonthlyIncome was a practical example of how sensitive employee data can be protected while still delivering meaningful HR insights.
•	Microsoft Fabric + Power BI + Data Security = a more complete, enterprise-ready analytics solution.
