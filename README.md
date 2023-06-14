# CSV Data Mapping Project

This project involves mapping the product descriptions from two CSV files. One CSV file contains data scrapped from Amazon, while the other CSV file contains point-of-sale (POS) data from a pharmacy company.

## Purpose

The purpose of this project is to map the product descriptions from the POS terminal CSV file with the corresponding "ED_MDM_PRODUCT_CODE" from the Amazon CSV file. By doing so, we aim to identify and match the products sold by the pharmacy company with the corresponding products available on Amazon.

## Features

- **CSV Data Import**: The project allows importing the two CSV files containing the necessary data for mapping.
- **Data Mapping**: The project provides functionality to map the product descriptions from the jaggi_756_ProductMaster.csv CSV file with the corresponding "ED_MDM_PRODUCT_CODE" from the amazon_ds file.
- **Result Export**: Once the mapping is complete, the project enables exporting the mapped data into a new CSV file for further analysis or integration with other systems.

## Technologies Used

- Python
- Pandas (Python library for data manipulation and analysis)
- CSV (Comma-Separated Values) file handling

## Usage

1. Clone the project repository from GitHub.
2. Install the required dependencies specified in the `A_final.ipynb` file.
3. Place the two CSV files, namely `amazon_data.csv` and `jaggi_756_ProductMaster.csv`, in the project directory.
4. Run the main script, `data_mapping.py`, to perform the mapping process.
5. Once the mapping is completed, the script will generate a new CSV file, `amazon_catalogue_modified.csv`, containing the mapped data.
