LAB NOC 11 — DHCP Configuration & Troubleshooting

🚀 Summary  
Real hardware lab focused on configuring DHCP on a Cisco 888 router and troubleshooting DHCP failure using APIPA symptoms.

🧩 Problem  
A PC could not obtain a valid IP address from DHCP and received an APIPA address in the 169.254.X.X range.

⚙️ Solution  
Configured DHCP pool, excluded reserved addresses, validated DHCP bindings, simulated DHCP service failure, restored service, and renewed the client lease.

🔍 NOC Analysis  
Topology: PC → Switch Fa0/7 → Switch Fa0/16 → Router 888  
Network: 192.168.10.0/24  
Gateway: 192.168.10.1  
DHCP range: 192.168.10.11 – 192.168.10.254  
Failure simulated: no service dhcp  
Verification: ipconfig, show ip dhcp binding, show ip dhcp pool  

✅ Result  
DHCP service restored successfully. PC received a valid 192.168.10.X address. Ticket NOC-LAB-11 closed.

🌍 Real World  
APIPA addressing is a common NOC symptom indicating DHCP failure or lack of DHCP server reachability.

🎯 Skills  
DHCP configuration  
DHCP troubleshooting  
APIPA diagnosis  
Cisco IOS verification commands  
Windows ipconfig release/renew  
NOC incident workflow  
Real hardware troubleshooting  

📂 Documentation  
📄 [Full Version (PDF)](./LAB_NOC_11_Full.pdf)  
📄 [Recruiter Version (PDF)](./LAB_NOC_11_Recruiter.pdf)  

🔐 Security Note  
No production credentials or sensitive network information are exposed. Lab addressing uses private IP ranges.
