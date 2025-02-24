# AAI530Group3

Authors:
Brian Johnson
Bosky Atlani
Mohammad Alkhawaldeh
 

## DataSet

This project uses the Taxi Service Trajectory (Mosquera-Lopez et al., 2023). The dataset originates from the ECML-PKDD 2015 Taxi Trajectory Prediction Challenge. It contains detailed trajectories of 442 taxis operating in Porto, Portugal from 01/07/2013 to 30/06/2014. The data was collected via GPS trackers installed in the taxis. Each trip’s trajectory was recorded, capturing GPS coordinates at 15-second intervals, along with other contextual metadata about the trip. 

For the purposes of this project, resource and time constraints, we have sampled rows from the original dataset

The sampled dataset can be retreived by contacting the authors

## Running the models

taxi_eda.ipynb contains the code to clean the dataset

taxi_next_location is the model for predicting the next location

taxi_demand is the model for prediction the demand by zone

taxi_all is combined file for all the models

The team chose the Long Short Term Memory (LSTM) model for predicting next location and the demand due to their ability to capture spatial-temporal patterns. A detailed report explains the architecture and results and can be obtained by contacting the authors. 


