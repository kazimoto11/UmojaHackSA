# UmojaHackSA
Descriprion
Ride-hailing apps like Uber and Yassir rely on real-time data and machine learning algorithms to automate their services. Accurately predicting the estimated time of arrival (ETA) for Yassir trips will make Yassir’s services more reliable and attractive; this will have a direct and indirect impact on both customers and business partners. The solution would help the company save money and allocate more resources to other parts of the business.

The objective of this hackathon is to predict the estimated time of arrival at the dropoff point for a single Yassir journey. Established in 2017, Yassir is the leading ride-hailing company in Algeria. It covers all major Algerian cities and is expanding its services to Tunisia, Morocco and France. Besides ride-hailing services, Yassir is making customers’ lives easier by providing diversified services such as goods and food delivery as well as telemedicine.

Data
Please find the data here on Zindi.

The data contains details for 119,549 trips (train and test are split by date). Each row contains a start location and end location (reported as latitude and longitude to within approximately 100m) and the travel distance along the fastest route. Each trip also has a timestamp, which can be used to pull the weather for that day from Weather.csv file. The weather data includes temperature, rainfall and wind speed for the time period during which the trip data was collected.

Files available for download: Train.csv - contains the input variables and the target,

Train.csv - contains the input variables and the target, ‘ETA’
Test.csv - matches Train.csv but without the ETA
SampleSubmission.csv - is an example of what your submission file should look like. The order of the rows does not matter, but the names of the IDs must be correct.
Weather.csv - contains daily weather summaries, based on data from the ERA5 dataset.
Variable Descriptions: 'ID' - A unique ID

'Timestamp' - Time that the trip was started
'Origin_lat', 'Origin_lon' - Origin (in degrees latitude and longitude)
'Destination_lat', 'Destination_lon' - Destination
'Trip_distance' - Distance in meters on a driving route
'ETA' - Estimated trip time in seconds
