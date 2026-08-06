# Semantic Model

## Purpose

This semantic model is the shared dataset for all Power BI reports in this project.

It provides a single source of truth for business calculations and KPIs.

---

## Model Design

The model follows a Star Schema.

### Fact Table

```
FactSales
```

### Dimension Tables

```
DimDate
DimProduct
DimProductSubcategory
DimProductCategory
DimPromotion
```

---

## Relationships

- One-to-Many relationships
- Single-direction filtering
- Star Schema design

---

## Measure Table

```
Measure Catalog
```

All business measures are stored in the Measure Catalog table.

---

## Initial Measures

### Sales

- Total Sales
- Sales Quantity
- Average Selling Price

### Cost

- Total Cost

### Profit

- Total Profit
- Profit Margin %

### Orders

- Total Orders
- Average Order Value

---

## Date Table

- Table: `DimDate`
- Date Column: `DateKey`
- Marked as the official Date table

---

## Model Standards

- Keep calculations in measures.
- Hide technical key columns.
- Use descriptive names for measures.
- Avoid unnecessary calculated columns.

---

## Planned Enhancements

- Time Intelligence measures
- KPIs
- Executive metrics
- Calculation Groups
- Field Parameters