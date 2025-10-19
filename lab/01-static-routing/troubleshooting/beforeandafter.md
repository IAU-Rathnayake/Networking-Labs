# 🧩 Troubleshooting Report — Before and After

## 🧠 Problem Summary
Describe what was not working initially.  
Example:
> PC2 could not reach PC1. Ping failed and traceroute stopped at R2.

---

## 🧪 Before Fix (Symptoms)
| Device | Issue | Command Used | Output / Observation |
|:--------|:-------|:--------------|:----------------------|
| R1 | Wrong next-hop IP | `show ip route` | Route missing for 192.168.2.0/24 |
| R2 | Incorrect interface | `show ip interface brief` | G0/1 down/admin down |
| PC2 | No default gateway | `ipconfig` | Gateway blank |

**Screenshot / Evidence:**  
`evidence/before-fix.png`

---

## 🛠️ Fix Applied
Describe what you changed or reconfigured.
Example:
