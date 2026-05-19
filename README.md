# Automated Threat Detection & Security Alert System Using Python
## Overview

This project simulates a Python-based security monitoring system designed to detect suspicious authentication behavior and generate automated security alerts.

The system processes login activity data to identify:

	•	repeated failed login attempts
	•	suspicious IP address behavior
	•	potential brute-force activity
	•	high-risk authentication patterns

The goal of this project is to demonstrate how Python can support SOC-style threat detection and automated security monitoring workflows.

⸻

## Objectives

	•	Analyze login authentication data
	•	Detect repeated failed login attempts
	•	Identify suspicious IP addresses
	•	Generate automated security alerts
	•	Simulate basic threat detection automation

⸻

## Tools & Technologies

	•	Python
	•	CSV log analysis
	•	File handling
	•	Dictionaries and loops
	•	Conditional logic
	•	Automated reporting
____

## Project Structure
python-threat-alert-system/
│
├── security_logs.csv
├── alert_system.py
├── alerts_report.txt
├── insights.md
├── README.md
└── screenshots/
____

## Dataset Overview

The dataset contains simulated login activity logs including:

* timestamps
* usernames
* IP addresses
* login status
* login attempt counts

⸻

## Core Features

### Failed Login Detection

The system identifies users with repeated failed login attempts.

### Suspicious IP Detection

IP addresses associated with high-risk login activity are automatically flagged.

### Automated Alert Reporting

The script generates a security alert report summarizing suspicious activity.

____

## Example Output

=== SECURITY ALERT REPORT ===

High-Risk Users:
ALERT: admin has 3 failed login attempts
ALERT: root has 2 failed login attempts

Suspicious IP Addresses:
WARNING: 192.168.1.10 triggered 1 high-risk events
WARNING: 203.0.113.5 triggered 2 high-risk events

_____


## Skills Demonstrated

* Python automation
* Security log analysis
* Threat detection logic
* Behavioral analysis
* Automated reporting
* SOC-style analytical thinking

⸻


## Author Note

This project is part of a self-built learning roadmap focused on:

* Python programming
* SQL analytics
* statistics fundamentals
* cybersecurity investigations
* security data analytics

It represents an effort to combine automation + analytics + cybersecurity thinking into practical portfolio projects.
