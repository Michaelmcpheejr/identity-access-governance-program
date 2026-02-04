# Tiered Admin RBAC Model (Zero Trust)

## Tier 0: Identity Control Plane

Roles that control the entire identity environment:

- Global Administrator
- Security Administrator
- Privileged Role Administrator

Controls:
- No standing privilege
- PIM recommended (enterprise)
- Quarterly access reviews

---

## Tier 1: Infrastructure Administration

Roles managing platforms and services:

- Exchange Administrator
- Network Administrator
- Endpoint Administrator

Controls:
- Group-based assignment only
- Monthly or quarterly reviews

---

## Tier 2: Helpdesk Operations

Support roles with limited permissions:

- Helpdesk Administrator
- User Administrator

Controls:
- No Tier 0 access
- Time-bound elevation where possible
- Monthly review recommended
