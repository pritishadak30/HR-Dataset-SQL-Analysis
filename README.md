📊 HR Database (MySQL Project)

This project focuses on HR data analysis using MySQL. It leverages an employee dataset to perform data cleaning, transformation, and advanced SQL queries for generating HR insights that can guide data-driven decision-making.

🔹 Features

✅ Database & Table Setup – Designed and structured hrdata database
✅ Data Cleaning – Standardized dates, added age & status fields, handled missing values
✅ HR Metrics & Insights –

Employee count (current & terminated)
Attrition rate calculation
Salary & age distribution
Department-wise salaries, absences, and performance trends
Demographic insights (gender, marital status, recruitment sources)

🔹 Project Structure
HR-Database-Project/
│── HRDataset.csv         # Employee dataset (raw data source)
│── HR Database.sql       # SQL queries for cleaning, transformation & analysis
│── README.md             # Project documentation
│── /images               # Screenshots or visualizations (optional)

🔹 Sample Query
-- Attrition Rate
SELECT 
 (CAST(COUNT(CASE WHEN EmployeesCurrentStatus = 0 THEN 1 END) AS FLOAT) / COUNT(*)) * 100 AS Attrition_Rate
FROM employees;

🔹 Example Outputs

📌 Employee Count
Category	             Count
Total Employees	        310
Current Employees	      240
Terminated Employees	  70

📌 Salary Range Distribution
Salary Range	     Employees
< 30K	                40
30K – 49K             120
50K – 69K	            95
70K – 89K	            40
90K and above	        15

📌 Age Group Distribution
Age Range	        Employees
20–29      	        80
30–39	              120
40–49	              70
50–59	              30
60+	                10


🔹 Tools & Technologies

MySQL / Workbench
SQL
HRDataset (CSV)

🔹 Outcomes

Workforce demographics overview
Salary and attrition insights
Departmental performance analysis
Data-backed HR decision support

🔹 Future Outlook

📈 Integration with BI Tools – Connect with Tableau/Power BI for interactive dashboards

🤖 Machine Learning Models – Predict attrition, performance, and hiring needs

🌍 Scalability – Extend dataset with real-time HR systems or larger employee databases

📊 Advanced Analytics – Correlation between performance, salary hikes, and employee retention

🧑‍💼 HR Strategy Insights – Use analytics to design better hiring and retention strategies

👨‍💻 Author

Pritish Adak

 📧 Email:pritish.p.adak@gamil.com
 
🔗 LinkedIn -www.linkedin.com/in/pritish-adak-710316260

💻 GitHub -https://github.com/pritishadak30

✨ This project highlights how SQL can be applied to real-world HR datasets to uncover valuable workforce insights, and sets the stage for predictive HR analytics
