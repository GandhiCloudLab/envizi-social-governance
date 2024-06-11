# Understanding Reports and Dashboards in Envizi

In this article, let us understand about the various reports and dashboards available in IBM Envizi ESG suite.

You will also be assisted with all the navigations that you can click and view on the dashboard to explore more details and view insights.

These insights will be help the users to make more informed decisions for optimal emissions management and to take next steps for decarbonization journey.

There are 4 types of reports available in Envizi.
- Dashboards
- Power Reports
- Extract Reports
- Envizi API

# 1 Dashboards

Dashboards are dynamic pages enabling the visualization and reporting of data in a graphical format.

They're accessible across different levels (Organizational, Group, Location, Account, Meter), typically found on a Summary page.

Below is the performance dashboard of the entire organization.

![](/images/190-dashboard-1.png)

Several controls are available in Dashboard.

- `Compare With` compares the current period with other periods.
- `View As` specifies the Unit of measure for the data in the dashboard. 
- `Time slider` indicates the current period chosen to display.
- The `filter` funnel activates the filtering options available: Groups, Measures, Regions, Locations.

## 1.1 Available Dashboards
Here is a list of important dashboards within Envizi.
<table>
    <tr>
        <th>Category</th>
        <th>Report Name</th>
    </tr>
    <tr>
        <td rowspan=9>Performance</td>
        <td>

[Organization Summary](https://github.com/ibm-ecosystem-engineering/envizi-reports/tree/main/50-org-summary)</td>
    </tr>
    <tr>
        <td>[Performance](https://github.com/ibm-ecosystem-engineering/envizi-reports/tree/main/51-org-performance)</td>
    </tr>
    <tr>
        <td>[Performance by Data Type](https://github.com/ibm-ecosystem-engineering/envizi-reports/tree/main/52-org-performance-by-datatype)</td>
    </tr>
    <tr>
        <td>[Performance by Group](https://github.com/ibm-ecosystem-engineering/envizi-reports/tree/main/53-org-performance-by-group)</td>
    </tr>
    <tr>
        <td>[Performance by Scope](https://github.com/ibm-ecosystem-engineering/envizi-reports/tree/main/54-org-performance-by-scope)</td>
    </tr>
    <tr>
        <td>[Performance by Tag](https://github.com/ibm-ecosystem-engineering/envizi-reports/tree/main/55-org-performance-by-tagtype)</td>
    </tr>
    <tr>
        <td>[Performance Trend](https://github.com/ibm-ecosystem-engineering/envizi-reports/tree/main/56-org-performance-by-trend)</td>
    </tr>
    <tr>
        <td>[Emissions Performance](https://github.com/ibm-ecosystem-engineering/envizi-reports/tree/main/57-org-emission-performance)</td>
    </tr>
    <tr>
        <td>[Energy Production](https://github.com/ibm-ecosystem-engineering/envizi-reports/tree/main/60-dashboard-energy-production)</td>
    </tr>
    <tr>
        <td rowspan=5>BENCHMARKS</td>
        <td>[Ranking Locations by Intensity](https://github.com/ibm-ecosystem-engineering/envizi-reports/tree/main/61-dashboard-ranking-locations-by-intensity)</td>
    </tr>                
    <tr>
        <td>[Ranking Locations by Ratio](https://github.com/ibm-ecosystem-engineering/envizi-reports/tree/main/62-dashboard-ranking-locations-by-ratio)</td>
    </tr>     
    <tr>
        <td>[Ranking Groups by Intensity](https://github.com/ibm-ecosystem-engineering/envizi-reports/tree/main/63-dashboard-ranking-groups-by-intensity)</td>
    </tr>
    <tr>
        <td>[Rate Analysis](https://github.com/ibm-ecosystem-engineering/envizi-reports/tree/main/64-dashboard-rate-analysis)</td>
    </tr> 
    <tr>
        <td>[Energy Star Portfolio](https://github.com/ibm-ecosystem-engineering/envizi-reports/tree/main/65-dashboard-energy-star-portfolio)</td>
    </tr> 
    <tr>
        <td>SOLAR</td>
        <td>[Solar Portfolio](https://github.com/ibm-ecosystem-engineering/envizi-reports/tree/main/66-dashboard-solar-portfolio)</td>
    </tr> 
    <tr>
        <td rowspan=2>METER ALERTS</td>
        <td>[Summary](https://github.com/ibm-ecosystem-engineering/envizi-reports/tree/main/68-dashboard-meter-alerts-summary)</td>
    </tr> 
    <tr>
        <td>[Notifications](https://github.com/ibm-ecosystem-engineering/envizi-reports/tree/main/70-dashboard-meter-alerts-notifications)</td>
    </tr> 
    <tr>
        <td rowspan=3>ISSUES</td>
        <td>[Summary](https://github.com/ibm-ecosystem-engineering/envizi-reports/tree/main/71-dashboard-issues-summary)</td>
    </tr>     
    <tr>
        <td>[Scheduled Issues](https://github.com/ibm-ecosystem-engineering/envizi-reports/tree/main/72-dashboard-issues-all-issues)</td>
    </tr>   
    <tr>
        <td>[All Boards](https://github.com/ibm-ecosystem-engineering/envizi-reports/tree/main/73-dashboard-issues-all-boards)</td>
    </tr>           
</table>

## 1.2 How to access Dashboards

The `Monitor` menu in top navigation contains several sub menus under the sections `PERFORMANCE`, `BENCHMARKS` and `METER ALERTS`. They are all the dashboards  available in Envizi.
![](/images/140-menu-0-org-monitor.png)

Dashboards are available at different levels in Envizi.

#### Organization Level
Here are the links to various dashboards available at the organization level. The menu items available in the first section (highlighted in dotted light blue line) of the each menu are the dashboards link.
![](/images/140-menu-1-org.png)

#### Group Level
Here are the links to various dashboards available at the group level. 
![](/images/140-menu-2-group.png)

#### Location Level
Here are the links to various  dashboards available at the location level. 
![](/images/140-menu-3-location.png)

#### Account Level
Here are the links to various  dashboards available at the account level. 
![](/images/140-menu-4-account.png)

## 1.3 Dashboards in Detail

Let us explore a dashboard in detail.

Here is the Organization Summary dashboard. The dashboard contains various information such as Emission, Costs, Summary and DayType Summary. 

- `Last updated On` show that time in which the data was refreshed from Envizi Data platform.
- A top left section shows the no. of locations, accounts and meters available in this organization.
- A section shows Emissions and Total cost. Also it shows the Actual/Accrued/Estimated percentages.
- Summary graph shows month wise emissions data for the last 12 months.
- Data Type Summary table shows the Emissions and Cost details for each DataType.

![](/images/120-Org-Summary-1.png)
![](/images/120-Org-Summary-2.png)

# 2. Power Reports

Envizi PowerReport is supercharged by Microsoft PowerBI. Envizi content powered by PowerReport provides a range of visual dashboards to support reporting.

![](/images/190-power-report.png)


## 2.1 Available Power Reports

Here are some of the important Power Reports available.

<table>
    <tr>
        <th>Category</th>
        <th>Report Name</th>
    </tr>
    <tr>
        <td rowspan=3>Base Platform</td>
        <td>
        
[Sustainability (Executive Report)](https://github.com/ibm-ecosystem-engineering/envizi-reports/tree/main/01-sustainability-executive-report)</td>
    </tr>
    <tr>
        <td>[Sustainability (Portfolio Performance)](https://github.com/ibm-ecosystem-engineering/envizi-reports/tree/main/12-sustainability-portfolio-performance)</td>
    </tr>
    <tr>
    <td>[Account Data Health Check](https://github.com/ibm-ecosystem-engineering/envizi-reports/tree/main/11-account-data-health-check)
</td>
    </tr>
    <tr>
        <td rowspan=3>Configurable Content</td>
        <td>

[Market-based Emissions](https://github.com/ibm-ecosystem-engineering/envizi-reports/tree/main/10-market-based-emissions)</td>
    </tr>
    <tr>
        <td>[CDP Climate Report](https://github.com/ibm-ecosystem-engineering/envizi-reports/tree/main/03-cdp)</td>
    </tr>
    <tr>
        <td>[Scope 3 Emissions](https://github.com/ibm-ecosystem-engineering/envizi-reports/tree/main/06-scope3-emissions-report)</td>
    </tr>
    <tr>
        <td>Programs</td>
        <td>[Programs Overview](https://github.com/ibm-ecosystem-engineering/envizi-reports/tree/main/08-programs-overview)</td>        
    </tr>
    <tr>
        <td rowspan=5 >Others</td>
        <td>[Envizi CSR Report](https://github.com/ibm-ecosystem-engineering/envizi-reports/tree/main/02-csr-report)</td>        
    </tr>
    <tr>
        <td>[Programs Savings](https://github.com/ibm-ecosystem-engineering/envizi-reports/tree/main/09-programs-savings)</td>        
    </tr>
    <tr>
        <td>[Utility Account Analytics](https://github.com/ibm-ecosystem-engineering/envizi-reports/tree/main/07-utility-account-analytics)</td>
    </tr>
    <tr>
        <td>[Turbonomic Performance Dashboard](https://github.com/ibm-ecosystem-engineering/envizi-reports/tree/main/40-turbonomic-performance-dashaboard)
        </td>        
    </tr>
</table>

## 2.2 How to access Power Report

#### Access via Menu

1. Click on `Reports > PowerReports`
![](/images/210-acess-power-report-1.png)

You will have power report list.

2. Click on any report that interests you.
![](/images/210-acess-power-report-2.png)

The report get displayed.
![](/images/210-acess-power-report-3.png)

#### Access via Global Search

1. You can also search for the report in the Global Search
![](/images/210-acess-power-report-4.png)

2. From the search result choose the appropriate report.
![](/images/210-acess-power-report-5.png)

## 2.3 Power Report in Detail

Lets us look at the one of a Power Report called `Scope 3 emissions Report` in detail.

#### 1. Open the Report

Open the report using the Reports search

![](/images/image-11.png)

![](/images/image-12.png)


###### 2. Report Home

Here is the report home page.

Click on the `>` to go to the next page

![](/images/image-13.png)

#### 3. Emissions Dashboard

Select the `Category 1 - Purchased ...`  and then

Click on the `Select a category to enable drill through` button.

![](/images/image-14.png)

#### 4. Category Analyis

Category Analyis get displayed.

Click on the `>` to go to the next page

![](/images/image-15.png)


#### 5. Contributor Dashboard

Contributor Dashboard is displayed.

Select the `Cairns Pty Ltd`  and then

Select the `contributor to enable drill through` button

![](/images/image-16.png)

#### 6. Contributor Analysis

Contributor Analysis get displayed.

Click on the `>` to go to the next page

![](/images/image-17.png)


#### 7. Data Gaps and Opportunities

Data Gaps and Opportunities Analysis get displayed.

![](/images/image-18.png)

Hover the circle to see the details in the tooltip.

![](/images/image-19.png)

#### 8. Various links

Here are the various links available to navigate to the above discussed screens.

![](/images/image-20.png)


## 2.4 PowerReport Edit

PowerReports can be edited and saved and kept private or shared with other Envizi users within your organization. The users with the PowerReport Edit work role can do this.

Here are the steps to edit the power report.

1. Open a Power report that you are interested.
2. Click on `Save a Copy` button.
![](/images/220-power-report-edit-1.png)

3. Enter the name and Click on `Save` button.
![](/images/220-power-report-edit-2.png)

4. Report cretaed and saved. Click on `View Report` button.
![](/images/220-power-report-edit-3.png)

5. The report is opened  for view. Click on `Edit` button.
![](/images/220-power-report-edit-4.png)

6. Make the changes.
![](/images/220-power-report-edit-5.png)

7. Report gets saved. 
![](/images/220-power-report-edit-5.png)


## 2.5 PowerReport Datasets

PowerReport Datasets are the `datasource` for the Power Reports in Envizi.  

PowerReports can be viewed, edited and saved, and shared with other Envizi users within the organization.  

Customers wishing to create their own reports or modify existing ones needs to utilize this dataset as a data source.

Here are the 3 datasets available in Envizi.

#### Monthly Dataset

The Monthly Dataset is an extensive collection of `monthly aggregated data` from your Envizi platform. It forms the backbone of most Standard PowerReports across various modules and serves as a foundation for creating impactful custom reports within the Envizi platform.

#### Survey Dataset

The Survey Dataset facilitates reporting on `surveys and scorecards` in Envizi’s PowerReport framework.

The dataset `includes all survey responses` for all surveys where at least one question has been answered. Survey responses from locations where no answers have been provided by respondents will be excluded from the dataset.

#### Daily Dataset

This dataset comprises various `daily metrics` obtained from `interval meter data`. This dataset is included as part of the Interval Meter Analytics module.

# 3 Extract Reports

IBM Envizi reports allow users to specify a range of selection criteria to view the data in screen and download and to send the report in mail.

Extracting reports provides the following options.
- Choose from various delivery methods (screen, email)
- Choose Groups, locations, Regions, Utilities, report time period/end date
- Choosing `Create Report and E-mail it now` in CSV, PDF, XLSX format
- Choosing `Schedule Report and E-mail it later` also adds the Daily, Weekly, ...etc. schedule.

Click Submit to run the report based on the selected parameters.
![](/images/301-extract-report-monthly-data-summary-4.png)

## 3.1 Available Extract Reports

Here are some of the important Extract Reports available.

<table>
    <tr>
        <th>Category</th>
        <th>Report Name</th>
        <th>Description</th>
    </tr>
    <tr>
        <td>Data Management</td>   
        <td>Account Style Data Extract</td>
        <td>This report extracts account items for a single account style</td>	
    </tr>
    <tr>
        <td>Data Management</td>
        <td>Annual Data Summary</td>
        <td>Shows annualized data held in all the accounts and meters for selected  locations</td>
    </tr>
    <tr>
        <td>Data Management</td>
        <td>Monthly Data Summary Report</td>
        <td>Shows all monthly data held in all the accounts and meters for selected  locations</td>	
    </tr>
    <tr>
        <td>Data Management</td>
        <td>Survey Responses</td>
        <td>This report creates a csv file that contains all the survey responses captured</td>
    </tr>
    <tr>
        <td>Emissions, Energy and Sustainability</td>
        <td>Consumption  Summary Report</td>
        <td>It provides a comprehensive review of the CO2e attributable to a location</td>	
    </tr>
    <tr>
        <td>Emissions, Energy and Sustainability</td>
        <td>Emission and Energy Factors</td>
        <td>This report lists the factors used to calculate the GHG emissions and energy consumed or produced within your organization.</td>	
    </tr>
    <tr>
        <td>Emissions, Energy and Sustainability</td>
        <td>Emission Sources Summary Report</td>
        <td>This report shows how much was consumed (kWh, L of fuel, etc.) at all locations and how much CO2e was emitted as a result.</td>	
    </tr>
    <tr>
        <td>Emissions, Energy and Sustainability</td>
        <td>Emissions by GHG Type</td>
        <td>This report summarizes emissions by Greenhouse Gas.</td>
    </tr>
    <tr>
        <td>System Setup Reports</td>
        <td>Account Style Extract</td>
        <td>This report lists all account styles in Envizi and their associated data type, sub type, field names (C1-C40) and account style rules.</td>	
    </tr>
    <tr>
        <td>Emissions, Energy and Sustainability</td>
        <td>Energy Consumption Detailed</td>
        <td>his report shows activity data in native units and energy in GJ for all locations across your organization.</td>	
    </tr>
    <tr>
        <td>EPA Energy Star Reports</td>
        <td>Energy Star Ratings</td>
        <td>extracts Energy Star ratings details that have been captured in Location Ratings</td>	
    </tr>
    <tr>
        <td>Extract Reports</td>
        <td>Attachment Summary</td>
        <td>provides a list of attachments across the Organization from Organization, Group, Location, Account and Meter levels</td>	
    </tr>
    <tr>
        <td>Extract Reports</td>
        <td>Audit History Report</td>
        <td>This report lists all changes made by a specified user within a company for the selected period.</td>
    <tr>
        <td>Extract Reports</td>
        <td>Extract for Accounts</td>
        <td>The report details account info such as account style, data type, location name and etc</td>	
    </tr>
    <tr>
        <td>Target Reports</td>
        <td>Monthly Performance - Actual vs Target and Budget</td>
        <td>Report compares the actual consumption in native units and cost  for a selected period</td>
    </tr>
</table>

## 3.2 How to extract the report

1. Enter a report name in the Global  Search. Ex: Monthly Data Summary
![](/images/301-extract-report-monthly-data-summary-1.png)
It will display the report in the search results.

2.  You can click on the report
![](/images/301-extract-report-monthly-data-summary-2.png)

It shows the report home page.

3. Click on the second page arrow in the top to go to next page.
![](/images/301-extract-report-monthly-data-summary-3.png)

The second page is displayed.
![](/images/301-extract-report-monthly-data-summary-4.png)

4. Click on `DOWNLOAD AS CSV` button to download the report in csv format.
![](/images/301-extract-report-monthly-data-summary-5.png)

The csv file looks like this.
![](/images/301-extract-report-monthly-data-summary-6.png)

# 4 Envizi API

The Envizi API helps to export data from the Envizi platform and allows users to access and retrieve data from Envizi directly through compatible third party software, such as Microsoft Excel, Tableau or Power BI, without the need to log in to Envizi's main user interface. This process is secured and it enables the users to create and consume custom dashboards and reports.

The Envizi API is built on top of Envizi's existing reporting framework. A selective list of Envizi reports can be exposed as APIs after going through a certification and validation process. With the Envizi API, users are able to get data in a pre-defined tabular report format which allows for further BI analysis and manipulation in the client tool. 

Technically, Envizi API is a Web Service API which employs RESTful architecture and returns data in JSON format. 

Using the APIs you can able to do the following.
- Retrieve report names
- Retrieve report parameters
- Retrieve report data

Refer the below article to understand about How to use Envizi API.

Use APIs to expose Envizi data to external systems
https://developer.ibm.com/articles/use-apis-to-expose-envizi-data-for-external-systems/


