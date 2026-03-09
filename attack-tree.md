# Attack Tree

Goal: Compromise Internal Network

Compromise Network
│
├── Gain Initial Access
│   ├── Exploit default router credentials
│   ├── Connect via Telnet
│   └── Exploit web server vulnerabilities
│
├── Establish Foothold
│   ├── Create rogue admin account
│   └── Install backdoor
│
├── Lateral Movement
│   ├── Exploit SMB shares
│   └── Harvest credentials
│
└── Achieve Objectives
    ├── Data exfiltration
    └── Persistent access