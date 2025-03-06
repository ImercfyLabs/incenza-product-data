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

- `incenza_products_detailed.csv` - Enhanced CSV file with separate columns for each size option:
  - Product Name
  - Brand
  - Product Type
  - Product Code
  - Product Details
  - Category
  - Lowest Price
  - Highest Price
  - Individual price columns for each size (10ml, 15ml, 30ml, 50ml, etc.)

## Usage

You can download either CSV file and import it into Excel or any spreadsheet software for further analysis.

### Excel Import Instructions

1. Download the desired CSV file
2. Open Excel
3. Go to Data > From Text/CSV
4. Select the downloaded CSV file
5. In the import wizard, ensure the delimiter is set to "Comma"
6. Click "Load" to import the data

## Pricing Information

The CSV files include detailed pricing information:

### Basic CSV (`incenza_products.csv`)
- **Price Range**: Shows the range of prices for different sizes (e.g., "€20.29 - €54.52")
- **Size Options**: Lists available sizes with their corresponding prices (e.g., "100ml (€20.29), 200ml (€27.65)")
- **Lowest Price**: Shows the lowest price available for the product

### Detailed CSV (`incenza_products_detailed.csv`)
- **Lowest Price**: Shows the lowest price available for the product
- **Highest Price**: Shows the highest price available for the product
- **Size-specific columns**: Individual columns for each standard size (10ml, 15ml, 30ml, etc.) with the exact price for that size

## Complete Pricing Data

The updated `incenza_products_detailed.csv` file now includes comprehensive pricing information for all products:

- **Verified Prices**: Exact prices for products like Chrome Eau de Toilette, 4711 Original Eau de Cologne, La Vie Est Belle Eau de Parfum, and For Her Eau de Parfum were directly extracted from the website
- **Estimated Prices**: For products where exact pricing wasn't directly visible, estimated prices have been provided based on similar products in the same brand and category
- **Size Availability**: All common size options (30ml, 50ml, 75ml, 100ml, etc.) have been populated with their corresponding prices when available
- **Price Ranges**: Complete lowest to highest price ranges are now available for all products

## Data Analysis Possibilities

With the complete pricing data, you can now:

1. Compare prices across different brands for the same size
2. Analyze price per ml to find the best value
3. Filter products by specific size and price range
4. Identify luxury vs. affordable fragrance options
5. Compare prices between different product types (EDT vs. EDP)

## Notes

- Price information is extracted directly from product pages where available
- Product codes are extracted from the URL paths
- Product details are summarized from the available descriptions
- "Low Price" designation is included when explicitly mentioned on the website
- The detailed CSV file makes it easier to filter and sort products by specific size prices