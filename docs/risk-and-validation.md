# Risk, Controls and Validation

## Key Risks

| Risk | Control |
|---|---|
| Demand variation | Periodic forecast review and exception monitoring |
| Transportation delay | Alternate carrier/route and emergency replenishment |
| Inventory imbalance | Transfer planning and safety-stock review |
| Master-data errors | Controlled master-data validation |
| Capacity shortage | Consolidation and alternate vehicle planning |
| Interface/data mismatch | Reconciliation between planning and execution data |

## Validation Tests

1. Confirm all modeled locations exist.
2. Validate product-location combinations.
3. Check transportation lanes and lead times.
4. Verify planning calendars.
5. Validate source-destination relationships.
6. Confirm inventory-transfer quantities.
7. Test route consolidation logic.
8. Test vehicle-capacity constraints.
9. Simulate a Bengaluru disruption.
10. Confirm KPI calculations and before/after results.

## Governance

Planning master data should have an identified owner, change-control process, review frequency and validation evidence. Transportation exceptions should be recorded with an owner, corrective action and closure status.
