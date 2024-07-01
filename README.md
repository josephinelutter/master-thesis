# Predicting Dengue Fever Incidence and Disease Dynamics under Climate Change in Southeast Asia
This repository contains the code and data for the master's thesis "Predicting Dengue Fever Incidence and Disease Dynamics under Climate Change in Southeast Asia" by Josephine Lutter, supervised by Professor Roberto Henriques. This master's thesis was presented as a partial requirement for obtaining the master’s degree in Data Science and Advanced Analytics, with a specialization in Business Analytics, at NOVA Information Management School, Universidade Nova de Lisboa.

## Keywords
Dengue Fever; Incidence Forecast; Deep Learning; Machine Learning; Climate Change

## Structure
For each of the 17 Southeast Asian locations, a notebook was created for initial exploratory analysis and data preparation of the raw secondary data obtained. Using Singapore as an example:

- Notebook 1: The input file is "Singapore.xlsm" and the output file "Singapore Cleaned.xlsx" contains the dataset with imputed values.
- Notebook 2: The input file is "Singapore 2.xlsm" and the output file "Singapore 3.xlsx" encompasses the dataset with location-specific outlier capping.
- Notebook 3a: The input file "All locations combined.xlsx" has two sheets: "With outlier capping" holds the combined datasets of all locations with location-specific capping, and "Without outlier capping" holds the combined datasets of all locations without outlier treatment, used for machine learning models.
- Notebook 3b: The input file "All locations combined.xlsx" has two sheets: "With outlier capping" holds the combined datasets of all locations with location-specific capping, and "Without outlier capping" holds the combined datasets of all locations without outlier treatment, used for deep learning models. For the climate change assessment, the datasets "Simulations RCP4.5_mod.xlsx" and "Simulations RCP8.5_mod.xlsx" hold the modifications according to simulated changes.

## License
This repository is licensed under the MIT License.
