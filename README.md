# Aircraft_landing_facilities_analysis
Aircraft Landing Facilities in the US
Geospatial data on US aircraft landing facilities and operational statistics
By Homeland Infrastructure Foundation
Retreive from Kaggle open-source dataset https://www.kaggle.com/datasets/thedevastator/aircraft-landing-facilities-in-the-us

About this dataset
The Aircraft Landing Facilities dataset provides comprehensive geospatial data on aircraft landing facilities across the United States. This dataset contains valuable information on the location, ownership, facility use, elevation, and operational statistics of these landing facilities.

Each landing facility is uniquely identified by a site number and is classified based on its type, such as whether it caters to general aviation or military operations. The dataset includes details about the number of aircraft based at each facility, including single-engine general aviation planes, jet engine planes, multi-engine general aviation aircraft, and helicopters.

Ownerships of the landing facilities vary and can be categorized into different types. The dataset also indicates if a facility has a control tower or customs landing rights. It provides insight into whether a facility offers commercial services or air taxi services.

Geospatial coordinates (latitude and longitude) allow for accurate location mapping of each landing facility. Additionally, information about each facility's proximity to the central business district (CBD) is included in terms of direction and distance.

Operational statistics offer insights into the activity level at each landing facility. It includes data on itinerant operations (takeoffs and landings), arrivals/departures count, enplanements (passengers boarded), passengers count overall at the establishment.

With this extensive dataset compiled from trusted sources like FAA's National Airspace System Resource Aeronautical Data Product and others mentioned in its source link provided with this dataset on Kaggle platform makes it an essential resource for various analyses related to aviation infrastructure planning, transportation management studies as well as market research within various sectors connected with air travel industry

How to use the dataset
How to Use the Aircraft Landing Facilities Dataset
The Aircraft Landing Facilities dataset provides geospatial data on aircraft landing facilities across the United States. This dataset includes information on location, ownership, facility use, elevation, and operational statistics. Here is a guide on how you can effectively use this dataset:

1. Familiarize Yourself with the Columns
The dataset contains numerous columns with various types of information. Before diving into the analysis, make sure you understand what each column represents. Below are some important columns to pay attention to:

SITE_NO: The unique identifier for each landing facility.
LAN_FA_TY: The type of landing facility.
OWNER_TYPE: The type of owner of the landing facility.
COUNTY_NAM: The name of the county where the landing facility is located.
CITY_NAME: The name of the city where the landing facility is located.
FULLNAME: The full name of the landing facility.
CERT_TYPE: The type of certification for the landing facility.
LATITUDE and LONGITUDE: Coordinates representing each landing facility's location.
2. Explore Location-based Information
One interesting aspect of this dataset is its geospatial nature. You can explore different locations based on a variety of parameters:

Distance from Central Business District (CBD)
Use the column CBD_DIST to analyze how far each airport or heliport is from its respective city's central business district (CBD). You can also utilize this data to study patterns in aviation infrastructure development around major cities.

Direction from CBD
The column CBD_DIR provides information about which direction an aircraft needs to travel from a given airport or heliport to reach its respective city's central business district (CBD). Analyzing this data might provide insights into flight path planning or geographical considerations for establishing airports.

Elevation
Use column ELEV to analyze the elevation of each landing facility. You can compare elevations between different airports to identify variations in topography and how they might impact aviation operations.

Coordinates
Latitude (LATITUDE) and longitude (LONGITUDE) values are provided for each landing facility. You can plot these coordinates on maps or perform spatial analysis to study patterns related to location, such as clustering of facilities or proximity to other landmarks.

3. Analyze Ownership and Use
Understanding the ownership and use of landing facilities is crucial for various analyses:

Owner Types
Column OWNER_TYPE indicates the type of owner for each landing facility

Research Ideas
Airport Planning: This dataset can be used for airport planning purposes. The information on location, ownership, facility use, elevation, and operational statistics can help in identifying suitable locations for new airport construction or expansion of existing airports.
Transportation Analysis: The dataset provides geospatial data on aircraft landing facilities across the United States. This information can be used to analyze the transportation network and connectivity between different cities and regions. It can help in identifying gaps in transportation infrastructure and optimizing routes.
Economic Development: The dataset includes information on the number of passengers, itinerant operations, arrivals, departures, and enplanements at each landing facility. This data can be utilized to assess the economic impact of aviation on different regions and guide investment decisions in infrastructure development and tourism promotion
Acknowledgements
If you use this dataset in your research, please credit the original authors.
Data Source

License
License: Dataset copyright by authors

You are free to:
Share - copy and redistribute the material in any medium or format for any purpose, even commercially.
Adapt - remix, transform, and build upon the material for any purpose, even commercially.
You must:
Give appropriate credit - Provide a link to the license, and indicate if changes were made.
ShareAlike - You must distribute your contributions under the same license as the original.
Keep intact - all notices that refer to this license, including copyright notices.
Columns
File: Aircraft_Landing_Facilities.csv

Column name	Description
X	The X-coordinate of the landing facility location. (Numeric)
Y	The Y-coordinate of the landing facility location. (Numeric)
SITE_NO	The unique identifier for each landing facility. (Text)
LAN_FA_TY	The type of landing facility. (Text)
EFF_DATE	The effective date of the landing facility data. (Date)
FAA_REGION	The FAA region where the landing facility is located. (Text)
FAA_DISTRI	The FAA district where the landing facility is located. (Text)
ST_POSTAL	The postal abbreviation of the state where the landing facility is located. (Text)
STFIPS	The FIPS code of the state where the landing facility is located. (Text)
FAA_ST	The FAA state code of the state where the landing facility is located. (Text)
STATE_NAME	The name of the state where the landing facility is located. (Text)
COUNTY_NAM	The name of the county where the landing facility is located. (Text)
COUNTY_ST	The state abbreviation of the county where the landing facility is located. (Text)
CITY_NAME	The name of the city where the landing facility is located. (Text)
FULLNAME	The full name of the landing facility. (Text)
OWNER_TYPE	The type of owner of the landing facility (e.g., public or private). (Text)
FAC_USE	The primary use of the landing facility (e.g., general aviation or military). (Text)
FAC_CYSTZP	The certification type of the landing facility. (Text)
LATITUDE	The latitude coordinate of the landing facility location. (Numeric)
LONGITUDE	The longitude coordinate of the landing facility location. (Numeric)
ELEV	The elevation of the landing facility in meters. (Numeric)
AERO_CHART	The aeronautical chart associated with the landing facility. (Text)
CBD_DIST	The distance from the landing facility to the central business district in miles. (Numeric)
CBD_DIR	The direction from the landing facility to the central business district. (Text)
ACT_DATE	The date when the landing facility data became effective. (Date)
CERT_TYPE	The certification type of the landing facility. (Text)
FED_AGREE	Indicates if a federal agreement exists for the landing facility. (Text)
INTERNATIO	Indicates if the landing facility has customs landing rights. (Text)
CUST_LNDG	Indicates if the landing facility provides customs landing services. (Text)
JOINT_USE	Indicates if the landing facility has joint-use agreements with multiple entities. (Text)
MIL_LNDG_R	Indicates if the landing facility is used for military landings. (Text)
CNTL_TWR	Indicates if the landing facility has a control tower. (Text)
S_ENG_GA	The number of itinerant operations (takeoffs and landings) by single-engine general aviation aircraft. (Numeric)
M_ENG_GA	The number of itinerant operations (takeoffs and landings) by multi-engine general aviation aircraft. (Numeric)
JET_EN_GA	The number of itinerant operations (takeoffs and landings) by jet engine general aviation aircraft. (Numeric)
HELICOPTER	The number of itinerant operations (takeoffs and landings) by helicopters. (Numeric)
OPER_MIL	The number of military operations at the landing facility. (Numeric)
ULTRALIGHT	The number of itinerant operations (takeoffs and landings) by ultralights. (Numeric)
COMM_SERV	Indicates if commercial services are provided at the landing facility. (Text)
AIR_TAXI	Indicates if air taxi services are provided at the landing facility. (Text)
LOCAL_OPS	The number of local operations (takeoffs and landings) at the landing facility. (Numeric)
ITIN_OPS	The number of itinerant operations (takeoffs and landings) at the landing facility. (Numeric)
MIL_OPS	The number of military operations at the landing facility. (Numeric)
Arrivals	The number of arrivals at the landing facility. (Numeric)
Departures	The number of departures from the landing facility. (Numeric)
Enplanemen	The number of passengers enplaned (boarded) at the landing facility. (Numeric)
Passengers	The total number of passengers at the landing facility. (Numeric)
