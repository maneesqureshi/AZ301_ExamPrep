# AZ301_ExamPrep
Prep Notes for AZ301 Exam

19th July
- Created Repository for AZ-301: Microsoft Azure Architect Design Exam Prep

Topic:

##Determine Workload Requirements (10-15%)

###Gather Information and requirements

https://docs.microsoft.com/en-us/azure/architecture/

- identify compliance requirements
https://docs.microsoft.com/en-in/azure/compliance/ 

https://www.microsoft.com/en-in/trust-center/compliance/compliance-overview

https://azure.microsoft.com/en-in/overview/trusted-cloud/compliance/

Read the white paper (Available in the Repo)
Read the Azure Security, Privacy, Compliance docs (Attached in the repo)


Audit Reports
https://servicetrust.microsoft.com/ViewPage/MSComplianceGuide

Regulatory Deep Dive for India
https://www.microsoft.com/en-sg/apac/trustedcloud/india.aspx

- identify identity and access management infrastructure
- identify service-oriented architectures
- identify accessibility requirements
- identify availability requirements
- identify capacity planning and scalability requirements
- identify deployability requirements
- identify configurability
- identify governance requirements
- identify maintainability requirements
- identify security requirements
- identify sizing requirements
- recommend changes during project execution
- evaluate products and services to align with solution
- create testing scenarios

##Optimize Consumption Strategy
###Design an Auditing and Monitoring Strategy
- optimize app service costs
- optimize compute costs
- optimize identity costs
- optimize network costs
- optimize storage costs
- define logical groupings (tags) for resources to be monitored
- determine levels and storage locations for logs
- plan for integration with monitoring tools
- recommend appropriate monitoring tool(s) for a solution
- specify mechanism for event routing and escalation
- design auditing for compliance requirements
- design auditing policies and traceability requirements

Designing Identitiy Management

4 Versions: Free, Office 365 apps, Premium P1, Premium P2


| features          | Free          | Office 365 Apps | Premium P1 | Premium P2|
| ----------------- |:-------------:| :--------------:| :---------:| ---------:|
| Directory Objects | 500000        | No Limit        | No Limit   | No Limit  |
| Company Branding  | No            | Yes             | Yes        | Yes       |
| Self-service password reset for cloud users | No         | Yes        | Yes   | Yes  |
| Service Level Agreement (SLA) | No        | Yes        | Yes   | Yes  |
| Device objects two-way synchronisation between on-premises directories and Azure AD (Device write-back) | No        | Yes        | Yes   | Yes  |
| Vulnerabilities and risky accounts detection | No        | No        | No   | Yes  |
| Risk events investigation | No        | No        | No   | Yes  |
| Risk based Conditional Access policies | No        | No        | No   | Yes  |
| Privileged Identity Management (PIM) 	 | No        | No        | No   | Yes  |
| Access Reviews 	 | No        | No        | No   | Yes  |
| Entitlement Management 	 | No        | No        | No   | Yes  |
