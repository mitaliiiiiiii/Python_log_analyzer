# Python_log_analyzer
#27
..........................................................................................................................................................................



Python Log Analyzer for Suspicious Activity Detection
Overview
This project is a beginner-friendly cybersecurity tool developed using Python that analyzes log files to detect suspicious login activity. The tool scans logs for failed login attempts, extracts IP addresses using regular expressions, and identifies possible brute-force attack behavior based on repeated failures.
The project is designed to simulate basic SOC (Security Operations Center) monitoring and introduce foundational concepts of log analysis and threat detection.
Features

--Detects failed login attempts
--Extracts IP addresses from logs
--Counts repeated login failures
--Identifies suspicious activity
--Alerts possible brute-force attacks
--Lightweight and beginner-friendly


Technologies Used=

-Python
-Expressions (Regex)
-File Handling
-Collections Module (defaultdict)
-Project Structure
-Plain text

Python_log_analyzer/
│
├── analyzer.py
├── sample_logs.txt
└── README.md

How It Works==

> Reads log entries from a text file
> Searches for failed login attempts
> Extracts IP addresses using regex
> Counts repeated failed attempts
> Generates alerts for suspicious behavior

Sample Detection Logic
Python
if failed_attempts[ip_address] >= 3:
    print("[ALERT] Possible Brute Force Attack!")
Example Output
Plain text
--- Suspicious Activity Report ---

IP Address: 192.168.1.15
Failed Attempts: 3
[ALERT] Possible Brute Force Attack!
Cybersecurity Concepts Learned
Log Analysis
Threat Detection
Brute Force Attack Identification
SOC Monitoring Basics
Regex Pattern Matching
Security Alerting
Real-World Relevance
Security teams and SOC analysts use log analysis to monitor systems for suspicious activity and detect unauthorized access attempts. This project simulates basic functionality used in SIEM platforms and introduces practical cybersecurity monitoring concepts.

Python
Regular Expressions (Regex)
File Handling
Collections Module (defaultdict)
Project Structure
Plain text



Future Improvements
-------------------------------------------
Real-time log monitoring
GUI dashboard
CSV/PDF report generation
Email alerts
Linux auth.log support
Threat intelligence API integration


Learning Outcome................
This project helped in understanding how cybersecurity analysts monitor logs, identify attack patterns, and build detection logic for suspicious activities using Python.


Author
MITALI TANTY


License.................
This project is intended for educational and learning purposes.
