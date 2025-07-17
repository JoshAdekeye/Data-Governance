# Data Governance
**by [Joshua Adekeye](https://github.com/JoshAdekeye)**

_Data Governance Leader · Clinical Data Management Expert · Epidemiologist · AI/ML · Implementation Scientist_

---

## Purpose

This repository serves as a **hub** for operational data governance and data quality engineering across **Informatica Data Quality**, **Ataccama ONE**, **Looker**, and **Alation**. It organizes upstream open‑source tooling (included as submodules or referenced links) alongside custom glue code, notebooks, and automation patterns for:

- Extracting and standardizing **data quality (DQ) metrics**.
- Synchronizing **metadata & lineage** into governed data catalogs.
- Surfacing **data trust indicators in analytics/BI** environments.
- Experimenting with **AI-augmented stewardship** and metadata enrichment.

---

## Quick Start

> Adjust paths/commands based on whether you use Git submodules, vendored copies, or a mix. (See `./tools/` for helper scripts once added.)

```bash
# example: clone and initialize submodules (if configured)
git clone git@github.com:JoshAdekeye/data-governance.git
cd data-governance
git submodule update --init --recursive
