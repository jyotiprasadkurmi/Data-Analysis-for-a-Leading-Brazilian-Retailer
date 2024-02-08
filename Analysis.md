<img width="452" alt="image" src="https://github.com/jyotiprasadkurmi/Data-Analysis-for-a-Leading-Brazilian-Retailer/assets/154520350/f093b06a-b16f-4aef-b53d-08e0fb6bc388">

 ## Data type of all columns in the “customers” table.
  - query:

    <img width="405" alt="image" src="https://github.com/jyotiprasadkurmi/Data-Analysis-for-a-Leading-Brazilian-Retailer/assets/154520350/4a2865e5-ae93-4c82-99df-dc81eee5b458">

  - Results:

    <img width="432" alt="image" src="https://github.com/jyotiprasadkurmi/Data-Analysis-for-a-Leading-Brazilian-Retailer/assets/154520350/eb6ec091-d3a8-480a-be3c-1a71929b10af">

  - Insights: Data_type of all the columns from the customer table, most of the rows are of STRING type and only customer zip_code is of INT type.

## Get the time range between which the orders were placed.
  - Query:

    <img width="452" alt="image" src="https://github.com/jyotiprasadkurmi/Data-Analysis-for-a-Leading-Brazilian-Retailer/assets/154520350/04564c5c-2baa-4728-93ff-9dd32d6ab4a9">

  - Results:
 
    <img width="452" alt="image" src="https://github.com/jyotiprasadkurmi/Data-Analysis-for-a-Leading-Brazilian-Retailer/assets/154520350/d18d910e-26c2-41bb-847d-0be6a8b1e63f">

  - Insights:The orders were placed between ‘2016-09-04 21:15:19 utc’  and ‘2018-10-17 17:30:18 utc’
 
## Count the Cities & States of customers who ordered during the given period.
  - Query:
 
    <img width="452" alt="image" src="https://github.com/jyotiprasadkurmi/Data-Analysis-for-a-Leading-Brazilian-Retailer/assets/154520350/5b3611b7-3762-4f62-baab-a04d5454832b">
  - Results:

    <img width="452" alt="image" src="https://github.com/jyotiprasadkurmi/Data-Analysis-for-a-Leading-Brazilian-Retailer/assets/154520350/d2cb936f-bc62-4698-8746-7bfa8e8bf87f">

  - Insights: Total no of cities is 4119 & states is 27 from where orders were placed during the time period  ‘2016-09-04 21:15:19 utc’ and ‘2018-10-17 17:30:18 utc’

## Is there a growing trend in the no. of orders placed over the past years?
  - Query:

    <img width="452" alt="image" src="https://github.com/jyotiprasadkurmi/Data-Analysis-for-a-Leading-Brazilian-Retailer/assets/154520350/08beaa17-80de-4d7d-be13-67a1e5920329">
  - Results:
    
    <img width="279" alt="image" src="https://github.com/jyotiprasadkurmi/Data-Analysis-for-a-Leading-Brazilian-Retailer/assets/154520350/edb83b7b-7282-4171-9b9a-c913f379485e">
  - Charts:

     <img width="473" alt="image" src="https://github.com/jyotiprasadkurmi/Data-Analysis-for-a-Leading-Brazilian-Retailer/assets/154520350/2dbe7df9-5f61-4455-94a8-9145189ae9e5">
  - Insights: Over the years the orders placed have skyrocketed. In the year 2016 orders was 329 and in the year 2017 and 2018 orders climbed to 45101 to 54011

## Can we see some kind of monthly seasonality in terms of the no. of orders being placed?
  - Query:

    <img width="452" alt="image" src="https://github.com/jyotiprasadkurmi/Data-Analysis-for-a-Leading-Brazilian-Retailer/assets/154520350/2be4cee2-d730-48be-a6f4-5d568cb381d3">
  - Results:
 
    <img width="248" alt="image" src="https://github.com/jyotiprasadkurmi/Data-Analysis-for-a-Leading-Brazilian-Retailer/assets/154520350/fa675f65-a310-4ae8-bb23-e4811a93ebea">
  - Charts:
 
    <img width="452" alt="image" src="https://github.com/jyotiprasadkurmi/Data-Analysis-for-a-Leading-Brazilian-Retailer/assets/154520350/a08b71ce-1b8e-4dd0-96bb-32df276dd916">
  - Insights:Yes we can see that over the months the orders have increased gradually and for the seasonality we can see that the second half of the year has always a linear increase in no of orders placed.

## During what time of the day, do the Brazilian customers mostly place their orders? (Dawn, Morning, Afternoon or Night)  
●	0-6 hrs : Dawn
●	7-12 hrs : Mornings
●	13-18 hrs : Afternoon
●	19-23 hrs : Night
  - Query:

    <img width="398" alt="image" src="https://github.com/jyotiprasadkurmi/Data-Analysis-for-a-Leading-Brazilian-Retailer/assets/154520350/b75eb896-cedf-4eeb-8855-dcf34fd73ad7">
  - Results:

    <img width="401" alt="image" src="https://github.com/jyotiprasadkurmi/Data-Analysis-for-a-Leading-Brazilian-Retailer/assets/154520350/9bcb7774-e7e7-4bd0-ba91-eee9da638b41">
  - Charts:

    <img width="404" alt="image" src="https://github.com/jyotiprasadkurmi/Data-Analysis-for-a-Leading-Brazilian-Retailer/assets/154520350/5168166d-3f98-4d92-99c8-25aad8cbfcc7">
  - Insights:From the DATA  we can see that Most of the Brazillians like to do shopping in the afternoon.
  - Recomendation:Target can put up offers like the hourly sales in the afternoon as more customers are active during that point of the day.

## Get the month on month no. of orders placed in each state.
  - Query:

    <img width="417" alt="image" src="https://github.com/jyotiprasadkurmi/Data-Analysis-for-a-Leading-Brazilian-Retailer/assets/154520350/70324bc1-1978-4d52-bdff-01dd027d51eb">
  - Results:

    <img width="417" alt="image" src="https://github.com/jyotiprasadkurmi/Data-Analysis-for-a-Leading-Brazilian-Retailer/assets/154520350/e0a029df-9412-48dc-a818-feda37462d4e">
  - Charts:

    <img width="417" alt="image" src="https://github.com/jyotiprasadkurmi/Data-Analysis-for-a-Leading-Brazilian-Retailer/assets/154520350/a829c85f-f274-43dc-bfda-b9805a4c9e41">
  - Insights:From here we can see that most no of orders are pouring out from the states of SP RJ and  MG
  - Recomendations:from here we can also check why not other states are not placing a good amount of orders and check on the situations .

## How are the customers distributed across all the states?
  - Query:

    <img width="417" alt="image" src="https://github.com/jyotiprasadkurmi/Data-Analysis-for-a-Leading-Brazilian-Retailer/assets/154520350/8261ee33-b40e-4637-ac67-db83852ea899">
  - Results:

    <img width="423" alt="image" src="https://github.com/jyotiprasadkurmi/Data-Analysis-for-a-Leading-Brazilian-Retailer/assets/154520350/a8eb8c01-f645-4271-a4e6-8170da085a79">
  - Charts:

    <img width="417" alt="image" src="https://github.com/jyotiprasadkurmi/Data-Analysis-for-a-Leading-Brazilian-Retailer/assets/154520350/ec672da2-fe9e-4507-a361-5c14461548a0">
  - Insights:From the chart you can see that 40k of the customers are in SP and almost all the states have less than 20k customers.

## A.	Get the % increase in the cost of orders from year 2017 to 2018 (include months between Jan to Aug only). 
  - Query:

    <img width="417" alt="image" src="https://github.com/jyotiprasadkurmi/Data-Analysis-for-a-Leading-Brazilian-Retailer/assets/154520350/a231d6cf-3e3e-4f6a-8847-684496206d46">
  - Results:

    <img width="417" alt="image" src="https://github.com/jyotiprasadkurmi/Data-Analysis-for-a-Leading-Brazilian-Retailer/assets/154520350/ffa13bc3-b3ff-47e1-b203-5c8ac645d430">
  - Charts:

    <img width="417" alt="image" src="https://github.com/jyotiprasadkurmi/Data-Analysis-for-a-Leading-Brazilian-Retailer/assets/154520350/9af3ebbb-c262-4b33-8dde-0e300d516362">
  - Insights:There has been an increase in the percentage of orders over the month clearly from the graph.

## Calculate the Total & Average value of order price for each state.
  - Query:

    <img width="417" alt="image" src="https://github.com/jyotiprasadkurmi/Data-Analysis-for-a-Leading-Brazilian-Retailer/assets/154520350/1f70e229-0e43-4eb5-a8bd-f5033fe2f2de">
- Results:

  <img width="417" alt="image" src="https://github.com/jyotiprasadkurmi/Data-Analysis-for-a-Leading-Brazilian-Retailer/assets/154520350/b612791b-dd61-4f39-b5fe-28ef301b0780">
- Charts:

  <img width="417" alt="image" src="https://github.com/jyotiprasadkurmi/Data-Analysis-for-a-Leading-Brazilian-Retailer/assets/154520350/cf11fe78-abff-4933-9408-372925bc0532">
- Insights:We can see here the order price of each state, the total and average value .

## Calculate the Total & Average value of order freight for each state.
- Query:

  <img width="417" alt="image" src="https://github.com/jyotiprasadkurmi/Data-Analysis-for-a-Leading-Brazilian-Retailer/assets/154520350/27822fad-cb03-4e19-a8ef-a8ed18f81e95">
- Results:

  <img width="417" alt="image" src="https://github.com/jyotiprasadkurmi/Data-Analysis-for-a-Leading-Brazilian-Retailer/assets/154520350/8dd151fc-bc95-437f-8c0b-951a3a2ec442">
- Charts:

   <img width="417" alt="image" src="https://github.com/jyotiprasadkurmi/Data-Analysis-for-a-Leading-Brazilian-Retailer/assets/154520350/3c7498e4-3f03-4501-86a2-1c6be20c2d0a">
- Insights:The total and average freight_value for each state has been shown here.

## A.	Find the no. of days taken to deliver each order from the order’s purchase date as delivery time.
## Also, calculate the difference (in days) between the estimated & actual delivery date of an order.
## Do this in a single query.
## You can calculate the delivery time and the difference between the estimated & actual delivery date using the given formula:
  ●	time_to_deliver = order_delivered_customer_date - order_purchase_timestamp
  ●	diff_estimated_delivery = order_estimated_delivery_date - order_delivered_customer_date
  - Query:

    <img width="417" alt="image" src="https://github.com/jyotiprasadkurmi/Data-Analysis-for-a-Leading-Brazilian-Retailer/assets/154520350/61ecc544-ec73-444e-9056-796667a976ee">
  - Results:

    <img width="417" alt="image" src="https://github.com/jyotiprasadkurmi/Data-Analysis-for-a-Leading-Brazilian-Retailer/assets/154520350/1a0c5a46-4b2e-4f05-aabc-eec1e44b67fe">
  - Charts:

    <img width="417" alt="image" src="https://github.com/jyotiprasadkurmi/Data-Analysis-for-a-Leading-Brazilian-Retailer/assets/154520350/14f06a44-9820-4663-a321-1bcb9ca6c84f">
  -  Insights:Here we can see that actual delivery time is lesser than the estimated delivery time
  -  Recomendations: We can show the estimated time in the app or website nearly equal to the actual because many of the customer shops whether the delivery time is less or not if they see a less estimated delivery they won’t switch to another Platform

## Find out the top 5 states with the highest & lowest average freight value.
  - Query:

    <img width="417" alt="image" src="https://github.com/jyotiprasadkurmi/Data-Analysis-for-a-Leading-Brazilian-Retailer/assets/154520350/a6e8d7da-2f79-4dac-8143-a4cf49cacdc1">
  - Results:

    <img width="417" alt="image" src="https://github.com/jyotiprasadkurmi/Data-Analysis-for-a-Leading-Brazilian-Retailer/assets/154520350/c12a4524-c74a-4f08-839b-a7fa71c2c99c">
  - Charts:

    <img width="417" alt="image" src="https://github.com/jyotiprasadkurmi/Data-Analysis-for-a-Leading-Brazilian-Retailer/assets/154520350/c3c9e337-1905-46c5-912e-b0f79f41deca">
  - Insights: Given here the top 5 states having highest_avg_freight and top 5 states having lowest_avg_freight.

## Find out the top 5 states with the highest & lowest average delivery time.
  - Query:

    <img width="417" alt="image" src="https://github.com/jyotiprasadkurmi/Data-Analysis-for-a-Leading-Brazilian-Retailer/assets/154520350/72c9714b-dda1-49cd-97d5-2e7b31c44f2e">
  - Results:

    <img width="417" alt="image" src="https://github.com/jyotiprasadkurmi/Data-Analysis-for-a-Leading-Brazilian-Retailer/assets/154520350/a0a5b48b-f2c9-400c-80cc-66a7c1c21226">
  - Charts:

    <img width="417" alt="image" src="https://github.com/jyotiprasadkurmi/Data-Analysis-for-a-Leading-Brazilian-Retailer/assets/154520350/661a38ab-ea03-46e7-8603-f2f2c3c3ae17">
  - Insights:Here the results are showing the highest delivery time and the lowest delivery time for the customer state.

## Find out the top 5 states where the order delivery is really fast as compared to the estimated date of delivery.
  - Query:

    <img width="417" alt="image" src="https://github.com/jyotiprasadkurmi/Data-Analysis-for-a-Leading-Brazilian-Retailer/assets/154520350/b1726be6-ac43-4fe1-bed9-eefe447187d2">
  - Results:

    <img width="417" alt="image" src="https://github.com/jyotiprasadkurmi/Data-Analysis-for-a-Leading-Brazilian-Retailer/assets/154520350/9a61d393-f1b0-4f7a-bd54-f1574d0c1300">
  - Insights:These are the top 5 states where the delivery time is very less.

## Find the month on month no. of orders placed using different payment types.
  - Query:

    <img width="417" alt="image" src="https://github.com/jyotiprasadkurmi/Data-Analysis-for-a-Leading-Brazilian-Retailer/assets/154520350/163f38e8-601d-4e44-91a2-f223c9af945e">
  - Results:

    <img width="417" alt="image" src="https://github.com/jyotiprasadkurmi/Data-Analysis-for-a-Leading-Brazilian-Retailer/assets/154520350/cba38178-ce57-4c4e-a2b2-6a04e2b6369a">
  - Charts:

    <img width="417" alt="image" src="https://github.com/jyotiprasadkurmi/Data-Analysis-for-a-Leading-Brazilian-Retailer/assets/154520350/4d05414b-e06c-4ccd-9df1-e4c86818fa5d">
  - Insights: Here we can see the payment_types that most of the customers have used to place their orders
  - Recomendations: Many of the customers have ordered using credit-card, we can rope in different credit card brands with offers for the customer and make a smooth experience for them.

## Find the no. of orders placed on the basis of the payment instalments that have been paid.
  - Query:

    <img width="417" alt="image" src="https://github.com/jyotiprasadkurmi/Data-Analysis-for-a-Leading-Brazilian-Retailer/assets/154520350/649a4d6e-2196-470d-ba56-111833fc0f0d">
  - Results:

    <img width="336" alt="image" src="https://github.com/jyotiprasadkurmi/Data-Analysis-for-a-Leading-Brazilian-Retailer/assets/154520350/a7144be5-91e7-4f04-b59e-5e8a137d5cbb">
  - Insights:Total no. of orders that have been used to pay in instalments and that orders where  instalments have been paid fully is 308























