
THE GLOBAL EV EVOLUTION (2010-2025)
================================================================================
  
  Analyzing Evolution of Electric Mobility and Future Adoption Projections
  ReDI School of Digital Integration — Data Analytics Project 2026
  Author: Aswathi S Nair

--------------------------------------------------------------------------------
PROJECT OVERVIEW
--------------------------------------------------------------------------------

This project analyzes the evolution of electric vehicle (EV) adoption globally
from 2010 to 2025 using data from the International Energy Agency (IEA) Global
EV Outlook 2026.

## Problem Statement:
  How has global EV adoption evolved from 2010 to 2025, and which countries,
  vehicle types, and regions are leading the transition?

## Key Questions Answered:  
  - How fast is global EV stock growing?
  - Which countries lead EV sales in 2025?
  - Is BEV or PHEV winning the market?
  - Is charging infrastructure keeping up with EV adoption?
  - What does 2035 look like under different policy scenarios?
  - What vehicle type leads in each country?
  - What is the EV market (sales share) per country?

## Data Source:
  International Energy Agency (IEA) — Global EV Outlook 2026
  https://www.iea.org/data-and-statistics/data-product/global-ev-outlook-2026

## LIST OF INCLUDED FILES

  EV_vehicle__3_.ipynb              — Main Jupyter Notebook with all code, analysis, visualizations, and documentation

  GEVO_EV_2026-Table 1.csv          — Original dataset from IEA 

  presentation_slides.pdf           — Final presentation slides 


## INSTRUCTIONS TO RUN THE ANALYSIS

STEP 1 — Install Python
  Make sure Python 3.8 or higher is installed on your computer.

STEP 2 — Install required Python libraries - use pip 

  All four libraries are needed:
    - pandas       — loading, cleaning, and filtering the dataset
    - numpy        — numerical calculations (arrays, growth rates)
    - matplotlib   — all charts and visualizations
    - jupyter      — to open and run the .ipynb notebook file
STEP 3 — Place the dataset in the correct location
 
STEP 4 — Open the notebook

STEP 5 — Run the notebook


## AI TOOLS USED

- Debugging code and understanding error messages
- Understanding chart options for correlation analysis

## NOTES

Loaded CSV with correct delimiter loaded with sep=',',decimal=','
Converted 'unit' column to lowercase, filled missing values in units with 'USD_2025

Changed country names - Renamed 'Turkiye'→Turkey, 'Viet Nam'→Vietnam, 'Lao
PDR'→Laos for clarity.

Dropped unused columns - 'Aggregate group' and 'Unnamed: 9' were empty

Handled missing region data - Rows with null 'region_country' were dropped —
geographic analysis requires location. World-level copy kept separately


