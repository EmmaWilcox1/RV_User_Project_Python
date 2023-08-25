# RV_User_Python

Python analysis of users of recreational vehicles, subsetted from recreation.gov dataset of 2022 reservations for public land use. Undertaken as indivualized project using a public dataset, for CareerFoundry Data Analystics course

# Objectives:

A car company has retooled to become an RV manufacturer, launching a new kind of camper under an original brand. They need descriptive insights and a predictive model for behavorial trends by those who already own and use RVs. The working assumption is that customers for the new brand will include people who are upgrading an existing RV, and first-time buyers of recreational vehicles. The company needs information about how far RV owners travel, how long they stay at campgrounds for what cost, the regions they prefer, and where their home states are, as seen in available data from public land use.

# Data:

-Data Name: “RIDB/Recreation.gov Historical Reservation Data” RIDBM= Recreation Information Database

-Data Citation: “Reservations2022”, Accessed ( https://ridb.recreation.gov/download ) on June 2023

-Data Source: Recreation.gov is managed by 12 different federal agencies. It is external data recorded and managed in accordance with the Federal Camping Data Standard, used to standardize campground data among federal agencies that manage campsites and campgrounds, including the National Park Service (NPS), the Bureau of Land Management (BLM), the Bureau of Reclamation (BOR), the United States Fish and Wildlife Service (FWS), the United States Forest Service (USFS), and the United States Army Corps of Engineers (USACE). The data source is trustworthy, not only because it comes from an established government source that has been collecting this data for more than a decade, but because there is extensive, recent documentation of the data standard is available for users.

-Data Collection: The data is usage data from online reservations, in addition to reservations made in the field or via call center. 
Without more information about the exact manner of data entry utilized for field and call center bookings, I am categorizing the data collection method as automatic and manual. 
The data for the year prior is released the following year. 

-Data Contents: The dataset contains 9653300 rows and 35 columns. It includes the facility ID (this is a key that could be used to merge other RIDBM datasets), 
the name of the park, latitude and longitude, state, the zip code of the customer making the reservation, the total paid, the number of nights booked, the start and end date of the stay 
as well as the date the reservation was made, the number of people staying, and equipment such as “RV.” 

-Data Limitations: Recreation.gov discloses that each federal agency provides and is responsible for the quality of data contained in the RIDB, and that data may be missing or incomplete, 
for example, some latitudes and longitudes may be blank. The data collection methods used in the field or at call centers seem likely to produce periodic errors, 
so there is some potential collection bias. A 2021 project using earlier reservation data, created by Tyler McIntosh, “The Camping Crunch” has documentation on data limitations he determined, 
including the fact that not every campground on public lands uses recreation.gov for bookings and cancellations are not included, however, more than 80% of public land with campgrounds are represented in dataset. PII appears to have been suppressed if collected, and thus a mechanism for determining return customers is not available.


# Vizualizations and Analysis created in Python with libraries:

-numpy

-pandas

-seaborn

-scipy

-matplotlib

-foliium

-json

-math

-SearchEngine

-sklearn

# Final storyboard and dashboard created with Tableau

-Storyboard (https://public.tableau.com/app/profile/emma1186/viz/TheJourneyistheDestinationRVUseandPublicLands/TheJourneyistheDestinationRVUseandPublicLands)

-Dashboard Design https://public.tableau.com/app/profile/emma1186/viz/JulyTrendsRVUseonPublicLand/JulyTrendsRVUseonPublicLand

#Contents:

-Project Management: Project Brief

-Data: Separated into Original and Prepared Data. This folder has not been included in repository because of space considerations.

-Scripts: Contains all the Jupyter scripts developed to clean, transform, analyze and visualize data

-Analysis: See links above
