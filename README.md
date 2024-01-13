# PyFlink Streaming Analysis with Kinesis Integration

This repository contains a Python script for stream processing using Apache Flink's Python API, PyFlink, with integration into AWS Kinesis Data Streams. The script is designed to create a real-time data processing pipeline that reads from a source Kinesis stream, performs sliding window aggregations, and writes the results to a sink Kinesis stream.

## Key Features

### Flink Table Environment Setup
- Utilizes PyFlink's Table API to create a streaming environment.
- Enables complex stream processing tasks using SQL-like syntax.

### AWS Kinesis Data Stream Integration
- Configured to interface with AWS Kinesis.
- Ability to consume and produce data from/to Kinesis Data Streams.
- Critical for applications relying on AWS for real-time data streaming and analytics.

### Sliding Window Aggregation
- Implements a sliding window over a 10-second interval.
- Computes minimum values from the streaming data.
- Useful for time-series analysis in streaming data.

### Dynamic Property Handling
- Method to handle application properties.
- Adapts to different environments (local or AWS-based setups).
- Customizes configurations such as stream names and AWS regions.

### UDF (User-Defined Function) Integration
- Demonstrates the use of UDFs in Flink.
- Enhances the capability to perform custom operations on stream data.
- Includes a UDF for converting timestamps to strings.

### Source and Sink Table Creation
- Defines and creates source and sink tables in Flink, connected to Kinesis streams.
- For reading and writing streaming data.

### Flexible Deployment
- Designed to run in both local environments and on AWS.
- Adaptable for development and production deployments.

## Getting Started

To use this script, clone the repository and set up your AWS environment with the necessary configurations for Kinesis Data Streams. Ensure you have PyFlink installed and configured in your development environment.



