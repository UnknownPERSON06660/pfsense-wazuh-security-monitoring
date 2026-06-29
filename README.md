# pfSense Firewall and Wazuh SIEM Integration

## Overview

This project demonstrates the implementation of a virtual Security Operations Center (SOC) lab using Oracle VirtualBox. pfSense is deployed as the network firewall while Wazuh is used as the Security Information and Event Management (SIEM) platform to centrally collect, monitor, and analyze firewall logs.

---

## Features

- pfSense Firewall Installation
- Wazuh SIEM Deployment
- Remote Syslog Configuration
- Administrative Access Control
- GeoIP Country Blocking using pfBlockerNG
- Centralized Firewall Log Monitoring
- Real-time Event Analysis in Wazuh Dashboard

---

## Lab Environment

- Oracle VirtualBox
- pfSense CE 2.7
- Wazuh 4.14
- Kali Linux
- Windows 11

---

## Network Topology

```
Internet
      │
      ▼
+--------------+
|   pfSense    |
+--------------+
      │
 ┌────┴────┐
 │         │
 ▼         ▼
Kali     Windows
      │
      ▼
+--------------+
| Wazuh Server |
+--------------+
```

---

## Project Documentation

Complete implementation steps are available in:

```
Documentation/pfSense_Wazuh_Documentation.pdf
```

---

## Author

Maarij
BS Computer Science
