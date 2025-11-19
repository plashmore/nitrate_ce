# Statistical Analysis
## 01-nitrate_analysis.ipynb
- Requires raw data from `01-input_data`
- Requires pickled calibration curve output from `02-calibration_curve`
- Uses calibration curve from earlier to calculate nitrate concentrations from raw data
- Calculates means of repeated measures
- Uses rigorous error propagation to calculate error for means
- Outputs data in to csv for future use
## 02-plots.ipynb
- Plots and models data from previous step
- Performs statistical analyses including normality testing (Shapiro-Wilks) and testing for heteroscedasticity (Breusch-Pagan)
- Also plots raw data from elecropherograms for publication
    - Requires raw data CSVs from `01-input_data`
