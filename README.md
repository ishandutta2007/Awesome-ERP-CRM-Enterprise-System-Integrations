# Awesome-ERP-CRM-Enterprise-System-Integrations

## Top ERP & CRM Enterprise System Integrations Ecosystem

**Curated List of SaaS Platforms & Open-Source GitHub Projects**  
*Focused on Contract-to-ERP Connectivity, iPaaS Orchestration & Self-Hosted Integration Frameworks*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **ERP & CRM Enterprise System Integrations**. These tools help organizations connect contract intelligence, CRM, ERP, and HR systems—covering everything from native CLM-to-SAP connectors and enterprise iPaaS platforms to open-source integration frameworks that eliminate per-connection or per-message licensing.

**Examples** include Icertis Platform Integrations (SAP, Microsoft, Salesforce, Workday), MuleSoft Anypoint, Boomi, Workato, Informatica Cloud, SAP Integration Suite, Azure Logic Apps, SnapLogic, Jitterbit, and Celigo (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted integration frameworks, open-source ERP/CRM development platforms, and community-driven connectivity—ideal for organizations seeking data sovereignty and avoiding per-vCore or per-task commercial licensing. The open-source landscape is genuinely functional: **Apache Camel** provides the widest connectivity with ~300 components, **Hubleto** offers an open-source PHP-based ERP/CRM framework for building custom integrations, and **Flowable** delivers BPMN orchestration for approval workflows across systems [citation:11].

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[Icertis Platform Integrations](https://www.icertis.com/products/platform/integrations/)** | **Native contract intelligence connectors for the major enterprise ecosystems.** **SAP**: brings contract data into S/4HANA and Ariba for source-to-pay. **Microsoft**: integrates with Dynamics 365, Teams, and M365 via Azure AI. **Salesforce**: manage contracts directly within the CRM. **Workday**: automate contract compliance for HR and procurement [citation:1]. | Included with Icertis CLM subscription (quote-only) | No standalone free tier; demo via sales |
| **[MuleSoft Anypoint Platform](https://www.mulesoft.com/)** | **Enterprise iPaaS and API management standard.** vCore-based pricing with typical contract minimums in the mid-five to low-six figures annually. **Median contract ~$68,695/year** (Vendr). Implementation services typically **20–40% of first-year software cost** [citation:2]. | Quote-only (median ~$68,695/year) | **30-day free trial** available |
| **[Boomi](https://www.boomi.com/)** | **Cloud-native iPaaS with Atom-based architecture.** **API Management is sold separately** in four editions (Professional to Enterprise Plus). **Pay-As-You-Go option: $99/month + usage** with no contract. Every Integration edition includes **six AI agents** (DesignGen, Scribe, Answers, Pathfinder, Boomi GPT, DataDetective) [citation:3][citation:14]. | Pay-As-You-Go: **$99/month + usage**; Editions: quote-only | **30-day free trial** ($0, full platform access) [citation:14] |
| **[Workato](https://www.workato.com/)** | **Task-based automation platform with transparent self-service pricing.** **Free: 50,000 one-time credits** (never expire). **Pro: $75/month** (2,500 credits/month) up to **$1,275/month** (50,000 credits). Credits cover Orchestrate, AI, and Agentic capabilities. **No credit rollover**—unused Pro credits expire monthly [citation:4]. | Pro: **$75/month** (2,500 credits); Free: 50K one-time credits | **Free**: 50,000 one-time credits, same platform capabilities as Pro [citation:4] |
| **[Informatica Cloud Data Integration](https://www.informatica.com/)** | Enterprise data integration and ETL within the IDMC platform. **Starting at €2,400/month** for Integration Cloud. **Consumption-based IPU pricing**—no public dollar rate; quote required based on sources and expected usage . | Integration Cloud: **from €2,400/month**; quote-only | No free tier; trial via sales |
| **[SAP Integration Suite](https://www.sap.com/)** | **Native SAP integration with 3,400+ prebuilt integrations** for SAP, third-party, and e-government applications. **Enhanced tier: 50K messages included/month**; Standard: 10K; Premium: 500K. **MCP Gateway** exposes APIs and data sources as governed MCP Servers for AI agents [citation:6]. | Quote-only (message-based tiers) | **Free tier**: unlimited SAP-to-SAP integrations with prebuilt content [citation:6] |
| **[Azure Logic Apps](https://azure.microsoft.com/en-us/products/logic-apps/)** | **Serverless integration workflows within Azure.** **Consumption model**: pay per action execution, with an initial free allocation of built-in actions per subscription. **Standard model**: fixed capacity for predictable workloads [citation:7]. | Consumption: per-execution; Standard: capacity-based | **Free allocation**: initial built-in actions per subscription [citation:7] |
| **[SnapLogic](https://www.snaplogic.com/)** | Enterprise iPaaS with AI and data integration capabilities. **Starting at $9,995/year** (Software Advice listing). Positioned for enterprise-scale integration with a visual designer [citation:8]. | **$9,995/year** (Software Advice) | No free tier; demo via sales |
| **[Jitterbit](https://www.jitterbit.com/)** | **"Unlimited" pricing model**—unlimited endpoints, trading partners, APIs, and AI agents at one locked-in multi-year price. Eliminates per-connection "success tax" [citation:9]. | Quote-only (Unlimited multi-year contract) | Free trial available |
| **[Celigo](https://www.celigo.com/)** | **iPaaS with strong NetSuite and ERP focus.** **Free plan: 2 endpoints, 1 flow** (no SSO, no on-prem agent). **30-day trial: unlimited endpoints, flows, and all features** (except integration apps) [citation:10]. | Quote-only (flow-based; median ~$14,787/year) | **Free**: 2 endpoints, 1 flow; **30-day trial**: unlimited everything [citation:10] |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Apache Camel](https://github.com/apache/camel)** | [![Stars](https://img.shields.io/github/stars/apache/camel?style=social&color=white)](https://github.com/apache/camel/stargazers) | **The most widely used open-source integration framework and reference implementation of Enterprise Integration Patterns.** Apache-2.0, Java/JVM. **~300 components** covering databases, messaging (Kafka, JMS, AMQP), cloud services, and SaaS apps. Routes in **Java, YAML, or XML DSL**. Runs standalone, in Spring Boot/Quarkus, or as native image. **Trade-offs**: no bundled API management or commercial support—you operate it yourself. **Best for Java teams wanting the widest connectivity and pattern coverage** without per-vCore licensing. |
| **[Hubleto](https://github.com/hubleto/erp)** | [![Stars](https://img.shields.io/github/stars/hubleto/erp?style=social&color=white)](https://github.com/hubleto/erp/stargazers) | **Open-source PHP-based ERP and CRM development framework.** **Free community apps** covering contacts, calendar, leads, deals, orders, and project management. **React + TailwindCSS UI**, built-in user management, permissions, and CLI automation tools. **Fast learning curve with comprehensive dev guide**—install in minutes with `composer create-project` [citation:11]. **Best for PHP teams wanting a flexible ERP/CRM foundation** to build custom integrations without licensing fees. |
| **[Flowable](https://github.com/flowable/flowable-engine)** | [![Stars](https://img.shields.io/github/stars/flowable/flowable-engine?style=social&color=white)](https://github.com/flowable/flowable-engine/stargazers) | **Open-source BPMN workflow engine for multi-step, conditional business processes.** Apache-2.0. Model contract approvals, order-to-cash flows, and cross-system orchestration with **BPMN 2.0**. Embeddable in Java applications or deployed as a standalone service. **Best for teams needing workflow orchestration** between ERP, CRM, and CLM systems without a commercial iPaaS. |
| **[Spring Integration](https://github.com/spring-projects/spring-integration)** | [![Stars](https://img.shields.io/github/stars/spring-projects/spring-integration?style=social&color=white)](https://github.com/spring-projects/spring-integration/stargazers) | **Enterprise Integration Patterns inside the Spring ecosystem.** Lightweight messaging framework extending Spring's programming model with EIP components—channels, routers, transformers, and adapters. **Best when integrations live inside Spring Boot applications** and you want to stay within the Spring programming model. **Trade-off**: a library, not a product—no visual designer or managed hosting. |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Cameleer](https://github.com/pmsudhi/cameleer)** | [![Stars](https://img.shields.io/github/stars/pmsudhi/cameleer?style=social&color=white)](https://github.com/pmsudhi/cameleer/stargazers) | **Apache Camel's routes rewritten as a single native Rust binary.** **2.5 ms startup and 7 MB peak memory** vs. JVM Camel's 1.1 s and 399 MB. Runs Camel's YAML/XML DSLs unchanged with ~230 components. **Built-in MCP server** for AI agent tools. **Best for serverless, edge, and AI-agent integration scenarios** where JVM overhead is prohibitive. |
| **[Apache NiFi](https://github.com/apache/nifi)** | [![Stars](https://img.shields.io/github/stars/apache/nifi?style=social&color=white)](https://github.com/apache/nifi/stargazers) | **Open-source data flow automation with a graphical interface.** Visual processor-based design for routing, transforming, and mediating data between systems. **Provenance tracking** for data lineage. **Best for real-time data movement** between ERP/CRM systems where a visual interface matters more than code-first EIP patterns. |

**Frameworks for building custom systems**: Choose **Apache Camel** for the widest connectivity and EIP patterns in Java , **Hubleto** for an open-source ERP/CRM foundation to build custom integrations on , or **Flowable** for BPMN orchestration of cross-system approval workflows —all without per-vCore or per-task commercial licensing that compounds at scale.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- ERP/CRM integration platforms handle sensitive business data including financial records, customer PII, and contract terms; enforce least-privilege connector permissions, secret rotation, and audit logging for all integration flows.
- **Pricing models vary dramatically and hidden costs compound.** **MuleSoft's vCore model** often leaves 20–30% of committed capacity unused—right-sizing at renewal can save **$352,000/year** on 44 unused vCores at $8,000 each [citation:13]. **Premium connectors add 15–40%** and must be licensed per environment (prod, staging, test, sandbox, DR) [citation:13]. **Boomi sells API Management separately** and implementation adds **20–40%** of software cost [citation:3][citation:14]. **Workato's credits don't roll over**—unused Pro credits expire monthly [citation:4]. **Celigo's free plan is limited to 2 endpoints and 1 flow** with no SSO or on-prem agent [citation:10]. **Open-source alternatives eliminate per-connection fees but require engineering effort**: Apache Camel is mature but JVM-heavy , Hubleto provides an ERP/CRM foundation but requires PHP development , and Flowable handles orchestration but not data transformation . **Validate whether you need managed iPaaS (MuleSoft, Boomi, Workato) or a self-hosted framework (Camel, Hubleto)** before committing.

---

**Made for integration engineers, ERP architects, and organizations building enterprise connectivity.**  
Let's make ERP and CRM system integrations more open, governed, and cost-predictable.
