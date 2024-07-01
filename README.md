# Predicting Dengue Fever Incidence and Disease Dynamics under Climate Change in Southeast Asia
This repository contains the code and data for the master's thesis "Predicting Dengue Fever Incidence and Disease Dynamics under Climate Change in Southeast Asia" by Josephine Lutter and supervised by Professor Roberto Henriques. This master's thesis was presented as a partial requirement for obtaining the Master’s degree in Data Science and Advanced Analytics, with a specialization in Business Analytics, at NOVA Information Management School, Universidade Nova de Lisboa.

## Keywords
Dengue Fever; Incidence Forecast; Deep Learning; Machine Learning; Climate Change

## Structure
For each of the 17 Southeast Asian locations, a notebook was created for initial exploratory analysis and data preparation of the raw secondary data obtained. Using Singapore as an example:

- Notebook 1: The input file is "Singapore.xlsm" and the output file "Singapore Cleaned.xlsx" contains the dataset with imputed values.
- Notebook 2: The input file is "Singapore 2.xlsm" and the output file "Singapore 3.xlsx" encompasses the dataset with location-specific outlier capping.
- Notebook 3a: The input data file "All-combined.xlsx" has two sheets: "With" holds the combined datasets of all locations with location-specific capping, and "Without" holds the combined datasets of all locations without outlier treatment, used for machine learning models.
- Notebook 3b: The input data file "All-combined.xlsx" has two sheets: "With" holds the combined datasets of all locations with location-specific capping, and "Without" holds the combined datasets of all locations without outlier treatment, used for deep learning models.

## License
This repository is licensed under the MIT License.
