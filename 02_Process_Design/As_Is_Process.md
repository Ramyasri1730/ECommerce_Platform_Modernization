# As-Is Customer & Order Process

```text
Customer
  ↓
Browse Product
  ↓
Add to Cart
  ↓
Checkout
  ↓
Payment Attempt
  ├── Failed → Retry / Abandon
  └── Success
        ↓
Order Processing Queue
        ↓
Inventory Update Delay
        ↓
Manual/Delayed Processing
        ↓
Logistics Handoff
        ↓
Partial Tracking
        ↓
Delivery
        ↓
Manual Return / Refund
```

## Pain Points
1. Checkout friction contributes to 68% cart abandonment.
2. Payment failure creates purchase leakage.
3. Inventory latency can cause overselling.
4. Order processing can take 24–48 hours.
5. Customers contact support for status updates.
6. Returns/refunds require manual intervention.
