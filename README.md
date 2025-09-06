# Weekly-HR-Management-Scorecard

This README file is for an interactive Excel dashboard for tracking an organization’s Global HR call center KPIs. It provides a clear and professional overview of the project, including its purpose, features, and how to use it.

About

This project is an interactive Excel dashboard designed to allow Global HR call center management to visualize and analyze call center employee KPIs. The dashboard leverages Excel features such as INDEX MATCH, FIELD ARRAYs, VLOOKUPs, SUMIFs, COUNTIFs, and interactive charts. The visible face of the dashboard tabs references several hidden tabs (Data, Times, Available, IC) copied and pasted as values from a separate overall capture form with an interlocking formulaic matrix that pulls information from nine distinct reports. The dashboard provides a dynamic and clear view of HR call center trends over time. This tool allows call center HR management to make data-driven decisions to improve employee service strategies.

Executive Summary

The Business Problem: Global call center HR management need a quick, reliable way to view call center employee KPIs. The three systems information is drawn from are non-integrated and do not lend themselves to Power BI capture, hence Excel. The pre-existing dashboard uses a massive pivot table that takes three days to assemble and post, and is often rife with errors.

The Solution: This new dashboard optimizes all of the necessary features from the previous overbuilt pivot table and can be assembled and posted in less than three hours, giving center management a quicker tool to visualize employee KPIs, have performance discussions, and take corrective action. Behind the background data tabs of this dashboard is a separate formulaic capture form utilizing a CRT to essentially mimic power query in a spreadsheet. Automated reports are pasted into capture forms, which process the data together giving it a heretofore missing unique identifier between the differing sheets allowing for data amalgamation.

Next steps: Absent the IT resources to develop feeds to integrate Workday, ServiceNow, and In Contact data together this new crude, but effective dashboard was developed and refined over the course of several weeks based off stakeholder engagement sessions to meet the employee oversight needs of HR global call center management.

The Impact: This new dashboard allowed for much faster visibility of call center employee KPIs, giving management the ability to have weekly performance conversations earlier in the week, especially APAC centers where Tuesday begins at the end of American Monday. Previously APAC could only have performance discussions Thursday or later. The dashboard also had built in error capture processes in the background capture forms to ensure data accuracy.

Dashboard Features

In_Contact_Time_Usage: This sheet features nested dropdowns that global HR users can select region, employee, and day of the previous week for employee time and productivity examination. The central pie chart is linked to the chosen employee and displays the various In Contact time usage functions. Data comes from the hidden Availability and Times tabs.

Individual_Performance_Metrics: This sheet features two nested dropdowns for region and employee selection. The sheet features individual employee KPIs for the previous 15 weeks for management to conduct comparative analysis and conduct employee coaching sessions. The data comes from the hidden Data tab.

Team_Performance_Metrics: This sheet allows management to examine KPIs across their respective teams by week. Overall center volume can be gleaned from the workforce examination. Comparative laggards can then be identified for additional coaching.

Agent_Refusal: Static sheet that displays refused calls for the prior week. Refused calls contribute to abandonment statistics, which is a management incentive measurable.

Agent_Weekly_Login_Data: Static sheet that displays agent login and logoff time for the previous week. Shift irregularities can then be discerned and discussed in coaching sessions.

Skills Used

Microsoft Excel: Used for all data manipulation, calculations, and visualization.

SQL: Used to customize the backend reporting (Workday process reporting, headcount report)

Excel Charts: Used to create the visual components of the dashboard.

Author
Ian Hood – github.com/Hood-Analytics
