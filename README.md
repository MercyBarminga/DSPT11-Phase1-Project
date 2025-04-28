##INTRODUCTION The aviation industry experiences the least number of accidents and can easily qualify as the safest means of transport. However when accidents occur they are fatal. The analysis here-in explores the type of aircraft vis a vis the number of accidents. Other factors in consideration are weather and the state. This is to inform business on which fleet to acquire for the expansion of its operations. The below analysis is designed for the aviation industry.

#Objectives

From the first five columns we can identify missing values indicated by NaN in the columns from a glance
In total there are 88889 rows and 31 columns
#Missing Values
According to the data on missing values; Event.Id, Investigation.Type, Accident.Number, Event.Date are the columns with no missing values while Schedule, Air.carrier, FAR Description, Latitiude. Longitude, Aircraft Category are missing plenty of data, they are almost empty.
The weather column is important for our analysis. It is a string therefore replacing the missing values will be similarly with a string.
#Duplicates
There are no duplicates in our dataset.
#Explore data distribution. We will look at the aircraft model, weather conditions, state, injuries
Most of the data needed to make a comparison is in strings form, in text.
#Data Exploration In this next section we are going to group the data by year and the injuries. We will further look at the model most frquently used that year. Additionally, we will gain more insight on the prevailing weather conditions and what the report captured at the time. To do so we extract the date from the Event.Date column and extract the year.
According to our data, 2003 had the most fatal injuries with 1074 fatal injuries
In the most fatal year, the broad phase of flight varied from cruise to take off to landing, standing, maneuvering. At this point we cannot attribute the accidents to the broad phase of the flight.
The accident with the most fatalities took place in Cotonou, Benin. Investigation ruled it out as an accident. The weather conditions were VMC (Visual Meteorological Conditions). For the next three we have Sudan, Peru and Mexico showing IMC (Instrument Meteorological Condition) where the weather is foggy, cloudy and visibility is low. Weather does not appear to be a great factor in influencing the number of accidents that occur.
The dataframe on the make and model in use, gives us 1042 rows and 3 columns of the makes and models on the year with the highest number of fatal accidents.
According to our data, leading is Cessna make 172N contributing 29 out of the 1074 total fatalities. Cessna make stands out as it appears most, however the model varies.
According to our data, the year with the least fatal injuries is 1979
In 1979,while the investigation ruled it as an accident, the report status indicates probable cause. It happened in Boston, Massachusetts. The weather condition recorded is VMC meaning clear skies. Weather condition does not seem to be a contributing factor. The broad.phase.of.flight reads climb. The make was a Mcdonnell Douglas and the model DC9.
The most frequent Broad phase of flight is landing.

##Data Visualization 
Data visualization is an integral part of analysis. This helps us to process data easily and good visuals may catch something that could easily be lost in details.

The bar graph shows the number of aircraft accidents. 2003 is the year with the most accidents and while the least is not very clear, it is plain sight that the number if any of aircraft accidents between 1974-1998 are very few.
According to the data we have, CESSNA is the leading in terms of accidents. We looked at the top 10 aircraft makes.
The pivot table is a great tool but it does not immediately give the much needed answers. Lets explore a heatmap.
#CONCLUSION
After careful consideration of factors at play, these are the recommendations for acquisition of the fleet;
- Consider aircraft makes with least number of accidents for instance Boeing, Bell, Robinson. 
- Landing was one of the most accident prone phases according to the analysis. Hence train pilots extensively in abnormal landing scenarios
- Take into consideration diversification of the Makes and Models to reduced operations risk and avoid fleet vulnerabilities.
- Invest in technology for weather monitoring as many accidents occured under VMC which is meant to be good weather therefore implying human error.