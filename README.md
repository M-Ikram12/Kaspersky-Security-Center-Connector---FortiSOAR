# FortiSOAR – Kaspersky Security Center Integration Issue Report

This repository documents the issues encountered while integrating **FortiSOAR** with **Kaspersky Security Center**, along with support communication logs and references.

## Overview

The primary goal of this integration was to enable **FortiSOAR** to:
- Query if a specific host exists in **Kaspersky Security Center (KSC)**
- Retrieve basic information about that host

> ✅ **Note:** The connector itself had no issue. All problems were caused by misconfigurations, improper user roles, or incorrect input parameters in playbooks.

---

## 🐞 Reported Issues

### 🔐 1. Access Denied – Error Code `1184`
- **Error Message:**
  ```json
  {
    "code": 1184,
    "message": "Access denied",
    "module": "KLSTD"
  }
