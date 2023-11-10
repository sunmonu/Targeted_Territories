# Project Overview
This project aims to analyze household debt data across various counties over time, focusing on identifying trends and correlations between household debt levels and the opening and remodeling dates of Target stores.

### The analysis involves:

1. Exploratory Data Analysis (EDA) to understand the distribution and trends within the Target and household debt data.
2. Time Series Analysis using SARIMAX to model and forecast household debt levels.

The final outcome of the project will be a set of models and visualizations that can aid in understanding the impact of socioeconomic factors on the opening and success of Target stores. I hope that if based on  local household debt levels we can predict if there is /should be a Target store.


### Data Dictionary for Household Debt Data

* Date -	The date when the data was recorded. Typically in a YYYY-MM-DD format.

* area_fips-	FIPS (Federal Information Processing Standards) code identifying counties or county-equivalent entities in the United States.
* low- Lower bound estimate of household debt in the area represented by area_fips.
* high - 	Float	Upper bound estimate of household debt in the area represented by area_fips.

### Data Dictionary for Target Data 

* Data Dictionary for target.csv
* Address.AddressLine1: The street address of the Target store.
* Address.City: The city in which the Target store is located.
* Address.County: The county in which the Target store is located.
* Address.Latitude: The geographical latitude coordinate of the Target store.
* Address.Longitude: The geographical longitude coordinate of the Target store.
* Address.PostalCode: The postal code or ZIP code for the Target store's location.
* Address.Subdivision: The state or province in which the Target store is located.
* LocationMilestones.LastRemodelDate: The date of the last remodeling of the Target store, if applicable.
* LocationMilestones.OpenDate: The date when the Target store was opened.
* Name: The name of the Target store.
* Store.StoreDistrictID: An identifier for the district in which the Target store is located.
* Store.StoreGroupID: An identifier for the group to which the Target store belongs.
* Store.StoreRegionID: An identifier for the region in which the Target store is located.
* SubTypeDescription: A description of the Target store subtype, if applicable.
* TypeCode: A code indicating the type of Target store.
* AllCapability: A descriptor of all capabilities that the store possesses.
* Remodeled: A flag indicating whether the store has been remodeled (True or False).

