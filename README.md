# BlinkitDashBoard
This project presents a comprehensive Power BI Dashboard for "Blink It: India's Last Minute App," designed to analyze sales, item performance, outlet characteristics, and regional trends. The dashboard empowers users with actionable insights into key metrics such as total sales, average sales, average ratings, and item visibility.

📂 Dataset Description
The dataset underpins the dashboard and includes critical attributes to analyze item sales, outlet characteristics, and customer preferences.

🗂 Dataset Columns:
Item_Fat_Content: Indicates the fat content of the item (e.g., Low Fat, Regular).
Item_Identifier: Unique identifier for each product.
Item_Type: Categorization of items (e.g., Fruits and Vegetables, Snack Foods).
Item_Visibility: Proportion of total area in the store where the item is visible.
Item_Weight: Weight of the product in kilograms.
Item_MRP: Maximum Retail Price of the item.
Outlet_Identifier: Unique ID for the store.
Outlet_Size: Size of the outlet (Small, Medium, High).
Outlet_Location_Type: Market location tier (e.g., Tier 1, Tier 2, Tier 3).
Outlet_Type: Type of the outlet (e.g., Supermarket Type1, Grocery Store).
Outlet_Establishment_Year: Year the outlet was established.
Years_Old: Derived column indicating the number of years since the outlet was established.

📌 Features of the Dashboard
Filter Panel: Dynamic filters allow slicing the data by:
Outlet Location Type: Tier 1, Tier 2, Tier 3.
Outlet Size: Small, Medium, High.
Item Type: Various product categories.
KPI Indicators: Display key metrics for quick insights.
Visual Elements:
Pie charts, bar charts, line charts, and tables for an interactive experience.
🔧 Data Cleaning and Processing
Data Preprocessing:
Removed duplicates and handled missing values.
Standardized "Item_Fat_Content" for consistency (e.g., 'low fat' → 'Low Fat').
Derived Columns:
Calculated "Years_Old" for outlets based on "Outlet_Establishment_Year."
🚀 Usage
Businesses can identify top-performing product categories and outlets.
Insights into regional preferences and outlet performance enable targeted marketing strategies.
