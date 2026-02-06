# Wazuh SIEM Lab

## Objective
Deploy a Wazuh SIEM environment, onboard a Windows endpoint agent, and verify
security event ingestion and alert visibility through both the dashboard and
log-level analysis.

## Environment
- Wazuh Manager (Linux)
- Windows 10 Endpoint (Wazuh Agent)
- Virtualized lab environment

## What I Did
- Deployed and configured the Wazuh SIEM manager
- Enrolled a Windows endpoint agent
- Generated Windows security and application events
- Verified alert ingestion in the Wazuh dashboard
- Validated alerts directly from alerts.json using the command line

## Evidence

### Agent Enrollment & Status
The Windows endpoint agent is successfully enrolled and reporting to the Wazuh
manager.

![Agent Active](Screenshots/Agent-Active.png)

---

### Security Events Dashboard
Security events from the endpoint are ingested and visualized within the Wazuh
dashboard.

![Wazuh Dashboard](Screenshots/Wazuh-Dashboard.png)

---

### Endpoint Event Detection
Individual Windows events are detected and classified by Wazuh, including
application errors and logon activity.

![Windows Event Alert](Screenshots/Error-ID.png)

---

### Alert Validation
Alert data was validated directly from the Wazuh alerts.json file using command-
line tools to confirm rule ID, description, and source agent.

![JSON Output](Screenshots/JSON-output.png)

## Key Takeaways
- SIEM deployment and endpoint agent onboarding
- Windows event monitoring and alert classification
- Log-level validation of security alerts using alerts.json


