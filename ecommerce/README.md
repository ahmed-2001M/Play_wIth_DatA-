# About Dataset

The dataset contains 541,909 entries and has the following columns:

## Columns
- **InvoiceNo**: Unique ID for each transaction.
- **StockCode**: Product code.
- **Description**: Description of the product.
- **Quantity**: The quantity of products purchased in a single transaction.
- **InvoiceDate**: Date and time of the transaction.
- **UnitPrice**: Price of each unit of the product.
- **CustomerID**: Unique ID for each customer.
- **Country**: Country where the transaction was made.

## Columns added after Feature Engineering
- **year**: Year of the transaction.
- **month**: Month of the transaction.
- **day**: Day of the transaction.
- **hour**: Hour of the transaction.
- **day_name**: Name of the day of the week (e.g. Monday, Tuesday, etc.).
- **month_name**: Name of the month (e.g. January, February, etc.).
- **item_problem**: Whether the product description indicates an item issue or not.
- **is_free**: Whether the transaction involved a free item or not.
- **is_canceld**: Whether the transaction was canceled or not.
- **Revenue**: The total revenue generated from the transaction.

## Columns that have nulls
- **Description :	0.27 %**
- **CustomerID :	    24.93 %**


## Observations from Univariate Analysis

- **InvoiceNo**:
  - there is Invoices have Id starts with C Indicates to Cancelation
  - this InvoiceNo 573585 is the most frequent Invoice

