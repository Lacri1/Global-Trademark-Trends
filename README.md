# Data-Driven Global Trademark Trend Analysis & Strategy

> A portfolio project analyzing 1.2 million trademark applications across 6 major global markets (2014-2023) to formulate market-tailored business strategies.

---

## Project Motivation

This analysis was conducted as a response to a data analysis challenge posed by MarkCloud, an AI-specialized IP domain analysis company. The primary goal was not merely to find a correct answer but to demonstrate comprehensive analytical capabilities—from problem definition and data preprocessing to deriving actionable business insights from complex, unstructured trademark data across six different jurisdictions.

By tackling this challenge, I aimed to showcase:
* Domain Understanding: Navigating complex IP datasets (e.g., Nice Classifications, Similar Group Codes).
* Analytical Thinking: Identifying structural market shifts (e.g., Digital Transformation, Pet Economy) beyond simple statistics.
* Strategic Application: Translating data trends into tangible business strategies for a global IP service platform.

---

## Project Overview

This project defines a market expansion strategy based on quantitative evidence. By analyzing trademark application data from South Korea, USA, Europe, China, Japan, and the Madrid System, I identified structural shifts in global industries and proposed specific business strategies.

* Period: 2014 - 2023 (10 Years)
* Data Volume: Approx. 1.2 million rows of trademark application data.
* Objective: To uncover market polarization and emerging industrial trends to guide business decision-making.

---

## Methodology & Data Pipeline

To ensure accuracy and actionable insights, I developed a data processing pipeline using Python (Pandas, Matplotlib):

1.  Data Preprocessing:
    * Integrated raw datasets from 6 different jurisdictions with varying formats.
    * Standardized unstructured Nice Classification (NCL) codes and date formats.
    * Exploded multi-class applications into granular data points for accurate category analysis.

2.  Seasonal Adjustment (Forecasting):
    * Addressed incomplete 2023 data by analyzing monthly application patterns from the previous 9 years (2014-2022).
    * Derived and applied a seasonal correction coefficient (2.5509) to estimate full-year performance with high precision.

3.  Visualization:
    * Applied Log Scale transformations to compare markets with vastly different volumes (e.g., China vs. Madrid System) on a single visual plane.
    * Created time-series visualizations to track the rise and fall of specific industries.

---

## Key Analysis Results

### 1. Global Market Polarization
The analysis revealed a distinct bifurcation in the global IP market:

* Volume Market (China, Madrid System):
    * Dominant Sectors: Food (Cl. 30), Agriculture (Cl. 31), Services (Cl. 43).
    * Insight: Driven by short product lifecycles and high-frequency filings. This market requires speed and cost-efficiency.
* Value Market (USA, Europe):
    * Dominant Sectors: Tech/Software (Cl. 9), Pharma (Cl. 5), R&D Services (Cl. 42).
    * Insight: High-value, IP-intensive industries. This market requires premium consulting and rigorous rights protection.

### 2. Structural Shifts in Korea
Analysis of the Korean market (2014-2023) highlighted three major trends:

* Digital Transformation: A clear decline in traditional manufacturing (Household/Kitchen - Cl. 21) contrasted with a steady rise in Software & IT Services (Cl. 9, Cl. 42).
* The Pet & Wellness Boom: Pet Food (Cl. 31) showed the steepest growth curve over the decade, while Healthcare (Cl. 5) remained resilient despite economic downturns.
* R&D Resilience: Even during the 2023 economic slowdown, filings for Scientific Services (Cl. 42) rebounded, indicating corporate focus on securing future technologies.

---

## Strategic Proposals

Based on these findings, I formulated three data-driven strategies for business growth:

1.  O2O All-in-One Bundling (Korea):
    * Insight: The boundary between products and platforms is blurring.
    * Action: When clients file for product trademarks (e.g., Cosmetics), statistically recommend filing for related service marks (e.g., Online Retail, Marketing) to increase ARPU (Average Revenue Per User).

2.  Category Killer: Pet & Health:
    * Insight: These sectors show structural, non-cyclical growth.
    * Action: Develop specialized AI classification models for these complex sectors (e.g., ingredients, supplements) to capture the growing market share.

3.  Multi-Track Global Expansion:
    * Track A (China/Madrid): Implement RPA (Robotic Process Automation) for a low-cost, high-speed service model targeting high-volume consumer goods.
    * Track B (US/EU): Deploy a Premium Consulting model involving expert review to navigate strict examination standards for high-tech and bio-pharma clients.

---

## Tools & Skills Used

* Language: Python
* Libraries: Pandas, Matplotlib, Seaborn
* Skills: Data Cleaning, Time-Series Analysis, Market Segmentation, Business Strategy Formulation
