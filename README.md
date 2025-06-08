# Coffee-Sales_-Excel

The project generally starts with a coffee bean seller who has sales data over several years. The seller wants to analyze this data to gain business insights.

**The Dataset:**
1. orders sheet: Contains details of each coffee order, including order ID, date, customer ID, product ID, quantity, and sometimes basic calculated fields like unit price.
2. products sheet: Details about the coffee products ( product ID, coffee type, roast type, package size, unit price).
3. customers sheet: Information about customers ( customer ID, name, email, country, loyalty card status).

**Importing data into Excel :-**
1. Transforming raw data into "Tables" for easier manipulation.
2. Cleaning common data issues:
   Removing duplicates and irrelevant entries.
   Fixing structural errors (inconsistent spellings, formatting).
3. Checking for data consistency.
4. Creating new calculated columns using Excel formulas (Sales by multiplying quantity and unit price).
5. Using lookup functions like XLOOKUP & INDEX MATCH to combine data from different sheets (bringing coffee type, roast type, size, and unit price into the main orders sheet from the products sheet).
6. Using IF functions for conditional logic (translating short codes like "Rob" to "Robusta" for clarity).

**Data Analysis (using Pivot Tables & Charts):**
1. Using Pivot Tables to filter and analyze specific subsets of data.
2. Creating Pivot Charts (bar charts, line charts) from the pivot tables to visualize insights.

**Dashboard Creation:**
1. Designing an interactive and visually appealing dashboard on a separate sheet.
2. Placing the various pivot charts and summary tables on the dashboard.
3. Implementing Slicers for interactive filtering (filter by coffee type, roast type, package size, loyalty card, country).
4. Adding a Timeline for chronological data trends.
5. Adding key performance indicator (KPI) cards (Total Sales Revenue, Total Orders, Average Order Value).
