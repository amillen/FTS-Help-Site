---
uid: installation.fts.network-requirements
title: Installation / FTS / Network Requirements
---

# Network Requirements

FTS Cloud requires a properly configured network to ensure reliable connectivity, system performance, and access to required cloud services.

This document outlines the **technical network requirements** needed to operate FTS Cloud successfully.

---

## Supported Network Configuration

### Wi‑Fi Requirements

FTS Cloud supports the following wireless standards [2]:

- **802.11b**
- **802.11g**
- **802.11n**

A stable wireless connection is required for normal operation.

---

## General Network Requirements

Your network must meet the following requirements:

- Support for **DHCP**
- Ability to access required external sites and domains
- Outbound internet access for cloud communication

---

## Required Accessible Sites

The following sites and domains **must be accessible** from the network for FTS Cloud to function correctly:

- **ftsware.com**
- **ftscloud.com**
- **vend.ftscloud.com**
- **ftsware.azurewebsites.net**
- **ftsware-vend.azurewebsites.net**
- **ftsware.blob.core.windows.net**
- **sendgrid.com**  
  *(Used for sending email from FTS Cloud)*

Blocking any of these domains may result in limited functionality or system failure.

---

## Important Notes

- Firewalls, proxies, or content filters must allow access to all required domains.
- Network changes should be reviewed to ensure continued FTS Cloud compatibility.
- If connectivity issues occur, verify DNS resolution and outbound access first.

---

