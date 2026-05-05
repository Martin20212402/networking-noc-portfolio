# LAB NOC 03 — EtherChannel Failure / VLAN Mismatch

## 🚀 Summary
Real hardware troubleshooting lab on a Cisco Catalyst 2960.

## 🧩 Problem
EtherChannel failed because member ports had a VLAN mismatch.

## ⚙️ Solution
The interfaces were reset, the old Port-Channel was removed, and both ports were reconfigured with matching settings.

## ✅ Result
Port-Channel 1 was restored successfully and verified with `show etherchannel summary`.

## 📂 Documentation

- 📄 [Recruiter Version (PDF)](./LAB_NOC_03_Recruiter.pdf)
- 📄 [Full Version (PDF)](./LAB_NOC_03_Full.pdf)
