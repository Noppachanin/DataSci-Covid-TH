# DataSci-Covid-TH
This repo is my group project during the master degree. My group investigated the insight of covid-19 test data in Thailand
We uses Covid-19 case records in Thailand during 2021-2022 provided by ministry of public health. 

The dataset is time-series of cases, so we perform data cleaning and case prediction using LSTM[]

# What we found
- We show that LSTM can be used to predict the increment of covid-19 cases under specific social-distancing policies
- LSTM model faiiled to accurately predict the total cases as there is the new high numbers of cases with respect to the data in training set
- We provide a policy guideline using Recovery and cases forecasting to predict bed reservation period to ensure that there will be an available bed for a new patient.
