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
![Agent-Active2](screenshots/Agent-Active2.png)

### Security Events In Wazuh Dashboard
![Wazuh-Dashboard](screenshots/Wazuh-Dashboard.png)

### Individual Alert List
![Error-ID](screenshots/Error-ID.png)

### Alert JSON Output
![json-output](screenshots/json-output.png)

## Key Takeaways
- SIEM deployment and agent onboarding
- Alert validation using endpoint logs
- Basic security event analysis

