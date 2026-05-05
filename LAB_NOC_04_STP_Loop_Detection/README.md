# LAB NOC 04 — STP Loop Detection & Prevention (Cisco Catalyst 2960)

## 🚀 Summary
Real hardware troubleshooting lab demonstrating Layer 2 loop detection using STP.

## 🧩 Problem
Network instability caused by a Layer 2 loop between two switch interfaces.

## ⚙️ Solution
STP detected the loop and blocked one interface.  
The redundant cable was removed.

## 🔍 NOC Analysis
- Loop: Fa0/6 ↔ Fa0/16  
- STP → Blocking state  
- Syslog used for analysis  

## ✅ Result
Network stabilized. STP reconverged successfully.

## 🌍 Real World
Layer 2 loops can cause broadcast storms and network collapse.

## 🎯 Skills
- STP
- Layer 2 troubleshooting
- Syslog analysis

## 📂 Documentation

- 📄 [Full Version (PDF)](./LAB_NOC_04_Full.pdf)
- 📄 [Recruiter Version (PDF)](./LAB_NOC_04_Recruiter.pdf)
