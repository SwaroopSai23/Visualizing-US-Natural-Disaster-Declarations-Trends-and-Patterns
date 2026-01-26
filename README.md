📊 Visualizing US Natural Disaster Declarations
(FEMA Dataset – End-to-End Data Analytics Project)


1️⃣ Problem Statement

Natural disasters occur frequently across the United States, but analyzing their long-term trends, geographical distribution, and incident patterns using raw data is challenging. This project aims to transform FEMA’s disaster declaration data into meaningful insights by performing systematic data cleaning, exploratory data analysis (EDA), and building an interactive Power BI dashboard. The objective is to support data-driven understanding of disaster trends and enable better preparedness and planning.

2️⃣ Dataset Description

Source: FEMA Disaster Declarations Dataset

Geographical Scope: United States (states and territories)

Time Period: Historical data spanning multiple decades

Key Attributes:

Disaster declaration and incident dates

State and region

Disaster / incident type (Flood, Storm, Drought, etc.)

Request status and assistance programs

Duration and frequency of incidents

This dataset represents real-world operational data, making it suitable for applied analytics and dashboard-driven insights.

3️⃣ Data Cleaning & Preparation (Before Dashboard Creation)

Before building the dashboard, the dataset was cleaned and prepared to ensure accuracy and reliability:

Missing values were checked across all columns to assess data quality.

Missing incident end dates were retained, as many disasters are ongoing or single-day events, making the absence of an end date valid.

Non-analytical identifier columns were removed since they do not contribute to trend or insight generation.

Data types were verified and corrected:

Date fields were formatted as date types

Numeric fields were converted to numeric formats

Categorical fields such as state and disaster type were treated as text

After cleaning, the structured dataset was imported into Power BI for modeling and visualization.

4️⃣ Exploratory Data Analysis (EDA in Business Context)

Exploratory Data Analysis was performed with a business-driven focus to understand:

How disaster requests vary over time

Which states are most affected

Which disaster types occur most frequently

Whether patterns exist across years and regions

EDA findings guided the selection of KPIs and visuals, ensuring the dashboard answered meaningful analytical questions rather than just presenting raw statistics.

5️⃣ KPIs & Measures Created

To summarize and monitor disaster trends, the following KPIs were created in Power BI:

Total Requests – Represents the overall number of disaster declaration requests

Unique States – Indicates the geographical spread of disasters

Rejected Rate – Shows the proportion of rejected requests, chosen instead of approval rate due to dataset characteristics

These KPIs provide a quick, high-level understanding of disaster activity.

6️⃣ Dashboard Structure & Visuals

The Power BI dashboard was structured into clear analytical components:

🔹 Overview Section

KPI cards showing total requests and state coverage

High-level summary of disaster activity

🔹 Time Trend Analysis

Line chart showing disaster requests by year

Helps identify spikes, declines, and long-term trends

🔹 State-wise Analysis

Bar chart highlighting top states by disaster requests

Filled map visualizing geographic concentration

🔹 Incident Type Analysis

Bar chart showing frequency of disaster types

Identifies dominant incident categories such as floods and storms

7️⃣ Interactive Filters (Slicers)

To enable dynamic analysis, slicers were added:

State Filter: Focuses analysis on selected states

Disaster Type Filter: Allows analysis of specific incident categories

Year Filter: Enables time-range based exploration

All visuals and KPIs update automatically based on slicer selections, allowing flexible and focused analysis.

8️⃣ Key Insights Derived

Disaster declaration requests have increased over time, with noticeable spikes in certain years

Floods and severe storms are the most frequently declared disaster types

A small number of states contribute a disproportionately high number of requests

Disaster activity shows variation across regions and time periods

9️⃣ Recommendations Based on Analysis

Focus disaster preparedness efforts on high-frequency states

Allocate resources based on historical disaster patterns

Strengthen planning for dominant disaster types such as floods and storms

Use historical trends as a foundation for future predictive analysis

🔧 Tools & Technologies Used

Python: Data cleaning and preliminary analysis

Pandas & NumPy: Data manipulation and transformation

Power BI Desktop: Data modeling, measures, and dashboard creation

Jupyter Notebook: EDA and documentation

GitHub: Version control and project sharing

🏁 Project Outcome

This project demonstrates an end-to-end data analytics workflow—from raw data cleaning and business-oriented EDA to interactive dashboard development—providing actionable insights into disaster trends, geography, and incident patterns using Power BI.
