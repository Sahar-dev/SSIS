# SSIS Purchase Data ETL Project

## Introduction

Welcome to the SSIS Purchase Data ETL (Extract, Transform, Load) project. This project aims to implement a robust ETL process using SQL Server Integration Services (SSIS) to extract data from the AdventureWorks database, transform it, and load it into a Data Warehouse named "Datawarehouse." The Data Warehouse will serve as a foundation for creating insightful dashboards on purchasing activities.
![project scheme](https://github.com/Sahar-dev/SSIS/blob/main/images/Star.PNG)

## Features

- **Data Extraction:** Extracts relevant purchase data from the AdventureWorks database.
- **Transformation:** Applies necessary transformations to clean, enrich, and structure the data.
- **Data Loading:** Loads the transformed data into the Datawarehouse Data Warehouse.
- **Fact Table:** Implements a Fact Table named `FactPurchase` capturing key purchasing metrics.
- **Dimension Tables:** Creates Dimension Tables for `DimEmployee`, `DimProduct`, `DimVendor`, and `DimShipMethod`.
- **Documentation:** Comprehensive documentation detailing project structure, data models, and ETL processes.

## Getting Started

### Prerequisites

Before getting started, ensure the following are installed:

- SQL Server with AdventureWorks database
- SQL Server Data Tools (SSDT) or SQL Server Management Studio (SSMS)
- SQL Server Integration Services (SSIS)

### Installation

1. Clone the repository:

   ```bash
   https://github.com/Sahar-dev/SSIS.git
2. Open the SSIS project in SQL Server Data Tools.

3. Update connection strings and configurations in SSIS packages as needed.
### Usage
1. Execute the SSIS packages in the correct order for data extraction, transformation, and loading.

2. Monitor SSIS execution logs for any issues or errors.

3. Explore the generated Datawarehouse Data Warehouse for insights.

### Documentation
For detailed information on the project, including project structure, data models, and ETL processes, refer to the full documentation.
