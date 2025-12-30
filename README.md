# Mock-Incident-Response-Log-Project
# Evan Jania 2025

Description:
A professional incident tracking system where you can log problems, document troubleshooting steps, root causes, and resolutions

Download: 
incident-response-log.html

Example Inputting:
Fill in the form with example data, such as
Title: "Application Won't Start After Windows Update"
System: "APP-SERVER-03"
Priority: High
Status: Resolved
Description: "SQL Server service failed to start after KB5034441 patch installation. Error 1067 in Event Viewer."
Troubleshooting: "Checked Event Viewer logs, found service dependency error. Verified SQL Server Agent was stopped. Checked database file permissions."
Root Cause: "Windows update changed service startup order, causing SQL Server to attempt start before dependent network services were ready."
Resolution: "Changed SQL Server service startup type to Automatic (Delayed Start). Service now starts successfully after reboot."

Thank you for reading!
