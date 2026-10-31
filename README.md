# Machine Learning and Sustainability Metrics: Optimising Risk Assessment and Default Prediction

This project links ESG sustainability indicators of energy-sector companies to financial risk. It estimates the probability of default (PD) and supports risk-weighted-asset calculation. It was an MSc project in Data Analysis for Business Intelligence at the University of Leicester.

## Data

| File | Content |
| --- | --- |
| `Sustainability_Data.xlsx` | 316 listed energy-sector companies with 16 ESG indicators: total and methane GHG emissions, safety incidents, workforce, women's representation, energy use and generation, water consumption |
| `Data_PD_Final.CSV` | Financial indicators per company: expected return, volatility, face value, enterprise value, and the estimated probability of default (PD) |

The data were gathered by web scraping company sustainability reports and extracting tables from PDFs. Ten Python PDF libraries were benchmarked for this step. See `Dataset_Documentation_sustainability_Risk_Weight_Asset_Calculation.pdf` for the variables and collection method.

## Code

The analysis code is in a Google Colab notebook. `Demonstration of the project in Google Colab.pdf` contains the link to open and run it.

## Licence

No licence has been declared yet.

## Author

Md Abu Sufian - ORCID [0009-0007-3503-6942](https://orcid.org/0009-0007-3503-6942)
