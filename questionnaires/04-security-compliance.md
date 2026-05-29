# Security & Compliance Assessment

## Purpose
Evaluate the security posture and compliance readiness for AI workloads on Salesforce.

## Questions

### Platform Security
1. Is Salesforce Shield enabled (Platform Encryption, Event Monitoring, Field Audit Trail)? (Yes/No/Partial)
2. Is Platform Encryption enabled for sensitive fields? (Yes/No)
3. Is Event Monitoring active with log analysis? (Yes/No)
4. Are login IP ranges and session settings configured? (Yes/No)
5. Is MFA enforced for all users? (Yes/No)

### Access Controls
6. Are profiles and permission sets aligned to least-privilege? (1-5 scale)
7. Is field-level security configured for sensitive data? (Yes/No)
8. Are sharing rules appropriate for data sensitivity? (1-5 scale)
9. Are connected app OAuth scopes minimized? (Yes/No)
10. Is session management configured (timeout, concurrent sessions)? (Yes/No)

### Compliance
11. Which compliance frameworks apply? (SOC 2 / HIPAA / PCI-DSS / GDPR / CCPA / Other)
12. Is Salesforce Health Check score above 80%? (Yes/No/Unknown)
13. Is data residency configured appropriately? (Yes/No/N/A)
14. Are audit trails sufficient for compliance requirements? (1-5 scale)

### AI-Specific Security
15. Are Einstein AI Trust Layer features enabled? (Yes/No/N/A)

## Scoring Weight
This section contributes **20%** to the overall AI Readiness Score.
