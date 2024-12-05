### Data_Operations_Team_Analysis
A Power BI Portfolio project to analyze efficiency of operations of a Data Operations Team at Pitchbook - a client of MorningStar.

### Dataset Information

This dataset contains a CSV file namely Data.csv.

A) The IPL_Ball_by_Ball data file contains 56,932 rows and 16 columns namely 1)Profile 2)Created Date	3)Secondary Completed Date 4)Close Date	5)Most Recent Unassign Reason 6)Secondary Researcher 7)Researcher Hire Date	8)Research Group 9)Time taken to Complete (secs) 10)Benchmark Points 11)Workflow Type	12)Workflow Process	13)Workflow Status 14)Workflow Priority	15)Workflow Region 16)Is Corrrection Req

### Problem Statement

A new Team Leader needs your help to better understand his/her Data Operations Team. You are provided with sample data that a 
PitchBook Business Intelligence Analyst encounters daily. Use the tools you are comfortable with to analyze and interpret the data to help 
provide useful insights to the TL.

### Report Details

The Report shared in the Power BI (.pbix) file consists of 7 Tabs which are -

#### 1)	Workflows closed by Research Groups :
To Monitor team’s production (i.e., profiles worked on), on a daily basis, Analyze team’s performance on a monthly basis and Report monthly performance metrics to manager, the Team Leader can utilize the 1st Tab which is the Workflows closed by Research Groups. This tab shows data only for the workflows which are closed. 
The Team Leader can view broad stats including Workflows Closed, Associated Research Groups, Total Researchers, Total Workflow types, Workflow Inefficiency, Total Benchmark Points Earned and Total Hours Worked.
This tab allows the TL to filter data based on any Research Group to monitor a particular group’s productivity. Moreover, it allows the TL to filter the data further based on a particular profile, Workflow Priority, Workflow Type, Workflow Process, Region. The TL can also look at the data for any range of Created dates and Closed dates for daily, weekly and monthly analysis.

#### 2)	Pending Workflows of Research Groups : 
To Understand the workflow (i.e., what workflow should be prioritized) and to Understand how workflow is being generated the TL can utilize the Pending Workflow of RGs tab along with the Pending Workflow of Researchers Tab. This tab shows data only for the workflows which are in the pending stage. 
On the Pending Workflow of RGs tab the Team Leader can view broad stats including Workflows Pending, Associated Research Groups, Total Researchers, Total Workflow types, Workflow Inefficiency, Total Benchmark Points Earned and Total Hours Worked.
This tab allows the TL to filter data based on any Research Group to monitor a particular group’s productivity. Moreover, it allows the TL to filter the data further based on a particular profile, Workflow Priority, Workflow Status, Workflow Type, Workflow Process, Region. The TL can also look the data for any range of Created dates and Secondary Research completed dates for daily, weekly, and monthly analysis.
     
#### 3)	Workflows Closed by Researchers : 
To Track individual researcher’s performance, Report production numbers to the manager, have meetings with individual researchers to discuss their performance and Report monthly performance metrics to manager, the TL can utilize the Workflows closed by Researchers Tab. This tab shows data only for the workflows which are closed. 
The Team Leader can view broad stats including Workflows Closed, Associated Research Groups, Total Researchers, Total Workflow types, Workflow Inefficiency, Total Benchmark Points Earned and Total Hours Worked.
This tab allows the TL to filter data based on any individual Researcher to monitor a particular Researcher’s productivity. Moreover, it allows the TL to filter the data further based on a particular profile, Workflow Priority, Workflow Type, Workflow Process, Region. The TL can also look the data for any range of Created dates and Closed dates for daily & monthly analysis.

#### 4)	Pending Workflows of Researchers : 
On the Pending Workflow of Researchers tab the Team Leader can view broad stats including Workflows Pending, Associated Research Groups, Total Researchers, Total Workflow types, Workflow Inefficiency, Total Benchmark Points Earned and Total Hours Worked.
This tab allows the TL to filter data based on any individual Secondary Researcher to monitor a particular researcher’s productivity. Moreover, it allows the TL to filter the data further based on a particular profile, Workflow Priority, Workflow Status, Workflow Type, Workflow Process, Region. The TL can also look the data for any range of Created dates and Secondary Research completed dates for daily, weekly, and monthly analysis.

#### 5)	Workflow Inefficiency : 
To Understand how workflow is being generated, whether there are any gaps and inefficiencies, the TL can utilize the Workflow Inefficiencies Tab. This tab shows data for all the types of workflows.
The Team Leader can view broad stats including Workflow Inefficiency %, Unassigned Workflows and Total Workflows.
Workflow Inefficiency % = [Total Unassigned Workflows / Total Workflows] * 100
This tab allows the TL to filter data based on any individual Researcher or Research Group to monitor the respective Workflow Inefficiency %. Moreover, it allows the TL to filter the data further based on Workflow Priority, Workflow Status, Workflow Type, Workflow Process, Region. The TL can also look the data for any range of Created dates and Secondary completed dates for daily, weekly, and monthly analysis.

#### 6)	Benchmark Points Analysis, 7)	Hours Worked Analysis :
To Revise targets for the team the TL can utilize the Benchmark Points Analysis & Hours Worked Analysis Tabs. These tabs show data for all the types of workflows.
The Team Leader can view broad stats including Average Benchmark Points, Median Benchmark Points, Average Hours Worked, Median Hours Worked.
Both these tabs allow the TL to filter data based on any individual Researcher or Research Group to monitor the respective stats. Moreover, it allows the TL to filter the data further based on Workflow Priority, Workflow Status, Workflow Type, Workflow Process, Region. The TL can also look the data for any range of Created dates and Secondary completed dates for daily, weekly, and monthly analysis.

### Instructions on how to run this project code on your system
Step 1 : Download this project repository as a zip file. 
Step 2 : Unzip the folder to your desired location 
Step 3 : If you don't have Microsoft Power BI Desktop Installed , go to https://www.microsoft.com/en-in/download/details.aspx?id=58494&msockid=39cd1c66ce6867ae13a2094ecfc066fd, download the suitable installer, install Microsoft Power BI Desktop and launch it. 
Step 5 : Navigate to this project folder. 
Step 6 : When inside, navigate to MorningStar.
Step 6 : Open the PitchBook BI Analyst Assessment.pbix using Microsoft Power BI Desktop.
Step 7 : Open the Assessment Write Up.docx ,go through the tabs mentioned above and check the visuals in the Power BI File by referring the Write Up for clear explanation.

### Purpose of Solving this problem

Analyzing a data operations team's workflow data serves several purposes, particularly to help the Team Leader understand their team’s performance, identify bottlenecks, and improve overall efficiency. Below are key insights and benefits this analysis can provide:

#### 1. Performance Evaluation
Individual Contribution: Assess the performance of team members (e.g., Profile, Research Group, Time taken to Complete).
Benchmarking: Compare the Time taken to Complete against Benchmark Points to evaluate efficiency.
Correction Trends: Identify if specific individuals or workflows frequently require corrections (Is Correction Req).

#### 2. Process Optimization
Workflow Analysis: Identify which Workflow Types and Workflow Processes are taking the longest time and why.
Bottlenecks: Pinpoint steps or regions (Workflow Region) with delays by analyzing the difference between Created Date, Secondary Completed Date, and Close Date.
Resource Allocation: Assess how resources (Research Group, Secondary Researcher) are distributed and whether reallocation could improve efficiency.

#### 3. Error Reduction
Common Errors: Examine patterns in Most Recent Unassign Reason and Is Correction Req to identify recurring issues.
Training Needs: Highlight areas where team members or processes consistently struggle, suggesting targeted training opportunities.

#### 4. Priority and Status Management
Workflow Prioritization: Analyze how Workflow Priority impacts completion times and resource allocation.
Status Insights: Examine Workflow Status to understand the progression and identify any stagnant tasks.

#### 5. Strategic Decision-Making
Hiring and Onboarding: Use Researcher Hire Date and performance data to assess whether new hires are meeting expectations and to refine onboarding processes.
Regional Insights: Determine regional strengths or weaknesses (Workflow Region) to guide operational strategies.
Capacity Planning: Use Time Taken to Complete and workflow volumes to predict workload and staffing needs.

#### 6. Improved Communication and Accountability
Transparency: Provide clear insights into individual and team productivity, fostering accountability.
Feedback Loops: Identify areas where researchers excel or struggle to facilitate constructive feedback.

By performing this analysis, the Team Leader gains actionable insights into operational efficiency, identifies areas for improvement, and ensures alignment with organizational goals. This data-driven approach supports better decision-making, leading to enhanced team performance and workflow management.
























