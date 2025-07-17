📌 Project Title:
Sales Tracker and Monthly Sales Analysis Dashboard

📝 Description:
This is a Google Sheets-based sales tracker project designed to record daily sales activities and provide automated monthly sales summaries and visual insights using pivot tables and charts.

📁 File Structure:
SalesData – Main sheet containing raw sales entries

Pivot_Analysis – Sheet containing pivot tables for summarized data

Dashboard – Visual dashboard built with charts and summaries

🔍 Features:
Sales Data Table

Captures each sale with:

Date of Sale

Invoice Number

Product Name

Product Category

Unit Price

Quantity Sold

Total Amount

Sales Rep

Region

Monthly Grouping

A helper column is used to extract the Month from the sale date using:

excel
Copy
Edit
=TEXT(A2, "MMMM")
This allows monthly grouping in pivot tables and charts.

Pivot Table Analysis

Sales grouped by:

Month

Product

Region

Sales Representative

All pivot tables dynamically update as new data is entered.

Visual Dashboard

Charts include:

Monthly Sales Trend (Line Column Chart)

Sales by Product 

Sales by Region (Column Chart)

Sales by Sales Rep (Bar Chart)

The dashboard provides a quick and clear visual representation of performance.

📊 Tools and Formulas Used:
=TEXT(Date, "MMMM") – Extracts the month name

Pivot Tables – For summarized data by group

Column Chart, Bar Chart – Used to visualize pivot table results

💡 How to Use:
Enter new sales records in the SalesData sheet.

Use the Month helper column to allow grouping.

Pivot tables in the Pivot_Analysis sheet will update automatically.

The Dashboard sheet shows the latest charts based on your data.

🎯 Purpose:
This project helps users track sales performance over time using organized spreadsheets, monthly summaries, and visual insights, without requiring complex tools or code.
