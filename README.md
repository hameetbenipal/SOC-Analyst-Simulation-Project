# SOC Analyst Simulation Project

## Objective

This project provided hands-on experience with the core responsibilities of a SOC Analyst, covering threat detection, investigation, and incident management within a simulated environment. I deployed multiple virtual machines (VMs), including Linux servers for an ELK stack, a fleet server, Kali Linux for attack simulations, and a Mythic server to execute command-and-control (C2) attacks. Additionally, I configured a Windows Server and a separate Windows VM dedicated to a ticketing system for incident management.

Simulated attacks included brute-force SSH and RDP attacks using Kali Linux and Crowbar, as well as a C2 attack on a target machine using a Mythic agent. Elastic was configured as a SIEM to monitor and detect these attacks through custom detection rules. I analyzed logs and telemetry data, visualized attack patterns using Elastic dashboards, and investigated alerts to identify indicators of compromise (IoCs).

To simulate real-world SOC workflows, I integrated OSTicket with Elastic to automatically generate incident tickets for every alert detected. This system allowed me to simulate incident assignments, collaborate through comments, and follow structured processes to resolve security incidents.

This project strengthened my skills in SIEM configuration, threat detection, log analysis, incident response, and ticketing systems, providing practical experience that aligns with industry best practices in modern SOC environments.

### Skills Learned

- Threat Detection & Investigation: Configured Elastic SIEM to detect and investigate brute-force SSH, RDP attacks, and command-and-control (C2) attacks using custom detection rules.
- Log Analysis & Telemetry: Analyzed security logs and telemetry data from Linux servers, Windows systems, and attack simulations to identify indicators of compromise (IoCs).
- Security Monitoring & Visualization: Created Elastic dashboards to visualize attack patterns, system events, and telemetry for real-time monitoring.
- Incident Response & Management: Simulated real-world incident response workflows using OSTicket, including alert triage, ticket creation, assignment, collaboration, and resolution.
- Virtual Machine Deployment & Configuration: Deployed and managed Linux (ELK stack, fleet server, Kali Linux, Mythic server) and Windows VMs to replicate SOC infrastructure.
- Attack Simulation: Executed brute-force attacks using Crowbar and C2 attacks using Mythic agent to test SIEM detection capabilities.
- Security Automation: Automated the generation of incident tickets in OSTicket from Elastic alerts to streamline SOC workflows.
- Collaboration & Communication: Simulated communication between SOC teams through incident ticket comments and cross-team assignments.
- Hands-on Experience with Security Tools: Gained practical experience using Elastic SIEM, OSTicket, Kali Linux, Mythic, Crowbar, and fleet servers in a SOC environment.


### Tools Used

- Elastic SIEM: Configured to monitor system logs, detect attacks, and visualize security telemetry using custom detection rules and dashboards.
- OSTicket: Integrated with Elastic to simulate incident ticketing workflows, including alert-to-ticket automation, assignment, and resolution tracking.
- Kali Linux: Used to simulate brute-force SSH and RDP attacks with Crowbar for testing SIEM detection capabilities.
- Mythic Server: Deployed as a command-and-control (C2) platform to simulate advanced cyber threats using Mythic agents.
- Fleet Server: Managed telemetry collection from Linux and Windows VMs, enabling centralized log aggregation in Elastic.
- Linux Servers (ELK Stack): Deployed and maintained Elastic, Logstash, and Kibana to capture, process, and analyze logs from simulated environments.
- Windows Server: Configured as a target machine for C2 attacks and brute-force attacks to generate real-world security events.
- Crowbar: Used for brute-force attacks on SSH and RDP protocols, simulating unauthorized access attempts.
- VirtualBox/VMware: Used to spin up and manage multiple VMs for the simulation environment, including Linux and Windows systems.
- Elastic Defend: Used as an EDR to enable capabilities of machine isolation.

## Steps

All steps and documentation for this lab are linked below.

<a href="https://github.com/hameetbenipal/SOAR-EDR-Project/blob/main/SOAR%20Project%20Documentation.pdf">Lab Documentation</a>
