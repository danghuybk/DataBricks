This repository stores my training work with Spark Structured Streaming on DataBricks platform. Including:
## 1. Practice Lab
### 1.1. Streaming Concepts Lab
- Stream data from a file and write it out to a distributed file system
- List and Stop active streams
### 1.2. Time Window Lab
- Use sliding windows to aggregate over chunks of data rather than all data
- Apply watermarking to throw away stale old data that you do not have space to keep
- Plot live graphs using display
### 1.3. Using Kafka Lab
- Establish a connection with Kafka and stream data
- Do some ETL jobs and time window function
## 2. Capstone Project: Twitter Streaming Data Pipeline
- In this capstone project, I will build a data pipeline to stream live Tweets through a message broker (Kafka) and Structured Streaming. 
- From the stream data, I will perform some ETL jobs to some information:
  - Most tweeted hashtag in last 5 minute window
  - A map of where tweets are coming from
![Most tweeted hashtag](“https://github.com/danghuybk/Spark-Training/blob/main/Structured%20Streaming/images/Mosted%20tweet%20hashtag.png”)
![Tweets map]("https://github.com/danghuybk/Spark-Training/blob/main/Structured%20Streaming/images/Tweets%20map.png")
