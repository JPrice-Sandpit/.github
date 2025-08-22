# Option 1:

# Security Information

This file outlines the security-related information for this repository and should be updated as the repository's context, ownership, and risk profile evolves.

---
## Repository Metadata Overview

## Repository Information
- **Repository Status**: _Actively Maintained | Operational | To be Archived_
- **Data Owner(s)**: _Name(s) or Role(s)_
- **Data Classification**: _Public | Protected | Highly Protected_
- **Business Criticality**: _Low | Medium | Business Critical | Mission Critical | Core Infrastructure_
- **ServiceNow CMDB Reference**: _[Business Application Name or CI Reference]_
- **App Context Tag**: _Unique 4 letter code representing the application_

---

### Security & Risk

- **Inherent / Current Risk Assessment Rating**:  
  _Rating assigned via Cyber Governance processes (e.g., Low / Medium / High / Extreme)_

- **Privacy Risk Rating**:  
  _Determined by Privacy Team through PIA processes.(e.g., Low / Medium / High)_
  
> Cyber Governance or Security Operations must be engaged to review and update existing risk assessments when key changes are made or new features introduced.
  - **Triggers for Review:**  
    - Major architectural changes  
    - Third-party integration  
    - Handling of sensitive data  
    - New API exposed  
- **Last Reviewed By:** Cyber Governance – Jan 2025

---

### Data Governance

- **Data Retention Requirements**:  
  _Refer to the Records & Data Management Plan (RDMP) if available (e.g., "Per RDMP-12345: Retain for 7 years")_

---

### Software Bill of Materials (SBOM)
> Key components, integrations, and third-party dependencies.

- **Critical Dependencies:**  
  - Node.js 20.x  
  - PostgreSQL 14  
- **Key Integrations:**  
  - Azure AD for Authentication  
  - AWS S3 Cold Storage  
- **Link to Full SBOM:** [View SBOM](./sbom.json)
> It is recommended best practice to include a SBOM file into your repository for software development and supply chain security. 

---

## References and Links
- **University Cyber Security Policy:** [Link](https://intranet.sydney.edu.au/services/it-phones/cyber-security/policy-and-procedures.html)
- **University Cyber Security Standards:** [Link](https://intranet.sydney.edu.au/services/it-phones/cyber-security/policy-and-procedures.html)
- **Business Criticality Scale:** [Link](https://sydneyuni.service-now.com/sm?id=kb_article_view&sysparm_article=KB0028955)
- **RDMP Guidance:** [Link](https://intranet.sydney.edu.au/research-support/managing-research/research-data-management.html)
- **GitHub Enterprise Managed User (EMU) Governance:** [Link](https://sydneyuni.service-now.com/sm?id=kb_article&sysparm_article=KB0033368)
- **How to Migrate Repository to Public GitHub** [Link](https://sydneyuni.service-now.com/sm?id=kb_article&sysparm_article=KB0013876)

## Report a Security Incident or Vulnerability

**To report a security issue, please use the Report a Cyber Security Incident in ServiceNow:** [Link](https://sydneyuni.service-now.com/sm?id=sc_cat_item&sys_id=ce467005db3c40909909abf34a9619d6&sysparm_category=a98d07b8dbd0b3002d38cae43a961964)

The Security Opertations team will send a response indicating the next steps in handling your report. After the initial reply to your report, the security team will keep you informed and collaborate with you as required to progress towards a fix, and may ask for additional information to provide guidance.

Security Scanning of repositories can be actioned with the following tools:

| **Scan type**               | **Software**                                                                                  | **Description**                                                                       |
| --------------------------- | --------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------- |
| Credentials scan            | [Trufflehog](https://trufflesecurity.com/trufflehog "https://trufflesecurity.com/trufflehog") | Scans code repository for secrets, passwords, and sensitive keys.                     |
| Library and License scan    | [Snyk](https://snyk.io/ "https://snyk.io/")                                                   | Test a Project for open-source vulnerabilities and license issues.                    |
| Code scan                   | [Snyk](https://snyk.io/ "https://snyk.io/")                                                   | Test source code for any known security issues (Static Application Security Testing). |
| Container scan*             | [Snyk](https://snyk.io/ "https://snyk.io/")                                                   | Test container images for any known vulnerabilities.                                  |
| Infrastructure as code scan | [Snyk](https://snyk.io/ "https://snyk.io/")                                                   | Test for any known infrastructure-as-code security issues.                            |

_* Container scanning is not applicable when the pipeline is not building a container image._


---

_**For any format updates to this document, coordinate with the Cyber Governance team.**_

---





# Option 2:

# Security Information

This file outlines the security-related information for this repository and should be updated as the repository's context, ownership, and risk profile evolves.

---

## Repository Status
> _Select one of the following statuses:_
- **Actively Maintained**
- **Operational**
- **To Be Archived**

_Current Status:_ **Actively Maintained**

---

## Data Owner(s)
> List of business or technical owners responsible for the data.

- Name: Jane Doe  
- Role: Application Owner  
- Email: jane.doe@university.edu.au  

---

## Data Classification
> Based on the University's Information Classification Framework.

- **Classification:** Highly Protected / Protected / Public

---

## Business Criticality
> As defined in ServiceNow or by Enterprise Architecture Standards and Business Impact Assessments.

- **Criticality Level:** Low / Medium / Business Critical / Mission Critical/ Core Infrastructure  

- **Business Impact if Unavailable:** e.g., Disruption to teaching or research workflows

---

##  ServiceNow CMDB Reference
- **Business Application Name:** Research Data Portal  
- **CI Reference:** `BUSAPP123456`  
- **Linked Services:** Storage Gateway, Identity Management, S3 Archive

---

## Risk Assessment Rating
> From formal Cyber Governance assessments.

- **Inherent Risk Rating:**  Low / Medium / High / Extreme
- **Residual Risk Rating:** e.g., Medium  
- **Assessment ID:** `CSGP-1234`

> Cyber Governance or Security Operations must be engaged to review and update existing risk assessments when key changes are made or new features introduced.
  - **Triggers for Review:**  
  - Major architectural changes  
  - Third-party integration  
  - Handling of sensitive data  
  - New API exposed  
- **Last Reviewed By:** Cyber Governance – Jan 2025

---

##  Data Retention Requirements
> Refer to the Records & Data Management Plan (RDMP) if available.

- **Retention Period:** 7 years  
- **RDMP Reference:** `RDMP-2025-017`  

---

### Software Bill of Materials (SBOM)
> Key components, integrations, and third-party dependencies.

- **Critical Dependencies:**  
  - Node.js 20.x  
  - PostgreSQL 14  
- **Key Integrations:**  
  - Azure AD for Authentication  
  - AWS S3 Cold Storage  
- **Link to Full SBOM:** [View SBOM](./sbom.json)
> It is recommended best practice to include a SBOM file into your repository for software development and supply chain security.

---

## References and Links
- **University Cyber Security Policy:** [Link](https://intranet.sydney.edu.au/services/it-phones/cyber-security/policy-and-procedures.html)
- **University Cyber Security Standards:** [Link](https://intranet.sydney.edu.au/services/it-phones/cyber-security/policy-and-procedures.html)
- **Business Criticality Scale:** [Link](https://sydneyuni.service-now.com/sm?id=kb_article_view&sysparm_article=KB0028955)
- **RDMP Guidance:** [Link](https://intranet.sydney.edu.au/research-support/managing-research/research-data-management.html)
- **GitHub Enterprise Managed User (EMU) Governance:** [Link](https://sydneyuni.service-now.com/sm?id=kb_article&sysparm_article=KB0033368)
- **How to Migrate Repository to Public GitHub** [Link](https://sydneyuni.service-now.com/sm?id=kb_article&sysparm_article=KB0013876)

## Report a Security Incident or Vulnerability

**To report a security issue, please use the Report a Cyber Security Incident in ServiceNow:** [Link](https://sydneyuni.service-now.com/sm?id=sc_cat_item&sys_id=ce467005db3c40909909abf34a9619d6&sysparm_category=a98d07b8dbd0b3002d38cae43a961964)

The Security Opertations team will send a response indicating the next steps in handling your report. After the initial reply to your report, the security team will keep you informed and collaborate with you as required to progress towards a fix, and may ask for additional information to provide guidance.

Security Scanning of repositories can be actioned with the following tools:

| **Scan type**               | **Software**                                                                                  | **Description**                                                                       |
| --------------------------- | --------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------- |
| Credentials scan            | [Trufflehog](https://trufflesecurity.com/trufflehog "https://trufflesecurity.com/trufflehog") | Scans code repository for secrets, passwords, and sensitive keys.                     |
| Library and License scan    | [Snyk](https://snyk.io/ "https://snyk.io/")                                                   | Test a Project for open-source vulnerabilities and license issues.                    |
| Code scan                   | [Snyk](https://snyk.io/ "https://snyk.io/")                                                   | Test source code for any known security issues (Static Application Security Testing). |
| Container scan*             | [Snyk](https://snyk.io/ "https://snyk.io/")                                                   | Test container images for any known vulnerabilities.                                  |
| Infrastructure as code scan | [Snyk](https://snyk.io/ "https://snyk.io/")                                                   | Test for any known infrastructure-as-code security issues.                            |

_* Container scanning is not applicable when the pipeline is not building a container image._
---

_**For any format updates to this document, coordinate with the Cyber Governance team.**_

