# PyBer_Analysis


## Overview:
A well know ride sharing company `Pyber` required a deep analysis for it ride data by city types. The objective of this project to analyze the ride sharing data to understand the rider and fare matrics for city type. The CEO of the company required the reports of visualizations of this data so that corrective action can be take for the growth of the business and understand the gaps if applicable.


## Resources & Environment

| Resource  
| -----------  
| city_data.csv      
| ride_data.csv




| Software / Environment | version | 
| ----------- |  ----------- | 
| Pandas version     | 1.4.2
| Numpy version      | 1.21.5
| Matplotlib version | 3.5.1
| Conda version      | 4.9.0
| ipykernal version  | 7.31.1
| Python version     | 3.9.12






## Results:

### Ride Count Data

<img width="806" alt="image" src="https://user-images.githubusercontent.com/22928255/190562550-c526625d-09d1-4e0d-8a95-15f4837bed22.png">

The average fare for rides in the rural cities is about $11 and $5 more per ride than the urban and suburban cities, respectively 




### Summary DataFrame

As per the given data( ride/city) , we analyzed and aggregation of PyBers ride sharing data, We have created a statistical overview and summary.

<img width="806" alt="image" src="https://user-images.githubusercontent.com/22928255/190563324-45d822ab-32dd-4c2e-bd5b-cb66ca1658f9.png">

Based on the date , we have our finding below :
* Rural cities have the highest average fare per ride and the least rides and drivers.
* Urban cities have the highest rides and total drivers and least average fare per ride. 
* The Analysis shows a relationship of Drivers by cities type and average fare per ride and average fare per drive. 
* During the end of month feburary , there was a peak in revenue ( fare ) , it may lead to any promotion by the company which increased the fare revenue. 






### Total Fare by City Type

<img width="806" alt="image" src="https://user-images.githubusercontent.com/22928255/190564682-fbd70037-bbdf-4740-bc93-d475f1188e23.png">

Based on the analysis , we confirmed that `62.7%` of fare was driving by the `Urban` cities. 


### Total ride by City Type

<img width="806" alt="image" src="https://user-images.githubusercontent.com/22928255/190565606-6fb8f8b3-1265-4ac3-ad9e-d93339b96c95.png">

Based on the analysis , we confirmed that `68.4%` ride from `Urban` cities. 

### Total Driver by City Type


<img width="806" alt="image" src="https://user-images.githubusercontent.com/22928255/190564825-f8160dc6-2e4c-429e-826b-c0ed91c4d158.png">


Based on the analysis , we confirmed that `80.9%` rides are from `Urban` cities. 

## Summary and Recommendations:

Based on the above analysis, there are the recommendations to `Pyber` :

* Urban Drivers have low average fare per ride, they should include the tiering system of time/distance based rides. 
* Have some business strategy to increase the drivers in Rural cities as there is low riders and Avg fare per drive is higher. 
* Weekly / Monthly promotions in the ride would provide the insight how the customer avail these offers. 
* Based on the data , Rural customer are using the pyber ride sharing for long distance rides. We have to focus on the short rides so that we will generate more fare revenue and have more drives in rural areas.
