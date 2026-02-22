# Climate-Dengue Correlation Analysis: Puducherry (2019)

## Project Overview

This project examines the relationship between monthly rainfall and dengue fever cases in Puducherry Union Territory.
The analysis covers four districts (Pondicherry, Karaikal, Mahe, and Yanam) that experience different rainfall patterns due to their geographic locations.

## Research Question

Does rainfall in a given month correlate with dengue cases in subsequent months? If so, what is the time delay?

## Data Sources

- **Rainfall Data**: India Meteorological Department (IMD GRID Model)
  - Daily records for all 12 months of 2019
  - Aggregated to monthly totals for each district
  
- **Dengue Cases**: State/UT Month Wise Dengue Cases 2018 - 2019
  - Monthly reported cases for Puducherry UT
  - Data available for January-June 2019

## Methodology

1. Cleaned and organized rainfall data using Excel pivot tables
2. Combined rainfall and dengue datasets using VLOOKUP functions
3. Created lag variables (1-month and 2-month delays)
4. Calculated Pearson correlation coefficients at different time lags
5. Compared rainfall patterns across the four districts

## Key Findings

### 1. Time Lag Effect
- **Same month**: Correlation = -0.33 (weak negative)
- **1-month lag**: Correlation = 0.16 (weak positive)
- **2-month lag**: Correlation = 0.55 (moderate positive)

**Interpretation**: Rainfall in a given month shows the strongest relationship with dengue cases occurring 2 months later. 
This aligns with the mosquito breeding cycle, which takes approximately 2-3 weeks, plus disease incubation time.

### 2. Spatial Variation
The four districts showed significant differences in annual rainfall:
- Mahe: 4,427 mm (located on Arabian Sea coast)
- Karaikal: 1,384 mm (located on Bay of Bengal coast)
- Yanam: 1,154 mm (located on Bay of Bengal coast)
- Pondicherry: 1,130 mm (located on Bay of Bengal coast)

Mahe receives nearly 4 times more rainfall than the other three districts due to its exposure to southwest monsoon winds from the Arabian Sea.

## Limitations

- Analysis covers only 6 months of dengue data (Jan-Jun 2019)
- Dengue cases reported at Union Territory level, not by individual district
- Does not account for other factors like temperature, humidity, or vector control activities
- Based on secondary data analysis

## Tools Used

- Microsoft Excel (pivot tables, VLOOKUP, correlation functions)
- Basic statistical analysis (Pearson correlation)

## Practical Application

If validated with longer time periods, this 2-month lag could help health authorities:
- Anticipate potential dengue outbreaks based on rainfall data
- Allocate medical resources in advance
- Time vector control interventions more effectively

## Acknowledgment

This is an independent learning project using publicly available data. It was conducted to understand epidemiological analysis methods and demonstrate data management skills.

Data sources: IMD public databases, Open Government Data Platform India.


