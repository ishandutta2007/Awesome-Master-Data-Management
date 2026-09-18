# Awesome-Master-Data-Management

## Top Master Data Management (MDM) Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Golden Records, Multi-Domain Master Data, Data Stewardship, Matching & Survivorship, Reference Data & Enterprise Data Governance*  

**Last updated: September 2026**



This repository tracks notable **SaaS / commercial platforms** and **open-source projects** for **Master Data Management (MDM)**. These systems create and maintain trusted “golden” records for critical business entities (customers, products, suppliers, locations, etc.), enforce data quality rules, support stewardship workflows, and distribute consistent master data across the enterprise.



**Examples** include Profisee, Reltio, Semarchy xDM, Ataccama, Informatica MDM, Stibo Systems (STEP), SAP Master Data Governance, IBM InfoSphere MDM, Talend MDM, EnterWorks / Precisely, TIBCO EBX, and related multi-domain MDM platforms (the category leaders).



**Open-source emphasis**: Enterprise MDM has historically been dominated by commercial vendors. Open-source options exist and continue to mature—led by **AtroCore**, **Yugandhar Open MDM Hub**, and **Fuyuko**—along with data-quality and integration building blocks. This section lists every significant relevant project found (note: many GitHub “MDM” results refer to *Mobile* Device Management, not Master Data Management).



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Reltio](https://www.reltio.com/)**  

  Cloud-native MDM and data unification platform focused on real-time golden records, identity resolution, relationship management, and AI-assisted data quality for multi-domain master data.



- **[Informatica MDM](https://www.informatica.com/)**  

  Enterprise MDM within the broader Intelligent Data Management Cloud, covering multi-domain mastering, data quality, integration, and governance at scale.



- **[Profisee](https://profisee.com/)**  

  Modern MDM platform emphasizing fast time-to-value, Microsoft ecosystem integration, and practical golden-record management for mid-market and enterprise use cases.



- **[Semarchy xDM](https://www.semarchy.com/)**  

  Smart Data Hub approach combining MDM, data integration, matching, stewardship, and governance with agile deployment characteristics.



- **[Ataccama, Stibo Systems (STEP), SAP MDG, IBM InfoSphere MDM](https://www.ataccama.com/)**  

  Established platforms for multi-domain MDM, product information management, data quality, and enterprise master-data governance.



- **[TIBCO EBX, EnterWorks / Precisely, Talend MDM](https://www.tibco.com/)**  

  Additional commercial solutions for reference data, product master data, multi-domain hubs, and data stewardship workflows.



- **[Other commercial MDM & data unification platforms](https://www.reltio.com/)**  

  Tools supporting customer, product, supplier, and location master data with matching, survivorship, and distribution capabilities.



## Open-Source GitHub Projects



- **[AtroCore](https://github.com/atrocore/atrocore)**  

  Open-source business application platform with ready-made solutions for Master Data Management (MDM), Product Information Management (PIM), and Digital Asset Management. Highly configurable data models, hierarchies, multi-language support, and golden-record style workflows (GPLv3 core).



- **[Yugandhar Open MDM Hub](https://github.com/yugandharproject/yugandhar-open-mdmhub)**  

  Open-source MDM hub project focused on Customer Data Integration (CDI) and multi-domain capabilities. Built with Spring/Hibernate, offers hundreds of pre-built services, and aims to provide a free alternative for master data management.



- **[Fuyuko](https://github.com/tmjeee/fuyuko)**  

  Open-source Master Data Management / Product Information Management application for managing product attributes, pricing, and related master data with a modern tech stack (LGPL).



- **[Other open MDM / PIM-oriented projects](https://github.com/search?q=%22master+data%22+OR+MDM+OR+PIM+golden+record)**  

  Community and research efforts aimed at golden records, product master data, and multi-domain data hubs (maturity varies).



- **[Data quality & matching open libraries](https://github.com/search?q=data+quality+OR+record+linkage+OR+entity+resolution)**  

  Open tools for deduplication, matching, survivorship logic, and data cleansing that form core building blocks of MDM solutions.



- **[Reference data & hierarchy management](https://github.com/search?q=reference+data+management+OR+hierarchy+management)**  

  Projects supporting controlled vocabularies, code sets, and hierarchical master data structures.



- **[Integration & pipeline open stacks](https://github.com/search?q=ETL+OR+data+integration+open+source)**  

  Open integration frameworks commonly used to feed and distribute master data to and from an MDM hub.



- **[Metadata & data catalog companions](https://github.com/search?q=data+catalog+OR+metadata+management+open+source)**  

  Tools that complement MDM by documenting data lineage, ownership, and business glossaries.



### Additional Strong Open-Source Options



- **AtroCore**: Most complete current open platform explicitly positioning MDM (and PIM/DAM) capabilities.

- **Yugandhar Open MDM Hub**: Service-oriented open MDM hub with substantial pre-built services.

- **Fuyuko**: Focused open MDM/PIM application for product-centric master data.

- **Composable stacks**: Open matching/entity-resolution libraries + workflow engines + databases + APIs for custom golden-record solutions.

- **Data quality first**: Many organizations start with open data-quality and matching tools before full MDM.

- Note: Avoid confusion with open-source *Mobile* Device Management (also abbreviated MDM).



**Frameworks for building custom systems**:  

**AtroCore**, **Yugandhar Open MDM Hub**, and **Fuyuko** are the strongest open-source starting points for Master Data Management / PIM-style hubs.  

Open data-quality, matching, and integration libraries provide additional building blocks.  

Commercial MDM platforms (Reltio, Informatica, Profisee, Semarchy, Ataccama, Stibo, SAP MDG, IBM, TIBCO EBX, etc.) deliver enterprise-scale matching engines, multi-domain models, stewardship UIs, AI-assisted data quality, governance workflows, and proven integration patterns that large organizations typically require.  

Mid-market and specialized teams may succeed with open platforms or hybrid approaches; complex multi-domain, regulated, or high-volume enterprise MDM usually relies on commercial solutions, sometimes augmented with open data-quality or catalog tools.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS/commercial or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Master data underpins critical business processes and analytics. Poor matching, incomplete survivorship rules, or weak governance can propagate errors across systems and decisions.

- Open-source MDM solutions offer transparency and no license fees but require expertise in data modeling, matching design, stewardship processes, integration, and ongoing data quality management. Evaluate scalability, security, compliance needs, and total cost of ownership carefully before production use.



---



**Made for data architects, master data stewards, data governance teams, and enterprise architects establishing trusted core data.**  

Let's expand open options for master data management while recognizing the matching sophistication, governance depth, and enterprise scale that leading commercial MDM platforms deliver.
