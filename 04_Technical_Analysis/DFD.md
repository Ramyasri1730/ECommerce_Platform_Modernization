# Data Flow Diagram — Level 1

Customer
  ↓
Commerce Platform
  ├── Customer Data Store
  ├── Product Catalog
  ├── Cart
  ├── Order Service
  ├── Inventory Service → Inventory Data
  ├── Payment Gateway → Payment Result
  ├── Logistics Provider → Shipment Events
  ├── Notification Service → Email/SMS/Push
  ├── Recommendation Engine → Product Recommendations
  └── Analytics Layer → Executive Dashboards

## Controls
Unique order/payment IDs, status-transition validation, payment/order reconciliation,
inventory reconciliation, audit logging and integration error monitoring.
