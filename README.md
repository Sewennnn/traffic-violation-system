Real-Time Traffic Violation Detection System

A real-time streaming pipeline that detects traffic violations from high-volume event data using Apache Kafka and Spark Structured Streaming, with persistent storage in MongoDB and real-time analytics visualizations.

⚙️ Tech Stack
- Apache Kafka – Real-time data ingestion
- Apache Spark (Structured Streaming) – Stream processing & analytics
- Python – Core processing logic
- MongoDB – NoSQL storage for processed results
- Docker – Containerized deployment
- Matplotlib – Real-time visualization

🏗️ System Overview
- Kafka ingests streaming traffic event data
- Spark Structured Streaming processes data in real time
- Violation detection logic identifies infractions (e.g., speeding)
- Results stored in MongoDB for persistence and querying
- Matplotlib visualizes trends and hotspot analysis

🚀 Key Features
- Real-time end-to-end streaming pipeline
- Stateful stream processing with Spark Structured Streaming
- Handles late & out-of-order events using watermarking
- High-throughput Kafka-based ingestion system
- Real-time violation analytics and hotspot detection

📊 Capabilities
- Detects traffic violations in real time
- Aggregates violations by time and location
- Identifies high-risk traffic zones
- Supports continuous streaming workloads

📁 Project Structure
```text
- producer/
  - producer_a.py → Event generator (type A traffic data)
  - producer_b.py → Event generator (type B traffic data)
  - producer_c.py → Event generator (type C traffic data)

- streaming/
  - data_design_streaming.py → Kafka + Spark Structured Streaming pipeline

- visualization/
  - dashboard.py → Traffic violation analytics & plots
```

💡 Key Highlights
- Built a distributed streaming system using Kafka + Spark
- Implemented stateful stream processing with event-time handling
- Designed scalable data pipeline architecture for real-time analytics
- Integrated storage + visualization for end-to-end insight delivery


