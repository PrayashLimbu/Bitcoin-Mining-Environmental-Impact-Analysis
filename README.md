Bitcoin Mining Environmental Impact Analysis
This repository contains a comprehensive analysis of Bitcoin mining's contribution to global temperature rise and climate change, featuring dataset analysis and research findings from 2010-2016.

Overview
Bitcoin mining's exponential growth has raised significant environmental concerns due to its massive energy consumption. This research project examines the relationship between Bitcoin mining activities and global temperature anomalies using empirical data analysis and Structural Equation Modeling (SEM).

Repository Contents
📊 Dataset: BTC_Footprints_v1.xlsx
A comprehensive dataset spanning 2010-2016 containing daily Bitcoin network metrics including:

Data Structure
Time Period: July 18, 2010 - August 12, 2016

Frequency: Daily observations

Total Records: 2,216 data points

Key Metrics Tracked

![image](https://github.com/user-attachments/assets/45d836c8-eb25-4e0d-b10c-43ece1440b3a)

Energy Source Breakdown
The dataset includes emissions data for different energy sources:

Coal (BTCOAL_*): Coal-based energy consumption and emissions

Oil (BTCOIL_*): Oil-based energy consumption and emissions

Gas (BTCGAS_*): Natural gas-based energy consumption and emissions

📄 Research Paper
Title: "Bitcoin Mining and its Contribution to Rising Global Temperatures"
Authors: Prayash Limbu*, Jagat Singh* (Chandigarh University)

Abstract
This research employs Structural Equation Modeling (SEM) to analyze the interconnectedness between Bitcoin mining, CO₂ emissions, and global temperature anomalies. The study reveals a concerning positive relationship between Bitcoin emissions and global temperature change, highlighting Bitcoin's potential contribution to climate change.

Key Findings
Environmental Impact Scale
Energy Consumption: Bitcoin mining consumes energy comparable to entire countries like Austria, Netherlands, or Spain
Carbon Footprint: In 2020-2021, Bitcoin network consumed 173.42 TWh, equivalent to 85.89 million tonnes of CO₂
Water Footprint: Estimated at 1.65 cubic kilometers during the same period
Land Footprint: Approximately 1,870 square kilometers

Temporal Analysis
The dataset reveals dramatic growth in Bitcoin's environmental impact:

Early Period (2010-2011):
Maximum emissions: ~94.4 million kgCO₂ annually
Energy consumption: ~148 million kWh annually

Peak Growth (2016):
Maximum emissions: ~12 billion kgCO₂ annually
Energy consumption: ~12 billion kWh annually

This represents a 12,600% increase in both energy consumption and emissions over 6 years.

Methodology
Data Processing Pipeline
Temporal Aggregation: Daily data converted to monthly chunks for analysis.

![image](https://github.com/user-attachments/assets/a1538bef-7e58-4647-8da1-b2675267211a)


Unit Conversion:

Carbon emissions converted from kg to metric tons (1 Mt = 1000 kg)
CO₂ measurements expressed in parts per million (ppm)
Conversion factor: 1 ppm = 2,129.7 metric tons of CO₂

Temperature Impact Calculation:
Used UCAR Climate Sensitivity Calculator
Estimated temperature increases linked to CO₂ emissions
Integration with NOAA temperature anomaly data

Statistical Analysis
Method: Structural Equation Modeling (SEM) using R's Lavaan package
Time Frame: 2011-2021 analysis period

Research Implications
Environmental Urgency
The analysis reveals Bitcoin mining as a significant contributor to climate change, with emissions comparable to those of major industrial nations. The exponential growth trajectory suggests urgent need for sustainable mining practices.
![image](https://github.com/user-attachments/assets/a8d02d96-61cb-4a37-a813-503c2a002644)


Policy Recommendations

Regulatory Framework: Need for carbon footprint assessment in crypto regulations
Renewable Energy Transition: Incentivizing renewable energy adoption in mining operations
Technological Innovation: Supporting development of energy-efficient consensus mechanisms


Citations
The research builds upon established climate science and cryptocurrency analysis:
Energy consumption analysis methodology adapted from Cambridge Bitcoin Electricity Consumption Index (CBECI)
Climate impact calculations based on NOAA National Centers for Environmental Information data
Statistical modeling approaches derived from established SEM frameworks in environmental research

Contributing
This repository supports ongoing research into cryptocurrency environmental impacts. Contributions welcome for:
Extended dataset analysis
Alternative modeling approaches
Regional impact assessments
Policy recommendation development

License
Dataset and analysis available for academic and research purposes. Please cite original research when using this data.
