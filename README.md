# Flight Analysis and Monte Carlo Simulation

Programming for Data Science coursework using Python and R to explore US flight data and implement the Random Walk Metropolis–Hastings algorithm.

**Author:** Darren Alexander  
**Institution:** University of London, SIM Global Education  
**Course:** Programming for Data Science (ST2195)  
**Period:** January–April 2025

## Project Overview

This project contains two components, each implemented in Python and R with accompanying reports.

### 1. US Flight Analysis

Explored 50,000 flight records by loading the first 10,000 records from each year between 2004 and 2008.

The analysis includes:
- Preparing and combining flight data across five years.
- Exploring departure delays by day of the week and time of day.
- Investigating the relationship between aircraft age and departure delays.
- Applying logistic regression to investigate flight diversions.
- Presenting results through visualisations and written analysis.

### 2. Metropolis–Hastings Simulation

Implemented a Random Walk Metropolis–Hastings sampler for a Laplace target distribution.

The simulation includes:
- Generating a chain of 10,000 samples.
- Calculating sample statistics and acceptance rates.
- Comparing simulated samples with the theoretical density.
- Exploring the effect of proposal step size on multiple chains.

## Tools and Methods

- Python and Jupyter Notebook
- R and R Markdown
- Data cleaning and visualisation
- Exploratory data analysis
- Correlation analysis
- Logistic regression
- Markov Chain Monte Carlo (MCMC)
- Metropolis–Hastings sampling

## Project Files

| Component | Python Notebook | R Markdown | Report |
|---|---|---|---|
| Flight analysis | [Python](Flight_Analysis_Python.ipynb) | [R](Flight_Analysis_R.Rmd) | [PDF](Flight_Analysis_Report.pdf) · [Word](Flight_Analysis_Report.docx) |
| Monte Carlo simulation | [Python](Metropolis_Hastings_Python.ipynb) | [R](Metropolis_Hastings_R.Rmd) | [PDF](Simulation_Report.pdf) · [Word](Simulation_Report.docx) |

## How to Explore the Project

1. Start with the PDF reports for the analysis and visualisations.
2. Open the Python notebooks to review the code and saved outputs.
3. View the R Markdown files for the R implementations.

To run the code locally, install the packages imported in each file. The flight analysis also requires the original datasets and updates to the local file paths.

## Data and Limitations

The original flight datasets are not included in this repository.

The flight analysis uses the first 10,000 records from each year rather than a random sample, so findings may not represent all US flights. Delay counts should also be distinguished from delay rates when comparing groups.

These files preserve the original academic submission. The statistical methods, convergence diagnostic implementation, and model evaluation should be reviewed before reusing the results.
