# Awesome-Synthetic-Data-Platform

## Top Supply Chain Sustainability Platforms



A curated list of leading platforms for supply chain sustainability, ESG risk and performance management, supplier due diligence, carbon/Scope 3 accounting, responsible sourcing, and regulatory compliance (CSDDD, LkSG, EUDR, etc.).  

**Primary focus: open-source software.**



Commercial / hosted platforms are listed separately for completeness. Open-source alternatives and community tools are emphasized throughout.



---



## SaaS / Hosted Platforms



| Platform | Description | Key Focus |

|----------|-------------|-----------|

| **[EcoVadis](https://ecovadis.com/)** | Leading provider of business sustainability ratings. Assesses suppliers on Environment, Labor & Human Rights, Ethics, and Sustainable Procurement with industry benchmarking and scorecards. | Supplier ESG ratings & benchmarking |

| **[IntegrityNext](https://www.integritynext.com/)** | Supply chain due diligence and ESG risk platform with automated risk detection, supplier engagement, regulatory coverage (CSDDD and more), and AI-driven supplier intelligence. | Due diligence & regulatory compliance |

| **[Assent](https://www.assent.com/)** | Supply chain sustainability and compliance platform helping manufacturers manage regulatory obligations, product compliance, and ESG data across complex supplier networks. | Product & supply chain compliance |

| **[Worldly](https://worldly.io/)** (formerly Higg) | Sustainability measurement platform widely used in apparel and consumer goods for environmental and social impact assessment across the value chain. | Industry impact measurement (apparel focus) |

| **[Prewave](https://www.prewave.com/)** | AI-powered supply chain risk and sustainability monitoring platform that detects risks from news, social, and other signals across multi-tier supply chains. | Real-time risk intelligence |

| **[Sedex](https://www.sedex.com/)** | Collaborative platform for sharing responsible sourcing data, audits, and sustainability performance among buyers and suppliers. | Responsible sourcing data sharing |

| **[Source Intelligence](https://www.sourceintelligence.com/)** | Supply chain compliance and ESG data management platform focused on regulations (PFAS, REACH, RoHS, EUDR, conflict minerals, etc.) with automation and supplier engagement. | Regulatory compliance & materials data |

| **[Achilles](https://www.achilles.com/)** | Supplier management and sustainability platform providing qualification, risk assessment, and ESG performance insights for procurement teams. | Supplier qualification & risk |

| **[Intertek Inform](https://www.intertek.com/)** | Assurance, testing, and supply chain sustainability solutions including audit programs, risk tools, and compliance support. | Assurance & audit-driven sustainability |

| **[osapiens HUB](https://osapiens.com/)** | Supplier intelligence and compliance platform supporting due diligence (LkSG, EUDR, etc.), onboarding, risk monitoring, and multi-tier transparency. | Supplier intelligence & due diligence |



---



## Open-Source Softwares



Fully featured commercial-grade supplier ESG rating networks and multi-tier due diligence platforms are scarce in pure open source. Stronger open-source building blocks exist for carbon accounting (especially Scope 3), emissions reporting, sustainable finance tools, and ERP-integrated sustainability modules.



### Core Frameworks & Sustainability Platforms



| Project | Description | License | Notes |

|---------|-------------|---------|-------|

| **[blockchain-carbon-accounting](https://github.com/hyperledger-labs/blockchain-carbon-accounting)** (Hyperledger) | Open-source blockchain applications for climate action and accounting: emissions calculations, carbon trading, validation of climate claims, and supply-chain decarbonization components. | Open source | Climate & carbon accounting on ledger |

| **Carbon accounting toolkits** | Open-source AI agents and MCP toolkits for auditable Scope 1/2/3 carbon accounting, emission factor matching, data quality scoring, and decarbonization workflows. | Apache-2.0 / various | Scope 3 & audit-ready carbon tools |

| **[Sustainability Odoo modules](https://github.com/sustainability-suite/sustainability-odoo)** | Open-source Odoo modules for CO₂e tracking, GHG Protocol-aligned accounting, CSRD-related features, emission factors, and sustainability reporting integrated with ERP. | AGPL-3.0 | ERP-native sustainability |

| **Supply chain sustainability reporting projects** | Python-based open projects for calculating and reporting distribution-network or logistics CO₂ emissions, often with Power BI or dashboard examples. | Various | Practical emissions reporting |

| **OS-Climate & sustainable finance tools** | Open-source initiatives for climate-smart investing, risk management, and ESG data handling (part of broader sustainable finance ecosystems). | Open source | Climate risk & finance |

| **Open supply chain visualization** | Open codebases for visualizing and analyzing supply chains (e.g., Sourcemap-related open components). | Various | Transparency & mapping |



### Specialized Libraries & Related Tools



| Project | Description | Focus Area |

|---------|-------------|---------|

| **Emission factor databases & calculators** | Open libraries and datasets for GHG emission factors, activity-based calculations, and Scope 3 category support. | Carbon calculation |

| **Input-output & LCA tools** | Open economic input-output and life-cycle assessment packages for estimating supply-chain impacts. | Impact estimation |

| **ESG data & reporting frameworks** | Open resources and code for aligning with CSRD/ESRS, GHG Protocol, and related disclosure standards. | Regulatory reporting |

| **Risk & news monitoring prototypes** | Open NLP and scraping approaches for basic supplier risk signal detection (far less mature than commercial AI platforms). | Risk signals |

| **ERP & procurement integrations** | Modules and connectors for Odoo, ERPNext, and similar systems to track sustainability attributes of purchases and suppliers. | Operational integration |

| **Dashboarding** | Metabase, Apache Superset, or Grafana on top of emissions and supplier data for internal sustainability scorecards. | Visualization & KPIs |



### Additional Notable Open-Source Tools



- **Self-hosted carbon accounting** — Combine open Scope 1/2/3 engines with internal activity data for auditable inventories.

- **ERP sustainability extensions** — Use Odoo sustainability modules or similar ERPNext customizations for operational CO₂ tracking.

- **Blockchain pilots** — Experiment with Hyperledger-based carbon accounting and tokenized claims for transparency projects.

- **Reporting pipelines** — Python + open BI stacks for logistics, procurement, and product-level emissions reports.

- **Data standards & taxonomies** — Open alignment with GHG Protocol, product category rules, and emerging digital product passport concepts.

- **Hybrid approaches** — Many organizations use commercial platforms (EcoVadis, IntegrityNext, etc.) for supplier ratings and due diligence while running open-source tools for internal carbon accounting and custom reporting.



**Note:** Commercial platforms dominate supplier ESG ratings, multi-tier due diligence, regulatory content libraries, audit networks, and real-time risk intelligence because these require large supplier networks, proprietary data, and continuous regulatory updates. Open-source strength lies in carbon accounting, emissions calculation engines, ERP-integrated sustainability modules, and transparent reporting pipelines that organizations fully control.



---



## Quick Start Recommendations



| Goal | Recommended Starting Point |

|------|---------------------------|

| Open-source carbon / climate accounting | **blockchain-carbon-accounting** or dedicated Scope 1/2/3 toolkits |

| ERP-integrated CO₂ & sustainability | **Sustainability Odoo modules** |

| Practical logistics emissions reporting | Community Python supply-chain sustainability projects |

| Supplier ESG ratings & benchmarking | **EcoVadis** |

| Supply chain due diligence & CSDDD | **IntegrityNext** or **osapiens HUB** |

| Product & regulatory compliance | **Assent** or **Source Intelligence** |

| Real-time multi-tier risk signals | **Prewave** |

| Responsible sourcing data sharing | **Sedex** |

| Apparel / consumer goods impact | **Worldly** |

| Supplier qualification & risk | **Achilles** |



---



## Contributing



Contributions, corrections, and new open-source projects are welcome.  

Please open an issue or pull request.



---



**Last updated:** August 2026  

Emphasizing open-source tools while documenting the major commercial platforms for context. Fully featured open-source supplier ESG rating and due-diligence networks remain limited; the strongest open options focus on carbon accounting, Scope 3 calculation, ERP sustainability modules, and transparent reporting pipelines. Commercial platforms lead in network-scale supplier ratings, regulatory coverage, and risk intelligence.
