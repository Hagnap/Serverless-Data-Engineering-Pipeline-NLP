# Serverless-Data-Engineering-Pipeline-NLP

This project 
  1) Reads a table from Dynamodb
  2) Puts the contents from the table into a SQS queue
  3) Calls a Lamda Function to take the contents from the queue and perform a Sentiment Analysis on each element
  4) The result of the Sentiment Analysis is then stored in a S3 Bucket
