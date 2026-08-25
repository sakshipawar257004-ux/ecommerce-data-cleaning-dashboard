# E-Commerce Operations Analytics & Data Cleaning Pipeline

## 📊 Project Scope
A comprehensive diagnostic optimization project designed to ingest raw transactional data logs, execute systemic structural cleanup operations, isolate operational leakage points, and assemble an interactive financial tracking dashboard.

## 📁 Repository Schema
- `ECommerce_Analytics_Dashboard.xlsx` - Master interactive reporting file featuring synced filter slicers and computed KPI performance scorecards.
- `Cleaned_Dataset_DecodeLabs.csv` - Sanitized, type-enforced master log records.
- `project3_queries.sql` - Production relational query script optimizing pipeline metrics.

## 🧹 Data Cleaning Protocols Completed
1. **Index Character Purge:** Cleared out erratic syntax formatting symbols (`:`, `!`) from the primary index fields.
2. **Type-Enforcement Transformations:** Converted core financial data fields (quantities, values, totals) from string text formats to true numeric properties to unlock calculations.
3. **Leakage Metric Engineering:** Crafted a custom Net Revenue column block to factor out lost business value originating from returns and cancellations.
