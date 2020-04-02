# corona-update

An Alexa skill that provides updates on the total number of COVID-19 cases and the deaths associated with it (for a particular country).

Data provided:
1. Total number of COVID-19 cases
2. Total deaths related to COVID-19

This skill consists of three parts:
1. Gathering data from https://www.worldometers.info/coronavirus/
2. Storing the data to database created with DynamoDB
3. Lambda function which runs on command from Alexa to provide the data for the country (user input)
