---
title: "Program Overview"
path: "/organizations/program-overview.html"
id: "organizations/program-overview"
---

HackerOne analytics dashboards provide metrics for a number of your engagements with HackerOne, including bug bounty (BB) and vulnerability disclosure programs (VDP). This helps you track the progress of your program and it also gives you a summary and deeper understanding of your program status.

![overview dashboard](/images/program-overview-1.png)

Analytics on your various HackerOne engagements can be viewed in two ways:
* Program-level - analytics for an individual bug bounty and vulnerability disclosure program
* Org-level - this is a new option that is being rolled out to cover analytics across multiple engagements (formerly called programs) with HackerOne

### Program-level Analytics
Program-level analytics can be viewed from Engagements > (selected program) > Dashboard. These are accessible only to users who are a member of the specific program. Organization admins must be a member of a program to see the program-specific metrics. You can view the following: 
* Submissions & Bounty
* Hacker Engagement
* Statistics
* Response Efficiency
* Explore

### Org-level Analytics
Org-level Analytics is a new feature that provides metrics across multiple engagements (aka programs) and allows you to select the comprehensive analytics across them. Each user will only be able to see analytics based on their membership to the program using the Analytics icon in the left-side navigation. 
* Submissions
* Bounty
* Hacker Engagement

New features and remaining analytics features are currently available at a program level only but will be added at a later time.

### Viewing and Download Options
All the data and charts can also be filtered, using the date selector at the top. After selecting a date range the displayed data will be aligned to the start and end date of the reporting interval (month, quarter, year). Additional filtering can be done with the selector at the top-right and by clicking on the Apply button at the bottom. This includes a variety of filters including program (aka engagement), severity, report state, assets, and others. A user must be a member of the program to see its metrics. 

![dashboard breakdown](/images/program-overview-3.png)

![Dashboard Filters](/images/program-overview-4.png)

Filtered analytics can also be used to create a saved view, called a segment. For example, you can create segments for specific assets, programs, or by severity levels. Click on the + Add Segment button, select the appropriate filters and assign a name. 


Each of the charts below allows you to download the chart as CSV, PDF, or PNG image files using the kabob menu (three vertical dots). Clicking on the table icon lets you switch between a table or chart view. 

![Kabob menu](/images/program-overview-6.png)

### HackerOne API
The raw data, i.e. the underlying reports and related details, can also be retrieved using the HackerOne API. The summarized data, similar to the CSV and table format, shown on these pages can be retrieved using the Analytics API endpoint (in Preview).
