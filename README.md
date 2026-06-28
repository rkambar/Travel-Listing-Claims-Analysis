# Travel-Listing-Claims-Analysis
Travel listing damage protection claims data engine and interactive dashboard built using Excel and Tableau Public to analyze operational risk and policy compliance.
# 🧳 Travel Listing Damage Protection Claims Analysis

## 📊 Project Overview
This repository features an operational data analysis project evaluating 750 unique damage protection claims filed under a short-term rental safety program. The project focuses on data quality, adjudication validation, spatial and temporal policy enforcement, and calculating financial recovery rates based on real-world operational guidelines.

An interactive dashboard modeling this dataset has been published to Tableau Public to provide operations managers with actionable business intelligence.

- **Live Interactive Dashboard:** [Tableau Public Live View](https://public.tableau.com/app/profile/rakesh.kambar/viz/TravelListingClaimsAnalysis/TravelListingClaimsAnalysis)

## 🛠️ Tech Stack & Skills
- **Data Visualization:** Tableau Public (Multi-page interactive metrics, cross-filtering, scatter distributions)
- **Data Architecture:** Advanced Excel (Database structuring, `COUNTIFS`, `SUMIF` pivot modeling, nested logical loops)
- **Domain Context:** Property & Casualty (P&C) frameworks, operational SLAs, fraud investigation, and short-term rental policy constraints

## 🔑 Core Operational Rules Enforced
The underlying analytical engine strictly models and validates automated corporate policies:
1. **Geographic Eligibility:** Claims filed for incidents occurring beyond a strict **100-meter threshold** from the property listing address are automatically flagged as ineligible and structurally waived.
2. **14-Day Reporting Window:** Incidents reported past the definitive **14-day host claim window** are automatically rejected at the intake gate to enforce operational SLAs.
3. **Evidence-Based Verification:** Claim outcomes heavily favor objective verification; claims backed by timestamped check-in or checkout media exhibit a **94%+ waiver enforcement success rate** for the target party.
4. **Structural Severity Clauses:** Wall and ceiling evaluations follow exact logic—minor wall scratches and paint touch-ups are filtered out as normal wear-and-tear, while actual structural wall holes are paid out at **100%**.
5. **Depreciation Floor Rule:** Missing items utilize a categorical depreciation model based on item age. A hard floor rule ensures depreciation never reduces the active cash value payout below **20% of its original cost** to protect host retention.
6. **ESA Regulatory Override:** Reflecting regional legal mandates in jurisdictions like California and New York, pet-related damages for verified emotional support animals are structurally waived.

## 📈 Key Analytical Findings & Portfolio Metrics

| Metric | Value | Operational Insight |
| :--- | :--- | :--- |
| **Total Claims Processed** | 750 | Full portfolio volume under evaluation |
| **Gross Estimated Damage** | $906,010.84 | Total financial risk exposure before adjudication |
| **Amount Charged to Guest** | $234,101.77 | Direct financial recovery successfully executed |
| **Overall Charge Recovery Rate** | 33.73% | Portfolio yield after filtering out waivers and policy rejections |
| **Geographic Distance Rejections** | 79 Claims | Auto-rejected instantly by the system for breaching the 100m rule |
| **SLA Window Rejections** | 51 Claims | Auto-rejected instantly for filing past the 14-day policy limit |

### 🔍 Advanced Visualizations Developed
- **Charge Rate by Category:** A volume-sorted, color-coded stacked bar chart tracking volume across all 12 damage categories, highlighting Furniture and Pet Damage as primary volume drivers.
- **Reporting Window Compliance:** Tracks strict intake SLA compliance, isolating a 100% auto-rejection rate for claims filed past policy bounds.
- **Geographic Eligibility Scatter Plot:** Maps spatial metadata against financial exposure to visualize a definitive policy cliff where all claims originating past 100 meters are structurally waived.
- **Wall-Ceiling Clause Logic:** A discrete visual breakdown proving that minor wear-and-tear scratches are successfully filtered out while structural wall holes achieve a 100% recovery rate.
- **Depreciation Impact Scatter Plot:** Evaluates continuous item age dimensions to map the downward-sloping payout curve driven by the actual cash value depreciation calculator.
- **Financial Resolution Pipelines:** Evaluates the gross financial weight across adjudication paths, isolating cost allocation between asset repairs, complete structural replacements, and cash disbursements.

## 📂 Repository Contents
- `Travel_Listing_Claims_Dataset_1.csv`: Raw data containing 750 records and 29 distinct operational fields.
- `Travel_Listing_Claims_Workbook.xlsx`: Fully formula-driven analysis sheets verifying logic branches and pipeline calculations.
- `Travel_Listing_Claims_Analysis.twbx`: Packaged Tableau dashboard containing full interactive actions and embedded data architecture.

## 👤 Author Contact & Portfolio Links
- **GitHub Profile:** [github.com/rkambar](https://github.com/rkambar)
- **Tableau Public:** [public.tableau.com/profile/rakesh.kambar](https://public.tableau.com/app/profile/rakesh.kambar)
- **Domain Domain Expertise:** 5.7+ Years of Operations, Adjudication, and Fraud Risk Management (Amazon, Sutherland, Omega Healthcare)
