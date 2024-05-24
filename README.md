# Power-BI
# Introduction
* Power BI takes intimidation and hassle out of data analysis and visualization.
* Power BI is a business analytics service by Microsoft. It provides interactive visualizations and business intelligence capabilities with an interface simple enough for end-users to create their own reports and dashboards.
* Power BI can connect to a wide range of data sources, including databases, cloud services, Excel files, and web services, allowing users to gather data from various sources and visualize it in meaningful ways.
*  It's often used for data analysis, data visualization, and sharing insights across an organization.

## Describe using Power BI to build data-driven analytics
* Microsoft Power BI is a collection of software services, apps, and connectors that work together to turn your unrelated sources of data into coherent, visually immersive, and interactive insights.
*  From data in a simple Microsoft Excel workbook, or a collection of cloud-based and on-premises hybrid data warehouses, Power BI lets you easily connect to your data sources, clean, and model your data without affecting the underlying source, visualize (or discover) what's important, and share that with anyone or everyone you want.
*  Power BI consists of a Microsoft Windows desktop application called Power BI Desktop, an online SaaS (Software as a Service) service called the Power BI service, and mobile Power BI apps that are available on phones and tablets.
*  These three elements, Power BI Desktop, Power BI Service, and Power BI Mobile apps are designed to let people create, share, and consume business insights in the way that serves them, or their role, most effectively.
*  ![image](https://github.com/ZiyandaPetela/Power-BI/assets/123364433/30b45bb6-16ae-4548-82b3-4b490bbb1624)

## Explore the different Power BI elements
* To create Power BI Solutions, there are several major building blocks. These elements help not only what data is being presented, but also how it appears to those users who are consuming it.
* Those elements are datasets, reports, and dashboards. All elements are organized into workspaces, and they're created on capacities.
######  More information on the elements:
* Capacities
* Capacities are a core Power BI concept representing a set of resources used to host and deliver your Power BI content.
*  Capacities are either shared or dedicated. A shared capacity is shared with other Microsoft customers, while a dedicated capacity is fully committed to a single customer.
*  Dedicated capacities require a subscription. By default, workspaces are created on a shared capacity.

*  Workspaces
*  Workspaces are containers for dashboards, reports, datasets, and dataflows in Power BI.
*  two types of workspaces: My workspace and workspaces.
*  My workspace is the personal workspace for any Power BI customer to work with your own content.
*  You can share dashboards and reports from your My Workspace.
*  If you want to collaborate on dashboards and reports or create an app, then you want to work in a workspace
*  Workspaces are used to collaborate and share content with colleagues. You can add colleagues to your workspaces and collaborate on dashboards, reports, and datasets.
*   With one exception, all workspace members need Power BI Pro licenses.
*   Workspaces are also the places where you create, publish, and manage apps for your organization.
*   Think of workspaces as staging areas and containers for the content that makes up a Power BI app.
*    So, what is an app? An app is a collection of dashboards and reports built to deliver key metrics to the Power BI consumers in your organization. Apps are interactive, but consumers can't edit them. App consumers, colleagues who have access to the apps, don't necessarily need Pro licenses.

## Semantic models
* A semantic model is a collection of data that you import or connect to.
* Power BI lets you connect to and import all sorts of semantic models and bring all of them together in one place. Semantic models can also source data from dataflows.
* Semantic models are associated with workspaces and a single semantic model can be part of multiple workspaces.
* When you open a workspace, the associated semantic models are listed under the semantic models tab.
* Each listed semantic model represents a collection of data. For example, a semantic model can contain data from an Excel workbook on OneDrive, an on-premises SSAS tabular semantic model, and/or a Salesforce semantic model.
## Shared semantic models
* When expert data modelers in your organization create and share optimized semantic models, report creators can start with those semantic models to build accurate reports.
* Your organization can have consistent data for making decisions, and a healthy data culture.
*  To consume these shared semantic models, just choose Power BI semantic models when
creating your Power BI report.

## Reports
* A Power BI report is one or more pages of visualizations such as line charts, maps, and other elements.
*  You can create reports in Power BI from scratch, import them from shared dashboards, or have Power BI generate them when connecting to datasets.
*  For example, when you connect to an Excel workbook that contains Power View sheets, Power BI creates a report based on those sheets. And when you connect to a SaaS application, Power BI imports a prebuilt report.
* There are two modes to view and interact with reports:

* Reading view: When a report is opened by a user, it's displayed in reading view.
* Editing view: For individuals that have edit permissions, editing view is used to modify the different elements on the report and how they're presented.
* When a workspace is opened, associated reports are listed under the Reports tab.
*  Each listed report represents one or more pages of visualizations based on only one of the underlying datasets. To open a report, select it.
*  When you open an app, you're presented with a dashboard. To access an underlying report, select a dashboard tile (more on tiles later) that was pinned from a report. Keep in mind that not all tiles are pinned from reports, so you may have to click a few tiles to find a report.
*  By default, the report opens in Reading view. Just select Edit report to open it in Editing view (if you have the necessary permissions).

## Dashboards
* A dashboard is a single canvas that contains zero or more tiles and widgets. Each tile pinned from a report or from Q&A displays a single visualization that was created from a dataset and pinned to the dashboard.
* Entire report pages can also be pinned to a dashboard as a single tile. There are many ways to add tiles to your dashboard, too many to be covered in this overview topic.
* Why do people create dashboards? Here are just some of the reasons:
* To see all information needed to make decisions in one glance.\
* To monitor the most important information about your business.
* To ensure all colleagues are on the same page, viewing and using the same information.
* To monitor the health of a business, product, business unit, or marketing campaign, etc.
* To create a personalized view of a larger dashboard and show all the metrics that matter to them.
* When you open a workspace, the associated dashboards are listed under the Dashboards tab. To open a dashboard, select it.
* When you open an app, you are presented with a dashboard. If you own the dashboard, you also have edit access to the underlying dataset(s) and reports.


# Describe cleaning and transforming data in Power BI Desktop
* Cleaning and transforming data is how you prepare your data and get it ready to be used.
* To begin transforming and cleaning data, you use the Power BI Desktop application.
* Power BI Desktop has three views:
* Report view: You can create queries to build compelling visualizations that you can share with others. You can arrange them as you want them to appear.
* Data view: See the data in your report in data model format, where you can add measures, create new columns, and manage relationships.
* Model view: Get a graphical representation of the relationships that are established in your data model and manage or modify them as needed.

* Power BI Desktop includes the Power Query Editor tool, which can help you shape and transform data so that it's ready for your models and visualizations.
* ![image](https://github.com/ZiyandaPetela/Power-BI/assets/123364433/7b365fbe-b079-4274-b5cc-57155a614b25)

* To begin, select Edit from the Navigator window to launch Power Query Editor. You can also launch Power Query Editor directly from Power BI Desktop by using the Transform Data button on the Home ribbon.
* ![image](https://github.com/ZiyandaPetela/Power-BI/assets/123364433/368f1531-d725-4805-9026-4ff936075cd1)

## Transforming data
* transforming data is the process of putting data into a format that is useable in your reports. Examples of the available transformations include removing a column from the table, duplicating the column under a new name, or replacing values.

 ## Clean data
 * While Power BI can import your data from almost any source, its visualization and modeling tools work best with columnar data. Sometimes, your data isn't formatted in simple columns, which is often the case with Excel spreadsheets.
 * When you clean data, you might combine those rows into a single item to better format the data to fit your needs.
 * Or you may have a series of numeric data that would need to be aggregated to display better. With Power Query, there are a series of tools that you can use to prepare the data.

# Describe using AI Insights to spot trends and anomalies
* Power BI’s insights feature helps organizations easily identify insights such as anomalies and trends in your data as you interact and consume elements such as reports, dashboards, and visualizations.
* It notifies you if there are interesting insights and provides explanations for them.
*  It works out-of-the-box on any report, so you can automatically start getting insights from your reports without any setup.
*  Power BI has multiple insights features that use artificial intelligence (AI):
*  Insights for reports: Analyzes data and finds anomalies and trends in your data as you interact with reports.
*  Insights for individual visuals: Analyzes and explains the fluctuations of data points in visuals.
*  Insights for dashboard tiles: Looks at the data being used to render that tile and presents them in interactive visuals.
*  Quick Insights for datasets: Automatically generate data insights on a dataset in the Power BI service.
*  AI Insights for data models in Power Query: Provide access to pretrained machine learning models from Azure Cognitive Services.

## Notifications
* Power BI elements such as reports, Power BI automatically runs insights analysis.
* When Power BI identifies insights, you're presented with a notification. You can choose to either see the insights or ignore them.
*  Notifications are a great way to proactively interact with suggested insights to ensure that you're not missing anything important such as if sales in a specific region increased.
*  Top insights are those insights that are noteworthy, based on factors like recency and significance of the trend or anomaly.

## Get insights on reports and visuals
* The notification capabilities alert and notify you of insights as you're working on reports. There are also many scenarios where you may just be able to get insights as you walk through some of the different elements. As you're working with Power BI reports and visuals, you can select Get insights to open the Insights pane.
* The pane only shows insights about the current report page, and it updates when you select a different page on the report.
*  As you work with individual visualizations, you can select More options (...) in the upper-right corner of a visual, and then Get insights to see insights about just that visual.

## Insights
* The Insights pane currently shows three types of insights:
* Anomalies: Represents something that is out of the ordinary from what is expected. For example, a smart thermostat that suddenly reads the temperature as 100 F when it's typically 72 F would be considered an anomaly.
* Trends: Represents a pattern that is found in time-series datasets. For example, if a company’s sales are steadily increasing through the month of April that would represent a trend.
* Key Performance Indicator (KPI) analysis: Helps you evaluate the current value against a defined target. For example, a company might set a sales goal at 1.2 million, but currently they are at 1 million.

## Anomalies
* An anomaly is an abnormality in time-series data, such as unexpected spikes and dips in the data. An algorithm computes a boundary around what is considered a normal or expected value. Any value found outside this boundary is marked as an anomaly
* There are three types of anomaly insights:
* Significant anomaly: The anomaly has a high score. Anomaly score indicates how far the point is from the expected range.
* Recent anomaly: The most recent anomaly in the measure.
* Anomaly summary: This insight type summarizes multiple anomalies in the measure.
* When an anomaly in your data is flagged, Power BI runs an analysis across the different dimensions in your data model to look for spikes or dips in the measure that correlates to the anomaly. They're shown as possible explanations ranked by strength.

## Trends
* A trend occurs when there's a prolonged increase or decrease in time-series data. There are a series of steps the Power BI algorithm uses to find meaningful trends. \
* It first performs data smoothening, interpolation, and time-series sampling. The trends are then identified for statistical significance based on the slope and length of a change in value.
*  The algorithm removes noise like seasonality and outliers
* There are four main trends flagged:
* Long trend: The trend is significant and is the longest trend within a single series or across multiple series in a visual.
* Steep trend: The trend is significant and is the steepest trend within a single series or across multiple series in a visual.
* Recent trend: The trend is significant and is the most recent trend within a single series or across multiple series in a visual.
* Trend reversal: Recent trend in a single series or across multiple series in a visual where the reversal is significant, compared to the previous trend segment.
* When a trend in your data is flagged, Power BI looks for and identifies the categories that most influenced the increase or decrease in the identified trend. Possible explanations are ranked based on the relative contributions from different categories to the increase or decrease in trend.

# KPI analysis
* KPI analysis with a target looks at the variance of the current value to its target. It's considered significant if the variance is high or low compared to other segments.
*  KPI analysis without a target looks at the value itself and flags ones that are high or low compared to other segments.
*  For KPI analysis explanations, Power BI looks for and identifies the categories that have higher or lower than anticipated values.
*  For KPI analysis with target, possible explanations are ranked based on Z-scores of the difference of the value from the target.
*  Whereas for KPI analysis without a target, possible explanations are ranked based on the Z-scores of the value itself

# Build a basic dashboard
* With Power BI, we can easily create and share a dashboard with a manager by connecting to a data source such as an Excel spreadsheet on your laptop.
* While the data sources that you use might be different, the process for building and sharing a dashboard are same.
* You need to take the following steps:
* Prepare your data: Preparing the data ensures that it's in a format that Power BI can easily consume.
* Build a report: The report contains the visuals that you want to include in your dashboard. Depending on the scenario, reports can be built in either Power BI Desktop or using the Power BI Service.
* Pin the report visuals to a dashboard: Dashboards are the primary element that users use for viewing data. They can include data from multiple reports as needed.
* Share a link to the dashboard: Any users with the link and the necessary permissions are easily able to view and interact with the data.

## Prepare the data
* The first thing you need to do is ensure that your data is ready to be consumed.
* Depending on the data source and the volume of data you're working with, you may need to do some data cleansing and transforming using Power Query.
* If you are connecting to an Excel spreadsheet, make sure the data is in a flat table, and that each column contains the right data type. For example, text, date, number, or currency.
*  It's also important that you have a header row but no columns or rows that display totals.
*  Total operations are handled in Power BI as we create the visuals.

## Upload your data to the Power BI service
* The Power BI service is where you're able to create reports that connect to your data sources. This includes Excel files that live on your computer.
* With a few simple clicks, you can attach to a dataset, and Power BI creates a blank dashboard where you're able to place visuals later.
* we attached to sample financial data. It shows the completed Financial Sample dataset, and the blank dashboard.

## Build your report
* Once you connected to your data, you can either create a new report or edit an existing report that was created previously. Then we can begin editing the report by using the editing view. On the right are the Visualizations, Filters, and Fields panes.
*  Your Excel workbook table data appears in the Fields pane. At the top is the name of the table, financials. Under that, Power BI lists the column headings as individual fields.
*  Different visualizations are available that you can use to display the data in your report. Different visualizations can be added to the report based on the data that you want to communicate.
*  Once you connected to your data, you can either create a new report or edit an existing report that was created previously.
*  Then we can begin editing the report by using the editing view. On the right are the
*  Visualizations, Filters, and Fields panes.
*  Your Excel workbook table data appears in the Fields pane. At the top is the name of the table, financials. Under that, Power BI lists the column headings as individual fields.
*  Different visualizations are available that you can use to display the data in your report. Different visualizations can be added to the report based on the data that you want to communicate.
*   In the image, multiple bar charts are being used to showcase the number of units being sold. Additionally, map control is included to show sales volumes per country/region.

* Each visualization includes a series of filters and controls that can be used to impact how the data is being presented. For example, if you want to change the sum of units sold to display profit by date, you could switch the Y-axis from Sum of Units sold, to Sum of Profit.
* More visualizations are being added to Power BI to reflect how business is being done. For example, there's a Power Apps visualization that lets you build a canvas app directly in your Power BI report, which is connected to the Power BI data set.
*  As people interact with the data, the data in the Power App changes. For example, you could create a canvas app that includes actions such as sending emails or scheduling meetings.

  ## Pin to a dashboard
  * After you have all your visualizations on your reports, you can build your dashboard.
 *  Dashboards are easy to build because you're just determining which visuals from your created reports you want to include.Pin to a dashboard
  * Since dashboards can have visuals from multiple reports, it makes it easy to have detailed dashboards that include data from multiple data sources, even if some of those data sources might be unrelated.

## Share a link to your dashboard
* Initially dashboards that you create are only visible to the person that created them.
* You can share your dashboard and underlying report with any colleague who has a Power BI account. They can interact with it, but they can't save changes.
*  If you allow it, they can reshare with others or build a new report based on the underlying dataset.

## Consider the business value of Power BI
* It's now common knowledge that data can improve business processes and increase revenue.

*With Microsoft Power BI, organizations can create powerful data analytics and data visualizations to help more effectively drive data-driven business decisions. With multiple options for connecting and working with data, reports and visualizations can be easily created based on the wide variety of data that organizations need to work with daily. Reports and dashboards can be shared and embedded in other applications, making it simple for them to be consumed by anyone who should have access to the data. 

# What can I do with the Power BI service as a consumer?
* We live in a data culture where business decisions should be based on facts, not opinions. We need data to help us make these decisions.
* Power BI can help make your job easier and more effective at the same time by converting all that data into charts and graphs to help you visualize your data in meaningful ways.
* You can view data insights from colorful and compelling visuals instead of just lists and tables.
*  can explore your data further by looking for trends, insights, and other business intelligence.
*  The intuitive features of Power BI allow you to slice the content and even ask questions by using your own words.
*   Let Power BI monitor your data for you, and send you alerts when data changes beyond or beneath a threshold you set. All your data is available anytime, whether it's in the cloud or on-premises, from any device
* because the content isn't static, you can explore your data further by looking for trends, insights, and other business intelligence.
*  The intuitive features of Power BI allow you to slice the content and even ask questions by using your own words. Let Power BI monitor your data for you, and send you alerts when data changes beyond or beneath a threshold you set.
*   All your data is available anytime, whether it's in the cloud or on-premises, from any device.

## How to know if you're a Power BI consumer
* The way you interact with Power BI depends on your job role. As a user or consumer, you're the person who receives dashboards, reports, and apps from designers who create them.
*  Also, you work in the online version of Power BI, called the Power BI service, to review and interact with this data to make business decisions.\
*  You don't need to be a data scientist to perform complex data analysis. Power BI does the complex work for you with straightforward and intuitive controls.

## Safely interact with content 
* You can explore and interact with your content.
* Filter, slice, subscribe, and export content without affecting the underlying dataset or the original dashboards, reports, or apps
## Display details on a visual
* Visuals are made up of datapoints. By hovering over a datapoint, you can view the details.

## Show data that is used to create a visual
* Use the Show Data feature if you want to view data that Power BI is using to build a visual.
*  The selected visual expands to fill the canvas, and the data displays under or alongside the visual.
## Export data
* n addition to showing the data that's used to create a visual, you can also export that data and view it in Microsoft Excel.
*  When you export to Excel, you're creating a separate document, a spreadsheet that isn't part of Power BI. Any changes that you make in the Excel file don’t impact the data in Power BI.
*   Whether you want to take a closer look at the data, or you want to use the data in another application or for another purpose, Power BI gives you that flexibility.
*   Exporting isn't limited to individual visuals; you can export entire reports to PowerPoint or PDF to share with your colleagues.

## Cross highlight and cross filter report content
* All visuals in a report are related. Highlight or select a value in one visual and instantly view its impact on the other visuals.

## Collaborate with colleagues
* Skip the email. With the Power BI comment feature, you can add a personal comment or start a conversation with colleagues about a dashboard, right there on that dashboard. The comment feature is just one of the ways you can collaborate with others.
# Get alerts when your data reaches a threshold
* Your data is live, and your visuals update automatically. If you want to be notified when data changes beyond or beneath a threshold that you've set, use data alerts.
* Power BI sends you an email when the value passes any upper or lower limit that you set.
* Power BI provides everyone, not just data specialists, with real insight into what's happening. As a consumer, you can make better and more informed decisions. In Power BI, you have the tools to explore and interact with the data to find answers to questions and to discover new insights. Additionally, you can:
* Ask questions by using natural language.
* Collaborate with your team.
* Share what you discover.
* Take action from your desk or on the go.
* Power BI is straightforward and delivers powerful data-backed business intelligence to help you answer questions, make decisions, track progress, make predictions, stay up-to-date on a regular cadence, and much more.
*You used Power BI Home and the navigation pane to find your content: dashboards, reports, and apps.
 You opened a dashboard and added alerts and comments. On that dashboard, you selected tiles to open and view reports. With a report open, you moved between the report pages, changed display options, explored filters and bookmarks, and viewed and exported the underlying data
# GET DATA WITH POWER BI
* Before you can create reports, you must first extract data from the various data sources.
*  Interacting with SQL Server is different from Excel, so you should learn the nuances of both systems. After gaining understanding of the systems, you can use Power Query to help you clean the data, such as renaming columns, replacing values, removing errors, and combining query results. Power Query is also available in Excel.
*   After the data has been cleaned and organized, you're ready to build reports in Power BI. Finally, you'll publish your combined semantic model and reports to
  Power BI service.

# Get data from files
* Organizations often export and store data in files.
*  One possible file format is a flat file. A flat file is a type of file that has only one data table and every row of data is in the same structure.
*  The file doesn't contain hierarchies.
*  Likely, you're familiar with the most common types of flat files, which are comma-separated values (.csv) files, delimited text (.txt) files, and fixed width files
*  Another type of file would be the output files from different applications, like Microsoft Excel workbooks (.xlsx).
*  Power BI Desktop allows you to get data from many types of files. You can find a list of the available options when you use the Get data feature in Power BI Desktop.
# Flat file location
* Local - You can import data from a local file into Power BI. The file isn't moved into Power BI, and a link doesn't remain to it. Instead, a new semantic model is created in Power BI, and data from the Excel file is loaded into it. Accordingly, changes to the original Excel file aren't reflected in your Power BI semantic model. You can use local data import for data that doesn't change.
* OneDrive for Business - You can pull data from OneDrive for Business into Power BI. This method is effective in keeping an Excel file and your semantic model, reports, and dashboards in Power BI synchronized. Power BI connects regularly to your file on OneDrive. If any changes are found, your semantic model, reports, and dashboards are automatically updated in Power BI.
* OneDrive - Personal - You can use data from files on a personal OneDrive account, and get many of the same benefits that you would with OneDrive for Business. However, you'll need to sign in with your personal OneDrive account, and select the Keep me signed in option. Check with your system administrator to determine whether this type of connection is allowed in your organization.
* SharePoint - Team Sites - Saving your Power BI Desktop files to SharePoint Team Sites is similar to saving to OneDrive for Business. The main difference is how you connect to the file from Power BI. You can specify a URL or connect to the root folder.
* ![image](https://github.com/ZiyandaPetela/Power-BI/assets/123364433/661c25ff-aeb4-46bf-b4a2-ddbc14efee01)
* Using a cloud option such as OneDrive or SharePoint Team Sites is the most effective way to keep your file and your semantic model, reports, and dashboards in Power BI in-sync. However, if your data doesn't change regularly, saving files on a local computer is a suitable option.

## Connect to data in a file
*  on the Home tab, select Get data. In the list that displays, select the option that you require, such as Text/CSV or XML. For this example, you'll select Excel.
## Select the file data to import
* This window shows you the data that is available in your data source (the Excel file in this example). You can select a table or entity to preview its contents, to ensure that the correct data is loaded into the Power BI model.
### Change the source file
* You might have to change the location of a source file for a data source during development, or if a file storage location changes. To keep your reports up to date, you'll need to update your file connection paths in Power BI.
* Power Query provides many ways for you to accomplish this task, so that you can make this type of change when needed.
* Data source settings
* Query settings
* Advanced Editor
* try changing the data source file path in the data source settings. Select Data source settings in Power Query. In the Data source settings window, select your file and then select Change Source. Update the File path or use the Browse option to locate your file, select OK, and then select Close.

## Get data from relational data sources
*  can use Power BI Desktop to connect directly to the database instead of using exported flat files.
*  Connecting Power BI to your database will help you to monitor the progress of your business and identify trends, so you can forecast sales figures, plan budgets and set performance indicators and targets.
*   Power BI Desktop can connect to many relational databases that are either in the cloud or on-premises.
## Select data to import
* After the database has been connected to Power BI Desktop, the Navigator window displays the data that is available in your data source (the SQL database in this example). You can select a table or entity to preview its contents and make sure that the correct data will be loaded into the Power BI model.
* Select the check box(es) of the table(s) that you want to bring in to Power BI Desktop, and then select either the Load or Transform Data option.
* Load - Automatically load your data into a Power BI model in its current state.
* Transform Data - Open your data in Microsoft Power Query, where you can perform actions such as deleting unnecessary rows or columns, grouping your data, removing errors, and many other data quality tasks.

## Import data by writing an SQL query
* Another way you can import data is to write an SQL query to specify only the tables and columns that you need.
* To write your SQL query, on the SQL Server database window, enter your server and database names, and then select the arrow next to Advanced options to expand this section and view your options. In the SQL statement box, write your query statement, and then select OK.
### Change data source settings
* After you create a data source connection and load data into Power BI Desktop, you can return and change your connection settings at any time. This action is often required due to a security policy within the organization, for example, when the password needs to be updated every 90 days. You can change the data source, edit permissions or clear permissions.


# Build Power BI visuals and reports
* Defining clear goals at the start of a reporting project is essential for its success. These goals provide a framework for identifying the specific needs related to audiences, report types, user interface (UI), and user experience (UX). Here's how to outline these goals for each area:
1. Audiences
Goal: Identify and understand the different stakeholders who will use the reports.
Requirements:
User Profiles: Define who the end users are (e.g., executives, managers, analysts, clients, general employees).
Information Needs: Determine what specific information each user group requires.
Access Levels: Establish different access permissions based on user roles to ensure data security and relevance.
2. Report Type
Goal: Specify the types of reports that will meet the needs of the identified audiences.
Requirements:
Frequency: Decide whether reports are needed on a daily, weekly, monthly, or ad-hoc basis.
Format: Determine the format of reports (e.g., dashboards, PDFs, spreadsheets).

### Identify the audience
* Identifying the audience is a vital step in the report design process because it allows the report creator to produce a result that is both practical and tailored to the needs of the report users.
* Report consumers can generally be classified into three groups:
* Executives
* Analysts
* Information Workers
* Executives are individuals tasked with making strategic plans and decisions, often with a medium to long-term perspective. They are responsible for ensuring the business operates efficiently. For example, C-level executives at Contoso Skateboard Store fall into this category.
* An analyst is someone who offers insights and guidance to the organization. Their responsibilities can vary widely, but they generally focus on assessing the effectiveness of business strategies, developing or enhancing processes, or implementing changes. A business analyst or data analyst in the sales division of Contoso Skateboard Store is an example of an analyst audience.
* An information worker is an individual who uses data to make decisions or take actions, typically on a daily operational basis. For instance, the inventory manager at Contoso Skateboard Store, who requires current information about stock levels, is an example of an information worker audience.
* An information worker is an individual who uses data to make decisions or take actions, typically on a daily operational basis. For instance, the inventory manager at Contoso Skateboard Store, who requires current information about stock levels, is an example of an information worker audience.

## Determine report types
* Generally, report design can be categorized by report type. There is often a direct correlation between the report audience and the type of report. Audience needs can be addressed by one or a combination of the following four report types:
* Dashboard
* Analytical
* Operational
* Educational
* Typically, executives use dashboards, analysts use analytical reports, and information workers use operational reports.
* ![image](https://github.com/ZiyandaPetela/Power-BI/assets/123364433/742c7184-c6ef-44fa-bcba-6da5e7e9874e)

### Dashboard
* The main objective of a dashboard is to swiftly convey the story within the data. User interactions are restricted, emphasizing insights tailored to the audience's specific needs.
*  Visual elements in the report are concise, self-explanatory, and prominently labeled. Dashboards aim to directly convey the significance of the data, reducing the likelihood of misinterpretation or uncertainty.
*  An executive dashboard serves as a prime illustration, typically showcasing key metrics on a single page. These dashboards address inquiries like "How is our performance?" or "Have we achieved our goals yet?"\

### Analytical reports
* An analytical report stands out as the most versatile type of report, catering to various needs of report consumers while offering a structured platform for analysis.
* The primary aim of an analytical report is to empower report consumers to explore a wide range of questions by engaging with the report and its visuals. These reports often feature numerous slicers to filter data and include intricate visuals that unveil detailed insights.
* Designed with a focus on user experience (UX), report pages in analytical reports are specifically crafted for interactivity. They offer multiple pathways for report consumers to navigate, enabling them to delve into topics of interest, share their discoveries, or backtrack to their starting point. Interactive features allow users to peel back layers, add context, and access detailed information. Common interactive features include drill down, drill through, and tooltips.
* A prime example of an analytical report transcends the simple "How are we doing?" inquiry to address questions like "Why did that occur?" or "What could happen next?"

# Define user interface requirements
* UI requirements relate to how reports are consumed and to the appearance and behavior of reports. Aspects to consider include form factor, input method, style and theme, and accessibility.

## Style and theme
* UI requirements should also consider style and theme. Strive to design reports with a consistent and distinctive appearance that is determined by a deliberate theme.
#### The report theme should express your organizational branding or aim to complement it. At a minimum, the theme should include the following elements:
* A brand mark or logo symbol.
* A palette of colors that align to, or complement, organizational branding. The colors should also be sufficiently different so that, when applied to visuals, they provide appropriate contrast when appearing side by side.
* Text settings, including font selection, sizes, and color.
* To manage style and theme changes effectively and efficiently, design reports that use images and themes that are stored in a central repository. This approach improves change management: Changes that are applied to the repository can automatically cascade through to reports.














