# Enterprise Security Lab

Enterprise Security Lab is a hands-on cybersecurity portfolio focused on enterprise information protection, security governance, secure architecture and practical security engineering.

The project is designed to demonstrate how security controls can be planned, implemented, tested and documented in a realistic enterprise environment.

## Current Focus

The current implementation focuses on Microsoft 365 security and Microsoft Purview as part of my preparation for the Microsoft SC-401 certification.

The laboratory includes:

- Microsoft 365 E3 test tenant
- Enterprise identity architecture
- Role-Based Access Control (RBAC)
- Microsoft Purview permissions
- Information Protection
- Sensitivity labels
- Data Loss Prevention (DLP)
- Data classification
- Retention and records management
- Audit and investigation capabilities
- Secure SDLC and application security
- AI security and governance

## Microsoft Purview Lab

A dedicated Microsoft 365 tenant has been configured to test enterprise data security controls.

### Identity Architecture

| Identity | Function | Access level |
|---|---|---|
| Global Administrator | Tenant administration | Privileged administrator |
| Joni Sherman | Information Security Administrator | Purview delegated administration |
| Megan Bowen | Finance user | Standard user |
| Adele Vance | Human Resources user | Standard user |

### Security Groups

| Security group | Purpose |
|---|---|
| `SEC-Purview-Admins` | Purview administration |
| `SEC-Finance-Users` | Finance department users |
| `SEC-HR-Users` | Human Resources department users |

The `SEC-Purview-Admins` security group has been assigned to the Microsoft Purview **Information Protection Admins** role group.

This implementation follows:

- Principle of least privilege
- Role separation
- Group-based access management
- Delegated administration
- Enterprise naming conventions

## Implementation Status

### Identity and Access Management

- [x] Microsoft 365 tenant created
- [x] Test identities created
- [x] Departmental security groups created
- [x] Administrative security group created
- [x] Purview role group assignment configured
- [ ] Administrative access validation
- [ ] Conditional Access design
- [ ] Multi-Factor Authentication validation

### Information Protection

- [ ] Data classification taxonomy
- [ ] Sensitivity labels
- [ ] Sensitivity label publishing policies
- [ ] Encryption and access restrictions
- [ ] Office document protection tests

### Data Loss Prevention

- [ ] Exchange Online DLP policy
- [ ] SharePoint and OneDrive DLP policy
- [ ] Finance data protection policy
- [ ] Human Resources data protection policy
- [ ] DLP incident testing
- [ ] Endpoint DLP assessment

### Governance and Compliance

- [ ] Retention policies
- [ ] Audit configuration
- [ ] Content Search
- [ ] Insider Risk Management assessment
- [ ] Data lifecycle documentation

## Secure Web Platform

The Enterprise Security Lab will also serve as the governance and security framework for an AI-assisted secure web platform developed as part of my Software Engineering bachelor thesis.

The platform will follow Secure SDLC principles and will include:

- Security requirements
- Threat modeling
- Secure architecture
- Authentication and authorization
- Application security testing
- Dependency and secret scanning
- CI/CD security controls
- Logging and monitoring
- AI-assisted security capabilities
- Governance and risk documentation

The application source code will be maintained in a separate repository to preserve a clear separation between:

1. Enterprise security governance and laboratory documentation
2. Software development and technical implementation

## Security Domains

This portfolio covers the following areas:

- Information Security Governance
- Data Security
- Microsoft Purview
- Governance, Risk and Compliance
- Identity and Access Management
- Secure Software Development Lifecycle
- Application Security
- Cloud Security
- AI Security
- AI Governance
- Security Automation
- Enterprise Risk Management

## Planned Repository Structure

```text
Enterprise-Security-Lab/
├── architecture/
├── documentation/
│   ├── identity-and-access-management/
│   ├── information-protection/
│   ├── data-loss-prevention/
│   ├── governance-risk-compliance/
│   └── secure-sdlc/
├── evidence/
├── policies/
├── diagrams/
├── templates/
└── README.md

```

## Certifications and Learning Path

This laboratory supports my current professional development path:

- CompTIA Security+ — Completed
- INE eJPT — Completed
- INE Certified Cloud Associate (ICCA) — Completed
- Microsoft SC-401 — In progress
- CISSP — In preparation
- GitHub Advanced Security — Planned

## Security and Privacy

All identities, documents and data used in this laboratory are synthetic.

No production credentials, personal information, confidential corporate information or customer data are stored in this repository.

Screenshots and technical evidence are reviewed and anonymized before publication.

## Roadmap

- [x] Microsoft 365 tenant setup
- [x] Enterprise identity structure
- [x] Security group architecture
- [x] Microsoft Purview delegated administration
- [ ] Sensitivity label taxonomy
- [ ] Information Protection deployment
- [ ] Data Loss Prevention policies
- [ ] Audit and investigation use cases
- [ ] Secure SDLC framework
- [ ] AI governance assessment
- [ ] NIST AI Risk Management Framework mapping
- [ ] ISO/IEC 42001 assessment
- [ ] Cloud security architecture
- [ ] Security automation
- [ ] Bachelor thesis secure web platform

## Technologies

- Microsoft 365
- Microsoft Purview
- Microsoft Entra ID
- GitHub
- GitHub Actions
- Markdown
- Python
- Azure
- Secure SDLC
- Large Language Models
