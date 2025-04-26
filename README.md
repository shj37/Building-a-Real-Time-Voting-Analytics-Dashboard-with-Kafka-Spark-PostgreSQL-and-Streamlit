# Real-Time Voting Analytics Dashboard with Kafka, Spark, PostgreSQL, and Streamlit

![project overview](https://miro.medium.com/v2/resize:fit:1100/format:webp/1*nWcZqavTVRr-GXHD20kvzg.jpeg)

![live voting dashboard](https://miro.medium.com/v2/resize:fit:1100/format:webp/1*S446NcCgir6Aiqt9uOd57A.gif)

## Overview  
This project simulates an election, streaming votes with Apache Kafka and processing them in real-time with Apache Spark. A Streamlit dashboard visualizes the results live, pulling data from PostgreSQL.  

## Technologies  
- **Apache Kafka**: Streams voter data.  
- **Apache Spark**: Processes votes in real-time.  
- **PostgreSQL**: Stores voter and candidate info.  
- **Streamlit**: Displays live analytics.  
- **Docker Compose**: Runs all services.  

## Features  
- Streams simulated election data for 250 voters across three candidates.  
- Computes real-time metrics like vote totals and leading candidate.  
- Shows results in an interactive dashboard.  

## How to Run  
1. Clone this repo.  
2. Install dependencies (`requirements.txt`).  
3. Start services with `docker-compose up`.  
4. Run the data generator, Spark job, and Streamlit app (see [docs](link-to-docs)).

## Learn More

This project is fully documented in a [Medium article series](https://medium.com/@jushijun/building-a-real-time-voting-analytics-dashboard-with-kafka-spark-postgresql-and-streamlit-6b28199e94ca).

## References
- CodeWithYu https://www.youtube.com/watch?v=X-JnC9daQxE&t=3s&ab_channel=CodeWithYu
- https://github.com/airscholar/realtime-voting-data-engineering

*All credit to CodeWithYu for the original project design and code.*