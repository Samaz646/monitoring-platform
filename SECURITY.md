# Security

Monitoring Platform is under active development.

## Reporting security issues

Do not publish credentials, enrollment secrets, bearer tokens, private infrastructure details or exploitable security findings in public issues.

Until a dedicated private reporting channel is configured, avoid posting sensitive details publicly.

## Repository hygiene

The repository must not contain runtime databases, agent identities, enrollment request files, server credentials, bearer/admin tokens, production logs, private hostnames/addresses or generated runtime state.

## Transport

HTTPS should be used when the platform is deployed across untrusted networks. Legacy Windows systems may require explicit TLS 1.2 handling.

Do not disable certificate validation as a normal deployment practice.

## Updates

Agent update packages are SHA-256 verified. Hash validation provides integrity checking but is not the same as publisher authenticity. Release signing is planned.
