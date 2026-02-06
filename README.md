# Wazuh SIEM Lab

## Objective
Deploy a Wazuh SIEM environment, onboard an endpoint agent, and verify alert generation and visibility.

## Environment
- Wazuh Manager (Ubuntu Server)
- Endpoint Agent (Ubuntu Desktop)

## What I Did
- Installed and configured the Wazuh manager
- Enrolled an endpoint agent
- Triggered an AppArmor security event on the endpoint
- Verified the alert in the Wazuh dashboard and via alerts.json

## Evidence

### Agent Connected
![Agent Connected](screenshots/Agent-Active2.png)

### Security Events In Wazuh Dashboard
![AppArmor Alert](screenshots/Wazuh-Dashboard.png)

### Individual Alert List
![Individual Alert List](screenshots/Error-ID.png)

### Alert JSON Output
![Alert JSON](screenshots/json-output.png)

## Key Takeaways
- SIEM deployment and agent onboarding
- Alert validation using endpoint logs
- Basic security event analysis

