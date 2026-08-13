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
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[Mostly AI](https://mostly.ai/)**  
  Enterprise synthetic data platform specializing in high-fidelity tabular data generation with strong privacy guarantees for regulated industries.

- **[Tonic.ai](https://www.tonic.ai/)**  
  Developer-focused platform for de-identifying production databases and generating realistic test/synthetic data with referential integrity.

- **[Gretel AI](https://gretel.ai/)**  
  Multi-modal synthetic data platform (tabular, text, time-series) with differential privacy, APIs, and developer-friendly workflows (now part of NVIDIA ecosystem in some contexts).

- **[Hazy](https://hazy.com/)**  
  Privacy-first synthetic data solution popular in financial services for complex tabular and time-series data with differential privacy.

- **[Synthea](https://synthetichealth.github.io/synthea/)**  
  Open-source synthetic patient generator focused on realistic medical histories (also widely used commercially and in research).

- **[Datomize](https://www.datomize.com/)**  
  Synthetic data platform for creating realistic customer and transactional datasets, especially for banking and AI model training.

- **[Betterdata](https://www.betterdata.ai/)**  
  Privacy-preserving synthetic data solution for AI development, data sharing, and product testing.

- **[Twinify](https://github.com/DPBayes/twinify)**  
  Privacy-preserving synthetic data generation tool that creates statistical twins of sensitive datasets (open-source core with research focus).

- **[MDClone](https://www.mdclone.com/)**  
  Healthcare-focused synthetic data platform enabling secure exploration and research on patient data without exposing real records.

- **[Mockaroo](https://www.mockaroo.com/)**  
  Popular online tool for generating customizable mock/synthetic datasets for testing and development.

- **[Synthetaic](https://www.synthetaic.com/)**  
  Synthetic data platform specializing in large-scale, high-quality data generation for computer vision and AI training.

- **[Statice](https://www.statice.ai/)**  
  Privacy-preserving synthetic data generation focused on structured data for analytics and machine learning (now often referenced in awesome lists).

- **[Syntho](https://www.syntho.ai/)**  
  AI-powered synthetic data platform for generating privacy-safe, high-fidelity datasets for analytics and AI use cases.

- **[Parallel Domain](https://paralleldomain.com/)**  
  Synthetic data platform for autonomous systems, generating photorealistic 3D scenes, sensor data, and annotated datasets.

- **[YData](https://ydata.ai/)**  
  Synthetic data and data quality platform supporting tabular, relational, and time-series generation with profiling and evaluation tools.

- **[Rockfish Data](https://www.rockfish.ai/)**  
  Synthetic data platform focused on privacy-preserving generation and data collaboration.

- **[Rendered.ai](https://rendered.ai/)**  
  Physics-based synthetic data generation for computer vision, remote sensing, and simulation environments.

- **[Cognata](https://www.cognata.com/)**  
  Synthetic data and simulation platform for autonomous vehicles and advanced driver-assistance systems.

- **[AI Reverie](https://aireverie.com/)**  
  Synthetic data generation for computer vision and AI training using simulation and generative techniques.

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
