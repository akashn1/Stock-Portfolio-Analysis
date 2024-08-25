# Personal Portfolio Dashboard

## Project Overview

This project creates a real-time portfolio analysis dashboard by integrating data from Grow, Google Sheets, and Power BI. It provides interactive visualizations and key performance metrics to help you track and optimize your investments.

<img width="721" alt="FINAL" src="https://github.com/user-attachments/assets/e47f979d-1d9b-4ee8-9d31-0d1480b4134e">

## Steps to Create the Dashboard

1. **Download Portfolio Report:**
   - Export your portfolio holding report from Grow in a suitable format, such as CSV or Excel.
![grow](https://github.com/user-attachments/assets/3bd94e07-6d00-49d0-bd65-1c0735833eac)

2. **Import Data to Google Sheets:**
   
   <img width="960" alt="sheet" src="https://github.com/user-attachments/assets/bfce32fb-06b6-4211-a118-d00a893eba60">

   - Upload the downloaded report to Google Sheets.
   - Utilize Google Finance functions within Google Sheets to fetch and integrate real-time market data with your portfolio data.
3. **Set Up Automatic Refresh:** Configure Google Sheets(You can use AppScript)
 to refresh data at specified intervals to ensure the market data is always up-to-date.

4. **Connect Google Sheets to Power BI:**
   
   <img width="960" alt="Table in power Bi" src="https://github.com/user-attachments/assets/452fc70e-a861-40ef-983e-8013100b3956">

   - Open Power BI Desktop and use the “Get Data” feature to establish a connection to your Google Sheets.
   - Ensure that the connection is set up to pull the latest data.

6. **Transform Data:**
   - Perform basic data transformations in Power BI to clean and structure your dataset. This includes handling missing values, adjusting data formats, and ensuring consistency.

7. **Create Measured Fields:**
   
   <img width="960" alt="Front page" src="https://github.com/user-attachments/assets/76279991-d5df-4a4c-b62e-ae3ec15f13d2">
   - Define and calculate essential metrics such as Total Investment Amount, Percentage Return, and XIRR (Extended Internal Rate of Return) to evaluate your portfolio’s performance.

8. **Build Visualizations:**
   - Design and create interactive dashboards and charts in Power BI. Visualize key performance indicators and trends to gain insights into your portfolio’s performance.
   - 
<img width="720" alt="RELIANCE" src="https://github.com/user-attachments/assets/e36a2808-cacc-4889-bd6f-59d8c38d5a79">



## Usage

- **Real-Time Dashboard:** Access your Power BI dashboard to monitor up-to-date portfolio data and performance metrics.
- **Data Refresh:** Google Sheets is set to refresh automatically at specified intervals, and you can also update your Power BI reports regularly to ensure the dashboard reflects the most current information.

## Contributing

Feel free to contribute to this project by submitting issues or pull requests. Contributions to improve functionality or add new features are welcome!

