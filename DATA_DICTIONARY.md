# Data Dictionary — Retail Sales Dataset (2025)

| Column Name | Data Type | Description | Example |
| :--- | :--- | :--- | :--- |
| `Order_ID` | String (PK) | Unique identifier for each customer order | `ORD-202500001` |
| `Order_Date` | Date | Date the order was placed (`YYYY-MM-DD`) | `2025-01-14` |
| `Month_Num` | Integer | Numeric month extracted from `Order_Date` (`1`–`12`) | `1` |
| `Month_Name` | String | Abbreviated month name (`Jan`–`Dec`) | `Jan` |
| `Quarter` | String | Fiscal quarter (`Q1`–`Q4`) | `Q1` |
| `Customer_ID` | String | Unique identifier assigned to each shopper | `CUST-14208` |
| `Gender` | Categorical | Customer gender (`Women`, `Men`) | `Women` |
| `Age_Group` | Categorical | Customer age bracket (`18-25`, `26-35`, `36-45`, `46-55`, `55+`) | `26-35` |
| `State` | Categorical | Indian state of delivery destination | `Maharashtra` |
| `Channel` | Categorical | E-commerce marketplace or platform (`Amazon`, `Flipkart`, `Myntra`, `Ajio`, `Direct Website`) | `Amazon` |
| `Category` | Categorical | High-level product category | `Ethnic Wear` |
| `Sub_Category` | Categorical | Specific product line within the category | `Kurta Sets` |
| `Quantity` | Integer | Number of units ordered in the line item (`1`–`3`) | `2` |
| `Unit_Price_INR` | Currency | Price per unit in Indian Rupees (₹) | `₹1,120` |
| `Gross_Sales_INR` | Currency (Formula) | Total pre-discount value (`=Quantity * Unit_Price_INR`) | `₹2,240` |
| `Discount_Pct` | Percentage | Promotional discount applied (`0%`–`15%`) | `10.0%` |
| `Net_Sales_INR` | Currency (Formula) | Final net revenue (`=Gross_Sales_INR * (1 - Discount_Pct)`) | `₹2,016.00` |
| `Order_Status` | Categorical | Delivery lifecycle status (`Delivered`, `Returned`, `Cancelled`, `In Transit`) | `Delivered` |
| `Payment_Mode` | Categorical | Payment method used (`UPI`, `Credit Card`, `Debit Card`, `Cash on Delivery`, `Net Banking`) | `UPI` |
