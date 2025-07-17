# Data Governance
**by [Joshua Adekeye](https://github.com/JoshAdekeye)**

> Central hub for cross‑platform data governance & data quality automation (Informatica · Ataccama · Looker · Alation).

## Contents
- [Informatica](#informatica)
- [Ataccama ONE](#ataccama-one)
- [Looker](#looker)
- [Alation](#alation)
- [Planned Tools](#planned-tools)

## Purpose

This repository serves as a **portfolio hub and integration workspace** for operational data governance and data quality engineering across **Informatica Data Quality**, **Ataccama ONE**, **Looker**, and **Alation**. It organizes key open‑source tooling and documentation references alongside custom automation patterns for:

- Extracting and standardizing **data quality (DQ) metrics**.
- Synchronizing **metadata & lineage** into governed data catalogs.
- Surfacing **data trust indicators in analytics/BI** environments.
- Experimenting with **AI-augmented stewardship** and metadata enrichment.

---

## Informatica

| Folder | Project | Notes |
|--------|---------|-------|
| `vendor/informatica/CDQ_Custom_Dashboard` | CDQ_Custom_Dashboard | Cloud Data Quality reporting template; extracts profiling metrics for dashboarding. |
| `vendor/informatica/REST-API-Samples` | REST-API-Samples (Enterprise Information Catalog) | Java/Python samples for EIC REST API (metadata, lineage, profiling). |
| `vendor/informatica/Informatica-EDC-REST-API-Samples` | Informatica-EDC-REST-API-Samples | Community Python utilities building on EDC REST APIs. |

## Ataccama ONE

Ataccama ONE artifacts (DQ rules, profiling configs) are created in ONE Desktop; use its built‑in EGit integration to version projects in GitHub. See the documentation references below:

| Doc | Link | Why It Matters |
|-----|------|----------------|
| Git Integration (Official) | [docs.ataccama.com](https://docs.ataccama.com/one-desktop/latest/projects/git.html) | Add repo, commit, push from ONE Desktop; enables versioning in GitHub. |
| ONE Desktop Git Integration (Community) | [community.ataccama.com](https://community.ataccama.com/master-data-management-reference-data-management-92/one-desktop-git-intergration-382) | Field tips & gotchas beyond official doc. |
| Integrating Git w/ Orchestration Server | [community.ataccama.com](https://community.ataccama.com/data-quality-catalog-94/integrating-git-with-orchestration-server-1230) | Deployment guidance for self‑managed environments. |
| Collaboration & Version Control Overview | [docs.ataccama.com](https://docs.ataccama.com/one-desktop/latest/projects/collaboration-and-version-control.html) | Broader collaboration models (Git vs SVN) & workflows. |

## Looker

| Folder | Project | Notes |
|--------|---------|-------|
| `vendor/looker/sdk-codegen` | sdk-codegen | Generates official Looker SDKs (Python, TS/JS, Go, etc.) for API automation. |
| `vendor/looker/embed-sdk` | embed-sdk | JS library for embedding & interacting with Looker content. |
| `vendor/looker/LookerEmbedReference` | LookerEmbedReference | Full React + backend examples for embedded analytics flows. |
| `vendor/looker/app-lookml-diagram` | app-lookml-diagram | ERD diagram extension for LookML models—governance mapping. |
| `vendor/looker/looker-explore-assistant` | looker-explore-assistant | LLM → Explore natural language query interface; extensible for DQ signals. |
| `vendor/looker/pylookml` | pylookml | Pythonic LookML parsing & generation; good for scripted governance tasks. |

## Alation

| Folder | Project | Notes |
|--------|---------|-------|
| `vendor/alation/Allie-SDK` | Allie-SDK | Python SDK for Alation REST APIs; manage & enrich catalog metadata programmatically. |
| `vendor/alation/alation-ai-agent-sdk` | alation-ai-agent-sdk | Build AI agents that access governed metadata from Alation; LangChain friendly. |
| `vendor/alation/Alation_Article` | Alation_Article | Community scripts for migrating Articles & catalog objects between instances. |

## Planned Tools

The `tools/` directory will contain custom integration scripts for:
- Cross-platform DQ metric extraction and standardization
- Metadata synchronization workflows
- Automated governance reporting
- AI-augmented data stewardship utilities

---

## Quick Start

```bash
# Clone this repository
git clone git@github.com:JoshAdekeye/data-governance.git
cd data-governance

# Explore platform-specific tooling
ls vendor/informatica/
ls vendor/looker/
ls vendor/alation/
ls docs/ataccama/

# Check upcoming integration tools
ls tools/
```

## License

This umbrella repository preserves the original licenses of all included projects. See individual project folders for specific license information.
