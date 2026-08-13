# Awesome-Synthetic-Data-Platform

## Top Synthetic Data Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Privacy-Preserving Synthetic Data Generation, Tabular & Multimodal Synthesis, and AI Training Data*
**Last updated: August 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Synthetic Data Platforms**. These tools generate realistic artificial datasets that preserve statistical properties and relationships of real data while eliminating privacy risks — supporting AI/ML training, testing, analytics, and secure data sharing.

**Examples** include Mostly AI, Tonic.ai, Gretel AI, Hazy, Synthea, Datomize, Betterdata, Twinify, MDClone, Mockaroo, Synthetaic, Statice, Syntho, Parallel Domain, YData, Rockfish Data, Rendered.ai, Cognata, and AI Reverie (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom model training, differential privacy, and open synthetic data pipelines — ideal for data scientists, privacy engineers, researchers, and developers building transparent, controllable synthetic data solutions.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

*Pricing and free-tier limits are as of August 2026 and may change — confirm with vendors. `(est.)` marks third-party estimates for vendors that do not publish list prices.*

| Platform | Description | Pricing | Free Tier Limit |
| --- | --- | --- | --- |
| **[Mostly AI](https://mostly.ai/)** | Enterprise synthetic data platform specializing in high-fidelity tabular data generation with strong privacy guarantees for regulated industries. | Marketplace plan from **$3,000/mo** (AWS); Team $3/credit; Enterprise $5/credit | Free forever — generate up to **100K rows/day** (2 credits/day, max 25/month) |
| **[Tonic.ai](https://www.tonic.ai/)** | Developer-focused platform for de-identifying production databases and generating realistic test/synthetic data with referential integrity. | Fabricate **Free $0/mo**; **Plus $29/mo** ($25 credits incl., PAYG after); Enterprise custom | Free — **$5 in monthly credits** (~9 complex generation sessions), no credit card |
| **[Gretel AI](https://gretel.ai/)** | Multi-modal synthetic data platform (tabular, text, time-series) with differential privacy, APIs, and developer-friendly workflows (now part of NVIDIA ecosystem in some contexts). | Team from **$295/mo** ($2.20/credit) | Developer free plan — **15 credits/mo** (~100K+ synthetic records or 2M transform records), 2 concurrent jobs, 1-hr runtime limit |
| **[Hazy](https://hazy.com/)** | Privacy-first synthetic data solution popular in financial services for complex tabular and time-series data with differential privacy. | Starter from **$500/mo** up to $2,000/mo; Enterprise custom (now offered via SAS Data Maker) | Free plan for new users — limited data rows/columns |
| **[Synthea](https://synthetichealth.github.io/synthea/)** | Open-source synthetic patient generator focused on realistic medical histories (also widely used commercially and in research). | **Free** (open-source, Apache 2.0) | Full features, unlimited use |
| **[Datomize](https://www.datomize.com/)** | Synthetic data platform for creating realistic customer and transactional datasets, especially for banking and AI model training. | Starter **$720/mo** billed annually ($800/mo monthly) — 160 credits/mo; Enterprise quote | Community — free forever, **40 credits/mo**, up to 20MB input |
| **[Betterdata](https://www.betterdata.ai/)** | Privacy-preserving synthetic data solution for AI development, data sharing, and product testing. | Not published — quote-based (enterprise contracts) | None (contact sales) |
| **[Twinify](https://github.com/DPBayes/twinify)** | Privacy-preserving synthetic data generation tool that creates statistical twins of sensitive datasets (open-source core with research focus). | **Free** (open-source, Apache 2.0) | Full features, unlimited use |
| **[MDClone](https://www.mdclone.com/)** | Healthcare-focused synthetic data platform enabling secure exploration and research on patient data without exposing real records. | Enterprise only — annual licensing est. from **$100K/year** (est.); no public list price | No public free tier (demo/trial on request) |
| **[Mockaroo](https://www.mockaroo.com/)** | Popular online tool for generating customizable mock/synthetic datasets for testing and development. | Silver **$60/yr** (100K rows/file, 1M records/day API); Gold $500/yr (10M rows/file); Enterprise $7,500/yr | Free forever — **1,000 rows/file**, 200 API requests/day |
| **[Synthetaic](https://www.synthetaic.com/)** | Synthetic data platform specializing in large-scale, high-quality data generation for computer vision and AI training. | Not published — feature-based pricing, no consumption charges (1-year license agreement) | None (platform evaluation period with license) |
| **[Statice](https://www.statice.ai/)** | Privacy-preserving synthetic data generation focused on structured data for analytics and machine learning (now part of Anonos). | From **3,990€/month** (per Slashdot) | Free version + free trial (per Slashdot) |
| **[Syntho](https://www.syntho.ai/)** | AI-powered synthetic data platform for generating privacy-safe, high-fidelity datasets for analytics and AI use cases. | Basic/Standard/Ultimate — quote-based (feature-based, no consumption charges) | Free trial; no permanent free plan |
| **[Parallel Domain](https://paralleldomain.com/)** | Synthetic data platform for autonomous systems, generating photorealistic 3D scenes, sensor data, and annotated datasets. | Not published — self-serve Data Lab API (subscription/usage-based) | None published (contact for access) |
| **[YData](https://ydata.ai/)** | Synthetic data and data quality platform supporting tabular, relational, and time-series generation with profiling and evaluation tools. | Pay-as-you-go **$1.00/credit** (1 credit = 1M data points or 10K tokens); Enterprise custom | Free plan — **1 free monthly credit**, all features included |
| **[Rockfish Data](https://www.rockfish.ai/)** | Synthetic data platform focused on privacy-preserving generation and data collaboration. | Not published — quote-based (enterprise) | Free trial — trial key / **30-day trial access** |
| **[Rendered.ai](https://rendered.ai/)** | Physics-based synthetic data generation for computer vision, remote sensing, and simulation environments. | Teams **$5,000/mo**; Organizations **$15,000/mo**; SDaaS project-based | Free trial available |
| **[Cognata](https://www.cognata.com/)** | Synthetic data and simulation platform for autonomous vehicles and advanced driver-assistance systems. | Not published — enterprise quote-based | Free DriveMatriX perception training dataset (no free platform tier) |
| **[AI Reverie](https://aireverie.com/)** | Synthetic data generation for computer vision and AI training using simulation and generative techniques. | Not published — enterprise/defense licensing (acquired by Meta, 2021) | None |

## Open-Source GitHub Projects
- **[Synthetic Data Vault (SDV)](https://github.com/sdv-dev/SDV)**  
  Leading open-source ecosystem for generating synthetic tabular, relational, and time-series data using statistical and deep learning models (CTGAN, TVAE, Gaussian Copula, etc.).

- **[CTGAN](https://github.com/sdv-dev/CTGAN)**  
  Conditional GAN implementation for high-quality synthetic tabular data generation, part of the SDV project.

- **[Synthcity](https://github.com/vanderschaarlab/synthcity)**  
  Comprehensive open-source library for synthetic data across modalities (static, time-series, survival) with privacy, fairness, and evaluation tools.

- **[ydata-synthetic](https://github.com/ydataai/ydata-synthetic)**  
  Python library offering GAN-based synthesizers (CTGAN, TimeGAN, etc.) for tabular and time-series data with Streamlit UI support.

- **[Gretel Synthetics](https://github.com/gretelai/gretel-synthetics)**  
  Open-source components from Gretel for LSTM/GAN-based synthetic data generation of tabular and sequential data.

- **[Synthea](https://github.com/synthetichealth/synthea)**  
  Open-source synthetic patient population generator that models realistic medical histories, conditions, and encounters.

- **[Twinify](https://github.com/DPBayes/twinify)**  
  Privacy-preserving software package for generating synthetic twins of sensitive datasets using differential privacy techniques.

- **[synthetic-data-generator (SDG)](https://github.com/hitsz-ids/synthetic-data-generator)**  
  Specialized framework for high-quality structured tabular data synthesis with efficient CTGAN implementations and evaluation metrics.

- **[Copulas](https://github.com/sdv-dev/Copulas)**  
  Library for modeling multivariate distributions using copulas, foundational for many statistical synthetic data approaches.

- **[SmartNoise / OpenDP](https://github.com/opendp/smartnoise-sdk)**  
  Differentially private open-source tools and synthesizers for generating privacy-preserving synthetic tabular data.

### Additional Strong Open-Source Options
- **[Faker](https://github.com/joke2k/faker)** and related libraries for rule-based mock data generation.
- **[DataSynthesizer](https://github.com/DataResponsibly/DataSynthesizer)** for differentially private synthetic data.
- Community **TimeGAN**, **DoppelGANger**, and **PrivBayes** implementations.
- Many **LLM-based synthetic data pipelines** (Distilabel, Magpie, etc.) for text and instruction data.
- Evaluation libraries such as **SDMetrics** for measuring synthetic data quality and privacy.

**Frameworks for building custom systems**: Combine **SDV / CTGAN / Synthcity** for core generation, **SmartNoise** for differential privacy, **SDMetrics** for evaluation, **Pandas + Scikit-learn** for preprocessing, and **Ollama** or local LLMs for generating synthetic text, labels, or complex multimodal datasets.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Synthetic data tools must be validated for statistical fidelity, privacy guarantees (e.g., differential privacy), and downstream utility before production use.
- Self-hosted open-source solutions require proper evaluation of leakage risks, model bias, and regulatory compliance (GDPR, HIPAA, etc.).

---
**Made for data scientists, privacy engineers, ML engineers, researchers, and organizations seeking safer data practices.**
Let's make synthetic data more open, high-quality, and privacy-preserving.
