## Overview

This project conducts an exploratory data analysis (EDA) of homelessness housing capacity across U.S. states using 2024 data from the U.S. Department of Housing and Urban Development (HUD).

By combining Housing Inventory Count (HIC) data with Point-in-Time (PIT) homelessness counts, the analysis evaluates how well housing resources align with homelessness need at the state level.

## Objectives

Examine the distribution of homeless housing capacity across U.S. states

Compare housing capacity to homelessness need using federally reported PIT counts

Identify disparities in housing availability relative to homeless populations

Create policy-relevant metrics and visualizations for stakeholders

## Data Sources

HUD Housing Inventory Count (HIC) – 2024

Provides counts of homeless housing beds by type (emergency shelter, transitional housing, permanent supportive housing)

HUD Point-in-Time (PIT) Count – 2024

Provides estimates of sheltered and unsheltered homeless populations

## Methods

Imported unstructured Excel data using readxl

Cleaned and transformed raw HUD tables using dplyr

Integrated multiple datasets through state- and year-level joins

Engineered a key metric: beds per homeless person

Conducted exploratory analysis through summaries and rankings

Created visualizations using ggplot2

Produced a reproducible analysis using R Markdown

## Key Findings

Homeless housing capacity is highly concentrated in a small number of states

Permanent supportive housing represents a substantial share of total beds in high-capacity states

Beds-per-person varies widely, highlighting mismatches between capacity and homelessness need

States with large homeless populations do not always have proportional housing capacity

## Visualizations

Top 10 states by total homeless housing beds

Housing capacity vs. homeless population scatter plot

Beds-per-person rankings by state

## Tools & Skills

Languages: R

Libraries: tidyverse, dplyr, ggplot2, readxl, scales

Techniques: Data cleaning, data integration, EDA, feature engineering, data visualization

Reporting: R Markdown, HTML output

## Next Steps

Extend analysis across multiple years (2007–2024)

Compare housing type availability to unsheltered populations

Conduct regional or per-capita comparisons

Explore descriptive modeling or trend analysis

## Author

India Flores
Aspiring Data Analyst | Public Policy & Social Impact Analytics
