# 🇺🇸 U.S. Population & Migration Patterns

### Spatial-Temporal Migration Intelligence for Policy and Strategy

[![Python](https://img.shields.io/badge/Python-Analytics-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Jupyter](https://img.shields.io/badge/Jupyter-Research%20Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org)
[![Census Data](https://img.shields.io/badge/U.S.%20Census-Migration%20Data-1D4ED8?style=for-the-badge)](https://www.census.gov)
[![Econometrics](https://img.shields.io/badge/Econometrics-Regression-7C3AED?style=for-the-badge)](#)
[![Status](https://img.shields.io/badge/Status-Completed-16a34a?style=for-the-badge)](#)

> A data-driven project exploring **domestic and international migration across U.S. states**, combining geospatial visualisation, trend decomposition, and regression modeling to support **business expansion strategy** and **evidence-based policy**.

---

## 🧭 Executive Summary

Migration reshapes labor markets, housing demand, consumption patterns, and regional productivity.  
This project quantifies where people are moving **to** and **from** in the United States, then links those movements to economic variables such as income and employment.

### Core insight:
- 🌞 Several Southern states show persistent in-migration strength (including foreign inflows)
- 🧳 Some regions face sustained domestic out-migration pressure
- 🏛️ Migration dynamics can be translated into actionable strategy for firms and public institutions

---

## 🗂️ Table of Contents

- [Project Purpose](#-project-purpose)
- [Research Questions](#-research-questions)
- [Data Sources](#-data-sources)
- [Analytical Architecture](#-analytical-architecture)
- [Methods](#-methods)
- [Key Findings](#-key-findings)
- [Visual Outputs](#-visual-outputs)
- [How to Reproduce](#-how-to-reproduce)
- [Project Structure](#-project-structure)
- [Tech Stack](#-tech-stack)
- [Policy & Business Relevance](#-policy--business-relevance)
- [Future Extensions](#-future-extensions)
- [Author](#-author)

---

## 🎯 Project Purpose

This project analyzes internal and external migration patterns across U.S. states to answer:

- Which states are net attractors vs. net senders of residents?
- How do migration flows evolve over time?
- What is the relationship between migration and economic outcomes?
- How can migration intelligence support strategic decision-making?

---

## ❓ Research Questions

| # | Question | Strategic Value |
|---|---|---|
| 1 | Which states gain or lose population through domestic migration? | Regional demand forecasting |
| 2 | Where is international migration concentrated? | Talent and labor market planning |
| 3 | Are migration patterns associated with income and employment trends? | Economic competitiveness analysis |
| 4 | Do migration shifts indicate long-run demographic rebalancing? | Infrastructure and policy planning |

---

## 📦 Data Sources

| Source | Coverage | Variables |
|---|---|---|
| **U.S. Census Bureau** | State-level population & migration | Domestic inflow/outflow, international migration, net migration |
| **Economic Indicators** | State-level macro indicators | Employment, income, related economic controls |

### Data dimensions used
- Spatial unit: **U.S. states**
- Time unit: **Multi-year trend panel**
- Flow types:
  - **Domestic migration**
  - **International migration**
  - **Net migration balance**

---

## 🏗️ Analytical Architecture

```text
Raw Census + Economic Data
          ↓
Data Cleaning & Harmonization
          ↓
Feature Engineering (Net Flows, Growth Rates, Ratios)
          ↓
Exploratory Spatial Analysis (Maps)
          ↓
Temporal Trend Analysis
          ↓
Econometric Modeling (Regression)
          ↓
Interpretation for Policy & Business
