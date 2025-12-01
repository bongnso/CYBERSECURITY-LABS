CYBERSECURITY-LABS / Log-Analysis / README.md

Log File Analysis

This folder contains hands-on log analysis work performed on Apache web server access logs and related security event data. The goal of these exercises is to identify suspicious activity, detect potential indicators of compromise (IoCs), and practice real-world security investigation techniques used in SOC environments.


Key Skills Demonstrated
	•	Parsing and reviewing Apache access logs
	•	Identifying abnormal HTTP requests
	•	Detecting repeated suspicious IP addresses
	•	Recognizing scanning attempts and exploitation patterns
	•	Flagging potential brute-force and shellshock activity
	•	Extracting IoCs for reporting and escalation
	•	Summarizing findings in security-focused documentation


1. Access Log Review

Analysis of lines taken from access-1.log and access-2.log, including:
	•	Suspicious GET requests
	•	Requests targeting xmlrpc.php
	•	Requests for unusual PHP scripts or foreign URLs
	•	Nonstandard user-agents
	•	HTTP 404, 403, and 500 patterns

2. IOC Identification

Detected potential IoCs such as:
	•	Malicious or foreign IP addresses
	•	Probing or scanning behavior
	•	Automated enumeration activity
	•	Possible exploitation attempts

3. Investigation of Notable Activity

Documented high-risk behaviors including:
	•	Repeated attempts to access xmlrpc.php
	•	Remote file inclusion attempts
	•	External sites probing internal servers
	•	High-frequency requests indicating bot traffic

4. Screenshots & Evidence

	•	Extracted suspicious log lines
	•	Highlighted IP addresses
	•	Patterns used in attacks
	•	Documentation steps used during analysis

 Tools Used
	•	Linux command line (grep, cat, head, tail)
	•	Wireshark (for correlated packet evidence when needed)
	•	TRiD for file classification
	•	Notepad / VS Code for reading logs
	•	Cybersecurity investigative workflows

Purpose of This Analysis

This project demonstrates my ability to:
	•	Perform practical log analysis
	•	Identify threat indicators in raw logs
	•	Understand attacker behavior through log patterns
	•	Apply SOC investigation methods
	•	Produce structured, professional documentation

These tasks mirror real responsibilities of a Junior SOC Analyst, Incident Response Technician, or Cybersecurity Analyst.

Additional related work will be found in:
	•	Incident-Reports (full investigative write-ups)
	•	Wireshark (packet capture analysis)
	•	Tools-and-Techniques (supporting utilities)
