# Incenza Product Data

This repository contains extracted product data from the Incenza perfume website (https://www.incenza.com/).

## Files

- `incenza_products.csv` - CSV file containing product information including:
  - Product Name
  - Brand
  - Product Type
  - Product Code
  - Product Details
  - Price Range (where available)
  - Category

## Usage

You can download the CSV file and import it into Excel or any spreadsheet software for further analysis.

### Excel Import Instructions

1. Download the `incenza_products.csv` file
2. Open Excel
3. Go to Data > From Text/CSV
4. Select the downloaded CSV file
5. In the import wizard, ensure the delimiter is set to "Comma"
6. Click "Load" to import the data

## Notes

- Price information is limited as the website doesn't display prices consistently without selecting specific options
- Product codes are extracted from the URL paths
- Product details are summarized from the available descriptions
- "Low Price" designation is included when explicitly mentioned on the website