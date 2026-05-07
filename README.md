# MDOT Transfer Analysis

An analysis of MDOT's MTA transfer performance.

## Deliverables

### 1. `___.sql`
A PostgreSQL database dump containing the integrated and normalized MTA transit 
datasets. Can be restored using `psql` to recreate the database schema and data.

### 2. `MDOT_Transfer_Analysis.pbit`
A Power BI template file containing the transit performance dashboards. Open in 
Power BI Desktop and connect to the restored PostgreSQL database to populate the 
visuals.
