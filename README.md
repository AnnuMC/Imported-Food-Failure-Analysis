# Imported Food Failures Dashboard: Insights from IFIS Inspections

## Objective

This project would involve examining the monthly failing food reports published by the Australian Department of Agriculture's Imported Food Inspection Scheme (IFIS) in the years 2022-2024. The IFIS is one part of the Australian food regulatory system, with imported food subject to post-border food regulation in each state and territory. The analysis could identify patterns in non-compliance, assess associated public health risks, and evaluate the effectiveness of current inspection protocols. 

## Problem Statements

1. which countries poses the greatest risk to Australian food safety standard?
2. Which food products require stricter inspection protocols?
3. Are some producers consistently failing food inspection protocols?
4. What major reasons contribute to the failing of the imported product?
5. Is there any seasonal trends that can help predict future risk?
6. Does patterns in reference criteria helps to evaluate the effectiveness of current protocols?


## Data Sources
https://data.gov.au/dataset/ds-dga-e56bcf6a-7bfb-4cb5-8c65-8ec18bd4b7d5/details?q=food%20import


## Tools & Technologies Used
Power BI


## Project Workflow

### Data Cleaning
To standardize all months report as same, corrected column name
Corrected the dates according to the month to which its reported
Renamed products with correct spellings
Renamed the country names with transformation table
Renamed producers
spilit reason and test applied as two seperate columns
split category and HO number
DAX used calculated measures to count no of products
Merged multiple years data
 
### Visualisation
 Visual Element like KPI cards, Bar graphs, line charts, pie charts. 
 Slicers, buttons, bookmarks, tooltips and cross report filtering adds interactivity to the visuals.

## Key Findings

1.Failed food count increases over years. The Risk category products show high increase in count whereas surveillance has slight dip.
2.Origin Trends: 
  India tops in risk category with major failed foods items like chilli powder and tapioca chips. In surveillance category, China tops with items failing in fruit and       vegetables residue screen test.
3.Producer Trends:
  Arira Pangindo from Indonesia has mostly failed in inspections in 2024 with cassava chips due to detection of hydrocyanic acid more than level permitted.
  Pt Rani Investindo has failed more products in September 2023
  Innovative Cuisine has contributed to high increase of food failure in 2024.
4.Criteria Trends: 
  FSC 1.4.1 failed more products from Indonesia & India on detection of Hydrocyanic acid, Histamine, Aflatoxin in excess levels. 
  FSC 1.4.2 tops the reference for food failure under surveillance category after undergoing fruit and vegetable residue test.

## Recommendations

As the failed food imports keeps increasing over the years, its important to closely monitor the specific producers and countries who repeatedly fail the Australian Standards. More than issuing certificate and re-exporting, measures to be taken to control their manufacturing and imports into Australia.

## Visual Examples
![Import Failure Dashboard](https://github.com/user-attachments/assets/751cbfc8-a097-4ec1-9e49-46c67d281c05)


## How to Run the Project

1. Using GitHub Desktop and Power BI Desktop: Clone the Repository- Download the Power BI project ( .pbip) file from your GitHub repository and save it locally. Open in Power BI Desktop- Navigate to the .pbip file in your local file system and open it in Power BI Desktop, which will open the .pbix file associated with the project. Preview and Make Changes- You can now interact with the report, data model, and other elements within the Power BI Desktop environment.

2. Using the Power BI Service: Import the .PBIX or .PBIP- You can upload the .PBIX file directly into the Power BI Service or import the entire .PBIP folder. View and Interact- The Power BI Service will allow you to view the report, interact with visuals, and potentially share it with others.
