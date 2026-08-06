# Resources

This folder contains local resources required for development.

## Dataset

This project uses the **Cleaned Contoso Dataset**.

Download it from:

https://www.kaggle.com/datasets/bhanuthakurr/cleaned-contoso-dataset

Extract the dataset into:

resources/
└── ContosoData/


> The `ContosoData` folder is ignored by Git and is not included in the repository.

---

## Tables Used

The semantic model currently imports the following tables:

### Fact Table

- FactSales

### Dimension Tables

- DimDate
- DimProduct
- DimProductSubcategory
- DimProductCategory
- DimPromotion

Additional tables from the dataset are intentionally excluded because they are not required for the current version of the semantic model.

---

## Notes

- The dataset is used for local development only.
- Report developers should download the dataset before opening the PBIP project.