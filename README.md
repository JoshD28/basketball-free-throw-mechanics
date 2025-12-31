# Basketball Free-Throw Mechanics

This repository presents an analysis of **basketball free-throw mechanics**
using **MLSE SPL Open Data**. The goal is to examine relationships between
mechanical variables and free-throw outcomes, and to describe patterns
associated with successful shooting performance.

## Objectives
1. **Process and clean free-throw tracking data** from MLSE SPL Open Data.
2. **Analyze mechanical variables** associated with free-throw execution.
3. **Compare successful and unsuccessful free throws** using descriptive
   and visual analysis.
4. **Interpret mechanical patterns** relevant to shooting performance.

## Data
- **Source:** MLSE SPL Open Data
- **Unit of analysis:** Individual free-throw attempts
- **Typical variables:**  
  - Joint or segment kinematics (as provided)  
  - Release characteristics  
  - Outcome (make/miss)

If the dataset is not included in this repository, see `data/README.md`
for instructions on how to obtain and place the data locally.

## Methods
- **Approach:** Descriptive and exploratory analysis
- **Processing:**  
  - Data cleaning and filtering  
  - Feature selection
- **Visualization:**  
  - Distribution plots  
  - Comparisons between outcomes  
  - Mechanically relevant summaries

## Outputs
- Summary statistics of free-throw mechanics
- Visual comparisons of makes vs misses
- Interpretation of mechanical factors related to performance

## How to Run
1. Clone or download this repository.
2. Ensure the dataset is available at `data/free_throw_data.csv`.
3. Open and run:
   - `notebooks/MLSE_SPL_Open_Data_Free_Throw_Mechanics.ipynb`

## Requirements
- Python 3.x
- pandas
- numpy
- matplotlib / seaborn

## Notes
This analysis focuses on **mechanical characteristics of free-throw shooting**.
Findings describe associations and patterns, not causal relationships or player
evaluation.
