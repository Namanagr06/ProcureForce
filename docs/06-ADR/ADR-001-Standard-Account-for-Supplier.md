# ADR-001

## Title

Use Salesforce Account as Supplier Master

## Status

Accepted

## Context

ProcureForce requires a supplier master to support procurement activities.

## Decision

The standard Salesforce Account object will represent Suppliers.

A dedicated Supplier Record Type will distinguish supplier records from other Account records.

## Consequences

Advantages

- Reuse Salesforce standard functionality.
- Standard sharing model.
- Standard reporting.
- Easier ERP integration.
- Lower maintenance.

Disadvantages

- Requires record types.
- Page layouts must be managed carefully.

## Approved By

ProcureForce Architecture Team