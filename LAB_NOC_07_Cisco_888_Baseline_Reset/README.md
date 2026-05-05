LAB NOC 07 — Cisco 888 Baseline Reset / Credential Recovery

🚀 Summary  
Real hardware lab focused on recovering administrative access and performing a full baseline reset on a Cisco 888 router.

🧩 Problem  
A used router arrived with unknown credentials. Console access required authentication, blocking administrative access.

⚙️ Solution  
Performed boot interruption using Break sequence, bypassed authentication, erased startup configuration, and reloaded the device.

🔍 NOC Analysis  
Access method: Serial console (PuTTY)  
Commands used: enable, erase startup-config, reload  
Verification: show running-config, show startup-config  
Result: startup-config is not present  

✅ Result  
Router successfully reset to factory baseline. No configuration, no users, clean Router# prompt. Ticket NOC-007 closed with full evidence.

🌍 Real World  
Credential recovery and baseline reset are critical NOC skills when integrating used equipment or handling access incidents.

🎯 Skills  
Cisco router recovery  
Console access troubleshooting  
NVRAM management  
Baseline configuration  
Incident documentation  
NOC workflow  

📂 Documentation  
📄 [Full Version (PDF)](./LAB_NOC_07_Full.pdf)  
📄 [Recruiter Version (PDF)](./LAB_NOC_07_Recruiter.pdf)  

🔐 Security Note  
Sensitive credential details intentionally omitted. This lab demonstrates secure recovery procedures without exposing passwords or secrets.
