## 📊 New York Data Breach Analysis

## Project Title: A Comprehensive Analysis of New York Data Breaches

# Overview

This repository contains a consolidated and structured dataset of data breach incidents reported in New York State. The project transforms large, unstructured Attorney General disclosure documents into an analyzable dataset suitable for large-scale cybersecurity research.

# Data Source

The dataset was constructed from eight large PDF disclosure files published by the New York Attorney General. These reports span multiple years and reporting formats.

# Dataset Description

Total records: 1,661 validated data breach incidents

Source format: Unstructured PDF disclosures

Key attributes include:

Organization name

Breach description

Breach discovery and notification dates

Number of individuals affected

Number of New York residents impacted (when available)

# Data Extraction & Preparation

Due to the complexity of the source documents, extensive preprocessing was required:

Text extraction from PDF disclosures

Consolidation into a single master dataset

Removal of duplicate, irrelevant, and corrupted records

Exclusion of administrative references, document codes, and non-incident text

Standardization of column formats and values

All missing or unclear values were preserved as missing to ensure transparency and data fidelity.

# Data Limitations

The dataset reflects reporting inconsistencies across time and disclosure mechanisms:

Some incidents lack intake identifiers

Breach timelines may be partially reported

Affected population counts are not always disclosed

Reporting formats vary across years

These limitations are inherent to the original disclosures and were not artificially corrected.

# Intended Use

This dataset is well suited for:

Longitudinal analysis of data breach trends

Evaluation of disclosure practices and delays

Sector and breach-type risk assessment

Comparative studies across U.S. states

Policy-driven cybersecurity research

# Citation

Users of this dataset should acknowledge the New York Attorney General as the original data source and cite this repository when publishing derivative work.

# License

This dataset is derived from publicly available records and is intended for research, educational, and policy analysis purposes.
