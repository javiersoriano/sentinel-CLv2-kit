# sentinel-CLv2-kit

This repository contains samples for multiple scenarios that are possible thanks to the new Log Analytics Custom Logs v2 and pipeline transformation features.

### Filtering

Ingestion time transformation allows you to drop specific fields from events or even full evets that you don't need to have in the workspace.

1. Dropping fields
2. Dorpping entire records
3. Multiple workspaces for idependent entities

### Enrichment/Tagging

1. Adding a value from an existing event by extending a JSON column 
2. Translating a value into a customer’s business related value (Geo, Departments,…)
3. Enriching an event or a field in the event with additional meaningful information


### PII Masking/Obfuscation

1. Masking last 4 digits of SSN
2. Removing email addresses
3. Masking credit card information

### Row level RBAC
