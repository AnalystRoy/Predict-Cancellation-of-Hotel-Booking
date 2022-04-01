## Predict-Cancellation-of-Hotel-Booking
We are going to develop a model that will predict where a particular booking made by a user will get cancelled or not

## Data Dictonary
It contain an elaborate description of the various columns in the table

## Important Question answered through performing Exploratory Data Analysis (EDA)
### Q1) Which Country have the highest number of guests?
### Ans) ![image](https://user-images.githubusercontent.com/88250882/161315372-dd1a92f0-7e4c-4f11-8315-e75659200719.png)
We use the library `folium` to create a choropleth using the `country_wise_data` variable. Based on the above choropleth we can Infer that the highest number of guests are from Portugal
### Q2) How much do guests pay for a night?
### Ans) ![image](https://user-images.githubusercontent.com/88250882/161316713-0d0cc8f3-ec93-4ea6-b336-adbd0842260f.png)
We use a boxplot to visualize the average price per room, depending on its type and the standard deviation. The `reserved_room_type` column has room types A, B, C, D, E, F, G, H, L, and P. Based on the boxplot we can conclude that the best price distribution with respect to city hotel is G room type and the best distribution of price with respect to resort hotel is H room type.
### Q3) How does the price per night vary over the year?
### Ans) ![newplot](https://user-images.githubusercontent.com/88250882/161318985-7586481d-7132-4f0f-8993-1aa4e4bcfe81.png)
This clearly shows that the prices in the `Resort hotel` are much higher during the summer. The price of the `city hotel` varies less and is most expensive during spring and autumn.
### Q4) Which are the most busy month or in which months Guests are high?
### Ans) ![newplot (1)](https://user-images.githubusercontent.com/88250882/161320111-ed2ba41c-1fcd-4c12-bf9c-57b0dc6751b6.png)
The City hotel has more guests during spring and autumn, when the prices are also highest. In July and August there are less visitors, although prices are lower.
The number of guests for the Resort hotel go down slighty from June to September, which is also when the prices are highest. Both hotels have the fewest guests during the winter.
### Q5) How long do people stay at the hotels?
### Ans) ![image](https://user-images.githubusercontent.com/88250882/161320679-923cb544-a35d-44dd-838d-6298a184bac9.png)
In city hotel guests mostly stay for 2-3 nights and in resort hotel guest mostly stay for 1-2 nights. However we can observe considerable number of guests have stayed in resort hotels for 7 nights.
 
