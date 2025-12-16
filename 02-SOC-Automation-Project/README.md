# SOC Automation project

## Objective
The goal of this project is to design and build an end-to-end SOC Automation Pipeline that demonstrates how security teams can accelerate alert triage using orchestration, enrichment, AI-driven analysis, and automated case creation.

This project replicates a modern SOC workflow where alerts generated in Splunk automatically flow into an automation engine (N8N), undergo enrichment via VirusTotal and AbuseIPDB, receive AI triage analysis via OpenAI, trigger incident creation in DFIR-IRIS, and finally notify analysts in Slack.
Additionally, Splunk MCP integrated with Claude enables AI-driven SIEM search and investigation.

This hands-on project showcases how SOAR + AI can reduce repetitive work, improve investigation consistency, and increase SOC efficiency.

### Skills Learned
- Designing automated SOC workflows using N8N (SOAR-like orchestration).
- Building and testing Splunk SIEM alerts using Windows + Sysmon telemetry.
- Performing automated indicator enrichment using VirusTotal & AbuseIPDB APIs.
- Generating structured AI-powered triage reports (MITRE ATT&CK + recommendations).
- Automating case creation in DFIR-IRIS through API integration.
- Sending real-time Slack notifications with enriched, analyst-ready data.
- Using Splunk MCP + Claude for natural-language SIEM investigations.

### Tools Used
* **Splunk SIEM** – Log ingestion, alert generation
* **Sysmon** – Endpoint telemetry
* **N8N** – Automation engine for orchestrating enrichment + AI workflow
* **OpenAI** – AI triage analysis and MITRE mapping
* **VirusTotal API** – Hash / IP reputation
* **AbuseIPDB API** – Malicious IP validation
* **DFIR-IRIS** – Automated case creation and incident tracking
* **Slack API** – Analyst notifications
* **Splunk MCP + Claude** – AI-powered SIEM investigation

## Screenshots
*Ref 1: Workflow Diagram*

<img width="1542" height="829" alt="image" src="https://github.com/user-attachments/assets/2fd067f7-d1de-4b33-a2fb-f78d87ae2547" />
*
*Ref 1: Workflow Diagram*

*Ref 1: Workflow Diagram*

*Ref 1: Workflow Diagram*

*Ref 1: Workflow Diagram*

*Ref 1: Workflow Diagram*

*Ref 1: Workflow Diagram*

## Learning Outcomes
- Gained practical experience automating SOC alert triage end-to-end.
- Learned how SIEM alerts flow through detection → enrichment → triage → escalation.
- Built SOAR-style workflows in N8N using webhooks, API calls, and conditional logic.
- Applied threat intelligence enrichment (VirusTotal, AbuseIPDB) to improve alert context.
- Used AI (OpenAI + Claude) for automated triage, MITRE mapping, and SIEM investigation.
- Automated incident case creation in DFIR-IRIS to mirror real-world IR processes.
- Strengthened API integration, JSON parsing, and security engineering skills.
