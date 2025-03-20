# First-Report-of-Sales

This Tableau dashboard titled "First Report of Sales" provides a summarized view of sales performance across different countries and top salespersons. 
The key metrics covered in this dashboard are:

- **Total Amount**
- **Boxes Shipped**
- **Shipment Count**
<br>
The dashboard also includes:
  - 1. Sales by Country (Bar Chart)
  - 2. Top 10 Sales Persons (Horizontal Bar Chart

 Data Modeling
- **Connecting Data Source: Connected the data source (likely Excel, CSV, or database) to Tableau.**
- **Data Relationships: Defined clear relationships between fields such as Country, Sales Person, Amount, Boxes Shipped, and Shipment Count.**
- **Field Hierarchies & Calculated Fields:**
   - **Created hierarchies if required (e.g., Region → Country).**
   - **Possibly created calculated fields to compute KPIs like Total Amount or Shipment Count.**

Data Cleaning
- **Null Values Handling:**
   - **Checked for any null/missing values in fields like Amount, Country, Sales Person and handled them (filtered/cleaned).**
- **Data Type Consistency:**
   - **Ensured correct data types (e.g., Amount as currency, Shipment Count as integer).**
- **Renaming & Formatting:**
   - **Renamed columns for better readability.**
   - **Formatted numeric fields properly (₹ symbol for Amount, commas for thousands).**

Data Processing
- **Aggregations:**
   - **Summed up Amount, Boxes Shipped, and Shipment Count.**
- **Filters & Sorting:**
   - **Applied filters (e.g., top 10 salespersons).**
   - **Sorted salespersons based on Amount.**
- **Grouping:**
   - **Grouped countries for country-wise sales aggregation.**
- **Calculated KPIs:**
   - **Computed total boxes shipped and shipment count.**

Data Visualization
- **Dashboard Creation:**
   - **Combined multiple worksheets (Sales Country, Top 10 Sales, Sales Summary) into a dashboard.**
- **Charts Used:**
   - **Bar Chart for Sales by Country.**
   - **Horizontal Bar Chart for Top Sales Persons.**
   - **KPI Text Tiles for Amount, Boxes Shipped, Shipment Count.**
- **Interactivity:**
   - **Included filter icons to allow user interaction.**
- **Design & Layout:**
   - **Used proper layout with consistent color scheme and spacing.**
   - **Set to Entire View for better visibility.**

Analysis and create a dashboard report.
