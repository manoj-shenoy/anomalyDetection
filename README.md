# anomalyDetection
This app is intended to be used for detecting anomalies in PO data, related to Fraud. In this application,Machine Learning Models are deployed to identify trends and patterns in the supplied data to identify any anomalies.

## What is Machine Learning?
Machine learning imparts computers the ability to layer information, associated with multiple variables on top of one another. This allows for quick identification of trends and patterns, that otherwise would be difficult and time-consuming to detect, even to the most trained human eyes.

## How to use this application.
1. Click on 'Main' Tab.
2. Select a CSV File.
3. For selecting CSV File, Click on Browse on the sidetab to the left.
This csv file must mandatorily have the following columns related to:
1. PONumber
2. vendor Name
3. Payment terms such as net10, Net30 etc
4. whether Increase in PO Amount - 1 for yes, 0 for No
5. Assigned Engineer related to PO
6. Whether Change in Completion date- 1 for yes, 0 for No
7. Probability - Default value should be zero for all PO's
This is the value we are going to use to detect any anomalies in data.
