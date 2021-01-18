# AVH
AutonomousVehicleHub


Introduction 

Autonomous Vehicle Hub (AVH) 
Location, Design and Management Systems 


Cities around the world are getting ready for Autonomous Vehicles driving on their road and one of question is where all the self driving cars will be parked while waiting to serve customers and getting their batteries charged, also getting their maintenance done? Autonomous Vehicle Hub (AVH) is the answer. If one of the transportation company wants to invest into building AVHs around the pilot city, let say Pittsburgh, PA and hire data science company to help them for locations to optimize their service performance as well as the asset management.

Problem

What are the main decision making points for the AVH location ?  In the middle of the city would have been perfect start maybe we can turn one of the high rise buildings into AVH, but is enough entire city? No ! AVHs has to spread around city based on population density as well as business density. Each city as unique as finger print but all of them have similar characteristics like one part of the city has more restaurant and bars compared to other parts of the city and that can be really important not only for the location also for the size of the AVH. 

Solution

Clustering Algorithms would be very good start to generate center points around the city based on population and business density. We will use these center points to find real estate to build AVH. KMeans Clustering will give company better insight when it comes to determine the location and size of the AVH. Basically we will be looking for center points of populated areas in the city so higher the density higher the size of the real estate or number of AVH. First, we will map the 9 mile radius of the city from downtown, for mapping all the restaurants, bars, etc... we will use Foursquare also we will get population density from USPS then we will place our random center points in 3 mile radius from downtown to locate some real estate options if we can’t anything what we are looking for, we will adjust the center points accordingly so center points will guide us to location that we are looking for. 
