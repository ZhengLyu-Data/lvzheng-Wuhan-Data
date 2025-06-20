## Overview
This project analyzes supply chain efficiency using a cleaned dataset of 10,999 shipment records. It highlights operational bottlenecks, delivery timeliness, and product shipment cost-performance through structured SQL logic and dashboard visualization.

## Data Visualization
The dashboard includes the following charts:

![metabase dashboard image](chart1_mode_of_shipment.png)
![metabase dashboard image](chart2_discount_by_importance.png)
![metabase dashboard image](chart3_rating_vs_cost.png)

## Data Architecture

![Data Architecture](supply_chain_data_pipeline_architecture.png)

## Prerequisites
- Python 3.10+
- Pandas / metabase
- SQLite (optional for local storage)
  
## How to Run This Project

- Step 1: Load data (already cleaned)
- Step 2: Use visualization script or Metabase dashboard builder
- Step 3: Review insights from chart outputs

🧩 Note on SQL Compatibility:
All SQL scripts in this project are designed using standard SQL syntax. While executed with SQLite for simplicity, the same structure is compatible with MySQL or PostgreSQL by changing the database connector and placeholder syntax (`?` → `%s`).

## Lessons Learned
- Product cost and customer rating are not always correlated
- Discounts vary more significantly by shipment method than product tier
- Shipment mode optimization directly impacts delivery timeliness

## Contact
For questions or collaboration: Linkedin and Tiwtter
