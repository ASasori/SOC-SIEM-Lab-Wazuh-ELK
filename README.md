# Personal SOC Lab & SIEM Implementation

## Overview
This project demonstrates the deployment of a centralized **Security Operations Center (SOC)** using **Wazuh** and the **ELK Stack** (Elasticsearch, Logstash, Kibana). The goal is to monitor system logs, detect intrusions, and visualize security threats in real-time.



## Architecture
- **Wazuh Manager:** Centralized engine for analyzing log data and triggering alerts.
- **ELK Stack:** Used for indexing (Elasticsearch) and visualizing (Kibana) security events.
- **Wazuh Agents:** Installed on endpoints (Linux/Windows) to collect logs and monitor file integrity.



## Features Implemented
- **Real-time Log Analysis:** Processing system and application logs.
- **File Integrity Monitoring (FIM):** Tracking unauthorized changes to sensitive system files.
- **Vulnerability Detection:** Automated scanning for outdated or insecure software versions.
- **MITRE ATT&CK Mapping:** Visualizing alert data based on known adversary tactics and techniques.

## How to Run
1. Ensure Docker & Docker Compose are installed.
2. Clone this repository.
3. Navigate to the single-node directory: `cd single-node`.
4. Start the stack: `docker-compose up -d`.
5. Access the Dashboard at `https://localhost`.

---
*Note: This lab is built for educational purposes and security research.*