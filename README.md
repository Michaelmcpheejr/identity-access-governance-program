# Identity & Access Governance Program (Azure Entra + Zero Trust)

## Overview

This repository contains an audit-ready **Identity & Access Governance (IAG)** program designed to enforce secure, compliant, and repeatable access controls across Azure Entra ID, Microsoft 365 administrative roles, and SaaS applications.

The program establishes governance for:

- Role-Based Access Control (RBAC)
- Privileged access risk management
- Joiner-Mover-Leaver (JML) identity lifecycle controls
- Periodic access reviews and certifications
- Azure Entra technical control mapping aligned to Zero Trust

This program is structured to support both security operations and audit readiness.

---

## Key Deliverables

- Tiered Admin RBAC Model (Tier 0 / Tier 1 / Tier 2)
- Privileged Access Risk Controls with exception governance
- Manual Joiner-Mover-Leaver SOP with ticket-based evidence
- Monthly privileged + quarterly standard access review cadence
- Access Review Tracker template for re-performance
- Azure Entra feature mapping (RBAC, MFA defaults, audit logs)

---

## How to Use This Repo

1. Start with the program charter: `docs/Program_Charter.md`
2. Review RBAC governance: `rbac/Tiered_RBAC_Model.md`
3. Understand privileged controls: `privileged-access/Privileged_Access_Risk_Controls.md`
4. Follow lifecycle governance: `jml/Joiner_Mover_Leaver_SOP.md`
5. Run access certifications: `access-reviews/Access_Review_SOP.md`
6. Map controls to Entra: `mapping/Azure_Entra_Control_Mapping.md`

---

## Portfolio Note

This repository uses simulated examples and governance artifacts for demonstration purposes. No real organizational credentials or sensitive access exports should be uploaded to public GitHub.

