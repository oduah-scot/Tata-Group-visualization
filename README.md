# Tata-Group-visualization
Empowering Business with Effective Insight 
Project details steps taken to analyse Let me begin by reviewing and cleaning the dataset based on the following criteria:Ensure that the quantity is not below 1 unit.
Ensure that the unit price is not below $0. The dataset has been cleaned, with 530,693 rows remaining. We removed any records where the quantity was less than 1 or the unit price was below 0. Once i'm done this, i can import the cleaned data into Power BI to create the required visuals. To create a time series visualization of revenue data for 2011, with monthly granularity in Power BI, follow these steps: Load the cleaned data (as per the previous instructions). Create a New Measure for Revenue. Go to the Data view. Select the table with your imported data. In the top ribbon, click on "New Measure" and create a measure for Revenue by multiplying the Quantity and Unit Price. ilter Data for the Year 2011. Create a new Report page. In the Visualizations pane, drag the InvoiceDate column into the "Filters on this page" area.Set a filter for the InvoiceDate to show only data from 2011: In the filter, choose "Advanced filtering" and select the range from 01/01/2011 to 31/12/2011.
Creating visualisation to respond to the CMO and CEO demand



#### [<h2>Certificate of Completion</h2>](https://forage-uploads-prod.s3.amazonaws.com/completion-certificates/Tata/MyXvBcppsW2FkNYCX_Tata%20Group_CwhEAuevvJsafxPg6_1727284227103_completion_certificate.pdf)

<h2>Practical Skills Developed</h2>

<b> Teamwork | Strategy | Project Planning | Data Understanding | Data Modeling | Data Analysis and leaning | Storytelling | Data Visualization | Presentations | Communication | Public Speaking </b> 

<h2>Tools Used</h2>

- <b>Power Quary</b>
- <b> Power Bi</b> 

<h2>Environment Used </h2>

- <b>Windows 11</b>

<h2>Project walk-through:</h2>

<p align="center">
Contents, Reactions and Reactions types Datasets: <br/>
<img src="https://i.imgur.com/D9nt71S.png" height="80%" width="100%" alt="Data Analysis Steps"/>
<br />
<br />
To create a time series visualization of revenue data for 2011, with monthly granularity in Power BI, Step-by-Step Guide:  Filter Data for the Year 2011
Create a new Report page. In the Visualizations pane, drag the InvoiceDate column into the "Filters on this page" area. Set a filter for the InvoiceDate to show only data from 2011: In the filter, choose "Advanced filtering" and select the range from 01/01/2011 to 31/12/2011. Step 4: Create a Time Series Line Chart Drag InvoiceDate into the Axis section of the canvas. Drag your newly created Revenue measure into the Values section. select the Line Chart option. In the InvoiceDate column, ensure the date granularity is set to Month. Click the dropdown under InvoiceDate (in the "Axis" field) and select Month to show monthly granularity. Step 5: Format the Visual.
Labels: Ensure data labels are visible to easily see monthly revenue values.Axis: Format the X-axis to display months properly (e.g., Jan, Feb, etc.).
Step 6: Add Seasonal Trend Analysis
This will give the CEO a clear view of the monthly revenue for 2011, allowing them to analyze trends and forecast for the upcoming year.
<br/>

  <img src="https://i.imgur.com/ubUeQzg.png" height="80%" width="80%" alt="Data analysis steps"/>
<br />
<br />
Filter Out the United Kingdom In the Report view, drag the Country column into the Filters pane (right-hand side). Under Filters on this visual, select Country.Choose "Advanced filtering" and apply the following filter: Country does not equal "United Kingdom." This will exclude the United Kingdom from the visual. Step 3: Create a Bar Chart for the Top 10 Countries by Revenue Drag Country into the Axis section of the canvas. Drag your Revenue measure into the Values section. create a bar chart. In the Visualizations pane, use the Filters section and apply a Top N filter: Click the drop-down next to Country.Select Top N and set it to show the Top 10 by Revenue.Step 4: Add Quantity Sold, Drag the Quantity field into the Values section alongside Revenue. The chart will now show both Revenue and Quantity Sold for the top 10 countries. Power BI will automatically stack the bars for the two values. Data Labels: Enable data labels for both Revenue and Quantity to display the actual values.
This chart will give the CMO a clear view of the top 10 countries generating the highest revenue (excluding the UK) while also showing the quantity sold.
 <br/>
<img src="https://i.imgur.com/7hHfj7d.png" height="80%" width="80%" alt="Data analysis steps"/>
<br />
To create a visual showing the top 10 customers by revenue, with the highest revenue-generating customer at the start and gradually decreasing, we will use a sorted bar chart in Power BI. Here's a step-by-step: Ensure the Revenue Measure is Created. In the Report view, drag the CustomerID column into the Axis section of the visual canvas. Drag the Revenue measure into the Values section. create a bar chart showing revenue by customer.use the Filters pane: Click on the drop-down next to CustomerID in the "Filters on this visual" section. Select Top N and set it to display the Top 10 by Revenue. Drag the Revenue measure into the By Value field. Click Apply filter Ensure the bar chart is sorted in descending order (highest to lowest revenue): Click on the three-dot menu (ellipsis) on the top-right of the chart. Choose Sort by Revenue. Make sure Sort descending is selected to show the highest revenue at the top and gradually decrease. 
<br/>
<img src="https://i.imgur.com/crSyx3J.png" height="80%" width="80%" alt="Data analysis steps"/>
<br />
<br />

To help the CEO gain insights on the demand for products across all countries (excluding the United Kingdom), we can create a map visualization in Power BI. This map will show the total quantity of products sold per country, giving a clear view of regions with the highest demand. Here's how to set it up step-by-step to Create the Map Visual for the CEO in Power BI: Step 1: Ensure the Data is Ready. Make sure the data includes the following columns:
Country: The countries where the sales occurred.
Quantity: The total quantity of products sold.
InvoiceDate (if filtering by specific time periods is necessary).
Step 2: Create the Map Visualization. Drag the Country Field: In Report view, drag the Country column to the canvas Add Quantity to the Map: Drag the Quantity column into the Size or Values field. This will scale the size of the circles (bubbles) on the map based on the total quantity of products sold in each country. Exclude the United Kingdom: In the Filters pane, drag the Country column into Filters on this visual. Set a filter to exclude the United Kingdom:Choose Advanced filtering.Set the filter to Country does not equal "United Kingdom".Step 3: Customize the Map: In the Format pane, customize the map's visual style to ensure all regions are clearly visible.
You can adjust the bubble size to ensure countries with higher demand stand out more.
Data Labels: Enable data labels to display the actual quantity sold for each country.
This will help the CEO quickly identify the countries with the highest demand without needing to hover over the map.
Step 4: Provide a Clear Overview, Use a flat map view so all the data points are visible in one glance.
Step 5: Analyze the Data for Expansion Opportunities
The map will visually show the regions with the greatest demand for the company's products.
The size of the bubbles will correspond to the total quantity sold, making it easy for the CEO to identify areas of high potential for business expansion.
This map visualization will give the CEO a clear overview of where the highest demand for products lies globally, excluding the United Kingdom, and help in identifying regions for potential business expansion.

<br/>
<img src="https://i.imgur.com/lIdXQ0e.png" height="80%" width="80%" alt="Data analysis steps"/>
<br />
<br />
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
