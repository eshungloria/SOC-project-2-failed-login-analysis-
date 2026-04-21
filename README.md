# SOC Project 2 — Failed Login Analysis (Brute Force Detection)

## 📌 Overview
This project focuses on analyzing Windows Security logs to detect failed login attempts and identify potential brute force activity.

## 🛠️ Tools Used
- Event Viewer (Windows)
- Virtual Lab Environment

## 🎯 Objective
- Monitor failed login events
- Identify patterns in authentication failures
- Differentiate between normal behavior and suspicious activity

## 🔍 Investigation Steps
1. Opened Event Viewer
2. Navigated to Windows Logs → Security
3. Filtered logs using Event ID 4625 (Failed Logon)
4. Reviewed multiple log entries
5. Analyzed timestamps, frequency, and account behavior

## 📊 Findings
- Multiple failed login attempts were observed
- Attempts were limited in number and spread over time
- Targeted a single user account

## 🧠 Analysis & Interpretation
Two failed login attempts were observed within a 2-minute time frame targeting a single account.

This behavior is consistent with normal user activity, such as incorrect password entry.

No clear indicators of brute force activity were identified. However, continued monitoring is recommended to detect any escalation in failed login attempts.

## 🖼️ Evidence
(Add your screenshots here)

## 🧾 Conclusion
The observed activity appears to be normal user behavior rather than a brute force attack. No signs of compromise were detected.

Continuous monitoring is recommended to ensure no escalation occurs.

## 📚 Skills Demonstrated
- Log Analysis
- Threat Detection
- Security Monitoring
- Analytical Thinking
- Incident Documentatio
