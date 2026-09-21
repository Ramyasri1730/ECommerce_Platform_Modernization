# Acceptance Criteria

## US-007 Simplified Checkout
**Given** a customer has an eligible cart  
**When** the customer starts checkout  
**Then** the platform displays required address, shipping and payment steps with clear totals.

**Given** all mandatory fields are valid  
**When** the customer submits payment  
**Then** the payment transaction is created once and the customer receives a clear outcome.

## US-009 Payment Retry
- A failed payment must show a clear failure reason/message.
- Customer can retry or select another method.
- A retry must not create a duplicate confirmed order.
- Successful retry must update the transaction and order state consistently.

## US-010 Inventory Visibility
- Product availability reflects the latest approved inventory event.
- Reserved inventory is excluded from available-to-sell quantity.
- Overselling scenarios are logged and alerted.

## US-011 Order Tracking
- Customer can see current order status.
- Shipment milestones are timestamped.
- Logistics status updates are mapped to customer-friendly statuses.
