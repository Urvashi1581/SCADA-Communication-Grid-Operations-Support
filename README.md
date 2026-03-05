# SCADA Communication & Grid Operations Support Lab

## Project Overview
This project simulates a SCADA environment used in industrial automation and grid operations. 
The goal was to understand how SCADA systems monitor, communicate, and troubleshoot industrial devices 
such as PLCs, field sensors, and HMI systems.

The lab demonstrates communication using industrial protocols, real-time monitoring, and troubleshooting 
common operational issues.

---

# SCADA Communication & Grid Operations Support

This project simulates a real-world SCADA environment used in industrial automation and grid operations. 
The lab demonstrates PLC integration, SCADA monitoring using Ignition, database logging, and troubleshooting 
of industrial communication issues such as network connectivity failures, scripting errors, and port communication problems.

The goal of the project was to understand how distributed industrial systems communicate and how support engineers 
diagnose and resolve operational issues.

## Technologies Used

- PLC Programming (Allen Bradley / Studio 5000)
- SCADA Platform (Ignition SCADA)
- Industrial Communication Protocols
  - Modbus TCP
  - DNP3
- Networking
  - TCP/IP
  - Port diagnostics
- Database
  - MySQL
- Automation scripting (Jython in Ignition)

---

## System Architecture

The simulated SCADA architecture includes:

PLC → Network → SCADA Gateway → Database → HMI Dashboard

Components used:

- PLC controller
- Ignition SCADA gateway
- MySQL database
- Industrial communication protocols
- HMI visualization

---

## Features Implemented

- PLC ladder logic for machine operations
- SCADA tag configuration and monitoring
- Database logging for production data
- HMI dashboards for operational visibility
- Alarm and event monitoring
- Communication troubleshooting

---

## Example PLC Logic

PLC ladder logic controls machine states and signals.

![PLC Ladder Logic](screenshots/plc_ladder_logic.png)

---

## SCADA Tag Configuration

Tags were configured in Ignition to monitor machine data and production values.

![Ignition Tag Editor](screenshots/ignition_tag_editor.png)

---

## SCADA Error Monitoring

Ignition gateway logs were analyzed to troubleshoot script and data errors.

![Ignition Logs](screenshots/ignition_logs_error.png)

---

## Network Diagnostics

TCP connections were monitored to verify communication between SCADA and field devices.

![Network Connections](screenshots/network_connections.png)

---

## PLC Network Configuration

PLC Ethernet configuration including IP addressing and communication parameters.

![PLC Network Settings](screenshots/plc_network_settings.png)

---

## Port Connectivity Testing

Port connectivity was tested using PowerShell and TCP diagnostics.

![Port Testing](screenshots/port_testing.PNG)

---

## Troubleshooting Scenarios Tested

The following failure scenarios were intentionally introduced:

- Incorrect PLC IP configuration
- Port communication failure
- SCADA script errors
- Database query issues
- Network connectivity failures

Each issue was analyzed using logs, network tools, and SCADA diagnostics.

---

## Key Learning Outcomes

- Understanding SCADA system architecture
- Industrial communication protocols
- Troubleshooting distributed automation systems
- Monitoring real-time industrial data
- Diagnosing network and protocol issues

---

## Troubleshooting Scenarios

During the lab environment testing, several failure scenarios were intentionally introduced:

- SCADA script execution errors in Ignition
- TCP communication failures between SCADA and field devices
- Incorrect PLC network configuration
- Database query errors
- Port connectivity failures

These issues were diagnosed using:

- Ignition Gateway logs
- TCP connection monitoring
- PowerShell port connectivity tests
- PLC Ethernet configuration diagnostics
  

## System Architecture
![SCADA Lab Architecture](architecture/scada_architecture.png)

## Future Improvements

- Implement additional industrial protocols
- Add automated alarm notifications
- Integrate advanced analytics dashboards

---
