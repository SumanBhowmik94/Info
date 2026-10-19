# Suman Bhowmik
**Sr. System Engineer – Active Directory & Identity** | IAM · PKI · Cloud · Automation
Bangalore, India • +91-9735765546 • bhowmik.suman94@gmail.com

## Summary

Identity and directory architect with 11+ years across Microsoft, AWS and enterprise product environments. Deep command of Active Directory internals, PKI/ADCS and Okta, with a track record of moving identity platforms from manual administration to Terraform-managed, workflow-automated and fully observable services. Spent four years as a Microsoft Support Escalation Engineer and one as an AWS Senior Cloud Support Engineer resolving the hardest AD, PKI and performance escalations for enterprise customers, and now architect a centralized Okta hub-and-spoke identity platform spanning 20 orgs at BlackLine. Fluent in PowerShell, Python and Terraform; comfortable owning design, delivery, operations and mentoring end to end.

## Core Competencies

| Area | Details |
|---|---|
| **Identity & Directory** | Active Directory DS (FSMO, replication, sites/site links, trusts, Group Policy, auditing, LDAP policies, time sync, backup/restore, RMAD object recovery), Okta (SSO/MFA, Org2Org hub-and-spoke, Workflows) |
| **Authentication Protocols** | Kerberos, NTLM, SAML 2.0, OIDC, OAuth 2.0 (private_key_jwt, DPoP), SCIM, certificate-based authentication, SPN design |
| **PKI / Certificate Services** | ADCS design, upgrade & migration, certificate templates, auto-enrollment, CEP/CES, MMC & web enrollment, cipher suite hardening, certificate lifecycle monitoring |
| **Automation & IaC** | Terraform (Okta, AWS, GCP, multi-environment module design), Okta Workflows, PowerShell (expert), Python |
| **Cloud Platforms** | AWS (EC2, Directory Service/Managed AD, WorkSpaces, AppStream 2.0, FSx storage for Windows, WorkDocs, WorkMail, CloudWatch, CloudTrail), GCP (GCE-hosted DCs and ADFS farms) |
| **Observability & Operations** | New Relic (custom integrations via nri-flex), PagerDuty alerting/paging, CloudWatch, Perfmon, incident management, RCA & major-incident reporting |
| **Performance & Debugging** | WPR/WPA, Xperf, WinDBG, Sysinternals (ProcMon, ProcDump, ProcExp, PSTools), LSASS high-CPU and slow-logon root cause analysis, user profile troubleshooting |
| **DNS & Networking** | Microsoft DNS (zone design, replication scopes, records), TLS and routing diagnostics, packet analysis with Wireshark, Network Monitor, Message Analyzer, NetSH |
| **Training and Mentorship** | Training and mentoring new hires, cube-side triages, complex MI and RCA discussion for proactive solutions |

## Professional Experience

### Sr. System Engineer – Active Directory | BlackLine Systems Development & Services, Bangalore
*Nov 2023 – Present*

- **Identity architecture.** Designed and recommended the target-state Okta hub-and-spoke architecture (1 hub + 19 spoke orgs): AD → central hub → Org2Org push to spokes with shadow-group-based admin role management. Presented the centralization strategy to leadership.
- **Infrastructure as code.** Built Terraform modules (okta-groups, okta-admin-role) with cross-module output wiring and root-level provider hoisting; rolled out through Test, Dev, Regression, Sandbox and Production environments. Automated Org2Org OIDC federation (private_key_jwt, scope grants, custom roles and resource sets), resolving provider-level gaps around DPoP, org scopes and ORN syntax.
- **Workflow automation.** Architected an Okta Workflows group-membership sync engine for hub-to-spoke mirroring with actor guards, idempotency checks and audit tables; templated .flopack deployments in Python for repeatable rollout across spokes. Wrote bulk provisioning scripts with service-app auth and rate-limit backoff.
- **Observability.** Instrumented AD, ADFS, ADCS and Okta in New Relic with PagerDuty paging; built a certificate-expiry monitoring pipeline via nri-flex to eliminate outage-causing cert lapses.
- **Platform delivery.** Own end-to-end delivery of directory and identity migration projects with zero or minimal production downtime; deploy domain controllers in GCP and AWS via Terraform; manage stakeholder impact across dependent services.
- **Security & modernization.** Leading RC4 cipher deprecation across the AD estate; driving inactive-account cleanup; building an AI agent for Okta system-log analysis.
- **Tier-3 operations.** Resolved ADFS SSO outages on the EU farm (expired MFA adapter certificates on GCE nodes), Okta risk-policy denials caused by proxy egress ASNs, and Okta AD Agent upgrade failures; maintain ADFS claims rules and DC/DNS availability for all dependent services.

### Senior Cloud Support Engineer | Amazon Web Services, Bangalore
*Jul 2022 – Nov 2023*

- **Directory on AWS.** Deployed and troubleshot domain controllers on EC2; designed and operated AWS Managed Microsoft AD, Simple AD and AD Connector, including forest trusts, client/server-side LDAPS, CloudWatch alarming and CloudTrail-based diagnostics.
- **End-user computing.** Ran WorkSpaces and AppStream 2.0 as a service: directory integration (managed and on-prem AD), authentication configuration, custom and BYOL image pipelines, fleets, stacks and stack policies, OneDrive/Google Drive home-folder integration.
- **Storage & collaboration.** Supported FSx for Windows and FSx for NetApp ONTAP (schedules, policies, backups) and WorkDocs sites, shares and permissions.
- **Escalation practice.** Reproduced trending issues in lab environments, escalated patterns to AWS product teams, and handled critical, highly complex customer cases with full case documentation.

### Support Escalation Engineer – Directory Services | Microsoft, Bangalore
*Jul 2018 – Jul 2022*

- **Active Directory.** Final escalation point for Active Directory DS (FSMO, replication, Group Policy, auditing, time sync, DC promotion, domain join) and Kerberos/NTLM authentication design and troubleshooting, including SPN planning and certificate-based authentication.
- **PKI.** Administered and upgraded ADCS: template design, certificate and cipher-suite migrations, and enrollment troubleshooting across MMC, web, auto-enrollment and CEP/CES channels.
- **Performance & debugging.** Root-caused LSASS high CPU, slow logon, no-logon, user-profile and RDP authentication issues using WPR/WPA, Xperf stack walks, WinDBG and Sysinternals; diagnosed network-layer failures with Wireshark, Netmon and NetSH captures.
- **ADFS.** Troubleshot ADFS claims, rules and federation failures for enterprise customers.
- **Enablement.** Trained new engineers, delivered advanced-topic triages to frontline teams, produced how-to videos and internal advisories, and reported emerging issue patterns to the product group.
- **Recognition.** Microsoft ACE Award 2019 (top performer, DS team APAC); three Momentum awards for highest customer satisfaction; two cultural awards.

### Active Directory Administrator (L3) | Tata Consultancy Services, Bangalore
*Jan 2018 – Jul 2018*

- Managed FSMO roles, LDAP policies, trusts, sites and site links, replication and Group Policy deployment; reviewed application and technical architecture requirements with input into AD design decisions.
- Ran directory backup/restore, single-object recovery with RMAD, weekly health checks, DC commissioning/decommissioning, compliance reviews and major-incident RCA documentation.

### Service Engineer | Diebold Nixdorf, Kolkata
*Jan 2015 – Jan 2018*

Owned customer issues end to end (remote and on-site): server builds and custom imaging, hardware/software maintenance, AD user and group administration, certificate issuance and revocation, and knowledge-base authoring.

## Certifications

- AWS Certified Solutions Architect – Associate
- Microsoft Certified Solutions Associate (MCSA) – G568-3765
- Microsoft Certified Professional (MCP) – G565-2214

## Education

- Secondary Education (10th) | General Stream
- Higher Secondary Education (11th) | Science Stream
- Engineering | Diploma in Engineering (3 years Full time) | Electronics and Telecommunication Engineering

## Languages

English (expert – speaking, reading, writing) • Hindi (expert – speaking)
