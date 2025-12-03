# Data-Driven Global Trademark Trend Analysis & Strategy

> **A portfolio project analyzing 1.2 million trademark applications across 6 major global markets (2014–2023) to formulate market-tailored business strategies.**

---

## Project Overview

This project was initiated to define a market expansion strategy based on quantitative evidence. By analyzing trademark application data from **South Korea, USA, Europe, China, Japan, and the Madrid System**, I identified structural shifts in global industries and proposed specific business strategies for an IP (Intellectual Property) service platform.

* **Period:** 2014 – 2023 (10 Years)
* **Data Volume:** Approx. [cite_start]1.2 million rows of trademark application data[cite: 9].
* [cite_start]**Objective:** To uncover market polarization and emerging industrial trends to guide business decision-making [cite: 6-7].

---

## Methodology & Data Pipeline

[cite_start]To ensure accuracy and actionable insights, I developed a data processing pipeline using **Python (Pandas, Matplotlib)**[cite: 9]:

1.  **Data Preprocessing:**
    * Integrated raw datasets from 6 different jurisdictions with varying formats.
    * [cite_start]Standardized unstructured Nice Classification (NCL) codes and date formats[cite: 10].
    * "Exploded" multi-class applications into granular data points for accurate category analysis.

2.  **Seasonal Adjustment (Forecasting):**
    * Addressed incomplete 2023 data by analyzing monthly application patterns from the previous 9 years (2014-2022).
    * [cite_start]Derived and applied a **seasonal correction coefficient (2.5509)** to estimate full-year performance with high precision[cite: 10].

3.  **Visualization:**
    * [cite_start]Applied **Log Scale** transformations to compare markets with vastly different volumes (e.g., China vs. Madrid System) on a single visual plane[cite: 11].
    * Created time-series visualizations to track the rise and fall of specific industries.

---

## Key Analysis Results

### 1. Global Market Polarization
The analysis revealed a distinct bifurcation in the global IP market:

* **Volume Market (China, Madrid System):**
    * **Dominant Sectors:** Food (Cl. 30), Agriculture (Cl. 31), Services (Cl. 43).
    * **Insight:** Driven by short product lifecycles and high-frequency filings. [cite_start]This market requires speed and cost-efficiency [cite: 59-63].
* **Value Market (USA, Europe):**
    * **Dominant Sectors:** Tech/Software (Cl. 9), Pharma (Cl. 5), R&D Services (Cl. 42).
    * **Insight:** High-value, IP-intensive industries. [cite_start]This market requires premium consulting and rigorous rights protection [cite: 64-67].

### 2. Structural Shifts in Korea
Analysis of the Korean market (2014-2023) highlighted three major trends:

* [cite_start]**Digital Transformation:** A clear decline in traditional manufacturing (Household/Kitchen - Cl. 21) contrasted with a steady rise in **Software & IT Services (Cl. 9, Cl. 42)** [cite: 99-102].
* [cite_start]**The "Pet & Wellness" Boom:** **Pet Food (Cl. 31)** showed the steepest growth curve over the decade, while **Healthcare (Cl. 5)** remained resilient despite economic downturns [cite: 104-107].
* [cite_start]**R&D Resilience:** Even during the 2023 economic slowdown, filings for Scientific Services (Cl. 42) rebounded, indicating corporate focus on securing future technologies [cite: 111-113].

---

## Strategic Proposals

Based on these findings, I formulated three data-driven strategies for business growth:

1.  **"O2O All-in-One" Bundling (Korea):**
    * *Insight:* The boundary between products and platforms is blurring.
    * [cite_start]*Action:* When clients file for product trademarks (e.g., Cosmetics), statistically recommend filing for related service marks (e.g., Online Retail, Marketing) to increase ARPU (Average Revenue Per User) [cite: 144-147].

2.  **Category Killer: Pet & Health:**
    * *Insight:* These sectors show structural, non-cyclical growth.
    * [cite_start]*Action:* Develop specialized AI classification models for these complex sectors (e.g., ingredients, supplements) to capture the growing market share [cite: 151-153].

3.  **Multi-Track Global Expansion:**
    * [cite_start]**Track A (China/Madrid):** Implement **RPA (Robotic Process Automation)** for a low-cost, high-speed service model targeting high-volume consumer goods [cite: 157-159].
    * [cite_start]**Track B (US/EU):** Deploy a **"Premium Consulting"** model involving expert review to navigate strict examination standards for high-tech and bio-pharma clients [cite: 162-163].

---

## Tools & Skills Used

* **Language:** Python
* **Libraries:** Pandas, Matplotlib, Seaborn
* **Skills:** Data Cleaning, Time-Series Analysis, Market Segmentation, Business Strategy Formulation
