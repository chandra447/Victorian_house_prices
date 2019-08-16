# Victorian_house_prices
Analysing the house prices in Victoria_Australia on the basis of location and the crime rate and different suburbs.
### Description<br>
The work consists of the data of house prices in victoria which are obtained from external agencies. The work involves analysing the price of the house based on the area, no of bathrooms, no of bedrooms etc and the crime rate in the suburb and as well the location of the house i.e the distance from the train station and the travel time to CBD.<br><br>
The facilities of public transport near to a house are determined by using the GTFS(General Transit Feed Specification) data which is obtained from the goople_api.<br><br>
For this study we are only considering that a location is good if there is a direct train to CBD(southern cross station) between 7am to 12am during all the weekdays.<br><br>
To analyse the crime data we are using the crime data in victoria based on the 2016 obtained from Crime statistics agency which is provided as a .xslx file<br><br>

### Usage<br><br>
The repository consits of House_prices.ipynb which demonstrates my work on the analysis.<br><br>
The prices.csv file consists of the house price data from a well reputed real estate agency.<br><br>
The  	VIC_LOCALITY_POLYGON_shp.zip consists of the shape file and it dependencies which gives the boundaries of the suburbs in Victoria Australia.<br><br>
The council_dataset.txt helps to determine to which council a suburb belongs to.<br><br>
The folders 1 and 2 contains the gtfs data which are downloaded from the google_api.<br><br>

### Future Development
With the integrated data from different resources we are built a clean and valid dataset which can be used to train a regression model which can help us in predicting accurate house price in victoria. which help us to avoid pitfalls of the agents.<br><br>
