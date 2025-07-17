# Cloud Data Quality Custom Dashboard

**Part of the Data Governance Portfolio by [Joshua Adekeye](https://github.com/JoshAdekeye)**

## Overview

The Cloud Data Quality Reporting Dashboard Template provides a framework to capture reporting metrics for data quality issues by extracting Profile Details from the Informatica CDQ Profile Warehouse. This template demonstrates how to visualize profiling data in business intelligence tools as part of a comprehensive data governance strategy.

## Components

- **Python Script** - `IICS_CDQ_Dashboard_Dataset.py` - Extracts DQ metrics from IICS
- **Power BI Report** - `CDQ_Report.pbix` - Sample dashboard for DQ visualization
- **Sample Data** - CSV files for testing the dashboard without live system connectivity

The sample report is built using Power BI, but any reporting tool can be utilized to design similar DQ dashboards.

## Prerequisites

**Informatica IICS Requirements:**
- User must have access to all profiles in the IICS organization
- Profiles must have executed at least once

**Technical Requirements:**
- Python 3.11.1 or higher
- Power BI Desktop (for viewing .pbix files)
- Appropriate network access to Informatica Cloud services

## Usage

1. Configure credentials and paths in `IICS_CDQ_Dashboard_Dataset.py`
2. Execute the Python script to extract current DQ metrics
3. Load the generated CSV files into your preferred BI tool
4. Use the provided Power BI template as a starting point for custom dashboards

## Integration with Data Governance

This template serves as a foundation for:
- Standardizing DQ metric extraction across platforms
- Creating consistent reporting formats for governance dashboards
- Enabling automated DQ monitoring workflows

*Part of the comprehensive data governance toolkit covering Informatica, Ataccama, Looker, and Alation platforms.*
