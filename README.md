# FDA-Import-Refusals

*Work in progress*

In this repository, I will use the ETL process (in Python/Jupyter Notebooks) to transform the FDA Compliance Dashboard dataset "Import Refusals". The goal of this repository is cleaning the data in order to ask the data specific questions that are not readily available from the existing dashboard.

The Import Refusals compliance dashboard (with visualizations) can be found here: https://datadashboard.fda.gov/ora/cd/imprefusals.htm

The full dataset as it is presented on that site, along with the reference guide for the column "Section Charges," are included in the Resources folder here.

## Challenges

### Incomplete information

The "full" dataset is available for download, but it is clear from the filters and visualizations included on https://datadashboard.fda.gov/ora/cd/imprefusals.htm that there is additional information that is not included in the downloadable dataset, namely the categorization by product type. However, it is possible to download filtered datasets by product type. Therefore one goal in reconstructing the full dataset will be to add a column 'Product Type' with the information from the filtered data.

### Multiple types of information contained in one column

In several instances, multiple data points are stored in one column. These will need to be extracted for more effective use.

### Refusal Charges

The Refusal Charges Reference will need to be merged with the main dataset for more informative visualizations.

## Techniques


## Dashboards and Data
