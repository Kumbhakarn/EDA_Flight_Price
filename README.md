# EDA_Flighr_Price
 This dataset contains flight pricing information, including various flight details such as airline, route, duration, and price, for domestic flights in India. The data allows for the exploration of how factors like departure city, stops, and travel time impact ticket pricing.
 
![TotalStopsVsCount](https://github.com/user-attachments/assets/4ca76c89-d821-4613-a6b0-ccbff2ce328d)   
![DestinationVsCount](https://github.com/user-attachments/assets/425a53ab-072a-4722-85b4-dcfbfa537e93)
![SourceVSCount](https://github.com/user-attachments/assets/4135faca-8278-403a-834b-6269fcdea34c)
![AirlineVSCount](https://github.com/user-attachments/assets/08f5aed6-1670-4e00-bed3-14086de4c20e)

**Observations from the Data:**
1. **Airline Popularity:** Jet Airways has the highest number of passengers, followed by IndiGo, indicating these airlines are the most frequently chosen by travelers in the dataset.
2. **Source and Destination Trends:** The majority of passengers are traveling from Delhi, followed by Kolkata. The most common destination is Cochin, with Bangalore being the second most frequent destination.
3. **Stopover Patterns:** A significant portion of travelers have at least one stop during their journey, followed by those with direct flights (zero stops). Passengers with two and three stopovers make up a smaller percentage of the dataset.


#### `Here are the insights from the exploratory data analysis:`

**1. Distribution of Flight Prices:** The price distribution is right-skewed, indicating that most flights are priced within a certain lower range, with fewer flights at higher prices.
![Flight Price](https://github.com/user-attachments/assets/53538f08-ae6a-4c95-aa37-0a05f5665469)

**2.Number of Flights by Airline:** IndiGo and Jet Airways have the most number of flights in the dataset, while other airlines have fewer flights. This suggests that these two airlines dominate the flight market in this dataset.
![Number of flights by airlines](https://github.com/user-attachments/assets/bfda4a15-50bb-475f-952d-0355e3e44834)

**3.Price vs Flight Duration:** There is a positive correlation between flight duration and price. Longer flights, especially those with more stops, tend to have higher prices. Jet Airways has the highest-priced flights, particularly for longer durations.
![Price Vs Duration](https://github.com/user-attachments/assets/1dc01c0f-e9cd-4737-bb1d-7c3afc295c3b)

**4.Price Distribution by Total Stops:** Flights with no stops generally have a lower price range. As the number of stops increases, so does the variability in price, with flights having two or more stops often being more expensive.
![Total Stops](https://github.com/user-attachments/assets/e892047f-64ef-4a25-bfad-116c300e1b86)

