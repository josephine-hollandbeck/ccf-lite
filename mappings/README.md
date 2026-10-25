# Mappings (Evening 3)

One file per framework. Each row links one ccf-lite control to one framework requirement.

| Column | What goes in it |
|---|---|
| `control_id` | ID from `controls/ccf.yaml` |
| `requirement_id` | Framework ID only (e.g. `CC6.1`, `A.8.5`, `PR.AA-01`, `164.312(d)`, `CIP-007 R2`) |
| `strength` | `full` or `partial` |
| `rationale` | Required for every `partial`: what the control does not cover |

**Copyright:** IDs only for SOC 2, ISO 27001, and NERC CIP. NIST and HIPAA text may be quoted.

Planned later: `ai_frameworks.csv` (Evening 7) and `iac_checks.csv` (AWS bonus, Evening 5b).
