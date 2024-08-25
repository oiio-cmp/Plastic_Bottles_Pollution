# Prediction Of Plastic Bottles Pollution With Linear Regression

## Executive Summary
The project aims to predict trends in plastic bottle litter from major manufacturers using a linear regression model. Sourced from Kaggle dataset ([URL link](https://www.kaggle.com/code/wastebase/country-of-manufacture-vs-detection/output?scriptVersionId=188923245)) was selected for its sufficient amount of records and its linkage to specific manufacturers, enabling a focused analysis of plastic waste trends.
Initial findings unsurprisingly indicate Coca-Cola with the highest projected increase in plastic bottle waste
in the next two years w. Overall, the trends show consistent growth in plastic waste across all manufacturers, signalling an upward trajectory in plastic bottle littering unless serious interventions are implemented.

## Project Background
This project emerged from a strong personal opposition to littering and single-use plastics, given their harmful impact on ecosystems, particularly from chemicals like Bisphenol (Verma et al., 2016). Plastics degrade slowly, according to Loakeimidis et al. (2016), “PETs seem to remain robust for approximately fifteen years” leading to the accumulation of plastic debris that damages wildlife and disrupts ecological balance.
To address this issue, I used a publicly available dataset containing “regularly-collected data about single-use plastic bottle waste found in public spaces, identified to the level of individual commercial products” (Kaggle, 2024). Data collection occurred predominantly in Africa, with some contributions from Europe. The row data is available in CSV format, with one CSV file per month of data.
The results are planned to be presented via social media to raise public awareness by demonstrating real-world trends in plastic pollution as consequences of littering.
I believe that raising awareness can encourages more people to reconsider their choices before purchasing another bottle of Coca-Cola or Pepsi. 

## Methodology
The methodology for this project involved using a linear regression model to predict future plastic bottle waste trends based on historical data from major manufacturers. Linear regression was selected for its simplicity and effectiveness in capturing time-based trends, particularly given the dataset's moderate size (12 000 rows) and clear temporal structure.

## Data Security and Ethical Considerations
This project handles data based on litter collected in public environments. While it does not involve personal information, care was taken to ensure accurate representation of manufacturers' contributions to environmental pollution. 
Ethical considerations include avoiding misrepresentation or bias when reporting manufacturers' impact. Given that the data reflects human observations, it was rigorously cleaned and validated to reduce inaccuracies.
 Transparency in the analysis was prioritized to ensure that the findings are used to support genuine environmental improvements rather than unfairly targeting specific manufacturers.
Additionally, any findings should be used to promote positive environmental change, avoiding misuse for greenwashing or misrepresentation of sustainability efforts.

## Data Collection and Preparation
The initial step starts with  csv files ingestion into SQL Server using SQL Server Integration Services (SSIS) into pre-existing table. The choice of SQL Server was determined by the familiarity and proficiency with the tool in applying data validation and cleanse techniques. 
Given the potential risks to data quality from manual inputs in the raw data, a rigorous analysis was conducted, including the following steps:
1. Imported fields format adjusted:
   
# URL image link
![Image URL](https://statisticsbyjim.com/wp-content/uploads/2020/07/TimeSeriesTrade.png)
# URL links
[URL link](https://donnemartin.com/#portfolio)

# bring in picture from file upload
![Folder Upload](.assets/Imgaes/CSVFormatImport.png)

