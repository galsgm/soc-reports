# 🛡 SOC Security Operations Report

## 📌 Overview
This report summarizes the security monitoring activities, findings, and incident response actions performed by the Security Operations Center (SOC) during the reporting period.

| Field | Details |
|-------|---------|
| Report Date | 25/11/2025 |
| Reporting Period | 01/11/2025 – 25/11/2025 |
| Prepared By | SOC Analyst Team |
| Review Cycle | Weekly |
| [picture1] (images1/picture1.png)
---

## 🔍 Monitoring Summary
| Category | Count |
|----------|-------|
| Total Events Analyzed | 54,320 |
| Alerts Generated | 162 |
| True Positive Incidents | 11 |
| False Positives | 94 |
| Escalated Cases | 6 |

---

## 🚨 Incident Breakdown
| Incident ID | Type | Severity | Status | Assigned To | Notes |
|-------------|------|----------|--------|-------------|-------|
| INC-001 | Malware | High | Closed | A. Gordon | Malware detected on workstation. Removed successfully. |
| INC-002 | Unauthorized Access Attempt | Medium | Open | L. Cohen | Brute-force attempt on VPN portal. Monitoring continues. |
| INC-003 | Phishing | High | Closed | M. Frost | Employee received phishing email. No compromise detected. |

---

## 🧾 Root Cause Analysis (Selected Incident)
```
Incident ID: INC-001
Summary: Malware infection detected on endpoint following email attachment execution.
Root Cause: User executed malicious attachment.
Impact: Single user workstation affected.
Containment: Endpoint isolated and malware removed.
Eradication & Recovery: Files scanned and restored, user re-educated.
Recommendations: Enforce email attachment filtering and security awareness training.
```

---

## 📡 Threat Intelligence Notes
- Observed phishing campaign linked to known threat group targeting similar industry sectors.
- No confirmed data exfiltration indicators.

Relevant IOC list:
```
IP: 185.199.110.133
Domain: secure-docs-mail.com
Hash: 89f1b9c47bd93d6fa75c8831e2e4e9ef7be204b5ccac0e82014
```

---

## 🛠 Actions & Improvements
| Action Item | Owner | ETA | Status |
|-------------|-------|-----|--------|
| Improve SIEM rule for VPN alerts | L. Cohen | 30/11/2025 | In Progress |
| Deploy patch to vulnerable systems | M. Frost | 27/11/2025 | Done |
| Schedule awareness training | A. Gordon | 05/12/2025 | Pending |

---

## 📈 SOC Metrics & KPIs
| KPI | Value |
|-----|-------|
| Mean Time to Detect (MTTD) | 45 minutes |
| Mean Time to Respond (MTTR) | 2 hours 13 minutes |
| Escalation Rate | 17% |
| Automation Coverage | 38% |

---

## ✔ Final Summary
```
Overall SOC Status: Elevated Risk
Key Points:
- Phishing campaign remains active.
- No confirmed compromise.
- VPN-related alerts are trending upward.
```

---

## 🔗 References
- SIEM Dashboard
- SOC Runbooks
- Incident Response Playbooks
