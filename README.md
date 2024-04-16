# Home_Sales
MOre expensive a house is, the more expensive and most views it had. 
In addition, catching data makes the processing time a little faster than normal data. After clearing the cache, it also makes the processing time a little faster. 

## What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.
Average Price for 4-Bedroom houses over the last 4 years seem to be contanstant:
YEAR_BUILT-$AVERAGE_PRICE
2022-$296,363.88
2021-$301,819.44,
2020-$298,353.78
2019-$300,263.70. 

## What is the average price of a home for each year the home was built, that has three bedrooms and three bathrooms? Round off your answer to two decimal places.
According to my data, 3 bedrooms and 3 bathrooms is around $290,000 because the prices have been around $290k.
YEAR_BUILT-$AVERAGE_PRICE
2017-$292676.79
2016-$290555.07
2015-$288,770.30
2014-$290852.27
2013-$295962.27
2012-$293683.19
2011-$291117.47
2010-$292859.62

## What is the average price of a home for each year the home was built, that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.
According to my data, 3 bedrooms, 3 bathrooms, 2 floor, >=2000sqft is around $292,000, but having that specific criteria of 2,000sqft and 2 floors has caused the properties to have a big price differences from $276k-$307k over the years rather than just being around $290k.
YEAR_BUILT-$AVERAGE_PRICE
2017-$280,317.58
2016-$293,965.10
2015-$297,609.97
2014-$298,264.72
2013-$303,676.79
2012-$307,539.97
2011-$276,553.81
2010-$285,010.22

## What is the average price of a home per "view" rating having an average home price greater than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.
Houses prices over One Million had more views, about 100 views than cheaper houses, and it took about 0.87seconds. 

## Using the cached data, run the last query that calculates the average price of a home per "view" rating having an average home price greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.
Cached data of Houses prices over One Million had more views, about 100 views than cheaper houses, and it took about 0.34seconds. 
Uncatched data of Houses prices over One Million had more views, about 100 views than cheaper houses, and it took about 0.31seconds. 
