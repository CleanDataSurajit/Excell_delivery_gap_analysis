Excel Delivery Gap Analysis using Power Query
This project demonstrates a complete data cleaning, transformation, and validation workflow using Microsoft Excel and Power Query. The dataset contains 120 rows of structured order data including Order ID, Order Date, Delivery Date, Quantity, Unit Price, and Total Amount.
🔍 Project Objective
The primary objective of this project is to calculate delivery lead time (Delivery Gap Days) while ensuring data accuracy and identifying inconsistencies in date logic.
🛠 Tools Used
Microsoft Excel
Power Query Editor
Data Validation Techniques
Conditional Logic in M Language
📌 Key Steps Performed
Converted raw dataset into structured table format.
Standardized date formats (dd-mm-yyyy).
Validated numerical columns (Quantity, Unit Price).
Verified Total Amount calculation (Quantity × Unit Price).
Created a custom column to calculate Delivery Gap Days.
Implemented logic to detect incorrect date entries where Delivery Date occurs before Order Date.
Applied conditional validation to handle negative or inconsistent delivery durations.
⚠ Data Validation Logic
If Delivery Date is earlier than Order Date, the system flags the row as a date error. This ensures data integrity and prevents incorrect reporting.
📈 Business Insights Enabled
Average Delivery Time
Maximum and Minimum Lead Time
Revenue Analysis
Order Processing Efficiency
💼 Why This Project Matters
This project reflects real-world data cleaning scenarios where incorrect dates and inconsistent values frequently occur. The validation logic ensures professional-level reporting standards suitable for business analysis and freelancing projects.
