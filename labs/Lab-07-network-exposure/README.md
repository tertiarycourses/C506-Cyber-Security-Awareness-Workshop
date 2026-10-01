# Lab-07: Map Network Exposure and Segmentation

**Course:** Cyber Security Awareness Workshop  
**Course code:** C506  
**Time:** 35 minutes  
**Alignment:** LO1, LO3  
**Tool:** [IP Calculator](https://alfredang.github.io/ipcalculator/)

## Scenario

A retail office needs separate zones for staff, guests, point-of-sale devices and management systems.

## Safety and authorisation boundary

- Use only the named training tool and the mock files in this folder.
- Do not enter real passwords, personal data, payment details or confidential information.
- Do not test any other website, network, account or organisation.
- Stop immediately if the target, data or behaviour differs from the written scope.
- Prefer reversible actions and preserve synthetic evidence.

## Mock data

- `mock-network-assets.csv`
- `mock-network-requirements.csv`

## Detailed procedure

1. Group the mock assets by trust level, data sensitivity and operational role.
2. Use the IP Calculator to create non-overlapping training subnets sized for each group.
3. Record network address, usable host range, broadcast address and proposed gateway for each zone.
4. Draw allowed flows and deny-by-default boundaries between staff, guest, point-of-sale and management networks.
5. Identify which services, if any, need internet exposure and add a monitoring or access-control requirement.
6. Review the design for excessive trust and document one residual risk.

## Completion standard

- Subnet plan
- Asset-to-zone mapping
- Allowed-flow matrix
- Exposure decisions
- Residual risk

## Reflection

What evidence would make you reverse your decision, and who would need to know?
