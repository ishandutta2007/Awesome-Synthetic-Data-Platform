<!--
  SEO meta-description: Curated list of the best synthetic data platforms, synthetic data generation tools, and open-source synthetic data GitHub projects for privacy-preserving AI training, test data generation, and analytics.
  SEO keywords: synthetic data, synthetic data platform, synthetic data generation, synthetic data tools, generative AI, privacy-preserving data, differential privacy, tabular data synthesis, multimodal synthetic data, AI training data, fake data generator, test data generation, data anonymization
-->

# 🚀 Awesome Synthetic Data Platform

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Privacy-Preserving Synthetic Data Generation, Tabular & Multimodal Synthesis, and AI Training Data*
**Last updated: August 2026**

<div align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a>
  <a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</div>

<br/>

<p align="center">
  <img src="assets/banner.svg" alt="Awesome Synthetic Data Platform banner — curated list of SaaS platforms and open-source projects for privacy-preserving synthetic data generation" width="100%">
</p>

## 📖 About This List

This repository tracks notable **SaaS platforms** and **open-source projects** for **synthetic data platforms**. These tools generate realistic artificial datasets that preserve the statistical properties and relationships of real data while eliminating privacy risks — supporting **AI/ML training**, **testing**, **analytics**, and secure data sharing.

**Examples** 🏆 include Mostly AI, Tonic.ai, Gretel AI, Hazy, Synthea, Datomize, Betterdata, Twinify, MDClone, Mockaroo, Synthetaic, Statice, Syntho, Parallel Domain, YData, Rockfish Data, Rendered.ai, Cognata, and AI Reverie (the category leaders).

**Open-source emphasis** 🧰: This section is heavily expanded with every major active project for self-hosting, custom model training, differential privacy, and open synthetic data pipelines — ideal for data scientists, privacy engineers, researchers, and developers building transparent, controllable synthetic data solutions.

Contributions welcome! 🎉 Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## 🗂️ Table of Contents

- [SaaS/Hosted Platforms](#-saashosted-platforms)
- [Open-Source GitHub Projects](#-open-source-github-projects)
- [How to Contribute](#-how-to-contribute)
- [Disclaimer](#-disclaimer)
- [Star History](#-star-history)

## ☁️ SaaS/Hosted Platforms

*Pricing and free-tier limits are as of August 2026 and may change — confirm with vendors. `(est.)` marks third-party estimates for vendors that do not publish list prices. **Company Size** shows the best-known figure per vendor — acquisition price, valuation, or total funding raised — and rows are sorted by company size, **descending**.*

| Platform | Company Size (Valuation / Revenue / Funding) | Description | Pricing | Free Tier Limit |
| --- | --- | --- | --- | --- |
| **[Gretel AI](https://gretel.ai/)** | **~$350M** — acquired by NVIDIA (2025) | Multi-modal synthetic data platform (tabular, text, time-series) with differential privacy, APIs, and developer-friendly workflows (acquired by NVIDIA, 2025). | Team from **$295/mo** ($2.20/credit) | Developer free plan — **15 credits/mo** (~100K+ synthetic records or 2M transform records), 2 concurrent jobs, 1-hr runtime limit |
| **[MDClone](https://www.mdclone.com/)** | **$104M** raised | Healthcare-focused synthetic data platform enabling secure exploration and research on patient data without exposing real records. | Enterprise only — annual licensing est. from **$100K/year** (est.); no public list price | No public free tier (demo/trial on request) |
| **[Parallel Domain](https://paralleldomain.com/)** | **~$77M** valuation | Synthetic data platform for autonomous systems, generating photorealistic 3D scenes, sensor data, and annotated datasets. | Not published — self-serve Data Lab API (subscription/usage-based) | None published (contact for access) |
| **[Hazy](https://hazy.com/)** | **~$45M** (est.) — acquired by SAS (2024) | Privacy-first synthetic data solution popular in financial services for complex tabular and time-series data with differential privacy. | Starter from **$500/mo** up to $2,000/mo; Enterprise custom (now offered via SAS Data Maker) | Free plan for new users — limited data rows/columns |
| **[Synthetaic](https://www.synthetaic.com/)** | **~$36M** raised | Synthetic data platform specializing in large-scale, high-quality data generation for computer vision and AI training. | Not published — feature-based pricing, no consumption charges (1-year license agreement) | None (platform evaluation period with license) |
| **[Mostly AI](https://mostly.ai/)** | **~$31M** raised | Enterprise synthetic data platform specializing in high-fidelity tabular data generation with strong privacy guarantees for regulated industries. | Marketplace plan from **$3,000/mo** (AWS); Team $3/credit; Enterprise $5/credit | Free forever — generate up to **100K rows/day** (2 credits/day, max 25/month) |
| **[Cognata](https://www.cognata.com/)** | **~$25M** raised | Synthetic data and simulation platform for autonomous vehicles and advanced driver-assistance systems. | Not published — enterprise quote-based | Free DriveMatriX perception training dataset (no free platform tier) |
| **[Tonic.ai](https://www.tonic.ai/)** | **~$18M** revenue (est.); **$45M** raised | Developer-focused platform for de-identifying production databases and generating realistic test/synthetic data with referential integrity. | Fabricate **Free $0/mo**; **Plus $29/mo** ($25 credits incl., PAYG after); Enterprise custom | Free — **$5 in monthly credits** (~9 complex generation sessions), no credit card |
| **[Datomize](https://www.datomize.com/)** | **~$12M** raised (as DataWizz) | Synthetic data platform for creating realistic customer and transactional datasets, especially for banking and AI model training. | Starter **$720/mo** billed annually ($800/mo monthly) — 160 credits/mo; Enterprise quote | Community — free forever, **40 credits/mo**, up to 20MB input |
| **[Rendered.ai](https://rendered.ai/)** | **$6M** raised | Physics-based synthetic data generation for computer vision, remote sensing, and simulation environments. | Teams **$5,000/mo**; Organizations **$15,000/mo**; SDaaS project-based | Free trial available |
| **[Rockfish Data](https://www.rockfish.ai/)** | **~$6M** raised | Synthetic data platform focused on privacy-preserving generation and data collaboration. | Not published — quote-based (enterprise) | Free trial — trial key / **30-day trial access** |
| **[AI Reverie](https://aireverie.com/)** | **~$6M** raised (acquired by Meta, 2021) | Synthetic data generation for computer vision and AI training using simulation and generative techniques. | Not published — enterprise/defense licensing | None |
| **[YData](https://ydata.ai/)** | **~$3M** raised | Synthetic data and data quality platform supporting tabular, relational, and time-series generation with profiling and evaluation tools. | Pay-as-you-go **$1.00/credit** (1 credit = 1M data points or 10K tokens); Enterprise custom | Free plan — **1 free monthly credit**, all features included |
| **[Betterdata](https://www.betterdata.ai/)** | **~$1.7M** raised | Privacy-preserving synthetic data solution for AI development, data sharing, and product testing. | Not published — quote-based (enterprise contracts) | None (contact sales) |
| **[Syntho](https://www.syntho.ai/)** | **~$1.2M** raised | AI-powered synthetic data platform for generating privacy-safe, high-fidelity datasets for analytics and AI use cases. | Basic/Standard/Ultimate — quote-based (feature-based, no consumption charges) | Free trial; no permanent free plan |
| **[Statice](https://www.statice.ai/)** | **Small** (acquired by Anonos, 2022) | Privacy-preserving synthetic data generation focused on structured data for analytics and machine learning (now part of Anonos). | From **3,990€/month** (per Slashdot) | Free version + free trial (per Slashdot) |
| **[Mockaroo](https://www.mockaroo.com/)** | **Bootstrapped** — ~$1–5M revenue (est.) | Popular online tool for generating customizable mock/synthetic datasets for testing and development. | Silver **$60/yr** (100K rows/file, 1M records/day API); Gold $500/yr (10M rows/file); Enterprise $7,500/yr | Free forever — **1,000 rows/file**, 200 API requests/day |
| **[Synthea](https://synthetichealth.github.io/synthea/)** | **N/A** — open-source | Open-source synthetic patient generator focused on realistic medical histories (also widely used commercially and in research). | **Free** (open-source, Apache 2.0) | Full features, unlimited use |
| **[Twinify](https://github.com/DPBayes/twinify)** | **N/A** — open-source | Privacy-preserving synthetic data generation tool that creates statistical twins of sensitive datasets (open-source core with research focus). | **Free** (open-source, Apache 2.0) | Full features, unlimited use |

## 🧪 Open-Source GitHub Projects

> ⭐ Star badges are live (via shields.io) and link to each repository's **stargazers** page. Repos are sorted by GitHub stars, **descending**.

- **[Faker](https://github.com/joke2k/faker)** [![GitHub stars](https://img.shields.io/github/stars/joke2k/faker?style=social&color=white)](https://github.com/joke2k/faker/stargazers) — Python package that generates fake data for you, widely used to populate test databases and mock datasets.
- **[CARLA Simulator](https://github.com/carla-simulator/carla)** [![GitHub stars](https://img.shields.io/github/stars/carla-simulator/carla?style=social&color=white)](https://github.com/carla-simulator/carla/stargazers) — Open-source simulator for autonomous driving research and synthetic sensor data generation (cameras, LiDAR, radar) for training perception models.
- **[ydata-profiling](https://github.com/ydataai/ydata-profiling)** [![GitHub stars](https://img.shields.io/github/stars/ydataai/ydata-profiling?style=social&color=white)](https://github.com/ydataai/ydata-profiling/stargazers) — One-line-of-code data quality profiling and exploratory data analysis for Pandas and Spark DataFrames.
- **[Mimesis](https://github.com/lk-geimfari/mimesis)** [![GitHub stars](https://img.shields.io/github/stars/lk-geimfari/mimesis?style=social&color=white)](https://github.com/lk-geimfari/mimesis/stargazers) — High-performance fake data generator for Python supporting 47 locales, ideal for testing and schema-based generation.
- **[Synthetic Data Vault (SDV)](https://github.com/sdv-dev/SDV)** [![GitHub stars](https://img.shields.io/github/stars/sdv-dev/SDV?style=social&color=white)](https://github.com/sdv-dev/SDV/stargazers) — Leading open-source ecosystem for generating synthetic tabular, relational, and time-series data using statistical and deep learning models (CTGAN, TVAE, Gaussian Copula, etc.).
- **[Distilabel](https://github.com/argilla-io/distilabel)** [![GitHub stars](https://img.shields.io/github/stars/argilla-io/distilabel?style=social&color=white)](https://github.com/argilla-io/distilabel/stargazers) — Framework for building fast, reliable, scalable LLM-based synthetic data and AI feedback pipelines based on verified research papers.
- **[Synthea](https://github.com/synthetichealth/synthea)** [![GitHub stars](https://img.shields.io/github/stars/synthetichealth/synthea?style=social&color=white)](https://github.com/synthetichealth/synthea/stargazers) — Open-source synthetic patient population generator that models realistic medical histories, conditions, and encounters.
- **[synthetic-data-generator (SDG)](https://github.com/hitsz-ids/synthetic-data-generator)** [![GitHub stars](https://img.shields.io/github/stars/hitsz-ids/synthetic-data-generator?style=social&color=white)](https://github.com/hitsz-ids/synthetic-data-generator/stargazers) — Specialized framework for generating high-quality structured tabular data with efficient CTGAN implementations and evaluation metrics.
- **[GenerateData](https://github.com/benkeen/generatedata)** [![GitHub stars](https://img.shields.io/github/stars/benkeen/generatedata?style=social&color=white)](https://github.com/benkeen/generatedata/stargazers) — Powerful, feature-rich random test data generator engine (the code behind generatedata.com) with 30+ data types and 12 export formats.
- **[ydata-synthetic](https://github.com/ydataai/ydata-synthetic)** [![GitHub stars](https://img.shields.io/github/stars/ydataai/ydata-synthetic?style=social&color=white)](https://github.com/ydataai/ydata-synthetic/stargazers) — Python library offering GAN-based synthesizers (CTGAN, TimeGAN, DoppelGANger, etc.) for tabular and time-series data with Streamlit UI support.
- **[CTGAN](https://github.com/sdv-dev/CTGAN)** [![GitHub stars](https://img.shields.io/github/stars/sdv-dev/CTGAN?style=social&color=white)](https://github.com/sdv-dev/CTGAN/stargazers) — Conditional GAN implementation for high-quality synthetic tabular data generation, part of the SDV project.
- **[Gretel Synthetics](https://github.com/gretelai/gretel-synthetics)** [![GitHub stars](https://img.shields.io/github/stars/gretelai/gretel-synthetics?style=social&color=white)](https://github.com/gretelai/gretel-synthetics/stargazers) — Open-source components from Gretel for LSTM/GAN-based synthetic data generation of tabular and sequential data, including a PyTorch DoppelGANger.
- **[Synthcity](https://github.com/vanderschaarlab/synthcity)** [![GitHub stars](https://img.shields.io/github/stars/vanderschaarlab/synthcity?style=social&color=white)](https://github.com/vanderschaarlab/synthcity/stargazers) — Comprehensive open-source library for synthetic data across modalities (static, time-series, survival) with privacy, fairness, and evaluation tools.
- **[Copulas](https://github.com/sdv-dev/Copulas)** [![GitHub stars](https://img.shields.io/github/stars/sdv-dev/Copulas?style=social&color=white)](https://github.com/sdv-dev/Copulas/stargazers) — Library for modeling multivariate distributions using copulas, foundational for many statistical synthetic data approaches.
- **[DoppelGANger](https://github.com/fjxmlzn/DoppelGANger)** [![GitHub stars](https://img.shields.io/github/stars/fjxmlzn/DoppelGANger?style=social&color=white)](https://github.com/fjxmlzn/DoppelGANger/stargazers) — GAN-based framework for generating high-fidelity synthetic time-series datasets with metadata (IMC 2020 Best Paper Finalist).
- **[SmartNoise / OpenDP](https://github.com/opendp/smartnoise-sdk)** [![GitHub stars](https://img.shields.io/github/stars/opendp/smartnoise-sdk?style=social&color=white)](https://github.com/opendp/smartnoise-sdk/stargazers) — Differentially private open-source tools and synthesizers for generating privacy-preserving synthetic tabular data.
- **[DataSynthesizer](https://github.com/DataResponsibly/DataSynthesizer)** [![GitHub stars](https://img.shields.io/github/stars/DataResponsibly/DataSynthesizer?style=social&color=white)](https://github.com/DataResponsibly/DataSynthesizer/stargazers) — Differentially private synthetic data generation tool for tabular datasets with attribute analysis and correlation preservation.
- **[SDMetrics](https://github.com/sdv-dev/SDMetrics)** [![GitHub stars](https://img.shields.io/github/stars/sdv-dev/SDMetrics?style=social&color=white)](https://github.com/sdv-dev/SDMetrics/stargazers) — Metrics library to evaluate the quality and efficacy of synthetic datasets (statistical similarity, ML efficacy, privacy).
- **[RDT (Reversible Data Transforms)](https://github.com/sdv-dev/RDT)** [![GitHub stars](https://img.shields.io/github/stars/sdv-dev/RDT?style=social&color=white)](https://github.com/sdv-dev/RDT/stargazers) — Library of reversible data transforms for turning raw data into machine-learning-ready formats.
- **[Twinify](https://github.com/DPBayes/twinify)** [![GitHub stars](https://img.shields.io/github/stars/DPBayes/twinify?style=social&color=white)](https://github.com/DPBayes/twinify/stargazers) — Privacy-preserving software package for generating synthetic twins of sensitive datasets using differential privacy techniques.

**Frameworks for building custom systems** 🛠️: Combine **SDV / CTGAN / Synthcity** for core generation, **SmartNoise** for differential privacy, **SDMetrics** for evaluation, **Pandas + Scikit-learn** for preprocessing, and **Ollama** or local LLMs for generating synthetic text, labels, or complex multimodal datasets.

## 🤝 How to Contribute

1. 🍴 Fork the repo.
2. ✏️ Add/edit entries in `README.md` (follow existing format).
3. 📋 Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. 🚀 Submit PR with a short explanation.

⭐ Star the repo if you find it useful!

## ⚠️ Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Synthetic data tools must be validated for statistical fidelity, privacy guarantees (e.g., differential privacy), and downstream utility before production use.
- Self-hosted open-source solutions require proper evaluation of leakage risks, model bias, and regulatory compliance (GDPR, HIPAA, etc.).

## 📈 Star History

<div align="center">
   <a href="https://www.star-history.com/?repos=ishandutta2007%2FAwesome-Synthetic-Data-Platform&type=date&legend=bottom-right">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-Synthetic-Data-Platform&type=date&theme=dark&legend=bottom-right" />
      <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-Synthetic-Data-Platform&type=date&legend=bottom-right" />
      <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-Synthetic-Data-Platform&type=date&legend=bottom-right" />
    </picture>
   </a>
</div>

---
**Made for data scientists, privacy engineers, ML engineers, researchers, and organizations seeking safer data practices.** 🛡️
Let's make synthetic data more open, high-quality, and privacy-preserving. ✨
