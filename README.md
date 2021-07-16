# BikeShareCaseStudy
Case study on cyclists bike share company

Welcome to the Cyclistic bike-share analysis case study!
##############################
CYCLISTIC:
##############################
Introduction:
------------
In 2016, Cyclistic launched a successful bike-share offering. Since then, the program has grown to a fleet of 5,824 bicycles that are geotracked and locked into a network of 692 stations across Chicago. The bikes can be unlocked from one station and returned to any other station in the system anytime.
One approach that helped make these things possible was the flexibility of its pricing plans:
1. single-ride passes,
2. full-day passes,
3.annual memberships.

Customers who purchase single-ride or full-day passes are referred to as casual riders.
 Customers who purchase annual memberships are Cyclistic members.
Cyclistic’s finance analysts have concluded that annual members are much more profitable than casual riders. Rather than creating a marketing campaign that targets all-new customers, there is a very good chance to convert casual riders into members. The casual riders are already aware of the Cyclistic program and have chosen Cyclistic for their mobility needs.
##############################
GOAL:
##############################
Design marketing strategies aimed at converting casual riders into annual members. In order todo that, however, the marketing analyst team needs to better understand
how annual members and casual riders differ,
why casual riders would buy a membership,
how digital media could affect their marketing tactics.
 In this case study, we will follow the steps of the data analysis process:
1. ask,
2.prepare,
3. process,
4.analyze,
5.share,
6. act.

##############################
Scenario
##############################
1.Ask
  Guiding questions
   1. What is the problem you are trying to solve?
   2. How can your insights drive business decisions?
-------
Key tasks
-------
1. Identify the business task
2. Consider key stakeholders
Deliverable
A clear statement of the business task
  -converting casual riders into annual members
Three questions will guide the future marketing program:
1. How do annual members and casual riders use Cyclistic bikes differently?
2. Why would casual riders buy Cyclistic annual memberships?
3. How can Cyclistic use digital media to influence casual riders to become members?
                                           --------------------------------
2.Prepare
I have downloaded the previous 12 months of Cyclistic trip data
here.This is public data that you can use to explore how different customer types are
using Cyclistic bikes.
Now, prepare our data for analysis using the following Case Study Roadmap as a guide:
Case Study Roadmap - Prepare
Guiding questions
● Where is the data located?
● How is the data organized?
● Are there issues with bias or credibility in this data?
● How are you addressing licensing, privacy, security, and accessibility?
● How did we verify the data’s integrity?
● How does it help you answer our question?
● Are there any problems with the data?

##############################
Key tasks
##############################
1. Download data and store it appropriately.
2. Identify how it’s organized.
3. Sort and filter the data.
4. Determine the credibility of the data.
##############################
Deliverable
##############################
A description of all data sources used to Process.
----------------------------------------------------------------------
3.Process
Next step is process our data for analysis using the following Case Study Roadmap as a guide:
Guiding questions
● What tools are you choosing and why?
● Have you ensured your data’s integrity?
● What steps have you taken to ensure that your data is clean?
● How can you verify that your data is clean and ready to analyze?
● Have you documented your cleaning process so you can review and share those results?
Key tasks
---------
1. Check the data for errors.
2. Choose your tools.
3. Transform the data so you can work with it effectively.
4. Document the cleaning process.
5. ##############################
Deliverable
##############################
Documentation of any cleaning or manipulation of data

##############################
STEPS FOLLOWED:
##############################
1. Download the previous 12 months of Cyclistic trip data.
2. Unzip the files.
3. Create a folder on  desktop or Drive to house the files. Use appropriate file-naming conventions.
4. Create subfolders for the .CSV file and the .XLS or Sheets file so that you have a copy of the original data. Move the
downloaded files to the appropriate subfolder.
5.  Open each .CSV file in Google Sheets and save it to the appropriate subfolder.
6. Open spreadsheet and create a column called “ride_length.” Calculate the length of each ride by subtracting the
column “started_at” from the column “ended_at” (for example, =D2-C2) and format as HH:MM:SS using Format > Cells >
Time > 37:30:55.
7. Create a column called “day_of_week,” and calculate the day of the week that each ride started using the “WEEKDAY”
command (for example, =WEEKDAY(C2,1)) in each file. Format as General or as a number with no decimals, noting that
1 = Sunday and 7 = Saturday.
8. Proceed to the analyze step.
                             ---------------------------------------------------------------
##############################
Analyze
##############################
Now that our data is stored appropriately and has been prepared for analysis, lets start putting it to work.
Guiding questions
 How should you organize your data to perform analysis on it?
● Has your data been properly formatted?
● What surprises did you discover in the data?
● What trends or relationships did you find in the data?
● How will these insights help answer your business questions?
Key tasks
1. Aggregate your data so it’s useful and accessible.
2. Organize and format your data.
3. Perform calculations.
4. Identify trends and relationships.
Deliverable
A summary of your analysis
 steps used in  spreadsheets:
1. Where relevant, made the  columns consistent and combine them into a single worksheet.
2. Cleaned and transformed the  data to prepare for analysis.
3. Conducted descriptive analysis.
4. Run a few calculations in one file to get a better sense of the data layout.
● Calculating the mean of ride_length
● Calculating the max ride_length
● Calculating the mode of day_of_week
5.  A pivot table to quickly calculate and visualize the data.
● Calculate the average ride_length for members and casual riders. Try rows = member_casual; Values = Average of ride_length.
● Calculate the average ride_length for users by day_of_week. Try columns = day_of_week; Rows =
member_casual; Values = Average of ride_length.
● Calculate the number of rides for users by day_of_week by adding Count of trip_id to Values.
7. Once  working with the individual spreadsheets, merged them into a full-year view.
8. Export a summary file for further analysis
steps for using SQL
Open your SQL tool of choice, then complete the following steps:
1. Import your data.
2. 2. Explored the data, perhaps looking at the total number of rows, distinct values, maximum, minimum, or mean values.
3. Where relevant, used JOIN statements to combine your relevant data into one table.
4. Investigate interesting trends and save that information to a table.
steps for using R
Open R Studio and use this script to complete the following steps:
1. Import your data.
2. Make columns consistent and merge them into a single dataframe.
3. Clean up and add data to prepare for analysis.
4. Conduct descriptive analysis.
5. Export a summary file for further analysis.



