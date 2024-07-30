# POWER BI - Coffee Shop Sales Dashboard | (Download dataset and pbix file in the attachments given above)
![image](https://github.com/user-attachments/assets/24c7af91-f196-4f47-aab9-ae6e37cf9907)


## Project Description
### Sales Report on different kinds of beverages sold during the first six months of 2023. The description for each visual is given below.


1. The KPI Banner shows the Total Sales, Total Orders and Total Quantity sold for each month along with their respective Sparkline visuals.
2. In Adiition the month - on month differences in KPIs is also displayed in the respective KPI parameters.
3. A custom calendar heat map is designed which dynamically adjusts based on selected month from the slicer. An additional tooltip was implemented to the visual to display the detailed metrics (Sales, Order, Quantity) when hovering over the calendar heatmap.
4. A Donut Chart indicates sales performance with respect to weekdays and weekends to analyze performance variations.
5. A custom bar chart to visualize sales data and Month-over-Month sales differnce by different store locations (Astoria, Hell's Kitchen and Lower Manhattan).
6. A column chart to analyze daily sales with respect to each month. An average line is incorporated to represent average daily sales.
7. A custom bar chart to analyze sales performance across different beverage categories.
8. A custom bar chart to display top 10 products based on sales volume.
9. A heat map visual is used to visualise sales patterns with respect to days and hours. 

## Dataset Model
![image](https://github.com/user-attachments/assets/e59b0b78-7a82-4150-866c-5f396f694036)

1. Dataset consists of an Excel file. The file consist of store location, product category, product type and product detail.
2. An additional date table was created using Calendar DAX Function.

## DAX Measures.
Twenty one DAX measures were used in Total. The prominent ones Include Total Sales, Total Orders, Total quantity, Current Month Sales, Current Month Quantity, Current Month Orders, Previous Month Sales, Previous Quantity, Previous Month Orders, MoM Sales growth, MoM Orders growth, MoM Quantity growth.

![image](https://github.com/user-attachments/assets/c719527b-584e-42b3-ba5a-13f562dc4b50)

![image](https://github.com/user-attachments/assets/db74b7cd-c2e5-4b8d-8aa2-4f0058412801)

![image](https://github.com/user-attachments/assets/b4cf520a-19c6-4c2b-976a-5947b32ef043)

![image](https://github.com/user-attachments/assets/84e7b016-d16f-4ac5-98a3-2f1425b9bccc)

![image](https://github.com/user-attachments/assets/f4c1efb6-c273-4e79-9a3a-3395523c283b)

![image](https://github.com/user-attachments/assets/937970ff-3af1-4bd2-9e45-9cdc19d8b5d7)

![image](https://github.com/user-attachments/assets/7b4dea1b-84a4-4081-a28c-b302b3e716a0)

![image](https://github.com/user-attachments/assets/0a2d1c7e-cb83-4f6d-9601-73cbe532a1ce)

![image](https://github.com/user-attachments/assets/27fa55e8-3a2d-47ad-87e2-adb780e5f8aa)

![image](https://github.com/user-attachments/assets/310c1557-2f27-41d5-a711-18276b3dcef1)

![image](https://github.com/user-attachments/assets/683a8622-a946-4952-a229-282f6eba4e57)

![image](https://github.com/user-attachments/assets/f86937d8-0368-4bb8-9925-cc24887ad801)

## DAX Measures for the Date Table

![image](https://github.com/user-attachments/assets/b3e074f0-fa02-419f-90c1-34d3d43c24de)

![image](https://github.com/user-attachments/assets/ed30747b-5c4a-463a-b977-f4b647d9fabc)

![image](https://github.com/user-attachments/assets/78494eb7-3dc2-4554-893e-4840ba62d1d5)

![image](https://github.com/user-attachments/assets/2a4b72dc-1011-4390-b156-5e2d81a6119f)

![image](https://github.com/user-attachments/assets/b61cce5d-3591-48fb-a5e5-af9b0a3fe3ed)

![image](https://github.com/user-attachments/assets/bb154a8a-8e4b-479e-a79f-a6a3b74638fe)

![image](https://github.com/user-attachments/assets/ad0fa539-ef6c-466e-b0ae-5a149d0ccb1f)

![image](https://github.com/user-attachments/assets/46f6797b-2ee9-4ef3-87da-3b611e2e5519)

![image](https://github.com/user-attachments/assets/3bed010b-c6a1-4f13-b98e-a60b3dce67f2)


## Dashboard Insights
1. The month of June has made the largest sales around $ 166K. January has made the least sales aroung $ 82K.

2. Weekday sales contributes to the majority of the revenue.

3. Coffee stands out to be highest evenue making product and packaged chocolate is the least revenue making product.

4. Barista E  spresso is the most liked coffee for the customers whereas drip coffee is the least favourite coffee for the customers.

5. Majority of the sales are happening between the time span of 07:00 am to 10.00 am irrespective of the days.
