# Awesome-Cloud-Sustainability-Platform

# Top Cloud Sustainability Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Carbon Accounting, GHG Protocol Reporting, CSRD Compliance & ESG Data Management*  
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Cloud Sustainability**. These tools help organizations measure, manage, and report greenhouse gas (GHG) emissions across Scopes 1, 2, and 3, comply with CSRD and GHG Protocol standards, and drive decarbonization initiatives.

**Examples** include Watershed, IBM Envizi, Microsoft Cloud for Sustainability, Greenly, Normative, Plan A, Sweep, Persefoni, Salesforce Net Zero Cloud, and SINAI Technologies (the category leaders).

**Open-source emphasis**: Cloud sustainability is a **commercially dominated category**, but a **growing open-source foundation exists** for carbon accounting and energy management. **MyEMS** is the industry-leading open-source energy management system with nearly a thousand project cases, ISO 50001 alignment, and carbon emissions reporting . **OpenGHG** provides a transparent, auditable carbon footprint calculator with explicit unit algebra and no black-box calculations . **GreenOps** delivers a full-stack ESG carbon accounting platform with audit trails and drag-and-drop report building . **Re-Emission** is a peer-reviewed Python library for reservoir GHG emissions . This section documents these production-grade solutions.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Watershed](https://watershed.com/)**
  Climate-first enterprise carbon accounting platform. Manages 3 gigatonnes of emissions. Features AI-assisted disclosure drafting, CDP API submission, strong data ingestion and quality controls, and broad ESG metric support.

- **[IBM Envizi](https://www.ibm.com/products/envizi)**
  Enterprise ESG data management and carbon accounting platform. 15 years of market experience, 247k connected locations, 200+ customers, 150 countries reached . Named a Leader in Verdantix Green Quadrant 2026. **Emissions API** provides standardized GHG Protocol-aligned calculations . IBM used Envizi to consolidate sustainability data from TRIERGA and Maximo into a single auditable system of record, reducing reporting costs by 30% and driving emissions reduction of 61.6% in 2022 .

- **[Microsoft Cloud for Sustainability](https://www.microsoft.com/en-us/sustainability/cloud)**
  Microsoft's enterprise sustainability platform built on Dynamics 365 and Power Platform. Provides carbon accounting across Scopes 1-3, standardized data models, and real-time sustainability data capture.

- **[Greenly](https://greenly.earth/)**
  User-friendly carbon accounting and product lifecycle assessment (LCA) tools. Pricing starts at $1,950/year. Good for smaller organizations early in their sustainability journey.

- **[Normative](https://normative.io/)**
  Integrated carbon accounting platform. Strong for supplier engagement, product carbon footprint (PCF) management, and financed emissions tracking.

- **[Plan A](https://plana.earth/)**
  Carbon accounting platform for EU decarbonization-first teams. Climate-first with regulatory mapping for CSRD/ISSB.

- **[Sweep](https://www.sweep.net/)**
  Sustainability intelligence platform with "report once, file everywhere" multi-framework mapping (CSRD, ISSB, GRI, CDP, SASB, TCFD, SB 253/261, UK SRS). Audit-ready filing with full data lineage.

- **[Persefoni](https://www.persefoni.com/)**
  Climate management and accounting platform. Best free on-ramp with Pro covering Scopes 1-3. Strong financed emissions capabilities (PCAF-aligned).

- **[Salesforce Net Zero Cloud](https://www.salesforce.com/)**
  Carbon accounting and ESG reporting platform integrated with Salesforce. Provides emissions tracking, supplier engagement, and regulatory reporting.

- **[SINAI Technologies](https://www.sinaitechnologies.com/)**
  Decarbonization platform for enterprise and financial institutions. Provides emissions measurement, scenario analysis, and abatement planning.

## Open-Source GitHub Projects

### Energy & Carbon Management Systems

- **[MyEMS](https://github.com/MyEMS/myems)**
  **The industry-leading open-source energy management system.** **v6.8.0** with **nearly a thousand project cases** and **CMA testing certification** . Aligned with **ISO 50001** (GB/T 23331-2020) energy management standard. **Core capability**: Collects, analyzes, and reports energy and carbon emissions for **electricity, water, gas, cooling, and heating** across buildings, factories, shopping malls, hospitals, parks, and energy-carbon management centers . **Enterprise options**: photovoltaics, energy storage, charging piles, microgrids, virtual power plants, equipment control, fault diagnosis, work order management, and AI optimization . **Architecture**: Python API, ReactJS Admin UI, AngularJS Web UI, Modbus TCP acquisition service, cleaning/normalization/aggregation services . **Commitment to permanent open source** with monthly small releases and annual major releases . Default Admin password: `!MyEMS1`.

### Carbon Accounting & Footprint Calculators

- **[OpenGHG](https://github.com/mindsongreen/OpenGHG)**
  **Transparent, auditable carbon footprint calculator for robust, methodology-driven carbon inventories.** **Key principles**: Separation of data domains (activity data, emission factors, conversions, parameters); **federated database architecture** allowing customer-hosted sensitive data; explicit unit and pair-of-units algebra; **no black-box calculations**; full traceability from input to results . **What it does**: Structured carbon calculations using calculation tabs; user-defined mapping and scopes; explicit formulas and unit algebra; line results, sub-totals, and tab totals . **What it does not do**: Does not prescribe how to map activities; does not automate scoping decisions; does not hide assumptions . **Architecture**: PHP (PDO, PostgreSQL) backend; HTML/JavaScript frontend . **Open source**.

- **[GreenOps](https://github.com/cherryaugusta/greenops-carbon-accounting-platform)**
  **Full-stack ESG carbon accounting platform.** Django 5.2 + Django REST Framework + React + TypeScript + Docker . **Features**: Employee carbon logging (travel and energy); automatic CO₂e calculation using emission factors; manager approval workflow via Django Admin; **full audit trail** of carbon log changes (django-simple-history); JWT-secured API; Swagger UI and ReDoc documentation; dashboard with charts and KPI summaries; multi-step validated form; **drag-and-drop report builder**; request latency logging middleware . **Tech stack**: PostgreSQL, Redis, Docker Compose . **Demo credentials**: Manager `Admin123!`, Employee `Employee123!`. **Portfolio-grade**, production-oriented internal reporting system reference.

### Product Carbon Footprint & LCA

- **[Re-Emission](https://github.com/)]**
  **Free, open-source Python library for estimating, visualizing, and reporting reservoir GHG emissions.** **GNU GPL v3.0** . **G-res framework**: Reports gross and net emissions integrated over 100-year horizon, with emission trajectories from impoundment year . **Implements**: G-res model (validated against G-res Tool v3.31), two reservoir phosphorus retention models, nitrogen and phosphorus land export model, two nitrous oxide emission models . **Integration**: Works with **GeoCARET** for automated regional-to-national scale emission inventories using spatially explicit models . **Docker execution** available. Applied to ~250 reservoirs in Myanmar and United Kingdom .

- **[ESG-Cradle to Gate](https://www.mdpi.com/2225-1154/14/1/26)**
  **User-friendly digital cradle-to-gate LCA tool for SMEs.** Calculates product-specific carbon footprints based on **ISO 14040/14044** and **CSRD guidelines** . **Database**: 622 precise emission factors from curated open-source databases (Climate Compass, AUS LCI, Climatiq) plus 4,378 non-curated factors from BONSAI . **Input panels**: Materials (raw materials, quantity, emission factors); Transportation (supplier distance, transport method); Processing (machine energy consumption) . **Freely accessible**, supports SMEs in establishing reliable emission inventories and identifying reduction priorities .

### AI-Powered ESG Reporting

- **[ESG Reporting AI](https://github.com/shashank-dj/esg-reporting-ai)**
  **AI-augmented ESG reporting platform with CSRD alignment and audit readiness scoring.** **Core capabilities**: Scope 1 & 2 emissions calculation; Scope 3 spend-based estimation; energy consumption tracking; facility-wise time-series analytics . **Audit intelligence**: ESG audit readiness scoring (0-100); data quality validation (missing data, range validation, cross-facility consistency); explainable audit logic . **CSRD alignment**: ESRS E1 mapping; GRI mapping; multi-framework coverage heatmap; CSRD gap analysis report . **AI copilots**: AI Narrative Copilot (grounded strictly in reported ESG data); AI Audit Risk Explainer; rate-limited, cost-controlled . **Tech stack**: Python, Streamlit, Pandas/NumPy, Plotly, OpenAI GPT-4o-mini .

### Additional Strong Open-Source Options

- **Energy & Carbon Management**: **MyEMS** (industry-leading, ISO 50001, nearly 1000 cases) .
- **Carbon Accounting**: **OpenGHG** (transparent, auditable, federated databases) , **GreenOps** (full-stack, audit trails, report builder) .
- **Product Footprint**: **Re-Emission** (GPL v3, reservoir emissions) , **ESG-Cradle to Gate** (ISO 14040/14044, SME-focused) .
- **AI ESG Reporting**: **ESG Reporting AI** (CSRD alignment, audit scoring, AI copilots) .
- **SME Digital Tools**: **EFRAG VSME** digital template and XBRL taxonomy (free, open-source for non-listed SMEs) .

**Frameworks for building custom systems**: Combine **MyEMS** for energy data collection and carbon emissions reporting across facilities, **OpenGHG** for transparent, auditable carbon calculations, **GreenOps** for full-stack ESG reporting with audit trails, and **Re-Emission** or **ESG-Cradle to Gate** for product-specific carbon footprints. Add **PostgreSQL** for persistence and **Docker** for deployment.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Cloud sustainability platforms handle sensitive emissions and supply chain data; ensure compliance with GHG Protocol, ISO 14064, CSRD, ISSB, and relevant regional disclosure regulations.
- **Open-source reality**: The open-source ecosystem for cloud sustainability is **developing but not yet equivalent to commercial platforms**. **MyEMS** provides production-grade energy management with nearly 1,000 project cases and ISO 50001 alignment . **OpenGHG** delivers transparent, auditable carbon accounting with no black-box calculations . **GreenOps** offers full-stack ESG reporting with audit trails . **Re-Emission** and **ESG-Cradle to Gate** provide rigorous product carbon footprint tools . However, **commercial platforms** (Watershed, IBM Envizi, Sweep, Persefoni) provide **deeper multi-framework mapping, supplier engagement at scale, and audit-ready workflows** that open-source alternatives cannot match without significant institutional investment. The open-source path is most viable for **energy management**, **transparent carbon calculations**, or **organizations with strong engineering capacity** seeking full data sovereignty.

---

**Made for sustainability managers, ESG analysts, carbon accountants, and corporate climate teams.**
Let's make cloud sustainability more open, transparent, and auditable.
