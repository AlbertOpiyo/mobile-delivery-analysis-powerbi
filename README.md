# MOBILE DELIVERY ANALYSIS

## INTRODUCTION
A consultancy implemented an app for a client to help them improve their delivery process and fulfillment from warehouses to stores.

The app was created so that drivers could scan the label as opposed to entering it manually while also recording the time of arrival, the time they left the store, and some other variables that the management was interested in improving.
The management is now looking to evaluate how the business has reacted and how effective the app is.

The senior consultant has extracted all data from the app and placed it into the file below. He now wants you to use this data and create a report or dashboard to help management visualize what is happening so that we can decide what the next stage of the transformation is.
The management is interested in answering the following questions:
* The time being spent at the store.
* The number of times the manual entry was still being used.
* The number of damaged labels.
* If returns are being collected.

## DASHBOARD

![mobile delivery analysis](https://user-images.githubusercontent.com/110673311/229688955-3ca3faa1-6e05-4de2-bc28-83782a90be88.png)


DATA ANALYSIS AND EXPLORATION
I used Power BI to analyze and visualize the data which helped me deliver the report to the managers for further decisions.
The dataset had three tables i.e.  Delivery, Whouse, and Stre.  These three tables are related and I will use the four main pillars of Power Bi (data transformation, data modeling, DAX calculations, and visualization) to analyze the tables and do some visualization.
I loaded the three tables in PowerBi for some transformation.
The first step in data analysis is always to check for any inconsistencies and clean the data. The data set that I was given had some errors in the delivery -Date Time Arrived at Store column. The date was written in a string format. I needed to change it to date/time format for easier and further analysis.
The other two tables- Whouse and Stre were clean so there was no need for any transformation.  

The warehouse and the stores are **10** and **50** in number respectively.

### Step 1 
Transform the string date to a date time character.

### Step 2 

aplpy the transformations and load the data to the powerbi report view tab

### Step 3
Go to the modeling tab and join the related columns in the three tables

![Modelling](https://user-images.githubusercontent.com/110673311/229691433-4fd71dd1-e3db-4dd0-889e-f5e1e7255d03.png)



After Modelling we now seek the truth from the tables.
I first wanted to know the total deliveries made in the warehouse- 7087 deliveries were made across all the stores

### Time spent 
After that, I calculated the time spent time on the store.- avg time spent was 29.72 minutes

I was then interested in knowing if scanning improves the delivery time – there was no significant improvement noted since  scanned time was 50.1%  of the time  and  manual time  was  49.9%  of the time

### Manual Entry Usage
Manual entry was being used 3511 times. This translates to 49.5% of the time.

### Number of damaged labels
The number of damaged labels is 3511. There is a correlation between Manual Entry and damaged labels.

### Returns collected
Goods returns were 3511

## Conclusion
* The Delivery app has not made any significant time improvement
* The goods returned, damaged labels and manual entry are highly correlated- does one cause the other? This should be looked into.








