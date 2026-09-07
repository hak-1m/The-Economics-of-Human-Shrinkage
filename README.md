# The Economics of Human Shrinkage 👶📉

> **Economic Drivers of Global Fertility Contraction: A Panel Fixed-Effects Analysis**

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![R-Project](https://img.shields.io/badge/Language-R%20%7C%20Econometrics-blue)](https://www.r-project.org/)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0003--4999--1861-green)](https://orcid.org/0009-0003-4999-1861)
[![DOI](https://img.shields.io/badge/Zenodo-Record%2022096153-blue)](https://zenodo.org/records/22096153)
[![Research Status](https://img.shields.io/badge/Status-Research%20Preprint-orange)](#)

---

## 📌 Executive Summary

Modern demography is characterized by a steady global decline in the Total Fertility Rate. In advanced and transitioning economies alike, fertility rates have consistently fallen below the natural replacement threshold. 

This research repository implements an advanced panel data econometric framework to evaluate the structural socio-economic determinants of global fertility contraction. By examining a comprehensive dataset spanning 6,120 country-year observations from 1990 to 2024, this project bridges microeconomic household production models with macro-level demographic transition theory. 

The study evaluates five primary structural drivers of birth rates: urbanization, per capita income, female labor force participation, life expectancy, and infant mortality.

---

## 🔬 Methodology and Approach

To formalize the economic drivers of fertility contraction, this project extends classic microeconomic household choice frameworks, where households face a trade-off between the quantity of children and the human capital quality investment per child. 

Rather than relying on simple cross-sectional comparisons, our empirical specification employs a dynamic Two-Way Panel Fixed Effects model using World Bank indicators. To ensure the highest empirical rigor, the models incorporate Driscoll-Kraay robust standard errors. This advanced covariance structure corrects for spatial dependence across neighboring countries, temporal cross-sectional correlation, and heteroskedasticity.

By contrasting standard Pooled OLS models (which compare differences between countries) with Panel Fixed Effects models (which isolate transitions within specific countries over time), the codebase successfully isolates the true within-country drivers of demographic change.

---

## 📊 Key Findings

Our empirical evaluation provides crucial insights into the mechanisms driving global fertility contraction:

* **Urbanization and Spatial Reconfiguration:** Urbanization exerts a powerful, persistent negative force on birth rates. The urban environment structurally transforms children from productive agricultural assets into high-cost commitments requiring substantial housing premiums, education, and service expenses.
* **The Income Paradox Reversal:** Our findings uncover a striking econometric phenomenon. While standard cross-sectional comparisons show that wealthier countries historically have lower fertility rates, controlling for time-invariant country characteristics reveals the opposite: within an established nation, incremental per-capita income growth acts as a stabilizing pro-natalist liquidity buffer.
* **Female Opportunity Costs:** Increased female inclusion in formal labor markets introduces a severe structural tradeoff between career advancement and maternal timelines. When women achieve financial autonomy without supportive institutional infrastructure, reproductive behavior contracts significantly.
* **Dissolution of Intergenerational Contracts:** Rising life expectancy and the expansion of formal pension systems eliminate the historic economic necessity of having large families as an old-age social security network. As existential safety increases, reproductive choices become guided purely by micro-level personal preferences.
* **Infant Mortality Dominance:** Child survival guarantees remain the primary empirical prerequisite for modern fertility rationalization. Reductions in infant mortality exhibit the strongest direct positive link with fertility stabilization, confirming that public health improvements are the initial catalyst triggering demographic transition.

---

## 🛠️ Data Pipeline & Technology Stack

* **Automated Data Extraction:** Programmatic retrieval of global longitudinal panel data (1990–2024) directly via the World Bank API connector (`wbstats` in R).
* **Multicollinearity & Diagnostic Testing:** Evaluation of Variance Inflation Factors (VIF) and Pearson correlation matrices to ensure robust structural inference.
* **Advanced Panel Econometrics:** Estimation of Two-Way Fixed Effects models using the `plm` framework combined with Driscoll-Kraay spatial and temporal robust standard error adjustments.

---

## 🎯 Public Policy Architecture for Demographic Stabilization

To address structural labor supply contractions and demographic imbalances, the paper outlines a three-pillar policy framework:

1. **Internalizing Maternal Opportunity Costs:** State policy must subsidize high-quality early childcare infrastructure and enforce flexible remote-work regimes to eliminate the penalty between professional development and family planning.
2. **Mitigating Urban Housing Frictions:** Governments should deploy targeted tax incentives for spacious family housing and promote regional urban decentralization to reduce density-induced fertility penalties.
3. **Restructuring Social Security:** Fiscal authorities should introduce fertility-linked pension credit bonuses, directly rewarding human capital production within national retirement systems.

---

## ✒️ Citation & Author Info

**Author:** Bekdaulet Abzhamiev  
**Role:** Researcher  
**ORCID:** [0009-0003-4999-1861](https://orcid.org/0009-0003-4999-1861)  
