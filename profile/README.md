# MLU Platform

Ministry of Labour and Immigration — eGDI Border Control Platform

Cambodia's national border control and immigration management system.

---

## Repositories

| Repository | Purpose |
|---|---|
| `mlu-infra` | Infrastructure — Terraform, Kubernetes, Proxmox |
| `egdi-platform` | eGDI Border Control — Angular frontend + Spring Boot microservices |
| `mlu-notification-service` | Shared notification — Email, Telegram, SMS |
| `mlu-integration-service` | Shared integration — Interpol, ASEAN, iAPI |

---

## Platform Status

Active Development — Phase 1

---

## Standards

- All changes go through Pull Request — no direct push to `main`
- Senior architect approval required on all PRs
- Every architectural decision recorded in DECISION-LOG.md
- Infrastructure and IaC must stay in sync at all times
