# mobile-delivery-analysis-powerbi

## INTRODUCTION
A consultancy implemented an app for a client to help them improve their delivery process and fulfillment from warehouses to stores.

The app was created so that drivers could scan the label as opposed to entering it manually while also recording the time of arrival, the time they left the store, and some other variables that the management was interested in improving.
The management is now looking to evaluate how the business has reacted and how effective the app is.

The senior consultant has extracted all data from the app and placed it into the file below. He now wants you to use this data and create a report or dashboard to help management visualize what is happening so that we can decide what the next stage of the transformation is.
The management is interested in answering four questions
The time being spent at the store.
The number of times the manual entry was still being used.
The number of damaged labels.
If returns are being collected.

DATA ANALYSIS AND EXPLORATION
I used Power BI to analyze and visualize the data which helped me deliver the report to the managers for further decisions.
The dataset had three tables i.e.  Delivery, Whouse, and Stre.  These three tables are related and I will use the four main pillars of Power Bi (data transformation, data modeling, DAX calculations, and visualization) to analyze the tables and do some visualization.
I loaded the three tables in PowerBi for some transformation.
The first step in data analysis is always to check for any inconsistencies and clean the data. The data set that I was given had some errors in the delivery -Date Time Arrived at Store column. The date was written in a string format. I needed to change it to date/time format for easier and further analysis.
The other two tables- Whouse and Stre were clean so there was no need for any transformation.  
The warehouse and the stores are 10 and 50 in number respectively.
Step 1 
Transform the string date to a date time character.

Step 2 aplpy the transformations and load the data to the powerbi report view tab
Step 3
Go to the modeling tab and join the related columns in the three tables

After Modelling we now seek the truth from the tables.
I first wanted to know the total deliveries made in the warehouse. -7087

After that, I calculated the time spent time on the store. I did it using the following DAX formula- avg time 29.72 minutes

I was then interested in knowing if scanning improves the delivery time – there was no significant difference (50.1% in scanned time vs 49.9% in manual time.








