# Coding Standards

## Tables

- Fact tables start with `Fact`.
- Dimension tables start with `Dim`.
- Use singular names where possible.

Examples

```
FactSales
DimDate
DimProduct
```

## Measures

Use descriptive names.

Good

```
Total Sales
Total Profit
Average Order Value
```

Avoid

```
Sales1
Measure1
Test
```

## Formatting

- Currency → Sales, Cost, Profit
- Percentage → Margin, Growth
- Whole Number → Counts

## Model Design

- Use a Star Schema.
- Avoid unnecessary calculated columns.
- Keep business logic in measures.
- Hide technical keys from report users.