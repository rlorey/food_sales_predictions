# Food Sales Predictions
## Purpose
The purpose of this project is to analyze relationships between outlet information and items sold at various locations and create a model to predict sales at BigMart.  
## Data

This data set includes 2013 sales data from BigMart.  There are 10 stores in different cities and 1,559 items represented in the data.
<img width="899" alt="Screen Shot 2021-11-22 at 3 07 52 PM" src="https://user-images.githubusercontent.com/62402303/142935476-663b0a10-7ee3-425a-a4ca-4227c7f2de78.png">
<img width="788" alt="Screen Shot 2021-11-22 at 3 09 15 PM" src="https://user-images.githubusercontent.com/62402303/142935655-bb397a2e-5809-41da-a7ca-a314f72f97e4.png">
>
https://datahack.analyticsvidhya.com/contest/practice-problem-big-mart-sales-iii/ 

## Visuals and Recommendations
#1 Maximum Retail Price vs. Outlet Sales


<img width="508" alt="Screen Shot 2021-11-19 at 2 05 35 PM" src="https://user-images.githubusercontent.com/62402303/142936135-721398d9-a605-46c9-95a3-c7e549a94c2d.png">
There is a direct correlation between MRP and Item Outlet Sales.  I recommend that BigMart continues to stock higher MRP items.


<br/><br/>

#2 Sale of Low Fat/Regular Items vs. Average Outlet Sales


<img width="535" alt="Screen Shot 2021-11-22 at 3 12 05 PM" src="https://user-images.githubusercontent.com/62402303/142936108-b8c6bbc4-f72c-4269-a703-264098a6e3ed.png">
There are almost twice the sales from Low Fat vs. Regular food items.  I recommend that BigMart diversifies it's food categories, possibly including, gluten-free, organic, vegan/vegetarian, and all-natural.  The company should track sales of these items and use them for future predictions.

<br/><br/>


#3 Outlet Type vs. Average Sales


<img width="504" alt="Screen Shot 2021-11-22 at 3 12 29 PM" src="https://user-images.githubusercontent.com/62402303/142936118-240e8edd-0726-4006-b6f6-19cc52b4965e.png">
The average sales were highest at Type 3 Supermarkets followed by Type 1, Type 2 and Grocery Stores.  I recommend that if new outlets are built, Type 3 Supermarkets would be the best option followed by Type 1 and then Type 2.  Grocery Stores are making the lowest average sales and I would recommend to potentially close these stores and/or not build any in the future.

<br/><br/>



## Sales Prediction Model

Decision Tree Regressor Model - Optimized for R^2

R^2 = 60%


<img width="200" alt="Screen Shot 2021-11-22 at 3 42 24 PM" src="https://user-images.githubusercontent.com/62402303/142939367-18143251-902f-48ad-84b5-502470e5fad6.png">


## Acknowledgments
* Anayltics Vidhya
* Codingdojo.com
