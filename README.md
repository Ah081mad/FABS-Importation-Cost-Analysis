# Importation Cost Analysis – FABS IMPORTATION COMPANY

## Project Overview
This Excel-based analysis simulates the role of a Junior Accountant at **FABS IMPORTATION COMPANY**, focusing on the financial implications of importing goods from China to Nigeria. The project covers unit pricing, shipping costs, cost breakdowns, and profit margins using real-world business logic.

## Dataset
The data was provided in a worksheet titled **"WEEK 3 DATA A"** and includes:
- Item names
- Quantity
- Total price in RMB
- Exchange rates
- Shipping weight and costs

## Key Calculations Performed
- Unit price in **RMB** and **Naira**
- Per-unit **shipping cost**
- Total **buying price** (unit + shipping)
- **Selling price** (with 15% margin)
- Percentage of **shipping vs unit price**
- **Total cost** of all purchases and shipping
- **Average shipping fee**
- **Percentage change** from unit cost to full cost

## Tools Used
- Microsoft Excel
- Advanced Formulas: `=SUM()`, `=AVERAGE()`, `=IF()`, `=ROUND()`
- Currency conversion logic
- Formatting and table customization

## Sample Calculations
```excel
=Total_Price / Quantity                     // Unit Price (RMB)
=Unit_Price * Exchange_Rate                // Unit Price (NGN)
=Buying_Price * 1.15                        // Selling Price
