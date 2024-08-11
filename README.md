# A-Dashboard-With-IBM-Cognos-Analytics
Project Overview
This project involves creating three dashboards using IBM Cognos Analytics. The dashboards will be built using two CSV data files: m5_survey_data_demographics.csv and m5_survey_data_technologies_normalised.csv. Each dashboard will contain four visualizations and focus on different aspects of the data: Current Technology Usage, Future Technology Trend, and Demographics.

Files Required
m5_survey_data_demographics.csv
m5_survey_data_technologies_normalised.csv
Instructions
Step 1: Upload Data Files
Download the two files: m5_survey_data_demographics.csv and m5_survey_data_technologies_normalised.csv.
Upload these files as data assets in your Cognos Analytics project.
Step 2: Create the Dashboard
Create a New Dashboard:

Create a new dashboard in Cognos Analytics.
Use the 2 x 2 rectangle areas tabbed template for each of the dashboard tabs.
Dashboard Tab 1: Current Technology Usage

Tab Name: Rename this tab to "Current Technology Usage."
Data Asset: Use m5_survey_data_technologies_normalised.csv.
Visualizations:
Panel 1:
Metric: Top 10 LanguageWorkedWith
Chart Type: Bar chart
Features: Utilize Bars, Length, and Color fields; Show value labels; Include a proper chart title.
Panel 2:
Metric: Top 10 DatabaseWorkedWith
Chart Type: Column chart
Features: Utilize Bars, Length, and Color fields; Show value labels; Include a proper chart title.
Panel 3:
Metric: PlatformWorkedWith
Chart Type: Word cloud chart
Features: Utilize Words, Size, and Color fields; Include a proper chart title.
Panel 4:
Metric: Top 10 WebFrameWorkedWith
Chart Type: Hierarchy bubble chart
Features: Utilize Bubbles, Size, and Color fields; Include a proper chart title.
Dashboard Tab 2: Future Technology Trend

Tab Name: Rename this tab to "Future Technology Trend."
Data Asset: Use m5_survey_data_technologies_normalised.csv.
Visualizations:
Panel 1:
Metric: Top 10 LanguageDesireNextYear
Chart Type: Bar chart
Features: Utilize Bars, Length, and Color fields; Show value labels; Include a proper chart title.
Panel 2:
Metric: Top 10 DatabaseDesireNextYear
Chart Type: Column chart
Features: Utilize Bars, Length, and Color fields; Show value labels; Include a proper chart title.
Panel 3:
Metric: PlatformDesireNextYear
Chart Type: Tree map chart
Features: Utilize Area hierarchy, Size, and Heat fields; Contrast label color; Include a proper chart title.
Panel 4:
Metric: Top 10 WebFrameDesireNextYear
Chart Type: Hierarchy bubble chart
Features: Utilize Bubbles, Size, and Color fields; Include a proper chart title.
Dashboard Tab 3: Demographics

Tab Name: Rename this tab to "Demographics."
Data Asset: Use m5_survey_data_demographics.csv.
Filters:
Apply a filter to include only entries with Gender as "Man" and "Woman."
Visualizations:
Panel 1:
Metric: Respondent classified by Gender
Chart Type: Pie chart
Features: Utilize Segments and Size fields; Display %; Include a proper chart title.
Panel 2:
Metric: Respondent Count for Countries
Chart Type: Map chart
Features: Utilize Regions-Locations and Regions-Location color fields; Include a proper chart title.
Panel 3:
Metric: Respondent Count by Age
Chart Type: Line chart
Features: Utilize x-axis and y-axis fields; Show value labels; Show markers; Include a proper chart title.
Panel 4:
Metric: Respondent Count by Gender, classified by Formal Education Level
Chart Type: Stacked bar chart
Features: Utilize Bars, Length, and Color fields; Show value labels; Include a proper chart title.
