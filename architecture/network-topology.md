
# Network Topology

## Objective
Design a segmented virtual network using pfSense
to restrict communication between different network zones.

## Planned Network Zones

| Zone | Purpose |
|---|---|
| LAN | Internal user systems |
| DMZ | Systems exposed to controlled network access |
| Management | Administrative access to network devices |
| Testing | Authorized security testing systems |

## Security Objectives
- Restrict unnecessary inter-zone communication.
- Prevent unauthorized access to management systems.
- Apply least-privilege firewall policies.
- Monitor and document network traffic.
- Test isolation between zones.

## Validation
Network segmentation will be validated using connectivity tests
and authorized port scans.

## Status
Architecture plan - implementation pending.
