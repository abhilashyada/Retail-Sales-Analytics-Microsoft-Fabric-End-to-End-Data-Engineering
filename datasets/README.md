# Source datasets

Copy the contents of `landing/` into the Fabric Lakehouse `Files/landing/` directory, preserving subfolders.

| File | Data rows |
|---|---:|
| customers/customers.csv | 8 |
| products/products.csv | 6 |
| sales/sales.csv | 55 |

The sales file intentionally includes a duplicate sale ID (S0050), zero quantity (S0051), unknown customer (S0052), negative price (S0053), and invalid date (S0054). Preserve these records to demonstrate Bronze deduplication and quarantine and Silver validation.

Expected reconciliation: 55 raw rows, 54 distinct sale IDs, 53 Bronze accepted rows, 50 Silver accepted rows.

Publish customer records only if synthetic or approved for public sharing.
