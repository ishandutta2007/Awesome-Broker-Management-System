# Awesome-Broker-Management-System

# Top Broker Management System (Insurance) Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Agency Management, Policy Administration & Commission Processing*  
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Insurance Broker Management Systems (AMS)**. These tools help insurance agencies, brokers, and managing general agents (MGAs) manage clients, policies, carriers, commissions, renewals, and claims workflows.

**Examples** include Applied Epic, Acturis, Open GI, Applied TAM, Novidea, BindHQ, Relay Platform, Veruna, HawkSoft, and EZLynx (the category leaders).

**Open-source emphasis**: This section is expanded with active projects for self-hosting, custom brokerage workflows, and transparent policy data management — ideal for independent brokers, P&C agencies, and developers building vendor-independent insurance management solutions. Note that the open-source ecosystem for full agency management systems remains limited, with most projects being academic, early-stage, or focused on specific modules like claims or commission calculation.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Applied Epic](https://www1.appliedsystems.com/)**  
  Comprehensive agency management system for P&C, employee benefits, and specialty insurance brokers. Widely used by independent agencies for policy, client, and financial management.

- **[Acturis](https://www.acturis.com/)**  
  Cloud-based insurance software platform serving brokers, insurers, and MGAs across commercial and personal lines in the UK and Europe.

- **[Open GI](https://www.opengi.com/)**  
  Insurance software solutions for brokers, insurers, and MGAs with policy administration, rating, and e-trading capabilities.

- **[Applied TAM](https://www1.appliedsystems.com/)**  
  Agency management system for independent insurance agents and brokers, part of the Applied Systems suite.

- **[Novidea](https://www.novidea.com/)**  
  Data-driven insurance platform for brokers, agencies, and MGAs built on Salesforce, covering the full policy lifecycle.

- **[BindHQ](https://www.bindhq.com/)**  
  Cloud-based policy administration and agency management platform for MGAs, wholesalers, and specialty brokers.

- **[Relay Platform](https://www.relayplatform.com/)**  
  Commercial insurance quoting and placement platform connecting brokers with carriers for faster binding.

- **[Veruna](https://veruna.com/)**  
  Salesforce-powered agency management system for independent brokers and agents. Launched Quote Hero in 2024 for two-way comparative rating integration and automated ACORD form generation . Raised $22.25M in Series B funding with investors including Guidewire Software .

- **[HawkSoft](https://www.hawksoft.com/)**  
  Agency management system for independent P&C insurance agencies with CRM, policy management, and accounting features.

- **[EZLynx](https://www.ezlynx.com/)**  
  Insurance agency management system with comparative rating, policy management, and customer engagement tools.

## Open-Source GitHub Projects

- **[Quickfire / Openfire](https://github.com/flashvenom/quickfire)**  
  The leading open-source insurance Agency Management System (AMS) for independent P&C brokers, wholesalers, and MGAs. Openfire is the open-source core framework focused on workflows, built with ASP.NET Core 10, Blazor Server, Entity Framework Core, Microsoft FluentUI, and SQL Server/SQLite. Features comprehensive client and policy management (contacts, addresses, locations, policies, carriers), API consolidation for payments, calls, leads, documents, and forms, OpenAI integration for custom prompts and data entry, centralized renewals and submissions with clear next actions, task assignment with goal dates, certificate issuance with built-in editor, natural language data querying, and background workers for follow-ups and routine duties. The Company Manual module provides structured procedure documentation with publishing controls, rich text editing, revision history, and audit trails. The Forms Library offers centralized PDF form management with version control . Active development with 42+ stars as of September 2026.

- **[Surefire](https://github.com/flashvenom/surefire)**  
  Agency Management System and productivity suite for P&C insurance agencies and brokers, built with Blazor .NET 9 and FluentUI. Related to the Quickfire/Openfire ecosystem, sharing the same development lineage. 33+ stars with active commits as of September 2026 .

- **[InsurancePro CRM](https://github.com/prolinkinfo/InsuranceProCRM)**  
  Open-source CRM empowering insurance agents to manage clients, policies, and leads through a comprehensive and intuitive platform. Built with JavaScript, 37+ stars with recent updates. Provides core CRM functionality including client management, policy tracking, and lead pipeline management for insurance professionals .

- **[DEMiHAT/IMS (Insurance Management System)](https://github.com/DEMiHAT/IMS)**  
  Full-stack Insurance Management System built with Python (Flask) and MySQL, MIT licensed. Provides a web interface for administrators and agents to perform CRUD operations on insurance data. Features customer management, policy creation and assignment, claims processing with status tracking, payment logging, and agent management with agent-customer linking. Database schema includes agents, customers, policies, claims, payments, and junction tables for relationships. Suitable for small insurance companies or as a learning foundation .

- **[GeoffreyOmollo/insurance-management-system](https://github.com/GeoffreyOmollo/insurance-management-system)**  
  Insurance Policy Management System built with Angular (frontend) and C#/.NET (backend), using PostgreSQL and Dapper ORM. Features comprehensive policy management including coverages (what insurance covers), exclusions (what is not covered), insurance types, and policies with policyholder details, monthly deductions, and policy limits. Provides full CRUD operations for all entities. Academic-quality codebase demonstrating modern full-stack architecture for insurance policy administration .

- **[pavith-raj/Insurance-Policy-Mangagement-System](https://github.com/pavith-raj/Insurance-Policy-Mangagement-System)**  
  Insurance Management Database designed with MySQL for managing policies, customers, claims, and premium payments. Features customer management, policy management across health/life/vehicle types, claims recording with status tracking, premium payment management, and SQL views for common queries. Includes specialized tables for health insurance (policyholder details, gender, age), life insurance (beneficiary, sum assured), and vehicle insurance (make, model, vehicle number). Provides a structured database foundation for insurance operations .

### Additional Strong Open-Source Options

- **Digital Claims Management System** — Enterprise-grade insurance claims management application built with React and Spring Boot, deployed on AWS. Supports secure claim submission, multi-step forms, document uploads to S3, real-time status tracking, role-based workflows for adjusters and supervisors, and audit logging with SLA monitoring .
- **INSure Insurance Sales Management** — Comprehensive insurance sales management tool built with React.js, Node.js, and MongoDB. Features sales management tracking policies, sales and commissions, lead tracking through the sales pipeline, and user-friendly interface for agents and administrators .
- **hwg-analytics-hub** — Comprehensive solution for managing and analyzing insurance claims data. Provides dashboards, reports, and analytics tools for tracking agreements, claims, and dealer performance using Supabase PostgreSQL with custom analytics functions including revenue growth calculations and leaderboards .
- **Insurance Analytics Platform** — Web application for managing and analyzing insurance claims with integrated machine learning capabilities for fraud detection. Features claims management, analytics dashboard with fraud detection analysis, admin panel for claims review, and ML-powered risk assessment. Built with React 18, Python Flask, and Scikit-learn .
- **Commission Calculation System** — Production-grade full-stack insurance commission platform designed for hierarchical commission processing. Features four-tier agency structure (Agent → Team Lead → Manager → Director), First Year Commission (FYC) payouts, override commissions, tier-based volume bonuses, automated clawbacks, immutable financial ledger for audit trails, real-time reporting dashboards, and CSV exports. Built with Flask, SQLite/SQLAlchemy, React, and TypeScript .

**Frameworks for building custom broker management solutions**: Combine **Quickfire/Openfire** as the core AMS foundation for P&C broker workflows with client, policy, carrier, and certificate management . Use **InsurancePro CRM** for CRM-centric agency operations with client and lead management . For claims-focused implementations, **Digital Claims Management System** provides enterprise-grade workflows with audit logging and SLA monitoring . For commission processing, **Commission Calculation System** demonstrates hierarchical payout logic with immutable ledger architecture . For policy administration with modern full-stack architecture, **GeoffreyOmollo/insurance-management-system** provides a clean Angular/.NET reference . Note that true enterprise broker management platforms with comparative rating, carrier connectivity, and ACORD form automation remain primarily commercial territory; open-source stacks provide strong workflow foundations, CRM capabilities, and policy management components that require integration for complete brokerage operations.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Insurance broker management tools must comply with insurance regulations, licensing requirements, and data privacy laws (GDPR, CCPA, state insurance regulations).
- Self-hosted open-source solutions require proper infrastructure, security hardening, and ongoing maintenance. Commission calculations and policy administration require insurance domain expertise for correct configuration.
- The open-source ecosystem provides strong CRM and policy management foundations, but full enterprise brokerage platforms with comparative rating, carrier connectivity, and ACORD form automation remain primarily commercial offerings.

---

**Made for insurance brokers, agency principals, MGA operators, and insurtech developers.**  
Let's make broker management more open, transparent, and efficient.
