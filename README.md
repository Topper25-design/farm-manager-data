# Farm Manager Price Data

This repository contains market price data for agricultural commodities across different currencies and regions.

## Data Structure

The price data is stored in `prices.json` with the following structure:

```json
{
  "CURRENCY_CODE": {
    "COMMODITY_NAME": {
      "REGION_NAME": PRICE_VALUE
    }
  }
}
```

### Supported Currencies
- ZAR (South African Rand)
- USD (US Dollar)
- GBP (British Pound)
- EUR (Euro)
- AUD (Australian Dollar)

### Commodities by Currency
Each currency has its own set of relevant commodities:

#### ZAR
- Maize
- Wheat

## Usage

The data can be accessed directly via the GitHub raw content URL:
```
https://raw.githubusercontent.com/YOUR_USERNAME/farm-manager-data/main/prices.json
```

## Updates

Price data is updated regularly to reflect current market conditions. 