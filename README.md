# NYC_Collisions_Project

Tools Used: Snowflake, AWS, Python, SQL, Tableau 

The primary objective was to leverage the Motor Vehicle Collisions dataset to gain insights into the patterns, causes, and consequences of road incidents, ultimately contributing to improved public safety measures and policy decisions. 

The project followed a structured data analysis approach, involving several key steps:

1. Data Preparation: Extensive data cleaning and transformation processes were undertaken, including handling missing data, parsing dates and times, and consolidating vehicle types.  Python was utilized for data cleaning and preprocessing.

2. Data Modeling and ETL: A dimensional modeling approach was adopted, designing a STAR schema with dimension tables (Date, Time, Location, Contributing Factors) and a central Collisions Fact table. SQL was employed for creating these tables and performing data transformations (Extract, Transform, Load) to load the cleaned data into a data warehouse in Snowflake.

3. Data Analysis and Visualization: Key Performance Indicators (KPIs) were identified, such as crashes by area, injuries/fatalities by contributing factors, and vehicle types involved. The team leveraged Tableau for data visualization, creating interactive dashboards and charts to uncover insights and trends from the analyzed data.

The analysis revealed valuable findings, including the identification of driver inattention/distraction and unsafe speed as predominant contributing factors to injuries and fatalities. Additionally, spatial patterns emerged, with boroughs like Brooklyn and Queens exhibiting higher crash rates, necessitating targeted interventions.

The project demonstrates the application of data engineering and analysis techniques, including data cleaning, ETL processes using Snowflake and AWS, dimensional modeling, and data visualization, to derive actionable insights from a complex dataset. The findings can potentially inform data-driven decision-making and policymaking aimed at enhancing road safety and reducing the impact of motor vehicle collisions in New York City.

![image](https://github.com/nischitabiradar/NYC_Collisions_Project/assets/143463343/777817ed-77b1-409c-b82c-a5f0e5768e57)
