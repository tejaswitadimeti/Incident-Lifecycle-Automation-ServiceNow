# Incident-Lifecycle-Automation-ServiceNow
ServiceNow project: incident lifecycle with knowledge, escalation, emergency change, child incidents and SLA tracking
Platform: ServiceNow Personal Developer Instance Program: ServiceNow Global Certification

About the project

In this project I took one realistic IT issue, an employee who suddenly cannot connect to the Corporate VPN, and handled it through a complete incident lifecycle in ServiceNow, from the first phone call to a reusable knowledge article.

Along the way the incident is classified, gets help from knowledge, is escalated to a Level 2 team, waits on an emergency change, picks up a duplicate report as a child incident, and is finally resolved and turned into a knowledge article. SLAs are tracked the whole time.

What I built
Step	What happens
Service hierarchy	Created the service Remote Access and the offering Corporate VPN
Incident creation	Logged INC0010005, "Unable to connect to Corporate VPN from home office", in Service Operations Workspace
Classification	Channel Phone, Category Network, Subcategory VPN, Urgency 2, Service, Offering and Configuration Item
Knowledge	Used Agent Assist to attach a VPN article and mark it helpful
Escalation	Moved the incident from the Service Desk to the Network team (Level 2), assigned to David Loo
Collaboration	Added a watch list and a work notes list so others stay updated
Emergency change	Changed the CI to PowerEdge T110 II, set the incident On Hold (Awaiting Change), and linked emergency change CHG0030003
Child incident	Logged a second user's report as child incident INC0010006, which resolved with the parent
Resolution	Recorded the cause and resolution, then resolved the incident
Knowledge creation	Created a new knowledge article from the resolved incident
SLA tracking	Response and resolution SLAs tracked, pausing while the incident was on hold
ServiceNow modules used
Incident Management
Knowledge Management and Agent Assist
Change Management
Service Level Management
CMDB (services, service offerings, configuration items)
Files in this repository
File	Contents
1. Ideation Phase.docx	Problem statement, empathy map, brainstorming and idea prioritization
2. Requirement Analysis.docx	Customer journey map, requirements, data flow diagram, user stories, technology stack
3. Project Design Phase.docx	Problem-solution fit, proposed solution, solution architecture
4. Project Planning Phase.docx	Product backlog, sprint schedule, velocity and burndown chart
5. Project Development Phase.docx	Build steps, performance testing and user acceptance testing
6. Project Documentation.docx	Full project report with output screenshots
Incident Lifecycle Management.mp4	Incident Lifecycle Management video (about 4.5 minutes, with captions)
Results

All 7 test cases passed: incident lifecycle, escalation, change integration, knowledge creation, child incident management, SLA tracking and multi-team collaboration.

Conclusion

This project shows a complete Incident Management lifecycle in ServiceNow. Bringing the Incident, Change and Knowledge modules together on one record makes incident handling faster, more consistent and easier to trace, and helps teams meet their SLAs
