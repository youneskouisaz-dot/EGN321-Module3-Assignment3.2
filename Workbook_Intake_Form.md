# Workbook Intake Form

## Workbook Source

Public sample inventory workbook obtained for classroom analysis.

## Workbook User Role

The workbook could be used by an inventory manager, store manager, purchasing employee, or another person responsible for monitoring stock and reordering items.

## Operational Purpose

The workbook is used to track inventory items, current stock quantities, unit prices, inventory values, reorder levels, reorder timing, reorder quantities, and discontinued products.

Its main purpose is to help the user understand current inventory status and identify items that may need replenishment.

## Frequency of Use

The workbook could reasonably be updated whenever inventory changes, such as:

- when new stock is received
- when products are sold or used
- when reorder quantities change
- when an item becomes discontinued

## Main Inputs

- Inventory ID
- Item name
- Description
- Unit price
- Quantity in stock
- Reorder level
- Reorder time in days
- Quantity in reorder
- Discontinued status

## Main Outputs

- Inventory value
- Reorder-related highlighting or status indicators
- Current inventory information for purchasing and stock-management decisions

## Workflow

1. The user enters or updates inventory item information.
2. Current stock quantities are maintained.
3. Reorder levels and timing information are entered.
4. The workbook calculates inventory value.
5. The workbook compares current stock with the reorder level.
6. Items that may need replenishment can be identified.
7. The user can use the results to support purchasing or inventory decisions.

## Initial Concerns

The following areas should be investigated further:

- Reorder thresholds are entered manually.
- Reorder quantities may depend on undocumented assumptions.
- Important business rules may not be clearly explained.
- Input validation may be limited.
- A new user may have difficulty understanding how the reorder logic works.

These concerns are preliminary and are not confirmed defects.
