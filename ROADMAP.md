# Roadmap

## Near term

- Stabilize the current Monitoring Platform Server and Windows Agent.
- Extend update-status visibility per agent.
- Improve documentation and installation flow.
- Add server-side capability display for legacy/limited collectors.
- Design the Custom Collector contract and status schema.

## Legacy Windows

- Build a separate compatibility layer for Windows Server 2012 / 2012 R2.
- Prefer WMF / PowerShell 5.1 where possible.
- Evaluate PowerShell 4.0 separately.
- Add WMI and Task Scheduler fallbacks where modern cmdlets are unavailable.
- Add SMART fallbacks and explicit `Limited` / `Unsupported` states.
- Evaluate Windows Server 2008 R2 only after 2012 R2 is stable.

## Platform expansion

- Linux agent
- ESP32 / IoT agent
- SNMP and UPS integrations
- OPNsense
- FRITZ!Box / TR-064
- AdGuard Home
- UrBackup
- Veeam
- NAS integrations
- hypervisor integrations
- generic HTTP/API collectors

## Security / transport

- HTTPS deployment documentation
- certificate handling
- release authenticity/signing in addition to SHA-256 integrity checks

## Custom Collectors

Planned generic collector types:

- Process / Script Check
- Folder Check
- File Age Check
- HTTP/API Check
- Command Check
- later: controlled PowerShell collector framework

Application-specific business logic should stay out of the standard agents.
