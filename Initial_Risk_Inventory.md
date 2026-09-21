# Initial Risk and Defect Inventory

## Purpose

This document records areas of the inventory workbook that deserve further investigation.

These are initial risks and suspected issues only. They are not confirmed defects unless later testing proves otherwise.

## Risk 1 — Manual Reorder Levels

### Observation
The reorder level for each item is entered manually.

### Why It May Be Risky
If a reorder level is entered incorrectly, the workbook may flag an item too early, too late, or not at all.

### Investigation Needed
Review how reorder levels are selected and determine whether the workbook provides any validation or guidance.

---

## Risk 2 — Undocumented Reorder Logic

### Observation
The workbook uses reorder-related logic and highlighting, but the business rules behind those decisions are not clearly documented.

### Why It May Be Risky
A new user may not understand why an item is being flagged or how the reorder decision is being made.

### Investigation Needed
Trace the formulas and conditional formatting used for reorder decisions and document the logic clearly.

---

## Risk 3 — Limited Input Validation

### Observation
Several important values, such as unit price, quantity in stock, reorder level, and reorder time, are entered manually.

### Why It May Be Risky
The workbook may accept unrealistic or invalid values such as negative quantities or incorrect prices.

### Investigation Needed
Test whether invalid values can be entered and determine whether data validation should be added.

---

## Risk 4 — Reorder Quantity Assumptions

### Observation
The workbook includes a quantity-in-reorder field, but it is not immediately clear how the amount should be determined.

### Why It May Be Risky
Different users may use different methods to decide how much inventory should be reordered.

### Investigation Needed
Determine whether the reorder quantity is calculated, manually entered, or based on an undocumented business rule.

---

## Risk 5 — Maintainability and Handoff

### Observation
The workbook contains formula-driven behavior but limited documentation explaining how the logic works.

### Why It May Be Risky
If another user takes ownership of the workbook, they may have difficulty understanding or safely modifying it.

### Investigation Needed
Document formulas, inputs, outputs, assumptions, and reorder rules so another user can maintain the workbook.
