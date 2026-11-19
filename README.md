# Splunk SOC Dataset Analysis

## Project Overview
This project demonstrates basic SOC analytics using Splunk Enterprise. It focuses on analysing Windows Security Events and Linux authentication logs using Splunk Data Models, Datasets, and Pivot reports.

## Tools & Technologies
- Splunk Enterprise
- Windows 11
- Linux (Kali Linux)
- Splunk Data Models
- Pivot Reports and Dashboards

## Project Implementation

- Created a Linux_Security Data Model for Linux security and authentication events.
- Created a Windows_Security Data Model for Windows security and logon events.
- Configured authentication datasets.
- Used Pivot to analyse and summarize indexed events.
- Created a basic SOC dashboard to monitor successful and failed login activity.

## Dashboard
The dashboard visualizes:
- Successful login events
- Failed login events

## Screenshots
Screenshots of the Data Models, Pivot report, and dashboard are available in the `screenshots` folder.

## Project Structure

```text
Splunk-SOC-Dataset-Analysis/
│
├── Project_Guide.pdf
├── README.md
└── screenshots/
    ├── windows-data-model.png
    ├── linux-data-model.png
    ├── pivot-report.png
    └── authentication-dashboard.png
```

## Data Source
The project uses Windows Security Events and Linux authentication logs indexed in the local Splunk Enterprise environment. Raw datasets are not included in this repository.

## Learning Outcomes
- Understanding Splunk Data Models and Datasets.
- Analysing Windows and Linux security events.
- Using Pivot for security event analysis.
- Building a basic authentication monitoring dashboard.

**Project Type:** Hands-on SOC Analytics Lab
