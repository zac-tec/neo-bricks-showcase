# From daily factory work to a usable application

## Problem

A factory needs a connected view of production, materials, sales and payments. Managers need to record work quickly, including entries made after the work happened. Owners need clear monthly comparisons and understandable calculations without reading long explanations.

## Implementation

The system connects production entries to material consumption and finished-stock batches. Sales feed the customer ledger and generate receipts. Administrator views bring together inventory, utility bills, costs and sales performance.

A separate company website presents products and contact information. The operational application remains authenticated and private.

## Improvements driven by use

### Easier review

The quantity ledger evolved into a year overview, month navigation and daily cards. Whole sales remain readable even when their inventory comes from several batches. Opening and closing balances include production, sales, damages and adjustments.

### Clearer customer workflows

A compact searchable directory opens customer accounts. Purchase history and payments are easier to inspect, with receipt previews and weighted average purchase rates. Sales-rate groups in the profit view reveal customer names and quantities without opening full accounts.

### Costs that reflect the workflow

Electricity is entered monthly; water bills cover two consecutive months and are apportioned by production mixes. Labour rates support effective dates. Profit calculations account for stock produced in earlier months rather than assuming every sold brick was produced in the selected month.

### Mobile usability

Client feedback led to smaller dashboard summaries, clearer action buttons, less explanatory text and predictable Back navigation. PWA asset versions are updated alongside frontend releases.

## Delivery and maintenance

The application moved from Raspberry Pi hosting to a VPS, with database preservation, HTTPS routing and managed startup. Continued changes use focused verification and rollback preparation. Encrypted backups and isolated restore checks complement source history.

## What this demonstrates

- Translating real operational feedback into data models and interfaces.
- Separating inventory quantities, invoice values, tax and transport costs.
- Preserving historical context while allowing corrections.
- Building and maintaining a full-stack application beyond its initial release.
- Documenting architecture publicly while keeping production information private.

No fabricated usage metrics or client financial results are used in this case study.
