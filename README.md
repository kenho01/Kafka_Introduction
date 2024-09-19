# Kafka Stock Market Data Simulation

## Summary
- Learnt Apache Kafka by simulating the extraction of stock market data from a CSV file using Python.
- The setup includes commissioning of a Kafka Producer and Consumer on an EC2 instance hosted on Amazon Web Services (AWS).
- Producer reads stock market data passed in periodically from a CSV file and sends it to a Kafka topic.
- Consumer listens to the topic and writes the consumed data as JSON files into an S3 bucket.
- TODO: Use AWS Crawler, Glue & Athena to analyze data.

