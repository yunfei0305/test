# Access Control Policy

## Purpose

Defines how user, service, and administrative access to production systems
is granted, reviewed, and revoked. Aligns with ISO 27001 A.9 and SOC 2 CC6.

## Scope

All production infrastructure, customer data stores, and internal tooling
with access to customer data.

## Principles

1. **Least privilege** — access is granted only as required to perform
   the user's role.
2. **Role-based access control** — permissions are grouped into roles;
   users are assigned to roles, never granted permissions directly.
3. **Separation of duties** — privileged operations require a second
   approver.
4. **Just-in-time access** — time-bound elevation for break-glass scenarios.

## Quarterly Access Review

An access review of all privileged accounts is performed every calendar
quarter. Results are documented and kept for at least 2 years.

## Offboarding

All access is revoked within 24 hours of termination.
