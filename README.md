# Awesome-ERP-CRM-Enterprise-System-Integrations

## Top ERP & CRM Enterprise System Integrations Ecosystem

**Curated List of SaaS Platforms & Open-Source GitHub Projects**  
*Focused on Contract-to-ERP Connectivity, iPaaS Orchestration & Self-Hosted Integration Frameworks*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **ERP & CRM Enterprise System Integrations**. These tools help organizations connect contract intelligence, CRM, ERP, and HR systems—covering everything from native CLM-to-SAP connectors and enterprise iPaaS platforms to open-source integration frameworks that eliminate per-connection or per-message licensing.

**Examples** include Azure Logic Apps, MuleSoft Anypoint, SAP Integration Suite, Informatica Cloud, Boomi, Workato, Icertis Platform Integrations, SnapLogic, Celigo, and Jitterbit.

**Open-source emphasis**: This section highlights active projects for self-hosted integration frameworks, open-source ERP/CRM development platforms, and community-driven connectivity—ideal for organizations seeking data sovereignty and avoiding per-vCore or per-task commercial licensing.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global enterprise Integration Platform as a Service (iPaaS) and enterprise system integration market is estimated at **$8.5 billion to $17.9 billion in 2025–2026**, expanding at a rapid compound annual growth rate (CAGR) of 19% to 30%. The sector is **moderately fragmented** with high top-tier concentration: while hyperscalers and legacy enterprise software giants (Microsoft, Salesforce MuleSoft, SAP, Informatica) command major multi-billion-dollar enterprise footprints, agile modern automation platforms (Workato, Boomi) and specialized vertical/open-source orchestrators prevent a winner-take-all monopoly by thriving across mid-market, hybrid cloud, and self-hosted environments.

## SaaS/Hosted Platforms

| Product | Company Size (Valuation / Revenue) | Description | Starting Pricing | Free Tier / Trial Limits |
|---------|------------------------------------|-------------|------------------|--------------------------|
| **[Azure Logic Apps](https://azure.microsoft.com/en-us/products/logic-apps/)** | **~$3.1 Trillion** market cap (Microsoft) / **$245B+** annual rev | **Serverless enterprise workflows and integration pipelines within Microsoft Azure.** Native hybrid connectivity to SAP, Dynamics 365, Salesforce, and enterprise messaging queues with hundreds of managed connectors. | **$0.000025 per action execution** (Consumption model); Standard fixed capacity starting at **~$175/month** per compute instance | **Free plan**: 4,000 free action executions per month (at the Azure subscription level) |
| **[MuleSoft Anypoint Platform](https://www.mulesoft.com/)** | **~$310 Billion** market cap (Salesforce) / **$34B+** annual rev | **Enterprise iPaaS and API management gold standard.** Provides API-led connectivity across ERP (SAP, Oracle) and CRM architectures. CloudHub and on-premise execution runtimes with Mule Credits and vCore allocations. | **$2,000/month** ($24,000/year billed annually) entry baseline; median enterprise contract **~$68,695/year** | **30-day free trial**: sandboxed trial environment with limited design flows and restricted runtime compute |
| **[SAP Integration Suite](https://www.sap.com/)** | **~$260 Billion** market cap (SAP SE) / **$35B+** annual rev | **Native enterprise integration backbone for SAP ecosystems with 3,400+ prebuilt integration packages.** Connects SAP S/4HANA, Ariba, SuccessFactors, and third-party systems via modern API & MCP gateways. | **~$830/month** (~€780/month) Basic edition / CPEA consumption (~$0.005 per message block beyond quota) | **Free plan**: 50,000 messages/month under SAP BTP Free Tier service plan; or **30-day free trial** tenant |
| **[Informatica Cloud Data Integration](https://www.informatica.com/)** | **~$7.8 Billion** market cap / **$1.68 Billion** annual rev | **Enterprise data integration, mass ingestion, and ETL/ELT within the Intelligent Data Management Cloud (IDMC).** High-throughput data pipelines linking ERP warehouses and operational CRMs. | **€2,400/month** (~$2,550/month) base Cloud Data Integration package | **30-day free trial**: limited to single-agent runtime processing and capped compute unit throughput |
| **[Workato](https://www.workato.com/)** | **$5.7 Billion** valuation (Series E) / **~$150 Million** ARR | **Low-code enterprise automation and iPaaS platform.** Combines API integration, workflow automation, and agentic AI orchestration across 1,000+ business applications with credit-based execution. | **$75/month** (Pro plan with 2,500 monthly task credits); scales up to $1,275/month for 50,000 credits | **Free plan**: 50,000 one-time starter credits (never expire, full platform capability) |
| **[Icertis Platform Integrations](https://www.icertis.com/products/platform/integrations/)** | **$5.0 Billion** valuation / **~$320 Million** ARR | **Contract Intelligence integration suite for enterprise systems.** Pre-built certified connectors synchronizing buy/sell contract governance between SAP S/4HANA, Ariba, Salesforce CRM, and Workday HR. | **~$88,000/year** median contract value (starting tiers typically ~$75,000–$100,000/year with enterprise onboarding) | **No free trial or free tier**: evaluation requires sales-scoped Proof of Concept (POC) with custom sample data |
| **[Boomi](https://www.boomi.com/)** | **$4.0 Billion** valuation (buyout) / **$500+ Million** ARR | **Cloud-native iPaaS with lightweight distributed Atom runtime architecture.** Offers pre-built ERP/CRM connectors, API management, and embedded AI agents (DesignGen, Scribe, Boomi GPT). | **$99/month + usage** (Pay-As-You-Go tier); fixed production edition bundles starting at **~$1,000/month** | **30-day free trial**: $0 access to full platform, cloud runtime, and connector catalog |
| **[SnapLogic](https://www.snaplogic.com/)** | **$1.0 Billion** valuation (Series H) / **~$140 Million** ARR | **Visual generative integration platform utilizing AI-assisted Snaps.** Visual pipeline building connecting enterprise ERPs, cloud data warehouses, and front-office CRMs without low-level script maintenance. | **$9,995/year** entry-level deployment packaging (annual contract required) | **30-day free trial**: available for AutoSync/data loader pipelines; core enterprise platform requires demo |
| **[Celigo](https://www.celigo.com/)** | **~$500 Million** estimated valuation / **~$90 Million** ARR | **Business-user friendly iPaaS optimized for NetSuite, Salesforce, and mid-market ERP integrations.** Preconfigured "Integration Apps" with automated error handling and sync flows. | **~$14,787/year** median contract (entry flow licenses starting at **~$600/month** billed annually) | **Free plan**: 2 endpoints and 1 active integration flow permanently free; plus a **30-day unlimited trial** |
| **[Jitterbit](https://www.jitterbit.com/)** | **~$450 Million** estimated valuation / **~$95 Million** ARR | **Low-code integration platform (Harmony) with flat-rate multi-year models.** Connects legacy on-prem ERP systems (SAP, Epicor) with modern SaaS CRMs and custom APIs. | **~$1,000/month** ($12,000/year billed annually) entry Standard tier | **14-day free trial**: request-based evaluation access with sample connectors and design studio |

## Open-Source GitHub Projects

| Project | Stars | Description |
|---------|-------|-------------|
| **[n8n](https://github.com/n8n-io/n8n)** | [![Stars](https://img.shields.io/github/stars/n8n-io/n8n?style=social&color=white)](https://github.com/n8n-io/n8n/stargazers) | **Fair-code licensed workflow automation platform with 400+ native connectors.** Visual node-based designer ideal for bridging ERP, CRM, and webhook events with custom JavaScript/Python logic and AI agent tools. Self-hostable via Docker. |
| **[Odoo](https://github.com/odoo/odoo)** | [![Stars](https://img.shields.io/github/stars/odoo/odoo?style=social&color=white)](https://github.com/odoo/odoo/stargazers) | **Extensible open-source enterprise suite (LGPLv3) featuring native ERP & CRM apps.** Exposes comprehensive XML-RPC, REST, and JSON-RPC APIs for bi-directional integration with external financial, sales, and supply chain applications. |
| **[ERPNext](https://github.com/frappe/erpnext)** | [![Stars](https://img.shields.io/github/stars/frappe/erpnext?style=social&color=white)](https://github.com/frappe/erpnext/stargazers) | **Full-featured open-source ERP system built on the Frappe framework (GPLv3).** Includes built-in REST API endpoints, webhook subscriptions, and modular doctype schemas for synchronizing orders, inventory, and customer databases. |
| **[Activepieces](https://github.com/activepieces/activepieces)** | [![Stars](https://img.shields.io/github/stars/activepieces/activepieces?style=social&color=white)](https://github.com/activepieces/activepieces/stargazers) | **Open-source no-code business automation tool (MIT license).** Modern TypeScript-based alternative to Zapier and Workato designed for internal tool orchestrations, ERP notifications, and multi-tenant webhook processing. |
| **[Airbyte](https://github.com/airbytehq/airbyte)** | [![Stars](https://img.shields.io/github/stars/airbytehq/airbyte?style=social&color=white)](https://github.com/airbytehq/airbyte/stargazers) | **Open-source ELT data integration engine (ELv2).** Contains 350+ pre-built connectors to replicate raw customer data, transaction records, and inventory state from ERPs and CRMs into data lakes and warehouses. |
| **[Flowable](https://github.com/flowable/flowable-engine)** | [![Stars](https://img.shields.io/github/stars/flowable/flowable-engine?style=social&color=white)](https://github.com/flowable/flowable-engine/stargazers) | **Open-source BPMN 2.0 and CMMN workflow engine (Apache-2.0).** Embeddable Java execution engine for modeling complex contract approval chains, order-to-cash sequences, and cross-system orchestration between ERP, CRM, and CLM databases. |
| **[Apache Camel](https://github.com/apache/camel)** | [![Stars](https://img.shields.io/github/stars/apache/camel?style=social&color=white)](https://github.com/apache/camel/stargazers) | **The reference open-source implementation of Enterprise Integration Patterns (Apache-2.0).** Features ~300 enterprise connectors covering JMS, Kafka, SAP, and REST endpoints. Routes defined via Java, YAML, or XML DSL. |
| **[Apache NiFi](https://github.com/apache/nifi)** | [![Stars](https://img.shields.io/github/stars/apache/nifi?style=social&color=white)](https://github.com/apache/nifi/stargazers) | **Open-source real-time data ingestion, transformation, and lineage platform (Apache-2.0).** Visual drag-and-drop canvas for orchestrating bidirectional data flows between disparate on-prem ERPs and cloud CRMs with audit tracking. |
| **[Camunda 7 Platform](https://github.com/camunda/camunda-bpm-platform)** | [![Stars](https://img.shields.io/github/stars/camunda/camunda-bpm-platform?style=social&color=white)](https://github.com/camunda/camunda-bpm-platform/stargazers) | **Battle-tested open-source BPMN workflow and DMN decision automation platform (Apache-2.0).** Orchestrates human tasks and automated microservices interfacing with core enterprise backends. |
| **[Spring Integration](https://github.com/spring-projects/spring-integration)** | [![Stars](https://img.shields.io/github/stars/spring-projects/spring-integration?style=social&color=white)](https://github.com/spring-projects/spring-integration/stargazers) | **Enterprise Integration Patterns inside the Spring Boot ecosystem (Apache-2.0).** Lightweight in-memory messaging channels, routers, transformers, and enterprise adapters for JVM-native integration services. |
| **[WSO2 Enterprise Integrator](https://github.com/wso2/product-ei)** | [![Stars](https://img.shields.io/github/stars/wso2/product-ei?style=social&color=white)](https://github.com/wso2/product-ei/stargazers) | **Open-source hybrid enterprise integration platform (Apache-2.0).** High-performance ESB and data services server facilitating message mediation, transformation, and legacy SOAP/REST protocol bridging across enterprise architectures. |
| **[Hubleto](https://github.com/hubleto/erp)** | [![Stars](https://img.shields.io/github/stars/hubleto/erp?style=social&color=white)](https://github.com/hubleto/erp/stargazers) | **Open-source PHP-based ERP/CRM development framework.** Provides customizable modules for contacts, orders, and deals with React + TailwindCSS UI, CLI automation, and modular data synchronization tools. |
| **[Cameleer](https://github.com/pmsudhi/cameleer)** | [![Stars](https://img.shields.io/github/stars/pmsudhi/cameleer?style=social&color=white)](https://github.com/pmsudhi/cameleer/stargazers) | **Apache Camel's routes compiled as a single native Rust binary.** Sub-3ms startup and 7 MB memory footprint executing Camel YAML DSL with built-in MCP server support for low-overhead serverless and AI agent integration flows. |

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format and table schema).
3. Include: name, link, company size or stars badge, starting pricing, free limits, and a concise 1–2 sentence description.
4. Submit a PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- ERP/CRM integration platforms handle sensitive business data including financial records, customer PII, and contract terms; enforce least-privilege connector permissions, secret rotation, and audit logging for all integration flows.
- Pricing models vary dramatically across commercial iPaaS: evaluate infrastructure vCores, credit consumption rates, and connector licensing terms before enterprise commitment. Open-source self-hosted options eliminate recurring license fees but require internal hosting and maintenance engineering.

---

**Made for integration engineers, ERP architects, and organizations building enterprise connectivity.**  
Let's make ERP and CRM system integrations more open, governed, and cost-predictable.
