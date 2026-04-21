# Data Retention Policy

## Retention Schedule

| Data Class                | Retention | Disposal Method        |
|---------------------------|-----------|------------------------|
| Customer PII              | 7 years   | Cryptographic erasure  |
| Authentication logs       | 1 year    | Automated deletion     |
| Access logs               | 90 days   | Automated deletion     |
| Backups (production DB)   | 35 days   | Volume-level deletion  |
| Email correspondence      | 3 years   | Vendor-managed purge   |
| Financial records         | 7 years   | Archival then deletion |

## Legal Hold

Data under legal hold is exempt from scheduled disposal. Legal counsel
must lift the hold before deletion resumes.

## Annual Review

This policy is reviewed annually by the Data Protection Officer.
