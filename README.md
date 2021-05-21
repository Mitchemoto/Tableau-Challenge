# Tableau-Challenge
Working with Tableau

#Station Locations
Station location page gives you just a overview of where the citibike stations are located to give you a sense of the area covered.

#Routelines
Route lines can be filtered by Origin, Destination or both. Switching between the options gives you a better feel for the spread of where people come from or go to based on the 
station location. It would like likely that many stations having the same origin and destination lines, would likely have commuter type people who are heading downtown to work. 

#Busiest Starting Points
The bubble map provides a scaling look at which are the busiest starting points. The benefit of this look is it helps citibike locate high rental stations so if they are 
restocking areas after charges, they would want to target these locations to drum up the most business.

#StartSDestinationCounts
This gives a look on where their customers are going based on the specific starting point. We can look at "Newport Pkwy" station and see that there are 5732 instances where the 
start station is the end station. Likely leading one to believe that they are just day customers using the citibike to mill around town and dropped the bike back off at the 
location they got it. 

#BikeUsageByStationName
Here we get a look at how many times the bike has been used over the timeframe of the data. We start to notice the same colors picking up at the same locations. So the more the 
bike is at those locations, the more its used. As those key color markers start to shrink, we notice the over all useage of the bike shrnks as well. The main failing of this 
part of the data is we do not know when the bike was put out into ciruclation so we do not know if the data is skewed. 

#CountofRentalsYQM
The time frame of the data set is just over a years worth of data. We cannot develop an annual trend with just a single year but we can make assumptions based on the data 
provided. The data also may be skewed due to March of 2020 being the start of the covid 19 lock downs so as mandatory stay at home orders were in effect the ridership would 
naturally drop. We can wager from the data that ridership picks up at the end of Q1 and grows over Q2 and peaks in Q3 during the summer months. The winter months in Q4 would be 
a natural drop as weather in the area would play into effect. 

#AvgTripByBirthYear
We get a sense that the younger crowd of people using the service tend to use the bike the longest. It is different that what I would have thought as I would have figured more 
of the 1990 and before ages would use the bike as a way to use around town during vacation. There was an abnormally large number of 1950 births for 0 gender in the data set 
that were removed as it likely was customers using over subscribers with full profiles. 

#TotalUsersByType/Gender
The data is skewed on this, the existence of 0 gender. This could be linked to customers not needing to create a full profile so entering in minimal data to rent the bike. The 
0 designation is much lower in Subscriber data than it is in Customer data. 0 designation in customers is ~61% where as its ~1% for Subscribers. To get the most accuarate 
demographic information, it may be better to use only subscribers for this portion. 

#UserTypePie and GenderCounts
Just gives a representation of customers represtaion of their customer base. Over 50% are subscribers. They will want to keep pushing that number up so they may continue to get 
accurate demographic information. 



