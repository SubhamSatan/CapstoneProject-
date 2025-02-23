
# README: Deaths by Natural Disasters and Climate Change

## Overview  
This Jupyter Notebook explores the impact of natural disasters on mortality rates over time and investigates possible correlations with climate change.

## Research Questions  
The analysis aims to answer the following questions:  
- How has the number of deaths per year from natural disasters changed over the last century?  
- How does mortality vary by country?  
- How does mortality vary by type of natural disaster?  
- Are there observable trends that could be attributed to climate change?

## Dataset  
The notebook likely uses datasets related to natural disaster records, climate patterns, and global mortality statistics. Ensure that you have the required dataset files before running the notebook.

## Dependencies  
The following Python libraries may be required:  
- pandas (for data manipulation)  
- matplotlib and seaborn (for data visualization)  
- numpy (for numerical computations)  
- scikit-learn (if any statistical modeling is included)  

You can install missing dependencies using:  
bash
pip install pandas matplotlib seaborn numpy scikit-learn


## Usage  
1. Open the notebook using Jupyter Notebook or Jupyter Lab.  
   bash
   jupyter notebook mainResearch.ipynb
   
2. Ensure that all dependencies are installed.  
3. Run the notebook cell by cell to explore data, visualizations, and insights.

## Expected Outcomes  
By the end of this analysis, users should be able to:  
- Identify trends in natural disaster-related deaths.  
- Understand regional variations in disaster mortality.  
- Recognize possible links between climate change and disaster patterns.

The notebook processes data and provides key insights related to the overlap between *disaster, temperature, and population datasets.* Here are the main findings:

1. *Country Data Overlaps:*
   - The disaster and temperature datasets contain *209* common countries.
   - *22 countries* are in the disaster dataset but missing in the temperature dataset (e.g., ANT, AZO, BMU, BRN, CSK, DDR).
   - *20 countries* are in the temperature dataset but missing in the disaster dataset (e.g., ABW, ALA, AND, ATA, ATF, BES).

2. *Population Data Comparison:*
   - The disaster and population datasets contain *191* common countries.
   - *40 countries* are in the disaster dataset but missing in the population dataset (e.g., AIA, ANT, ASM, COK, CSK, CYM, DDR, GLP).
   - *6 countries* are in the population dataset but missing in the disaster dataset (e.g., AND, HOS, LIE, MCO, NRU, SMR).

These summaries highlight data inconsistencies and gaps that may need addressing for accurate analysis.
