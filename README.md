# Majids_Hotel
a flex dashboard in R for analyzing and illustrating Hotel's info and residence state. you can also use this dashboard to predict price per night, using a pre-trained model 

![hotel residence](https://github.com/pariyamd/Majids_Hotel/blob/main/hotel_residence.jpg)

## This shiny App consists of three parts:
### 1. Hotel Residence
you can choose a date and the graph will show hotel residence state by circles indicating room number and type of occupied rooms.
![price demand](https://github.com/pariyamd/Majids_Hotel/blob/main/price-demand.jpg)
### 2. Room Price and Demand
you can choose a period of time and room types, using left bar, and on the right you can see the price and demand alternation during the specified time period per room type.
![predict](https://github.com/pariyamd/Majids_Hotel/blob/main/predict.jpg)
### 3. Predict Room Price
Ive trained a Gradient Boosted Model using H2o, and saved that model.
you can enter a reservations delatails and using that model you can see the predicted price of your reservation

