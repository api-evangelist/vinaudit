# VINaudit

Vehicle history and VIN decoding REST API for accessing accident records, title information, mileage history, ownership records, and NHTSA recall data for any US vehicle. VINaudit is an NMVTIS-approved data provider founded in 2011, headquartered in Kirkland, Washington.

## APIs

- **Vehicle History API** - Raw vehicle history data from NMVTIS covering title records, odometer readings, accident records, salvage information, and theft records for US and Canada vehicles
- **Vehicle Specifications API** - Standardized vehicle specifications by VIN or YMMT including engine, transmission, fuel economy, dimensions, colors, equipment, recalls, warranties, and photos
- **Vehicle Market Value API** - Current market value estimates using aggregated data from millions of recent sale listings with low, average, and high-end values
- **Vehicle Ownership Cost API** - 5-year total cost of ownership calculations by VIN covering depreciation, insurance, fuel, maintenance, repairs, and taxes
- **Vehicle Image API (Beta)** - Original stock vehicle images by make, model, year, and trim

## API Endpoints

- `https://api.vinaudit.com/v2/query` - Query VIN records
- `https://api.vinaudit.com/v2/pullreport` - Generate vehicle history report
- `https://api.vinaudit.com/v2/report` - View generated report
- `https://specifications.vinaudit.com/v3/specifications` - Vehicle specifications
- `https://specifications.vinaudit.com/v3/selections` - Vehicle selections

## Authentication

API key-based authentication. Keys are generated from the VINaudit members dashboard after account registration. Pass the key as a `key` query parameter in all requests. A demo key (`VA_DEMO_KEY`) is available for testing.

## Links

- [Website](https://www.vinaudit.com)
- [Developer Guide](https://www.vinaudit.com/vin-api-developers-guide)
- [Vehicle Data API](https://www.vinaudit.com/vehicle-data-api)
- [Blog](https://www.vinaudit.com/blog)
- [LinkedIn](https://www.linkedin.com/company/vinaudit)
- [X / Twitter](https://twitter.com/vinauditllc)

## APIs.json

This repository contains an [APIs.json](apis.yml) index file cataloging VINaudit's public APIs, along with supporting documentation for pricing plans, rate limits, and FinOps guidance.
