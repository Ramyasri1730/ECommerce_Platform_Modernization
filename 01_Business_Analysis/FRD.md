# Functional Requirements Document (FRD)

## Customer
- FR-001 Register account using approved identity/contact fields.
- FR-002 Authenticate securely.
- FR-003 Create/update profile.
- FR-004 Add/edit/remove addresses.
- FR-005 Add/remove wishlist items.

## Product
- FR-006 Display product catalog.
- FR-007 Search by keyword.
- FR-008 Filter by category, price, brand, rating and availability.
- FR-009 Display product details and reviews.
- FR-010 Display availability using current inventory status.
- FR-011 Display recommendation widgets.

## Cart & Checkout
- FR-012 Add/update/remove cart items.
- FR-013 Apply valid coupons.
- FR-014 Calculate subtotal, discount, tax/shipping and total.
- FR-015 Validate address and shipping option.
- FR-016 Create payment transaction.
- FR-017 Handle payment success/failure/retry without duplicate order creation.

## Orders
- FR-018 Create confirmed order.
- FR-019 Generate invoice.
- FR-020 Display order history.
- FR-021 Display real-time shipment milestones.
- FR-022 Confirm delivery.

## Returns
- FR-023 Validate return eligibility.
- FR-024 Create return request.
- FR-025 Track return status.
- FR-026 Trigger refund after approved conditions.
- FR-027 Support replacement request.

## Notifications
- FR-028 Send email/SMS/push notifications for defined events.

## Analytics
- FR-029 Provide sales dashboard.
- FR-030 Provide customer dashboard.
- FR-031 Provide marketing dashboard.
- FR-032 Provide inventory dashboard.

## Non-Functional Requirements
- NFR-01 Availability: target 99.9% monthly platform availability.
- NFR-02 Performance: key customer pages should meet agreed response-time SLA under expected load.
- NFR-03 Security: protect authentication, payment and personal data.
- NFR-04 Auditability: log material order, payment, refund and status changes.
- NFR-05 Scalability: support traffic growth without redesign of core workflows.
- NFR-06 Reliability: prevent duplicate order creation during payment retries.
- NFR-07 Usability: mobile-responsive customer journeys.
- NFR-08 Observability: operational failures and integration errors must be monitorable.
