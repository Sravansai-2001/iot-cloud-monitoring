# Hybrid Edge-Cloud System for Real-Time Industrial Asset Monitoring

This repository contains the implementation of a hybrid edge-cloud architecture designed for real-time industrial asset monitoring. The system combines edge computing (using Raspberry Pi with Node-RED, Mosquitto, InfluxDB, and Grafana) with cloud computing (Microsoft Azure IoT Hub, Stream Analytics, Data Lake, and Power BI) to enhance Overall Equipment Effectiveness (OEE).

## Project Overview

This project simulates industrial sensor data, processes it locally at the edge for low-latency response, and transmits it to the cloud for scalable storage and advanced analytics. Dashboards in Grafana and Power BI are used for real-time and historical visualization of key operational metrics.

## Features

- Industrial data simulation using Python
- Edge computing for local data processing and visualization
- MQTT-based messaging with Mosquitto
- Real-time visualization using Grafana
- Cloud integration with Microsoft Azure services
- Centralized storage and analytics with Azure Stream Analytics and Data Lake
- Interactive reporting with Power BI

## Folder Structure


## Technologies Used

**Edge Layer:**
- Raspberry Pi
- Mosquitto (MQTT Broker)
- Node-RED (Visual Flow-based Programming)
- InfluxDB (Time-Series Database)
- Grafana (Local Dashboard Visualization)

**Cloud Layer:**
- Microsoft Azure IoT Hub (Device Connectivity)
- Azure Stream Analytics (Data Processing)
- Azure Data Lake (Scalable Storage)
- Power BI (Business Intelligence and Visualization)

**Programming Language:**
- Python (Sensor Data Simulation)

## Sample Dashboards

**Grafana Dashboards:**
- Machine availability and downtime
- Good vs scrap units
- Production and shift-based performance metrics

**Power BI Dashboards:**
- Shift and manager-based job counts
- Product-specific job performance
- Scrap rate trends and OEE analysis

## Key Results

- Edge visualization latency: Less than 50 milliseconds
- Cloud dashboard latency: Under 200 milliseconds
- Improved OEE: 15% reduction in unplanned downtime, 10% increase in production efficiency
- Supports up to 10,000 data points per minute without degradation

## Future Enhancements

- Real-time data from physical industrial sensors
- Predictive maintenance using machine learning
- Deployment across multiple industrial sites
- Enhanced security mechanisms and encryption
- Integration with industrial protocols like OPC-UA and Modbus

## Documentation

Detailed project report including system design, implementation steps, architecture diagrams, performance analysis, and references is available in [`documentation/documentation.pdf`](./documentation/documentation.pdf).

## Author

**Sravan Sai**

## Contact

For questions or collaboration:

- Email:sravansai2001ch@gmail.com  
- LinkedIn: www.linkedin.com/in/sravansai2001
