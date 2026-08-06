# Sales Performance Analysis Dashboard

Power BI dashboard analyzing 100,000 sales transactions across 
product, customer, and time dimensions.

## Screenshot
<img width="1262" height="708" alt="image" src="https://github.com/user-attachments/assets/b09609fd-e85f-44ea-a794-20d04ec3cf2a" />


## Key Insights
- Electronics & Accessories are the most profitable categories (~39%, ~38.6% margin)
- Any discount reduces profit margin by ~6.6 percentage points
- 60%+ of orders come from Bronze-tier customers
- Sales have stayed flat (~$10M/year) since 2018

## Data Model
Star schema: FactSales (100K rows) + DimProduct + DimCustomer + DateTable

## Tools
Power BI Desktop, DAX, Power Query

## Files
- `PROJECT.pbix` — full interactive dashboard
- `PowerBI_Final_Presentation.pptx` — presentation deck
- `data/` — source CSVs
- `docs/dax-measures.md` — DAX reference
