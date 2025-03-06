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
  - Size Options (where available)
  - Lowest Price (where available)

## Usage

You can download the CSV file and import it into Excel or any spreadsheet software for further analysis.

### Excel Import Instructions

1. Download the `incenza_products.csv` file
2. Open Excel
3. Go to Data > From Text/CSV
4. Select the downloaded CSV file
5. In the import wizard, ensure the delimiter is set to "Comma"
6. Click "Load" to import the data

## Pricing Information

The CSV now includes detailed pricing information where available:

- **Price Range**: Shows the range of prices for different sizes (e.g., "€20.29 - €54.52")
- **Size Options**: Lists available sizes with their corresponding prices (e.g., "100ml (€20.29), 200ml (€27.65)")
- **Lowest Price**: Shows the lowest price available for the product

For products marked as "Low Price" on the website, the actual lowest price is now included when available.

## Notes

- Price information is extracted directly from product pages where available
- Product codes are extracted from the URL paths
- Product details are summarized from the available descriptions
- "Low Price" designation is included when explicitly mentioned on the website
- Some products don't display pricing information without selecting specific options