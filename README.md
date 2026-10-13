# Awesome-Esg-Carbon-Accounting-Software

## Top ESG & Carbon Accounting Software Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Emissions Calculation, CSRD Reporting & Sustainability Data Management*  

**Last updated: March 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **ESG & Carbon Accounting Software**. These tools help organizations measure Scope 1, 2, and 3 emissions, prepare CSRD-aligned sustainability reports, manage ESG data collection, and track decarbonization progress.



**Examples** include Salesforce Net Zero Cloud, Persefoni, Watershed, Sweep, Plan A, Sinai Technologies, Greenly, Sphera, Emitwise, and Normative (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, transparent emissions calculation, and open ESG reporting — ideal for sustainability teams, compliance officers, and developers seeking auditable, vendor-independent carbon accounting.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Salesforce Net Zero Cloud](https://www.salesforce.com/products/net-zero-cloud/)**  

  Enterprise carbon accounting platform built on Salesforce. Features Scope 1/2/3 emissions tracking, supplier engagement, and CSRD-ready reporting with audit trails.



- **[Persefoni](https://persefoni.com/)**  

  Climate management and accounting platform (CMAP) for enterprises and financial institutions. Features PCAF-aligned financed emissions, CSRD compliance, and audit-ready reporting.



- **[Watershed](https://watershed.com/)**  

  Enterprise climate platform for carbon accounting, disclosure, and decarbonization. Features supplier data collection, CSRD/ISSB reporting, and clean energy procurement.



- **[Sweep](https://www.sweep.net/)**  

  Carbon and ESG data management platform. Features Scope 1/2/3 tracking, supplier engagement, CSRD reporting, and decarbonization planning.



- **[Plan A](https://plana.earth/)**  

  ESG and carbon accounting software for businesses. Features automated emissions calculation, CSRD/ESRS reporting, and net-zero target setting.



- **[Sinai Technologies](https://www.sinai.com/)**  

  Decarbonization platform for carbon-intensive industries. Features scenario analysis, marginal abatement cost curves, and CSRD compliance.



- **[Greenly](https://greenly.earth/)**  

  Carbon accounting platform for SMEs and mid-market. Features automated data collection, Scope 1/2/3 calculation, and CSRD-ready reporting.



- **[Sphera](https://sphera.com/)**  

  ESG performance and risk management platform. Features corporate and product carbon footprints, supply chain sustainability, and regulatory reporting.



- **[Emitwise](https://emitwise.com/)**  

  Carbon accounting and reporting platform for complex supply chains. Features Scope 3 mapping, CSRD compliance, and supplier engagement.



- **[Normative](https://normative.io/)**  

  Carbon accounting engine for enterprises. Features science-based targets, CSRD reporting, and full supply chain emissions tracking.



## Open-Source GitHub Projects



- **[OpenGHG Carbon Calculator](https://github.com/mindsongreen/OpenGHG)**

  Open-source, transparent carbon footprint calculator (license varies) designed for robust, auditable, and methodology-driven carbon inventories . Key principles include separation of data domains (activity data, emission factors, conversions, parameters), federated database architecture allowing customer-hosted sensitive data, explicit unit algebra, no black-box calculations, and full traceability from input to results. Backend PHP/PostgreSQL with HTML/JavaScript frontend .



- **[CarbonInk](https://github.com/lxzxl/carbonink)**

  Free, open-source, local-first GHG carbon accounting for desktop (MIT) . Features AI extraction from utility bills and receipts, ISO 14064-1 inventory reports, Scope 1/2/3 tracking with audit-grade calculation snapshots, and built-in MCP server for Claude/Cursor integration. Runs fully offline — data never leaves the device. macOS + Windows. No account, no cloud, no subscription .



- **[carbon-footprint-mcp](https://pypi.org/project/carbon-footprint-mcp/)**

  MCP server for calculating organizational carbon footprints from bank statements and financial exports using EPA GHG emission factors (MIT) . Runs 100% locally, sends no financial data to external APIs, stores no data by default. Computes Scope 1/2/3 emissions, scores carbon intensity by revenue/headcount, and generates HTML/Markdown reports. Works with Claude Desktop, Cursor, and other MCP clients .



- **[ESG-Report-Studio](https://github.com/SebastianDabkowski/ESG-Report-Studio)**

  ESG responsibility report platform (license TBD) supporting structured, controlled, and auditable ESG reporting . Treats ESG report as management and compliance artifact, not marketing document. Features reporting scope definition, report structure configuration, data collection/validation, ownership assignment, completeness tracking, assumptions documentation, and CSRD/ESRS mapping. Includes audit data retention policies and role-based access controls. In discovery/architecture phase .



- **[ESG-Copilot](https://github.com/omkardongre/ESG-Copilot)**

  AI-powered ESG compliance automation platform (MIT) with enterprise-grade security . Features 5 AI agents: Regulation Research, ESG Data Collection, Emissions Calculator (Scope 1/2/3 via Climatiq API), Report Generator (GRI/SASB/TCFD), and Chat Agent (permission-aware RAG). Auth0 integration with Token Vault, FGA Store for document-level authorization, and audit logging. Tech stack: Next.js 14, Node.js, LangChain.js, Google Gemini, BigQuery, Pinecone .



- **[ESG Reporting AI](https://github.com/shashank-dj/esg-reporting-ai)**

  AI-augmented ESG reporting platform (license varies) combining deterministic ESG calculations with grounded AI copilots for audit-ready, CSRD-aligned reporting . Features Scope 1/2 calculation, Scope 3 spend-based estimation, audit readiness scoring (0-100), CSRD/ESRS E1 mapping, GRI mapping, multi-framework coverage heatmap, AI Narrative Copilot with deterministic fallback, and ESG-to-financial impact analysis. Python/Streamlit tech stack .



- **[Lcpy](https://github.com/spirdgk/lcpy)**

  Open-source Python package for parametric and dynamic Life Cycle Assessment (LCA) and Life Cycle Costing (LCC) analysis (license varies) . Provides computational environment for developing parametric and dynamic LCA-LCC models integrated with process simulations. Supports uncertainty analysis, machine learning, and optimization libraries. Designed for process engineers, practitioners, and researchers familiar with Python .



- **[Activity Browser](https://github.com/LCA-ActivityBrowser/activity-browser)**

  Open-source GUI for Brightway2 LCA software (license varies) . Features fast LCA calculations for multiple reference flows and impact categories, parameter/scenario modeling, uncertainty analysis, Contribution analyses, Sankey Diagrams, Monte Carlo, and Global Sensitivity Analysis. Extensible via plugins. Version 3 beta supports Multi-functionality and Brightway 2.5 .



- **[Appa LCA](https://github.com/appalca)**

  Python framework (open-source) for integrating Life Cycle Assessment into design flows . Validated for ecodesign tool requirements. Facilitates implementation of new ecodesign strategies by making LCA integration into design flows more flexible and efficient. Code and case study data available on GitHub .



- **[pyteealca](https://gitlab.dlr.de/tt-tea/teeatool/pyteea-lca)**

  Python-based Life Cycle Assessment tool (license varies) developed at DLR (German Aerospace Center) . Object-oriented LCA framework with active development status. Documentation available via Zenodo .



- **[SCOOP Carbon Accounting Project](https://github.com/SCOOP-Carbon-Accounting)**

  Open-source carbon accounting project (license varies) using metrology discipline with the rigor of financial reporting frameworks . Supports IEEE standards efforts P7802 and P3469, translating scientific principles into practical projects. Presented at IEEE SusTech 2026 .



- **[WILMA](https://dinaopt.w-hs.de)**

  AI-supported assistance system for double materiality analysis (open-source from 2027) . Developed at Westfälische Hochschule for SMEs. Features structured preparation phase, guided analysis process, sustainability management modules, and automated documentation. Interactive tutorials, help icons, word search, and progress display. Tested with evaluation companies in Westmünsterland region. Free open-source solution from 2027 .



### Additional Strong Open-Source Options



- **[esrs-xbrl-parser](https://github.com/Climate-Action-Agency/esrs-xbrl-parser)** — Tools for parsing European Sustainability Reporting Standards (ESRS) taxonomies in XBRL format (TypeScript) .

- **[xBRL-Forge](https://github.com/antonheitz/xBRL-Forge)** — Open source iXBRL Report, xBRL Report and xBRL Taxonomy Generator (Python) .

- **[Open-Earth-Foundation/blockchain-carbon-accounting](https://github.com/Open-Earth-Foundation/blockchain-carbon-accounting)** — Fork of Hyperledger Labs blockchain carbon accounting (TypeScript/Python) .

- Community **n8n** workflows for ESG data collection automation and supplier engagement.



**Frameworks for building custom systems**: Combine **CarbonInk** or **OpenGHG Carbon Calculator** as the core emissions calculation engine with **ESG-Report-Studio** for CSRD-aligned reporting structure, **Lcpy** for product-level LCA analysis, **Activity Browser** for detailed life cycle assessment, and **PostgreSQL** for data persistence — creating a fully self-hosted, enterprise-grade ESG and carbon accounting platform.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- ESG and carbon accounting platforms handling sustainability data must comply with reporting regulations (CSRD, ESRS, GHG Protocol, ISO 14064, etc.).

- Self-hosted open-source solutions require proper validation of emission factors, methodology alignment, and ongoing maintenance. Regulatory compliance, legal sign-off, and external assurance remain the responsibility of the reporting organization and its appointed auditors .



---



**Made for sustainability teams, ESG analysts, compliance officers, and developers building transparent carbon accounting solutions.**  

Let's make ESG & Carbon Accounting more open, data-driven, and auditable.
