📊 IEEE Student Registration Dashboard - Power BI

🚀 Project Overview

This project is a dynamic Power BI dashboard that visualizes and analyzes IEEE student registrations from an online data source. It includes data cleaning, KPIs, and interactive visuals to help stakeholders monitor student registrations, course popularity, and event performance.

📂 Features

✅ Data Cleaning & Processing

- Removed duplicate and useless course names.

- Standardized date format for weekly and monthly trends.

- Filtered valid university emails to track authentic registrations.

- Transformed text-based date column into Date format.

📈 Key Performance Indicators (KPIs)

- Total Students Registered → COUNT(Student ID)

- Students per Course → COUNT(Student ID) by Course

- Top 3 Departments with Most Registrations

- Registrations by Month → COUNT(Student ID) by Month(Timestamp)

- Percentage of Valid University Emails → (COUNT(Valid Emails) / COUNT(Total Students)) * 100

- Average Students per Department → COUNT(Student ID) / COUNT(Distinct(Department))


🎛 Slicers for Interactivity

- Department Slicer → View registrations by department.


📂 Files & Structure


🛠️ How to Use

- Load the Data → Connect to the provided URL to fetch student registration details.

- Data Cleaning → Ensure courses are standardized, dates are in correct format, and emails are validated.

- Apply DAX Measures → Use provided KPIs to track metrics.

- Add Slicers → Make the report interactive with department, course, and rating filters.

- Publish to Power BI Service → Share insights with stakeholders.

🔗 Future Enhancements

- 📌 Live Data Updates → Automate data refresh from the URL.

- 📌 More KPIs → Track attendance and participation rates.

- 📌 Predictive Analysis → Use Power BI AI visuals to predict registration trends.



For any queries or suggestions, reach out at your.email@example.com.

🎯 This Power BI dashboard transforms raw IEEE student registration data into meaningful insights for decision-making! 🚀

