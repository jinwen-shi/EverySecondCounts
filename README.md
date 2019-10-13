# EverySecondCounts
This project is completed within 3 weeks at Insight Data Science, Boston MA

## Goal
- This project uses a data-drive approach to predict the arrival time for 911-dispatched calls in San Francisco
- To help the dispatcher, caller and the first responder conduct a timely communication, further improving the government efficiency for emergency response
 
## Data Source
- Retrive the 950,000 911-dispatched incidents from 2016 to 2019 
- The data source comes from 'Fire Department Calls for Service' table from DataSF.com

## Method
- Use various python packages to explore and generate features comprising temporal, geospatial and dispatch information
- Build random forest regression model to predict the response time from the selected features
- Build a baseline model to comare and evaluate the performance of the random forest model

## Result
- The derived model achieves 40% reduction on the Mdedian Absolute Error

## Implementation
- The functions of the derived model is embedded into the web app: http://everysecondcounts.live/
- This web app is implemented using Dash with Python and deployed on AWS



