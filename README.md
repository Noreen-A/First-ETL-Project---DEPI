# Data Engineering Mock Task

Workflow: Python, Pandas, Faker, SQL Server (SSMS), SQLAlchemy (Docker optional). Generates mock data (Products JSON, 12 CSVs, Customers). Loads 12K transactions into Orders. Handles delta inserts, updates product prices, and uses merge/change data capture to sync modified & new transactions. Skills: ETL, DWH, incremental loading, SQL.

## Features
- Mock data generation for products, transactions, and customers.
- First load of 12K transactions into Orders table.
- Delta inserts for new daily data.
- Product price updates reflected in Orders.
- Merge/Change Data Capture for updated and new transactions.

## Tools Used
- Python, Pandas, Faker
- SQL Server (SSMS), SQLAlchemy
- Docker (optional)

## Skills Demonstrated
- ETL Pipelines
- Data Warehousing Basics
- Incremental Loading
- Data Modeling
- SQL Operations
