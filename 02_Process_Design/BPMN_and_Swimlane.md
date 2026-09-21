# BPMN / Swimlane Specification

Use the following lanes in a BPMN diagram:

**Customer | Commerce Platform | Payment Gateway | Inventory | Warehouse | Logistics | Customer Support | Finance**

### Main Flow
Customer selects product → Commerce validates availability → Customer checks out → Payment Gateway authorizes → Commerce confirms payment → Inventory reserves stock → Warehouse processes order → Logistics creates shipment → Platform receives tracking events → Customer views tracking → Delivery confirmed.

### Exception Flows
- Payment failure → retry/alternate payment → if successful continue.
- Inventory unavailable → hold/replace/cancel according to policy.
- Shipment delay → tracking update + customer notification.
- Return request → eligibility validation → approval → pickup/replacement/refund.
