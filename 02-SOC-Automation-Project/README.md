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

<img width="765" height="500" alt="n8n workflow" src="https://github.com/user-attachments/assets/503362d6-7f42-457d-a6e4-63fe6b5f2e60" />
<br><br>

*Ref 2: Splunk Alerts*

<img width="958" height="415" alt="Splunk Alert 1" src="https://github.com/user-attachments/assets/6c0eadd6-fe40-4680-adf6-c112237e6788" />
<br><br>

*Ref 3: Slack Alert*

<img width="954" height="500" alt="Slack Alert 1" src="https://github.com/user-attachments/assets/37bba559-4403-439a-a031-2d8e446185a9" />
<br><br>

*Ref 4: DFIR-IRIS Case Creation*

<img width="955" height="496" alt="IRIS Case 1" src="https://github.com/user-attachments/assets/0b1e6bdc-bcab-4695-992d-d2831d168a44" />
<br><br>

*Ref 5: Splunk Logs*

<img width="957" height="502" alt="Splunk Logs 1" src="https://github.com/user-attachments/assets/af07b68e-3999-407b-8aeb-b06fd1107be5" />
<br><br>

*Ref 6: Claude Search*

<img width="954" height="497" alt="Claude 1" src="https://github.com/user-attachments/assets/5bbeb56d-d00e-4d93-b05a-8adfb8cab34f" />
<br><br>
<img width="957" height="500" alt="Claude 2" src="https://github.com/user-attachments/assets/1d05f872-a401-4f8c-ad5f-83021cfc7c77" />
<br><br>

## Learning Outcomes
- Gained practical experience automating SOC alert triage end-to-end.
- Learned how SIEM alerts flow through detection → enrichment → triage → escalation.
- Built SOAR-style workflows in N8N using webhooks, API calls, and conditional logic.
- Applied threat intelligence enrichment (VirusTotal, AbuseIPDB) to improve alert context.
- Used AI (OpenAI + Claude) for automated triage, MITRE mapping, and SIEM investigation.
- Automated incident case creation in DFIR-IRIS to mirror real-world IR processes.
- Strengthened API integration, JSON parsing, and security engineering skills.
