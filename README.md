# Electric_Vehicle_Population_Dashboard
Analyzing Electric Vehicle Adoption Trends and Performance Across Regions
1. Project Overview:
The Electric Vehicle Population Analysis project aims to explore trends and insights from statewide electric vehicle registration data. The dataset contains detailed information about EV models, manufacturers, electric range, MSRP, geographic distribution (city, county, census tract), and eligibility for clean vehicle incentives.
Objective:
The main objective is Analyze EV Adoption Trends, Understand Geographic Distribution, Evaluate Market Characteristics, Assess Environmental & Policy Impact, Build Interactive Dashboards.
________________________________________
2. Data Sources:
●	Source Description and Timeline: Catelog/ Google Dataset Search.
●	Domain: Environment/ Marketing
________________________________________
3. Problem Statement:
      1. Analyze overall electric vehicle (EV) adoption across different regions using the dataset.
     2. Identify trends in EV growth by model year to understand how adoption has changed over time.
     3. Compare EV manufacturers to determine which makes and models are most widely used.
     4. Evaluate electric range performance across vehicles to understand capability differences between BEVs and PHEVs.
    5. Identify geographic hotspots (cities, counties, ZIP codes) where EV adoption is highest.
   6. Determine the distribution of vehicle types (BEV vs PHEV) across regions.
   7. Examine CAFV eligibility trends to see how many vehicles qualify for clean fuel programs.
   8. Provide insights to support EV infrastructure planning, such as charging station expansion in high-adoption areas.
   9. Create interactive visualizations and filters to allow decision-makers to explore EV characteristics by location, model year, make, vehicle type, and electric range.

________________________________________
4. Attribute (Column /Features) Details: 
Attribute Name	Data Type	Description
Vehicle Identification Number	Integer / String	Unique identifier for each vehicle
Model Year	Numeric (Integer)	Year of Manufacture
Make	String (Text)	Manufactured company name
Model	Integer / String	Specific type of model
Electric Vehicle Type	String (Text)	Hybrid or electric vehicle type
Clean Alternative Fuel Vehicle (CAFV) Eligibility	String (Text)	Eligible or not for Clean Alternative Fuel Vehicle
Electric Range	Numeric (Integer)	Electric vehicle range
Base MSRP	Numeric (Integer)	Base Speed of the vehicle
Legislative District	Numeric (Integer)	Vehicle charging district number
DOL Vehicle ID	Numeric (Integer)	Unique number for Department of licensing
County	String (Text)	Country of vehicle manufacture
City	String (Text)	City of Vehicle manufacture
State	String (Text)	State of Vehicle manufacture
Postal Code	Numeric (Integer)	Postal code of vehicle
Vehicle Location	String / Integer	Location of vehicle
Electric Utility	String (Text)	Usage of Electricity
2020 Census Tract	Numeric (Integer)	Census tracking of vehicle
________________________________________
5. Tools & Technologies
●	Excel: Data cleaning, transformation, and Pivot Tables.
●	Power BI: Data modelling, DAX calculations, visualization, and interactive dashboard creation.
________________________________________
6. Data Pre-Processing (Excel / Power Query)
Tasks Performed:
●	Data Cleaning & Transformation: Removed duplicates, handled missing values, standardized formats, and created calculated fields for Country, City, State, Postal Code, Make, Model, Electric range, Base MSRP, Legislative District, Vehicle Location, Electric Utility, 2020 Census Tract columns.
●	Filtering & Sorting: Organized data to focus on relevant records for DOL Vehicle ID.
●	Pivot Tables: Generated Pivot Tables for data summarisation and initial insights.
●	Convert the data into Fact and Dimension Table 
Fact Table – Electric Vehicle Population Data
Dimension Table – Dimvehicle, DimGeography
●	Data Model: Established relationships between tables, defined cardinality, and created lookup tables where necessary.
●	Calculated Columns & DAX Measures: 
DAX Measure:
Total EVs = COUNT('Electric vehicle population'[VIN ])
Analysis and Visualizations (Power BI):
EV adopted by year
EV by State (Region)
Top 10 EV Makers
BEV vs PHEV
Average Electric Range
CAFU Eligibility
●	Key Findings: 
Strong Growth in EV Adoption
•	Electric vehicle registrations have increased significantly in recent years, with a sharp rise after 2018.
•	This indicates growing consumer acceptance and supportive government policies.
Battery Electric Vehicles (BEVs) Dominate
•	BEVs account for a larger share of total EVs compared to Plug-in Hybrid Electric Vehicles (PHEVs).
•	The market is gradually shifting toward fully electric solutions.
Regional Concentration of EVs
•	EV adoption is highly concentrated in a few states and cities.
•	Urban and coastal regions show much higher EV penetration than rural areas.
Top Manufacturers Lead the Market
•	A small number of manufacturers contribute to the majority of EV registrations.
•	Certain brands consistently appear among the top performers across multiple years.
Improvement in Electric Range
•	Average electric range has improved steadily with newer model years.
•	Technological advancements are making EVs more practical for long-distance travel.
CAFV Eligibility Coverage
•	Most registered EVs qualify for Clean Alternative Fuel Vehicle (CAFV) incentives.
•	Incentive eligibility plays a key role in adoption decisions.

●	Analysis insights:
           Descriptive : Summarize historical EV data to understand current and past trends.
•	Total EV registrations have increased consistently year over year.
•	Battery Electric Vehicles (BEVs) represent the majority of EVs compared to Plug-in Hybrid Electric Vehicles (PHEVs).
•	EV adoption is unevenly distributed, with certain states and cities accounting for a large share of registrations.
•	A small number of manufacturers dominate the EV market.
•	Average electric range has improved with newer vehicle model years.
•	Most vehicles qualify for CAFV (Clean Alternative Fuel Vehicle) eligibility.

           Diagnosis: Identify the factors driving observed trends and patterns.
•	Higher EV adoption in specific states is driven by:
o	Strong government incentives
o	Better charging infrastructure
o	Higher urbanization levels
•	BEVs dominate due to:
o	Lower long-term operating costs
o	Zero fuel dependency
o	Improvements in battery technology
•	Manufacturers with wider model portfolios and higher electric ranges show stronger market penetration.
•	Vehicles with CAFV eligibility see higher adoption, highlighting the impact of incentive policies.
•	Older model years show lower range and adoption due to technological limitations at the time.
             Predictive: Forecast future EV adoption based on historical patterns.
•	EV registrations are expected to continue growing rapidly if current trends persist.
•	BEVs will likely further increase their market share, gradually reducing the dominance of PHEVs.
•	Average electric range will continue to improve as battery technology advances.
•	EV adoption will expand beyond current hotspots into mid-tier cities and emerging regions.
•	Manufacturers investing in high-range and affordable models will gain market share.
             Prescriptive: Recommend actions based on insights to optimize outcomes.
             For Policymakers:
•	Expand CAFV incentives to underserved regions.
•	Invest in public charging infrastructure in low-adoption areas.
•	Encourage EV adoption in rural and semi-urban regions through targeted subsidies.
            For Manufacturers:
•	Focus on producing affordable BEVs with longer electric ranges.
•	Expand model offerings to cater to diverse customer segments.
•	Target high-growth regions identified through adoption trends.
           For Utility & Infrastructure Planners:
•	Prioritize charging station deployment in emerging EV markets.
•	Use adoption trends to forecast electricity demand and grid upgrades.
10. Conclusions:
* The Electric Vehicle market is rapidly expanding and transitioning toward fully electric vehicles.
* Geographic, technological, and policy factors strongly influence adoption patterns.
* Improvements in battery technology and electric range are accelerating consumer confidence.
* Manufacturers focusing on high-range BEVs and regions investing in charging infrastructure are driving the market forward.
* Overall, the dataset highlights a positive and sustainable future for electric mobility, with continued growth expected in the coming years.

