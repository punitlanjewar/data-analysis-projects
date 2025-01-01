# E-commerce Brand Sales Report

### Report Overview:

This comprehensive report is a multi-layered(Bookmark functionality) dashboard designed in Power BI, offering a detailed and structured view of various business metrics and performance insights. The report includes multiple thematic pages, each providing a focused analysis:

* Serves as the primary dashboard summarizing high-level metrics such as Total Cities, Orders, Revenue, Profit, and Cost.
* Includes visualizations like bar charts, pie charts, and other visuals to give an overview of orders by City, Customer Type, and Product Categories.
* Focused on profit-related metrics, providing a detailed breakdown of profits across categories, regions, and time periods.
* Highlights the top 10 performing entities, such as cities, products, or customer segments, based on key business metrics like revenue or orders.
* Provides insights into the bottom 10 entities, helping identify areas requiring attention or improvement.
* Each thematic page has its dedicated insights layer, offering an in-depth analysis of the data shown. These layers provide actionable insights based on trends and patterns, enabling decision-making at a granular level.

### Data Modelling

The data modeling process for this report was carried out with the goal of enhancing performance, scalability, and ease of reporting. A single flat table was transformed into a star schema by splitting it into multiple dimension tables and a fact table. This structure supports optimized query performance and improves the overall user experience in Power BI.

### First Layer (Home Page/Bar Chart View)

![Screenshot 2024-12-20 162147](https://github.com/user-attachments/assets/b894d86a-3e75-4866-8c41-da32ec450de6)

### First Layer (Home Page/Map View)

![Screenshot 2025-01-01 161816](https://github.com/user-attachments/assets/887def3a-a05d-44e1-ac26-ad9ec36e872c)

### First Layer (Home Page/Insights)

![Screenshot 2024-12-20 162352](https://github.com/user-attachments/assets/7555a5ca-d8e8-4d82-943e-7c1e15b57d9a)

### Second Layer (Profit Page)

![Screenshot 2024-12-20 162203](https://github.com/user-attachments/assets/ee24983c-9003-4656-9861-3b4da2a91eda)

### Second Layer (Profit Page/Insights)

![Screenshot 2024-12-20 162417](https://github.com/user-attachments/assets/0a65b448-6256-4076-8727-e8c543737c24)

### Third Layer (Top 10)

![Screenshot 2024-12-20 162316](https://github.com/user-attachments/assets/655ee7e3-2b96-4176-a374-a3fd9ccd4fe2)

### Third Layer (Top 10/Insights)

![Screenshot 2024-12-20 162437](https://github.com/user-attachments/assets/c08c04fc-c043-43ec-ad70-9b7c968517c1)

### Fourth Layer (Bottom 10)

![Screenshot 2024-12-20 162330](https://github.com/user-attachments/assets/88214f0d-e015-426c-9b26-10859f9a788f)

### Fourth Layer (Bottom 10/Insights)

![Screenshot 2024-12-20 162437](https://github.com/user-attachments/assets/c08c04fc-c043-43ec-ad70-9b7c968517c1)

### Report Insights

#### Home page(First Layer)

#### 1. Overall Matrices:

The dashboard highlights key performance indicators (KPIs), including:
* Total Cities: 52
* Total Orders: 9,648
* Total Units Sold: 2 Million
* Total Revenue: $120 Million
* Total Profit: $47.22 Million
* Total Cost: $72.94 Million

#### 2. Orders by City:

**Notable observations:
A bar chart displays the total number of orders across different cities.**
* Denver has the highest orders count (288).
* Multiple cities, such as Albany, Atlanta, and others, report 216 orders each.
* The chart is scrollable, indicating additional cities in the dataset.

#### 3. Orders by Customer Type:

A bar chart categorizes orders based on customer types:
A pie chart represents the distribution of orders across product categories:
* Street Footwear: **33.31% (3.214K orders)**
* Athletic Footwear: **33.35% (3.218K orders)**
* Apparel: **33.33% (3.216K orders)**

**The distribution is nearly equal across all three categories.**

#### 4. Interactivity:

* Filters for **Gender**, **Year**, and **Months** allow users to customize the view dynamically, enabling a focused analysis of specific periods or demographics.

#### Profit (Second Layer)

#### 1. Profit by City:

* **New York** generates the **highest** profit at **$2.1M**, followed by **Charleston** with **$2.0M**.
* Cities such as **San Francisco, Miami, and Portland** also have profits exceeding **$1.6M**.
* Cities like **Albuquerque, Denver, and Columbus** have the lowest profits, at **$1.0M each**.

#### 2. Profit by Region:

* The **Northeast region** leads in profitability with **$12.4M**, followed closely by the **West region** at **$11.9M**.
* The **South region** reports **$9.2M** in profit, while both **Southeast and Midwest regions** trail at **$6.9M** each.


#### 3. Profit by Product Category:

* The **Street Footwear** category contributes the most profit at **$18.12M (38.3%)**.
* **Apparel** comes next, with **$16.07M (34.02%)**, while **Athletic Footwear** contributes **$13.04M (27.6%)**.
* The profit distribution suggests Street Footwear is a major driver of profitability.

#### 4.  Profit by Quarter:

* Profit trends by quarter show a peak in **Q3** at **$14.1M**, followed by **Q2** at **$11.9M**.
* **Q4** reports a decline to **$11.5M**, while **Q1** has the **lowest** profit at **$9.7M**.
* This indicates **strong** seasonal **performance** in **Q3**.

#### 4.  Profit by Customer Type:

* **Consumers** dominate profitability with **$25.31M (53%)**.
* **Corporate customers** contribute **$13.78M (29%)**, while Home Office lags at **$8.14M (17.24%)**.
* The focus on **Consumers** aligns with the major share of profit contribution.

#### Top 10 (Third Layer)

#### 1. Profit by Top 10 Customers:

* **Jonathan Diaz** leads with the highest profit contribution at **$39K**.
* Close followers include **Jennifer Rob, Erika Gomez, and Stanley Male, each** contributing **$38K**.

#### 2. Units Sold by Top 10 Cities:

* New York has the highest units sold at 112K, followed by Charleston (102K) and Houston (90K).

#### 3. Revenue by Top 10 States:

* New York generates the maximum revenue at $8.7M, followed by California at $8.6M and Florida at $7.8M.

#### Bottom 10 (Fourth Layer)

#### 1. Profit by Bottom 10 Customers:

* Jessica Wilson has the lowest profit contribution among active customers at $75.
* Jennifer Campbell, Benjamin Smith, and John Thomas contribute slightly higher profits, ranging from $93 to $108.
* Four customers (Isabella Baker, Maleackenzie, Seth Green, Sydney Male) recorded $0 profit, indicating no transactions or activity.

#### 2. Units Sold by Bottom 10 Cities:

* Wichita has the highest units sold among the bottom 10 cities at 29.5K, followed by Providence (27.5K) and Indianapolis (26.3K).
* Omaha recorded the lowest units sold at 19.2K, followed by Baltimore and Minneapolis (both 20.8K).

#### 3. Revenue by Bottom 10 States:

* Rhode Island contributes the highest revenue among the bottom 10 states at $1.20M, followed closely by Missouri ($1.19M) and Indiana ($1.08M).
* Nebraska records the lowest revenue among the bottom states at $0.73M, significantly trailing behind others like Minnesota ($0.90M) and Iowa ($0.91M).

#### Insights (Fifth Layer)

The Insights Layer provides a detailed breakdown of key metrics and actionable insights within each section of the report. It is accessible dynamically through the Insights Button within individual layers like **Home page, Profit, Top 10, Bottom 10,**. This allows users to delve deeper into data-driven decisions without leaving the context of the primary view.