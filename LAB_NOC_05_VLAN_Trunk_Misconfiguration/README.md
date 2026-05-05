# LAB NOC 05 — VLAN Trunk Misconfiguration

## 🚀 Summary
Real hardware troubleshooting lab on a Cisco Catalyst 2960 focused on VLAN trunk allowed-list issues.

## 🧩 Problem
Users in VLAN 20 lost connectivity while users in VLAN 10 continued working normally.

## ⚙️ Solution
The trunk allowed VLAN list was corrected on both interfaces to allow VLAN 10 and VLAN 20.

## 🔍 NOC Analysis
- Trunk link: Fa0/6 ↔ Fa0/16
- Issue: VLAN 20 was not allowed on Fa0/6
- Key command: `show interfaces trunk`
- Fix: `switchport trunk allowed vlan 10,20`

## ✅ Result
VLAN 20 connectivity restored. Ticket NOC-LAB-05 closed.

## 🌍 Real World
A wrong trunk allowed list can silently isolate one VLAN while other VLANs keep working.

## 🎯 Skills
- VLAN trunking
- Allowed VLAN list troubleshooting
- Layer 2 troubleshooting
- NOC incident handling

## 📂 Documentation

- 📄 [Full Version (PDF)](./LAB_NOC_05_Full.pdf)
- 📄 [Recruiter Version (PDF)](./LAB_NOC_05_Recruiter.pdf)
