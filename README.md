# Analysis of Time Use in the 2022 American Time Use Survey

This repository contains a detailed analysis of time use patterns based on the 2022 American Time Use Survey (ATUS) data. The report focuses on estimating means and variances of different nonwork-related time activities.

## Sampling Methodology

### Sampling Design

- **Design Type:** 3-stage stratified cluster sample.
  
### Sampling Stages

1. **First Stage:** Selection of households proportional to state population.
2. **Second Stage:** Stratification based on household characteristics.
3. **Third Stage:** Random selection of an eligible individual within each household.

### Variables of Interest

- $T_1$: Total nonwork-related time spent alone every day.
- $T_2$: Total nonwork-related time spent with household family members every day.
- $T_3$: Total nonwork-related time spent with spouse every day.
- $T_4$: Total nonwork-related time spent with friends every day.

**Estimates:**

- $\hat T_1 = 314.45$ minutes/day
- $\hat T_2 = 245.10$ minutes/day
- $\hat T_3 = 158.87$ minutes/day
- $\hat T_4 = 24.06$ minutes/day

## Variance Estimation

### Replication Method

- **Replication Type:** Modified balanced half-sample method.
- **Replicate Weights:** 160 replicate weights generated.

### Variance Estimates

The variance estimates for each time variable are computed as follows:

- $\widehat{\text{Var}}(\hat T_1) = 10.07$
- $\widehat{\text{Var}}(\hat T_2) = 12.85$
- $\widehat{\text{Var}}(\hat T_3) = 7.57$
- $\widehat{\text{Var}}(\hat T_4) = 1.64$

## Data Source

The analysis is based on the 2022 American Time Use Survey (ATUS) data (https://www.bls.gov/tus/data/datafiles-2022.htm).

### Data Usage

The report demonstrates how to estimate means and variances of different time activities using complex survey data and replication methods.
