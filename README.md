# Outlier Node Model Training
## Data Preprocessing
* Data was gathered from the NASA IMS Bearing Data Set
* This data was melted and combined into a single parquet file containing over 7 million records
* We use polars instead of pandas and a parquet instead of csv for efficiency in order to handle all of this data