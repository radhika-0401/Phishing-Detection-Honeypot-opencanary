# Phishing-Detection-Honeypot-opencanary

This project implements a phishing detection honeypot using OpenCanary. It deploys decoy services (FTP, SSH, HTTP) to attract and log unauthorized access attempts, providing real-time Telegram alerts when suspicious activity is detected

Features
✅ Deploys honeypot services (FTP, SSH, HTTP)
✅ Captures phishing attempts and unauthorized logins
✅ Sends real-time alerts via Telegram
✅ Logs all activity for further analysis
✅ Helps identify potential phishing threats

Architecture
1.OpenCanary Deployment – Configured on a Kali Linux machine.
2.Service Emulation – Mimics common attack vectors (FTP, SSH, HTTP).
3.Logging & Monitoring – Captures attacker interactions in JSON logs.
4.Real-time Alerting – Sends Telegram notifications for detected events.
5.Analysis & Reporting – Provides insights into attack patterns.
