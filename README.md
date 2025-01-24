# Arsenal-Themed Module 2 Assignment 

## Overview
This project uses Apache Kafka to demonstrate real-time data streaming with an Arsenal Football Club theme.  
In the world of streaming data, producers publish messages, and consumers process those messages in real-time.  
Here, we celebrate Arsenal with custom producer and consumer scripts to process football-related data.

### Key Features:
- **Producers** send Arsenal-themed messages to a Kafka topic.
- **Consumers** listen to the topic and generate alerts based on detected keywords like `goal`, `win`, and `red`.

---

## Installation and Setup

Before starting, ensure the following:
- You have installed **Python 3.11**.
- **Apache Kafka** is installed and running (using WSL for Windows users).  

Follow these steps to set up your environment:

1. Install the Kafka Streaming Platform.
2. Start the Zookeeper service:
   ```bash
   bin/zookeeper-server-start.sh config/zookeeper.properties
