# Shopee Product Dataset & Data Collection Service

Structured, analysis-ready Shopee product data for e-commerce research, market intelligence, pricing analysis, competitor monitoring, and product discovery.

This repository contains a limited sample dataset. Larger datasets, custom keywords, categories, stores, markets, and scheduled updates are available on request.

---

## What We Provide

We collect and structure publicly available Shopee product information into clean datasets that are easy to use in Python, Excel, databases, BI tools, and machine learning workflows.

Available delivery formats:

- JSON
- JSONL
- CSV
- Excel
- Custom database schema
- API or scheduled file delivery

---

## Supported Markets

Current coverage may include:

- Taiwan
- Singapore
- Malaysia
- Indonesia
- Thailand
- Vietnam
- Philippines
- Brazil
- Colombia
- Chile
- Argentina
- Cambodia
- Laos

Market availability and field coverage may vary by country.

---

## Available Data Fields

Depending on the market and product category, datasets may include:

- Country / market
- Search keyword
- Product ID
- Shop ID
- Product title
- Product description
- Current price
- Minimum price
- Maximum price
- Original price
- Currency
- Discount information
- Historical sales
- Product rating
- Rating count
- Product images
- Brand
- Category path
- Shop location
- Product condition
- SKU / variation name
- Model ID
- SKU price
- Stock availability
- Estimated shipping days
- Pre-order status
- Collection timestamp
- Raw structured product metadata

Custom fields can be discussed before collection.

---

## Example Record

```json
{
  "country": "tw",
  "keyword": "iphone 16",
  "item_id": "example_item_id",
  "shop_id": "example_shop_id",
  "name": "Apple iPhone 16 128GB",
  "price": 15500,
  "price_min": 15500,
  "price_max": 17500,
  "currency": "TWD",
  "sold": 25,
  "rating_star": 4.9,
  "rating_count": 68,
  "brand": "Apple",
  "categories": [
    "Mobile & Accessories",
    "Mobile Phones"
  ],
  "shop_location": "New Taipei City",
  "sku_count": 4,
  "has_stock": true,
  "crawl_time": 1783156967
}
```

The example above is simplified. Actual field availability depends on the source market, product, seller, and requested dataset.

---

## Use Cases

This dataset can be used for:

- Competitor price monitoring
- Product and category research
- Cross-market price comparison
- Brand and seller analysis
- Market trend analysis
- Product availability tracking
- SKU and variation analysis
- E-commerce dashboards
- Data science and machine learning
- Lead generation based on public business information
- Academic and commercial research

---

## Custom Data Collection

Custom collection options include:

- Specific keywords
- Product categories
- Shop or seller lists
- Product ID lists
- Multiple Shopee markets
- Daily, weekly, or monthly updates
- Price and stock monitoring
- Custom output fields
- Deduplication and normalization
- Translation and language normalization
- Database-ready exports

Please provide the following information when requesting a quote:

1. Target country or countries
2. Keywords, categories, shops, or product URLs
3. Required fields
4. Estimated number of records
5. Update frequency
6. Preferred output format
7. Delivery deadline

---

## Sample Dataset

The files in this repository are limited samples intended to demonstrate:

- Field coverage
- Data structure
- Output quality
- Encoding and formatting
- Multi-market compatibility

The public sample may contain anonymized IDs, shortened descriptions, reduced image data, and limited record counts.

Full datasets are not published directly in this repository.

---

## Data Quality

The collection pipeline may include:

- Duplicate removal
- Price normalization
- Currency preservation
- Category normalization
- SKU extraction
- Unicode and emoji support
- Invalid record filtering
- Timestamping
- Optional personal-data removal
- JSON schema validation

Because marketplace content changes frequently, no dataset should be treated as permanently static.

---

## Delivery Options

Available delivery methods may include:

- GitHub Release
- Private cloud storage
- Google Drive
- S3-compatible storage
- Secure file transfer
- Email for small samples
- Scheduled delivery
- Custom API integration

---

## Pricing

Pricing depends on:

- Number of markets
- Number of records
- Data complexity
- Required fields
- Collection frequency
- Delivery method
- Custom processing requirements

Contact us for a sample and quotation.

---

## Contact

For samples, custom datasets, or commercial cooperation:

- Email: `zhouhongenlu@gmail.com`
- Telegram: `@+44 75 4867 2793`
- X / Twitter: `[@zhouhongen](https://x.com/MANYCANFUN)`
- GitHub: `[https://github.com/zhouhongen](https://github.com/zhezhouhongen)`

Replace the placeholders above with your real contact details.

---

## Important Notice

This project is not affiliated with, endorsed by, or sponsored by Shopee or Sea Limited.

Shopee and related names, logos, and trademarks belong to their respective owners.

Datasets are intended to contain publicly available product information only. Buyers and users are responsible for ensuring that their use of the data complies with applicable laws, privacy requirements, intellectual property rules, contractual obligations, and platform terms.

No account credentials, private messages, payment information, authentication tokens, cookies, or non-public personal data are included.

---

## License

The sample data and collection scripts may use separate licenses.

Before using this repository, review:

- `LICENSE` for source code
- `DATA_LICENSE.md` for dataset usage terms

Commercial redistribution of the full dataset is not permitted unless separately agreed in writing.
