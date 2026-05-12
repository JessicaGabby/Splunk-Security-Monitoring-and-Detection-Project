# Splunk-Security-Monitoring-and-Detection-Project
Windows Security Event Log monitoring using Splunk, SPL queries, dashboards, and alerting

## Technology Used
- Splunk Enterprise
- Windows Security Event Logs
- SPL
- Event Reviewer
- PowerShell

## Objectives
- Install and configure Splunk
- Ingest Windows Security Event Logs
- Verify log ingestion
- Run SPL searches for authentication events
- Build a 3‑panel security dashboard
- Configure an automated alert for failed logins

### Windows Event Log Ingestion
- Confirms that Windows Security logs were added as a data source.

  ## Alert Configuration
  - Trigger Condition: Number of results > 0
  -  Trigger: Once
  -  Action: Add to Triggered Alerts
  -  Severity: Medium
  -  Expiration: 24 hours
  -  Schedule: Every 5 minutes

## Failed Login Attempts (EventCode 4625)
- SPL search showing failed authentication attempts.

 ## Successful Login Events (EventCode 4624)
- SPL search showing successful logins.


## Event Code Frequency Visualization
- Shows the most common Windows Security Event Codes.

## Security Dashboard
- Three‑panel dashboard showing failed logins, successful logins, and event frequency.

  
