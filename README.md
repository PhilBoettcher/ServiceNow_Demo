# ServiceNow Alert-to-Incident Automation with ChatOps Integration
Built an end-to-end automation in ServiceNow to convert monitoring alerts into enriched incidents and push real-time notifications to Slack. Implemented a Flow Designer pipeline that listens to new Monitoring Alert records, creates an Incident, enriches it with CMDB data, and maps alert severity to impact/urgency according to business rules. Integrated Slack via incoming webhooks to post incident details and deep links into a dedicated #incident-notifications channel for on-call engineers.

Installed and configured a Windows-based ServiceNow MID Server, including service account setup, config.xml tuning, and validation so the platform can execute remote diagnostics and orchestration tasks against Windows infrastructure in future extensions of the project.

<img width="2558" height="1308" alt="flow_designer" src="https://github.com/user-attachments/assets/7018d162-d41a-40a2-88c6-20a1a6e208bc" />
<img width="2558" height="1316" alt="test_incident" src="https://github.com/user-attachments/assets/a140a2e6-9edf-445c-b85d-2f68ee631e8f" />
<img width="2549" height="1349" alt="slack" src="https://github.com/user-attachments/assets/e1183d24-0c43-4754-b891-1c8c35dd48f1" />
<img width="2558" height="1302" alt="mid_server" src="https://github.com/user-attachments/assets/952ff0b6-222b-4117-bbb3-177fc854700b" />
