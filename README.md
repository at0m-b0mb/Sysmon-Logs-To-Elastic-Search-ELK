# Sysmon Logs to Elastic Search (ELK) Integration

![Project Logo](link-to-your-project-logo.png) <!-- You can add a project logo if you have one -->

## Overview

This project is a Security Information and Event Management (SIEM) and log analysis solution that uses Sysmon, Elasticsearch, Logstash, and Kibana to collect, store, process, and visualize Windows event logs. The primary objective is to enhance cybersecurity by detecting and responding to security threats, particularly at Vellore Institute of Technology.

- **Project Duration:** July 2023 - Present
- **Associated with:** Vellore Institute of Technology
- **Project Lead:** Kailash Parshad

## Project Description

This project follows a structured approach to collect and analyze Windows event logs, providing several key benefits:

- **Data Collection:** Using Sysmon to collect a wide range of Windows event logs, including those related to file system access, registry changes, network activity, and process creation.

- **Data Storage:** Sending collected logs to Elasticsearch, a scalable and distributed search engine that is well-suited for handling large volumes of logs.

- **Data Processing:** Employing Logstash to filter, transform, and enrich logs. Logstash is used to filter out irrelevant logs, normalize log data, and add additional fields.

- **Data Visualization:** Utilizing Kibana to create interactive dashboards and explore log data visually. These dashboards help track suspicious activities and identify potential security threats.

## Project Benefits

- **Data Analysis:** The ability to collect and analyze large volumes of Windows event logs.
- **Security Threat Detection:** Identification of potential security threats.
- **Response Capability:** Ability to respond to security threats quickly and effectively.
- **Enhanced Cybersecurity:** Improving the overall cybersecurity posture of Vellore Institute of Technology.

## Skills Developed

- Sysmon installation and configuration.
- Elasticsearch installation and configuration.
- Logstash installation and configuration.
- Kibana installation and configuration.
- Log analysis.
- Security threat detection and response.

## Project Links

- **GitHub Repository:** [Sysmon-Logs-To-Elastic-Search-ELK](https://github.com/at0m-b0mb)
- **LinkedIn Profile:** [Kailash Parshad on LinkedIn](https://www.linkedin.com/in/kailash-parshad/)

## Installation Guides

- **Elasticsearch on Debian:** [Elasticsearch Debian Installation Guide](https://www.elastic.co/guide/en/elasticsearch/reference/current/deb.html)
- **Installing Kibana:** Follow your system's package manager for installation.
- **Installing Logstash:** Follow your system's package manager for installation.
- **Downloading Sysmon on Windows:** [Sysmon Downloads](https://docs.microsoft.com/en-us/sysinternals/downloads/sysmon)

## Getting Started

To get started with this project, follow these steps:

1. **Install Elasticsearch** by following the provided guide.
2. **Install Kibana** and **Logstash** on your system.
3. **Configure Sysmon** on your Windows machines using the provided configuration file.
4. **Install Elastic Agent** to forward logs to Elasticsearch.
5. **Explore Kibana** and set up your custom dashboards.
6. **Run KQL queries** in Kibana to filter and analyze data.
