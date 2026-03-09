# STRIDE Threat Model

## Overview

Threat model based on vulnerabilities discovered during network assessment.

## Assets

- Router
- Servers
- SMB shares
- IoT devices

## STRIDE Analysis

### Spoofing
Default router credentials allow impersonation of admin users.

### Tampering
Attackers may alter router configuration.

### Repudiation
Limited logging may prevent attribution.

### Information Disclosure
Telnet exposes credentials in cleartext.

### Denial of Service
IoT compromise may disrupt network.

### Elevation of Privilege
Outdated SSH may allow privilege escalation.