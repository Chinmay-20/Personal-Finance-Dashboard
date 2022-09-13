# Personal-Finance-Dashboard
11/09
Personal expenses dashboard
Need : 
This project implements idea of BYOD(Bring your own data)
This project is implemented to bring FINANCIAL DISCIPLINE
To learn power BI and data analytics
To embed data analytics in daily life.
 

Outcome:
This project tells your spending pattern
This project tells how are you saving money
What is my net worth.
Am i making my saving target or not
Which months are financially bad or good

Technical outcome
We will build tooltips in power BI. Which will show extra or extended screens if we have less screen area. We will build additional UI controls 

We can add every months data to this file by just extending the column

Practical execution
Open power bi
Click on get data 
Select excel file
Then a dialog box will open select a table which has the data
Sometimes we cannot load the excel file because it is not in flat file format so we have to make some transformations
So instead of loading select transform data. The power query editor window will open
Data is set now. Instead of directly creating dashboard, mock the dashboard and understand the need of client. What client want to fill in dashboard, see in dashboard and most important thing to client 


Transformations on data 
Select all columns 
Go to transform and do unpivot columns
Change column name
Change datatype of values to fixed decimal. It can be changed by selecting 1,2,3 in side of datatype name
Add column telling the year. For that first select date column and change the datatype to date. And then select date in transform column section. Change datatype of that column to date.
We can also combine data here from different files, data coming from different source. 
Select close and apply in left upper corner under home section. 


Important things for dashboard 
KPI (Key Performance Indicators) : which tells the income and out of that income how much percent is the expense in timeline fashion. There should be selection of months and years  like 2019 vs 2020 . if 2019 is selected, what is income, % expense and net worth 


Design of dashboard (WE NEED TO CAPTURE THE PURPOSE OF DASHBOARD AND ALWAYS ASK QUESTIONS WHILE BUILDING THE DASHBOARD IT WILL GIVE CLEAR PERSPECTIVE) 
Most important thing of dashboard should always go to top list.
So KPI’s in top left 
Selection should be in top left place which will give relevance of selection
Application workflow
If u select year 2020 it will show the data for 2020. 
We will have 2 KPI’s one for selection and one will be same which will keep showing overall wealth, overall income, overall expense ratio
We will have expense breakdown percentage in left bottom corner. 
We will have savings breakdown besides expense breakdown
When income is increased we have to see whether savings and expenses have increased. We don’t know when we are doing this kind of stuff. So we can interpret numbers and they will tell when you will your habit and there might be some pattern.
We will draw a graph with expense %, savings % with change in income Month on month percentage
The right bottom will show table with details of expenses 
Tool tips : if page is full and but we want to see more details like details of EMI if you are paying from months. Tool tip is useful to see this extended windows. 
Application Workflow : we hold the mouse and it will bring a chart and show the things
BUIDLING DASHBOARD
Select enter data. Create table window will open. Give table name and click on load
Fo to fields in right side click in key measures (table name created in step 1) and click on create new measure.
Give name to measure and write formula and select data type.
Create new total income add formula SUM(FinData[value]) but here we dont want to include savings and expenses THIS IS MOST IMPORTANT FORMULA.
Just Drag measure into free area and you will see 
Add new measure (expense)
Add new measure (Saving)
Add new measure expense percentage
Add new measure (saving %)
If you want to change in font of something u can copy paste it for every other
Go to format your visual in side of build visual and select font and size 
Bring total income, expense %
Go to model select measures and change the format for all
