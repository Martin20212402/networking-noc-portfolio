# LAB NOC 02 — Port Security (Cisco Catalyst 2960)

## 📌 Overview
This lab demonstrates Layer 2 security using Port Security on a real Cisco Catalyst 2960 switch.

## 🧠 Scenario (NOC)
A device connects to the network. The NOC engineer must:
- Verify baseline
- Configure port security
- Detect unauthorized MAC
- Recover the port

## ⚙️ Configuration
- switchport port-security
- switchport port-security maximum 1
- switchport port-security mac-address sticky
- switchport port-security violation shutdown

## 🔍 Verification
- show mac address-table
- show port-security interface fa0/1

## 🚨 Behavior
- Only 1 MAC allowed
- New MAC → err-disabled
- Recovery → shutdown / no shutdown

## 🧪 Result
Port secured successfully. Sticky MAC learned.

## 🏭 Real World
Prevents unauthorized devices in industrial networks (SCADA, cameras, etc.)

## 🎯 Skills
- Layer 2 Security

## 📂 Documentation

- 📄 [Full Documentation (Technical Version)](./LAB_NOC_02_FULL.pdf)
- 📄 [Recruiter Version (Short)](./LAB_NOC_02_RECRUITER.pdf)
- Port Security
- Troubleshooting
- NOC Thinking
