# Video-Game-Sales-Ratings

## 1. Project Overview and Objective
This project aims to convert raw data named "Video Game Sale and Rating" into a refined format suitable for data warehouses, providing meaningful insights for data analysts, and facilitating user-friendly features for data visualization. By employing techniques such as data cleansing, normalization, and manipulation, the objective is to uncover significant patterns, trends, and key metrics from the raw data. The incorporation of supplementary fields will empower users to create dashboards, enabling the communication of compelling narratives to a broader audience.

## 2. Timeline and Milestones
For this project, I opted to give precedence to the gathering of requirements and the design phase, with a specific focus on data cleaning and data mining. This strategic approach holds particular merit for a small project constrained by a tight schedule. The advantages of emphasizing these aspects include the attainment of clear requirements and the creation of an efficient design, both of which contribute to minimizing development efforts.

**Milestone	Timeline**

* Requirement Gathering and Document	12/26 - 1/1/24
* Design	1/2/24 - 1/10/24
* Development	1/11/24 - 1/15/24
* Testing	1/16-24 - 1/19/24
* Implementation	1/20/24

## 3. Resources
**Owner:** Brendon Hwang; 
**Tools:** PostgreSQL, Microsoft Excel

## 4. Tasks
The following tasks outline the necessary steps to transform raw data into meaningful information. This list also specifies the data quality standards, emphasizing the need for cleaning and modification.
* 4.1 Create Data Dictionary
* 4.2 Create a reference table for the “Name” field: Creating a reference table for game names serves the purposes of normalizing data, facilitating easy data retrieval, and enhancing data quality.
* 4.3 Replace null value: Replace null value to "Data Not Available" with four fields (Name, Genre, Publisher, Developer, Rating)
* 4.4 Create new fields: The inclusion of the "Year_Range_of_Release" field facilitates data analysis by offering a concise timeframe for examination.  Create field that rank following sale fields (NA_Sales, EU_Sales, JP_Sales, Other_Sales, Global_Sales)
