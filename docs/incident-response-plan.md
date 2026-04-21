# Incident Response Plan

## Severity Levels

- **SEV-1**: Customer data exposure, production outage > 30 min.
- **SEV-2**: Degraded service, partial feature outage.
- **SEV-3**: Internal-only issue with no customer impact.

## Runbook

1. **Detect** — alerting fires or user reports issue.
2. **Triage** — on-call engineer assigns severity and pages responders.
3. **Contain** — isolate the blast radius (revoke creds, disable endpoint,
   failover region).
4. **Eradicate** — identify root cause and remove it.
5. **Recover** — restore service and verify normal operation.
6. **Postmortem** — blameless review within 5 business days. Written
   postmortem committed to this repo.

## Tabletop Exercises

Quarterly tabletops covering ransomware, credential compromise, and
data-exfiltration scenarios.
