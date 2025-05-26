# nashville-housing-data-cleaning
This repository contains SQL scripts used to clean and prepare the Nashville Housing dataset for analysis.

## Cleaning Concepts Covered

- Standardize `SaleDate` format  
- Populate missing `PropertyAddress` values  
- Split `PropertyAddress` into Address and City  
- Split `OwnerAddress` into Address, City, and State  
- Convert `SoldAsVacant` values from Y/N to Yes/No  
- Remove duplicate records using `ROW_NUMBER()` and CTE  
- Drop unused columns
