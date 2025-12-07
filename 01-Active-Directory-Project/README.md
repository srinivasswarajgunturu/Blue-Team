## Active Directory Project

## Objective

This project builds a hands-on Active Directory (AD) detection lab using VMware Workstation Pro.  
The goal is to simulate enterprise Windows infrastructure, ingest security telemetry in Splunk, generate attack activity using Kali Linux and Atomic Red Team, and practice blue-team detection, investigation, and troubleshooting.

---

## Skills Learned

- Built and managed a multi-VM Active Directory lab using **VMware Workstation Pro**.
- Promoted Windows Server 2022 to a Domain Controller and joined Windows 10 endpoints to the domain.
- Installed and configured **Sysmon** + **Splunk Universal Forwarder** to ingest Windows & Sysmon logs into Splunk.
- Investigated brute-force authentication attacks generated from Kali Linux.
- Used **Atomic Red Team** to emulate known adversary techniques (MITRE ATT&CK aligned).
- Practiced troubleshooting telemetry ingestion between Windows endpoints and Splunk.
- Strengthened knowledge of AD user/group management, GPOs, domain joins, and enterprise-style logging.

---

## Tools Used

### Virtualization
- **VMware Workstation Pro** (Primary hypervisor)

### Operating Systems
- Windows Server 2022 (Domain Controller)
- Windows 10 (Domain-joined endpoint)
- Kali Linux (Attack machine)

### Logging & Detection
- Splunk Enterprise (SIEM)
- Splunk Universal Forwarder
- Sysmon with SwiftOnSecurity config

### Attack Simulation
- Kali Linux (Brute force, enumeration)
- Atomic Red Team (TTP emulation)

## Lab Architecture

Ref 1: Lab Network Diagram

<img width="1025" height="639" alt="image" src="https://github.com/user-attachments/assets/f68e0df5-e4bf-4044-9031-3ac7c4ca4783" />

## Screenshots

-Brute Force Attack

Ref 2:

<img width="845" height="439" alt="Brute Force Attack" src="https://github.com/user-attachments/assets/66fda161-a092-4c8f-a584-07993cf27805" />


-Splunk Log for failed login EventCode=4625 from Kali

Ref 3:

<img width="705" height="503" alt="Splunk log" src="https://github.com/user-attachments/assets/fbb5a51f-b162-49ea-b17a-a1f51420f5ac" />


-Splunk Log for success login EventCode=4624 from kali

Ref 4:

<img width="740" height="500" alt="Kali success login" src="https://github.com/user-attachments/assets/42f5a6db-ac48-4e14-8059-7ccc5dcd7954" />


## Learning Outcomes
By completing this Active Directory Detection Lab, I:
- Gained end-to-end experience setting up an AD environment similar to a small enterprise.
- Practiced ingesting and validating telemetry from multiple Windows hosts into Splunk.
- Simulated and investigated authentication attacks and Atomic Red Team techniques.
- Strengthened my blue team mindset around detection engineering, log source validation, and incident investigation in a SIEM.




