# Initial Network Security Assessment

## Overview

A security review was conducted on a small hospitality venue network to identify potential vulnerabilities and operational risks.

The environment consisted of standard small-business infrastructure including:

* Internet gateway/router
* Switch infrastructure
* Wireless access point
* POS systems
* CCTV/NVR system
* Staff devices

The objective of the assessment was to identify weaknesses that could lead to network compromise or service disruption.

---

## Key Vulnerabilities Identified

### Default Credentials

Multiple infrastructure devices were still using factory default administrative credentials.

**Risk:**
An attacker with network access could gain full administrative control of critical systems.

---

### Outdated Firmware

Several network devices were running outdated firmware versions.

**Risk:**
Known vulnerabilities could potentially be exploited.

---

### Insecure Remote Access

Remote administration services were exposed without secure tunnelling.

**Risk:**
Management interfaces could be targeted from outside the network.

---

### Weak Wireless Configuration

Wireless security configuration did not follow current best practices.

**Risk:**
Unauthorized devices could potentially access internal services.

---

## Assessment Outcome

The environment contained several **high-risk but easily remediated vulnerabilities** common in small
