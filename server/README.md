# Monitoring Platform Server

Current development baseline: **v0.1.23**.

The server is the central component of Monitoring Platform. It manages enrollment, device state, policies, agent releases, logs and the WebGUI.

## Current capabilities

- FastAPI REST API
- manual agent enrollment approval
- persistent device identity
- heartbeat/current-state processing
- online/offline calculation
- service and process policies
- agent release management
- LAN discovery
- persistent SQLite data
- persistent server logging
- dark WebGUI
- partial live refresh on agent details

The active source baseline is maintained from the v0.1.23 build while the public repository structure is being established.
