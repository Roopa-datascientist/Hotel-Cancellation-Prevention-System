# Hotel Booking Cancellation Prevention & Decision Support System
 📌 About the Project
    This project analyzes hotel booking data to identify bookings that may have a higher chance of cancellation.It also identifies the likely cancellation driver and suggests an action that the hotel can take.

 Main Flow
Data → Analysis → Risk → Likely Driver → Action → Decision

🎯 Objectives
- Analyze hotel booking data
- Understand cancellation patterns
- Identify cancellation risk
- Classify bookings as Low, Medium, or High Risk
- Identify likely cancellation drivers
- Suggest suitable actions
- Create a Power BI dashboard for decision support

🛠️ Tools Used
- Python
- Pandas
- Jupyter Notebook
- Power BI
- CSV

📊 Dashboard

![Hotel Cancellation Dashboard](Hotel%20Cancellation%20.png)
The Power BI dashboard contains:
- Total Bookings
- Cancelled Bookings
- Cancellation Rate
- Estimated Booking Value
- Cancellation Count by Risk Level
- Cancellation Rate by Lead Time
- Cancellation Distribution by Deposit Type
- Cancelled Bookings by Likely Driver
- Decision Support Table
- Risk Level Filter
- Hotel Filter

🔍 Risk Levels
Bookings are classified into:
- Low Risk
- Medium Risk
- High Risk
The risk level is calculated using a rule-based scoring method based on booking information.

💡 Decision Support
The system provides:
Risk Level → Likely Driver → Recommended Action
For example:
High Risk → Previous Cancellation History → Send confirmation and cancellation-policy reminder

📁 Project Files
- 01_dataset_check.ipynb – Python analysis
- cancellation predict.pbix – Power BI dashboard
- dashboard_kpis.csv – Dashboard KPI data
- decision_support_table.csv – Decision support data
- final_cancellation_analysis.csv – Final analysis data
- powerbi_cancellation_data.csv – Power BI data
- Hotel Cancellation .png – Dashboard image

📂 Dataset
The project uses the **Hotel Booking Demand dataset.
The original raw dataset is not included in this repository.

⚠️ Limitations
- The dataset is historical.
- Cancellation reasons are identified as **likely drivers**, not actual customer-stated reasons.
- Risk levels are rule-based and not machine-learning predictions.
- Estimated booking value is an analytical estimate.

🚀 Future Improvements
- Add Machine Learning cancellation prediction
- Add real-time risk detection
- Add actual cancellation reasons
- Add automatic alerts
- Track the effectiveness of recommended actions

👩‍💻 Author
Roopa P
B.Sc. Data Science Student
Areas of Interest
- Data Analytics
- Data Science
- Business Intelligence
- Machine Learning
- Python
- SQL
- Power BI
- Tableau
