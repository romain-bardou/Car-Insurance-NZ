# Vehicle Theft Analysis for Insurance Optimization in New Zealand

## 📋 Overview

This project analyzes vehicle theft data in New Zealand to optimize insurance pricing, reduce theft-related claim costs, and enhance customer segmentation. The report leverages a dataset on stolen vehicles and a 2025 vehicle fleet sample to identify theft patterns, develop a risk-based pricing model, and propose actionable strategies for an insurance company. Key findings highlight high-risk profiles (e.g., Nissan Saloons, Auckland) and low-risk profiles (e.g., Toyota Caravans, Southland).

## 🔍 Objectives

- Identify characteristics of frequently stolen vehicles and their overrepresentation relative to the vehicle fleet.
- Analyze geographic variations in theft rates.
- Develop a predictive pricing model using risk scores (from -0.5 to 1.0) to adjust premiums.
- Recommend strategies for premium adjustments, risk mitigation, and customer segmentation.

## 📊 Key Findings

- **High-Risk Profiles**: Nissan Saloons (risk score 0.806), motorcycles (0.96), silver vehicles (1.0), vehicles from 1995–2008 (1.0), and regions like Auckland (1.0) and Gisborne (1.0).
- **Low-Risk Profiles**: Toyota Caravans (-0.07), station wagons (-0.50), grey vehicles (-0.50), and regions like Southland (-0.42) and Marlborough (-0.24).
- **Pricing Model**: `Annual Premium = Base_Premium × (1 + Risk_Score) + Fees`, with weighted factors (20% brand, 15% type, 5% color, 20% year, 40% region).

## Report Structure

The report (`Car_Insurance_Premiums_NZ.pdf`) includes:

- **Executive Summary**: Key findings and pricing model.
- **Introduction**: Project goals and data sources.
- **Methodology**: Data cleaning, analysis, and tools (Excel, Python, Power BI).
- **Results**: Visualizations, overrepresentation trends, and premium calculations.
- **Discussion**: Interpretation of findings.
- **Recommendations**: Premium adjustments, anti-theft discounts, and segmentation.
- **Sources**: Datasets and references.
- **Appendix**: Brand rates and premium coefficients.

## Datasets

- `stolen_vehicles.xlsx`: Theft data (brand, type, year, color, region, date).
- `make_details.xlsx`: Brand classifications (standard vs. luxury).
- `locations.xlsx`: Regional data (population, density).
- `fleet.xlsx`: 100,000-record sample of the 2025 NZ vehicle fleet.

## Tools Used

- **Excel**: Data cleaning, standardization, pricing model.
- **Python (pandas)**: Data filtering and sampling.
- **Power BI**: Interactive visualizations (histograms, heatmaps, line charts).

## Limitations

- Lack of seasonal theft data, recovery rates, and anti-theft device information.
- Potential differences between 2025 fleet data and 2022 theft data on electrical vehicles.
- Excludes driver-related data, focusing on vehicle characteristics.

## Recommendations

- **Premium Adjustments**: Increase by 20% for high-risk categories (e.g., Nissan Saloons), reduce by 10% for low-risk (e.g., Toyota Caravans).
- **Risk Mitigation**: Offer 5–10% discounts for anti-theft devices.
- **Segmentation**: Target urban customers (Auckland, Gisborne) with comprehensive plans and rural customers (Southland, Marlborough) with budget plans.
- **Data Enhancement**: Collect seasonal data and anti-theft statistics.
- **Marketing**: Use social media for urban clients and local channels for rural clients.

## 📚 Sources

- New Zealand Transport Agency (NZTA): [Vehicle Fleet Data](https://www.nzta.govt.nz/resources/new-zealand-motor-vehicle-register-statistics/)
- Insurance Council of New Zealand (ICNZ): [ICNZ](https://www.icnz.org.nz/)
- AA Insurance: [AA Insurance](https://www.aainsurance.co.nz/)
- Financial Markets Authority (FMA): [FMA](https://www.fma.govt.nz/)
