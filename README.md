# California Property Close Price Prediction

**Author:** Soonbee Hwang

## Overview

This project explores the development of a machine learning model for estimating the final sale price of single-family residential properties in California.

The goal is to build a reproducible workflow that covers data exploration, preprocessing, feature engineering, model development, and evaluation. The project will begin with a simple regression baseline and compare it with more advanced machine learning approaches.

## Project Objectives

- Understand the structure and quality of residential property data
- Identify property and location features related to sale price
- Develop a reproducible data-preprocessing workflow
- Compare multiple regression models
- Evaluate model accuracy and consistency over time
- Document modeling decisions, results, and limitations

## Data Availability

The datasets used in this project are not included in this repository due to licensing and privacy restrictions.

Raw and processed data will remain in a private local environment. This public repository will contain only code, project documentation, and aggregated results that do not reveal individual property records.

## Approach

The project will follow four general stages:

1. **Data understanding:** Review the schema, feature definitions, missingness, and data quality.
2. **Data preparation:** Clean the data, create appropriate features, and organize chronological training and evaluation sets.
3. **Model development:** Establish a baseline and compare it with more advanced regression models.
4. **Evaluation:** Measure overall performance and investigate how prediction errors vary across time, locations, and property groups.

## Current Status

### Week 1 — Project Setup  
**September 21–27, 2026**

Completed:

- [x] Reviewed the project objective and requirements
- [x] Created and configured the public repository
- [x] Added safeguards to prevent private data and credentials from being committed
- [x] Confirmed access to the required data
- [x] Downloaded multiple months of historical sold-property records to a private local directory
- [x] Confirmed that the downloaded files are available locally

In progress:

- [ ] Verify the local Python, Git, and notebook environment
- [ ] Review the property metadata and important feature definitions
- [ ] Create a short reference for the key columns
- [ ] Confirm that the monthly files can be loaded successfully

## Repository Structure

```text
IDX-Exchange-Data-Science/
├── docs/          # Project notes and feature documentation
├── notebooks/     # Exploratory analysis and model development
├── src/           # Reusable project code
├── tests/         # Tests for reusable code
├── .gitignore
└── README.md
```

## Next Steps

The next stage will focus on loading the monthly files, checking schema consistency, examining missing values and duplicates, and exploring the distributions of the target and major property features.
