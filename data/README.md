# Dataset Information

This project uses the **Online Retail Dataset** for customer cohort and Customer Lifetime Value (CLTV) analysis.

## Dataset

**File Name:** `OnlineRetail.csv`

This dataset contains transactional records for a UK-based online retail company, including:

- Invoice Number
- Stock Code
- Product Description
- Quantity
- Invoice Date
- Unit Price
- Customer ID
- Country

## Why isn't the dataset included?

The dataset is not included in this repository because it is relatively large and to keep the repository lightweight.

## How to use

1. Download the **Online Retail Dataset** from a trusted source.
2. Rename the file to:

```
OnlineRetail.csv
```

3. Place it inside the `data/` directory:

```
data/
└── OnlineRetail.csv
```

4. Run the notebook:

```
notebooks/Cohort_Analysis.ipynb
```

The notebook will automatically load the dataset from:

```python
../data/OnlineRetail.csv
```

## Expected Dataset Format

| Column |
|---------|
| InvoiceNo |
| StockCode |
| Description |
| Quantity |
| InvoiceDate |
| UnitPrice |
| CustomerID |
| Country |