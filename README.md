# Flight Delays Exploration and Visualisation
## by Gladys Dalla


## Dataset

The dataset reports of flight arrival and departure details including carriers and reasons for delays for all commercial flights within the USA, from October 1987 to April 2008. This is a large dataset: there are nearly 120 million records in total, and takes up 1.6 gigabytes of space compressed and 12 gigabytes when uncompressed.

The datasets used(1997.csv, 2007.csv, carriers.csv, airports.csv) can be found here: https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/HG7NV7

For each flight the following data was recorded:

1. Identification information: flight number, date and tail number (air-craft identification)
2. Flight information: carrier code (like AA for American Airlines), origin and destination airports codes
3. Time information: scheduled and actual departure (or arrival) hour, and their difference being the departure or arrival delay (with a one-minute precision)
4. Flight duration information: scheduled and actual duration
5. On-ground information: taxiing duration and take-off or landing hour
6. Delay reason (if available): part of the delay that can be attributed to the carrier, to the weather, to the air traffic control, to security reasons or to late arrival of the aircraft from the previous flight

## Summary of Findings

- The longest delay was 2598 minutes(equals 43 hours and 18 minutes) — almost a whole two days! The route is from **Palm Beach International(PBI) airport to Detroit Metropolitan-Wayne County(DTW) airport** using **NortWest Airlines(NW)** on October 3rd 2007. The scheduled departure time local was at 12:59 pm, but the actual departure time was at 08:20 am. The scheduled arrival time was at 03:51 pm, but the actual arrival time was at 11:09 am. The reason of delay recorded was carrier with 2580 minutes and Late Aircraft Delay of 18 minutes.

- 6am to 10pm are the most favoured time for travel with 7pm for arrival and 8am for departure prefered in the 90s. This shows not much change after a decade.

-Most flights fall in the range of 11 miles and 1200 miles.

- In the 2000s, 49% of flights arrive early than expected and only 15% of flights arrive more than 30 minutes late and 35% less than 30 minutes late. This came to be very surprising to me as the vast majority of flights arrive ahead of schedule. Moreover, only around 15% of flights are late by more than 30 minutes, which is far fewer than I personally expected. Compairing to the 90s, flights have improved after a decade by both early arrival and late arrival of less than 30 minutes. Their is a 5% increase in early arrivals and 11% decrease in late arrivals of less than 30 minutes. However, their is a 5% increase of late arrivals of more than 30 minutes which is a concern.

- Among the airlines; Atlantic Southeast Airlines(EV) experiences the highest amount of arrival delays with an average of 17 min with Southwest Airlines experiencing the least amount of arrival delays with an average of 6 minutes. Aloha Airlines and Hawaiian Airlines are the only airlines with no delays as they arrive earlier than expected.

- Among the top 10 busiest airlines; the highest delays are experienced by American Airlines (AA) which is the 2nd highest in number of flights overall. The least number of delays are experienced by Southwest Airlines (WN) which tops the list of highest number of flights overall. This is in contrast with each other and shows the superiority of SouthWest Airlines.

- Among the airports; Atlanta Intl(ATL) Airport has the highest inbound and outbound traffic while Downtown(MKC) Airport has the least. Nantucket Memorial(ACK) airport experiences the highest delays while Mercedita (PSE) Airport experiences the least delays. 

- Among top 10 maximum traffic airports; George Bush Intercontinental(IAH) and Phoenix Sky Harbor International(PHX) have significant dispersion of delays. ORD(Chicago O'Hare International), however, was almost twice as delayed all the time, compared to every other high
volume airport.

- Among the routes; Kahului(OGG) - Honolulu International(HNL) route is the highest travelled. Ontario International(ONT) to Washington Dulles International(IAD) route experiences the highest delays while McCarran International (LAS) Airport to Central Illinois Regional(BMI) Airport experiences the least delays.

- Among the busiest routes; Maximum delay experienced by the busiest routes is 20 minutes with United Airlines. This shows the busiest routes don't have high number of delays with the airlines that cover these routes. McCarran International(LAS) to Los Angeles International(LAX) route(to and fro) experiences the highest delays among the airlines that fly this route while LIH to HNL is the route that experiences less delays(to and fro) amongst the airlines that fly this route
 
- Summer months of June, July and August together with Winter season in December and February experience high delays. while Autumn months of September, October and November experience minimal delays.

- Friday and Thursday have the highest delays while Saturday has the least delays.

- Late Aircraft Delay is the highest delay reason and experienced highly in winter season (December, January and February)together with Summer season (June, July and August). In winter it could be due to the clearing of snow off the runways and in the summer it could be due to the high people traffic.   

- Carrier Delay is the second highest delay and also experienced highly in winter season (December, January and February) together with Summer season (June, July and August)

- Weather Delay is highly distributed in Winter season(December, January and February) compaired to summer season (June, July and August). This could be so due to the snow.


## Key Insights for Presentation

**Insight 1**

- There are delayed arrivals as well as earlier arrivals and the most of them are between -42 to 48 min differ of the scheduled time.

**Insight 2**

- In the 2000s, 49% of flights arrive early than expected and only 15% of flights arrive more than 30 minutes late and 35% less than 30 minutes late. This came to be very surprising to me as the vast majority of flights arrive ahead of schedule. Moreover, only around 15% of flights are late by more than 30 minutes, which is far fewer than I personally expected. Compairing to the 90s, flights have improved after a decade by both early arrival and late arrival of less than 30 minutes. Their is a 5% increase in early arrivals and 11% decrease in late arrivals of less than 30 minutes. However, their is a 5% increase of late arrivals of more than 30 minutes which is a concern.

**Insight 3**

- Among the airlines; Southwest Airlines tops the list with the highest volume of flight numbers in the 2000s. This is an increase from the 90s of 47%. Delta Air which toped in the 90s has a reduced volume with a drop of 48%.

- Among the airlines; Atlantic Southeast Airlines(EV) experiences the highest amount of arrival delays with an average of 17 min with Southwest Airlines experiencing the least amount of arrival delays with an average of 6 minutes. Aloha Airlines and Hawaiian Airlines are the only airlines with no delays as they arrive earlier than expected.

- Among the top 10 busiest airlines; the highest delays are experienced by American Airlines (AA) which is the 2nd highest in number of flights overall. The least number of delays are experienced by Southwest Airlines (WN) which tops the list of highest number of flights overall. This is in contrast with each other and shows the superiority of SouthWest Airlines.

**Insight 4**
- Among the airports; Atlanta Intl(ATL) Airport has the highest inbound and outbound traffic while Downtown(MKC) Airport has the least. Nantucket Memorial(ACK) airport experiences the highest delays while Mercedita (PSE) Airport experiences the least delays. 

- Among top 10 maximum traffic airports; George Bush Intercontinental(IAH) and Phoenix Sky Harbor International(PHX) have significant dispersion of delays. ORD(Chicago O'Hare International), however, was almost twice as delayed all the time, compared to every other high
volume airport.

**Insight 5**
- Among the routes; Kahului(OGG) - Honolulu International(HNL) route is the highest travelled. Ontario International(ONT) to Washington Dulles International(IAD) route experiences the highest delays while McCarran International (LAS) Airport to Central Illinois Regional(BMI) Airport experiences the least delays.

- Among the busiest routes; Maximum delay experienced by the busiest routes is 20 minutes with United Airlines. This shows the busiest routes don't have high number of delays with the airlines that cover these routes. McCarran International(LAS) to Los Angeles International(LAX) route(to and fro) experiences the highest delays among the airlines that fly this route while LIH to HNL is the route that experiences less delays(to and fro) amongst the airlines that fly this route

**Insight 6**
- Late Aircraft Delay is the highest delay reason and experienced highly in winter season (December, January and February)together with Summer season (June, July and August). In winter it could be due to the clearing of snow off the runways and in the summer it could be due to the high people traffic.   

- Carrier Delay is the second highest delay and also experienced highly in winter season (December, January and February) together with Summer season (June, July and August)

- Weather Delay is highly distributed in Winter season(December, January and February) compaired to summer season (June, July and August). This could be so due to the snow.