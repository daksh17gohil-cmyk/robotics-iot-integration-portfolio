# IoT Edge Data Pipeline & Relational Storage Engine

## 📌 Project Overview
A high-performance, low-latency data pipeline designed to ingest raw, asynchronous hardware sensor logs, sanitize data anomalies in real-time, and structure the output into a relational MySQL database. 

This engine solves the common "garbage-in, garbage-out" issue faced by hardware startups by bridging the gap between noisy physical sensors and structured business analytics.

## 🛠️ Tech Stack
* **Languages:** Python 3.10+
* * **Database:** MySQL
* **Key Focus:** Hardware-Software Integration, Data Sanitization, Low-Latency Writing

## 🚀 Core Architecture
1. **Ingestion Layer:** Connects to device serial ports or MQTT brokers to pull raw hardware streams.
2. **Sanitization Layer:** Algorithms filter out sensor signal noise, dropped frames, and hardware calibration errors.
3. **Storage Layer:** Relational insertion schema optimized for high-write operational tracking.

## 📦 Quick Start
```bash
# Clone the repository
git clone [https://github.com/daksh17gohil-cmyk/robotics-iot-integration-portfolio.git](https://github.com/daksh17gohil-cmyk/robotics-iot-integration-portfolio.git)

# Install dependencies
pip install -r requirements.txt

# Run the pipeline simulation
python main.py
