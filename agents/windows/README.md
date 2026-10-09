# Windows Agent

Current development baseline: **v0.3.27**.

The Windows agent provides the standard monitoring functions for supported Windows systems.

## Current capabilities

- CPU and memory monitoring
- storage usage and SMART
- network information
- services and service policy
- service auto-recovery
- processes and process policy
- Windows Event Log collection
- inventory collection
- scheduled-task runtime status
- LAN discovery
- enrollment and persistent identity
- central policy synchronization
- automatic update validation and rollback

The standard agent intentionally contains only general-purpose monitoring functions. Customer-specific checks belong in Custom Collectors.
