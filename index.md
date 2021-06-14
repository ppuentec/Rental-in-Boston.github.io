![Boston](https://raw.githubusercontent.com/ppuentec/Rental-in-Boston.github.io/gh-pages/Boston3.jpg)

## Rental properties in the Boston area

Now that a more significant percentage of the population is getting vaccinated, the pandemic allows us to start leaving our homes. Now, we can visit family members and plan a vacation.

During this summer more people will start vacationing in many places across the country, including the Boston area. Some may want to invest in rental properties and try to capture some of the dollars that will become available from travelers in the coming months. 

Suppose you are exploring buying rental properties and try to start an Airbnb business in the Boston area. In that case, you may want to begin your analysis by answering the following fundamental questions:

- What is the expected revenue per day that I can receive from a rental property in that market?
- What is a good level of occupancy rate so I can become more profitable?
- What to do to predict rental prices for a small apartment or house in that part of the country?

### Rental property data used

To answer these questions, I took data from Airbnb in Boston, and I provided some insights about the available properties and rental prices of small parcels in that area.

### Rental property data cleaning and preparation 

I took Rental property information from Kagel about the Boston market. The data was very large, I had to eliminate several columns of data, eliminate unnecesary data and transform some data for calculations.

I also calculated an 'Average Daily Rate' that will indicate the level of revenues that can be expected in that market. I have also calculated an 'Occupancy Rate' that will provide some information about the actual occupancy level and indicate market saturation and possible loss of revenue for current property owners.

![Avg Daily Rate](https://raw.githubusercontent.com/ppuentec/Rental-in-Boston.github.io/gh-pages/ADR.jpg)

## Main findings

i) Expected revenue per day
After cleaning up some rows and columns of unuseful data, I was able to find out that most of the properties in Boston are rented for around $100 and $150 per day. This rates include cleaning fees that must be prorated if the client rent more days.

![Rental Rates](https://raw.githubusercontent.com/ppuentec/Rental-in-Boston.github.io/gh-pages/Rental_Rates.jpg)

Another important finding is that people are willing to pay a higher rental fee for apartments with more bathrooms than with more bedrooms. So investor should give a priority to buy properties with more bathrooms than bedrooms. See charts below:

![Rental Rates with more bathrooms](https://raw.githubusercontent.com/ppuentec/Rental-in-Boston.github.io/gh-pages/RatesVSBathrooms.jpg)

![Rental Rates with more bedrooms](https://raw.githubusercontent.com/ppuentec/Rental-in-Boston.github.io/gh-pages/RatesVSBedrooms.jpg)

ii) Occupancy rates
Similarly, occupancy rates are very high or very low in the Boston area. Considering all types of properties in my analysis (total number 3,268), I found out that 1,254 properties had a very low availability which may indicate that owners prefer to lose some money and keep properties rented. This also may contribute to lower the overall rental rates for the area.

![Occupancy rates](https://raw.githubusercontent.com/ppuentec/Rental-in-Boston.github.io/gh-pages/Occupancy_rates.jpg)

iii) Approach to a rental price model
On the other hand, high availability may indicate that some properties are overprice leading to loss of profitabilities as well. See chart below for details:

Finally, I tried to build the foundation for a linear regression model to predict price of small properties up to two bedrooms and two bathrooms. I obtained r-squared values for house and apartments. In my analysis using dummy variables for bedrooms and bathrooms provided me a better r-squared values for the model. 

## Conclusion

If you are interested in entering into the airbnb business in the Boston area, investor should expect rental values between $100 and $150 per day. Customers are more interested in paying for more bathrooms than bedrooms. Most of the occupancy rate are either too low or too high which may indicate loss of revenue for current property owners. While building a liner regression model try to keep it simple and use dummy variables to avoid overfitting or underfitting issues.

Please feel free to use my analysis and data and build a more sophisticated model before making any invertsment decision.

Good luck!
