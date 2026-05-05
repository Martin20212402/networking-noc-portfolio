# LAB NOC 06 — MAC Address Tracking

## 🚀 Summary
Real hardware lab focused on identifying a device using only its MAC address on a Cisco Catalyst 2960.

## 🧩 Problem
An unknown device was detected on the network. The NOC needed to locate the exact switch port using only the MAC address.

## ⚙️ Solution
Used MAC address table lookup and interface status verification to identify the exact port where the device was connected.

## 🔍 NOC Analysis
- MAC address: c4da.2604.8923
- Command used: `show mac address-table`
- Result: Device found on Fa0/1
- Verification: `show interfaces status | include Fa0/1`

## ✅ Result
Device successfully located on port Fa0/1. Ticket NOC-006 closed with documented evidence.

## 🌍 Real World
MAC tracking is one of the most common Layer 2 troubleshooting techniques used in NOC environments.

## 🎯 Skills
- MAC address-table analysis
- Layer 2 troubleshooting
- Device identification
- Network security basics
- NOC incident workflow

## 📂 Documentation

- 📄 [Full Version (PDF)](./LAB_NOC_06_Full.pdf)
- 📄 [Recruiter Version (PDF)](./LAB_NOC_06_Recruiter.pdf)
