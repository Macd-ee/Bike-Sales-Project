
# Bike Sales Dashboard


## Problem Statement

This report helps Bike Sales shop to draw business insights  by providing realtime insights from customer demographics . It helps the shop to monitor and analyze critical data related to age of customers ,income of customers, education background and communiting distance. 

## Objectives
- Tracking Age bracket of customers
- Average income of customers based on gender
- Education background of customers
- Communiting distance of customers



### Steps followed 

- Step 1 : Load data into Excel Worksheet, dataset is a csv file.
- Step 2 : Open the worksheet and checked for any duplicates.
- Step 3 : Performed data cleaning techniques
          a) Check and corrected data types accross all columns
          b) Trimmed all spaces in all columns 
          c) Wrote in full abbreviations such as F = Female and M = Male in full using find and replace.
          d) Used the Upper tool to standardize text case within columns
- Step 4 : Added an Age Bracket Column using IF Statements 

        IF(L2>54,"Old",IF(L2>=31,"Middle Age",IF(L2<31,"Adolescent","Invalid")))



- Step 5 : In the pivot tables worksheet, the first pivot table made was average income based on gender
      
   ![Screenshot 2024-12-11 144621](https://github.com/user-attachments/assets/64271526-21e7-4fb5-b3e8-f8b51716caf8)

   After the pivot table a pivot chart was inserted to visualize the metric

  ![Screenshot 2024-12-11 144650](https://github.com/user-attachments/assets/c11d915a-01cc-487e-96d3-59a60d44122d)
 

- Step 6 : The second pivot table was based count of bikes in relation to commute distance.

![Screenshot 2024-12-11 145424](https://github.com/user-attachments/assets/9037a8c5-ab20-45b8-8a4f-f00f6ec17432)

     A pivot line chart was inserted to visualize the pivot table

![Screenshot 2024-12-11 145500](https://github.com/user-attachments/assets/15c51e38-5a9c-4a2b-b367-120ca9951e48)


- Step 7 : The third pivot table was based on the purchase of bikes in relation to customer age bracket

![Screenshot 2024-12-11 150004](https://github.com/user-attachments/assets/6cbeb475-4ef2-467c-8417-a5e475e393a4)

A pivot line chart was inserted to visualize the pivot table

![Screenshot 2024-12-11 150015](https://github.com/user-attachments/assets/8c2cbb02-0af0-4713-aaca-34e09db79c03)


- Step 8 : Into the dashboard worksheet,
3 slicers based upon 
                     a) Education background
                     b) Region
                     c) Marital Status
                      were inserted for filtering.

![Screenshot 2024-12-11 150638](https://github.com/user-attachments/assets/69be217f-914a-4377-835c-149ee33e5b33)
 
- Step 9 : The pivot tables were combined to comeup with a dashboard 

 

![Screenshot 2024-12-11 150914](https://github.com/user-attachments/assets/e0eb3acf-d15d-4d91-bc37-7a8001e52353)



# Insights

A single page dashboard was created on Ms Excel.

Following insights can be drawn from the dashboard;


       a) Age Bracket of most buying customers = Middle Age(31-53 years)
       b) Commute Distance of buying customers = 0-1 Miles
       c) Average salary of Males - $60 124
       d) Average salary of Females - $55 774
       

           

 

