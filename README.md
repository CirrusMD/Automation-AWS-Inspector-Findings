# DRAFT - Automation: AWS Inspector Findings to POAM

## Google Apps Script Project
- Enable Google Drive API: Within the Apps Script Editor, enable the Google Drive API from the Services tab.

## Fetch AWS Inspector Results
- AWS API Gateway: Set up an AWS API Gateway that triggers a Lambda function to get AWS Inspector results.

## Google Apps Script to Interact with AWS
- URL Fetch Service: Use the URL Fetch Service in Google Apps Script to make a request to your AWS API Gateway.
- Handle Response: Process the JSON response from AWS and convert it into a format suitable for CSV conversion.

## Create/Update CSV in Google Drive
- CSV Conversion: Convert the processed data into CSV format using Google Apps Script methods.
- Create/Update File: Check if a CSV file exists. If not, create a new one, else update the existing file.



-----------
```
## FUTURE TO-DO
### Data Manuliplation Prior To Updating POAM
### Updating of POAM
### Schedule Schedule Execution
```
