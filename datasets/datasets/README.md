# Datasets

This folder contains **fictional / anonymized** datasets used to build dashboards.

## sample_orders.csv
Operational dataset for order/dispatch tracking and reporting.

**Columns**
- order_id: unique order identifier
- created_date: order creation date (YYYY-MM-DD)
- status: in_preparation | in_transit | delivered | cancelled
- lead_time_days: days from creation to delivery (if delivered)
- backlog_flag: 1 if lead_time_days > 7 else 0
- incident_flag: 1 if an incident happened else 0
- incident_severity: low | medium | high (optional)
- region: operational region (North/Central/South)
- channel: Sales channel (B2B/B2C)
