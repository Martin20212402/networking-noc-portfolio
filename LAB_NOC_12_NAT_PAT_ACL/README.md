LAB NOC 12 — NAT (PAT) + ACL

🚀 Summary  
Real hardware lab focused on configuring NAT PAT (overload) and ACLs on a Cisco 888 ISR to simulate Internet access for an internal LAN.

🧩 Problem  
Users had valid internal IP addresses but could not reach the simulated Internet network.

⚙️ Solution  
Configured VLAN interfaces, defined NAT inside/outside roles, created ACL for internal traffic identification, configured PAT overload, and validated active translations.

🔍 NOC Analysis  
Inside network: 192.168.10.0/24  
Outside network: 200.1.1.0/24  
NAT mode: PAT overload  
Verification commands:
- show ip nat translations
- show ip nat statistics
- show access-lists
- show running-config | include nat

✅ Result  
NAT PAT operational successfully. Internal devices reached simulated Internet using a single public IP translation.

🌍 Real World  
NAT PAT is commonly used on WAN edge routers in enterprise, industrial, mining, and branch office environments.

🎯 Skills  
NAT PAT configuration  
ACL troubleshooting  
WAN edge troubleshooting  
Cisco IOS verification  
Layer 3 troubleshooting  
Real hardware troubleshooting  
NOC workflow documentation  

📂 Documentation  
📄 [Full Version (PDF)](./LAB_NOC_12_Full.pdf)  
📄 [Recruiter Version (PDF)](./LAB_NOC_12_Recruiter.pdf)  

🔐 Security Note  
No production credentials, public IPs, or sensitive infrastructure information are exposed.
