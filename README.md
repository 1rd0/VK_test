Project: Spark Log Processing

Description

This project demonstrates how to use Apache Spark for processing log data in a scalable and efficient manner. It generates sample log data containing email addresses, actions (CREATE, READ, UPDATE, DELETE), and timestamps. The Spark application then reads the data, calculates weekly aggregates by action type (CREATE, READ, UPDATE, DELETE) for each email address, and saves the results as CSV files.

Features

Data Generation: Creates realistic log data using the Faker library.
Spark Integration: Leverages Spark for distributed data processing.
Weekly Aggregation: Calculates weekly counts of actions per email.
CSV Output: Generates CSV files containing the aggregated data.
