# Task 8 – Identify & Remove Suspicious Browser Extensions + VPN Hands-On

## 📝 Objective
Gain hands-on experience with browser security and Virtual Private Networks (VPNs).  
Task includes:  
- Removing suspicious browser extensions  
- Installing and configuring a VPN  
- Verifying IP address change  
- Testing for DNS/IP leaks  
- Understanding VPN benefits and limitations

---

## 🔍 1. Identify & Remove Suspicious Browser Extensions

### ✔ Steps Performed
- Opened **Chrome → Extensions → Manage Extensions**
- Reviewed each extension based on:
  - Publisher authenticity
  - Required permissions
  - Ratings and number of downloads
- Removed unnecessary or suspicious extensions
- Restarted browser and rechecked for any unwanted extensions

### ✅ Outcome
Browser cleaned and only trusted extensions kept.

---

## 🔐 2. VPN Setup & Configuration

### VPN Used: **ProtonVPN (Free Tier)**

### ✔ Steps Performed
1. Signed up on ProtonVPN’s official website  
2. Downloaded & installed the Windows client  
3. Logged in and enabled:
   - **Kill Switch**
   - **DNS Leak Protection**
   - Default protocol: **WireGuard**
4. Connected to the nearest free VPN server
5. Verified successful connection

---

## 🌐 3. IP Verification

### Before VPN
- Checked IP on **WhatIsMyIPAddress.com**
- Displayed original ISP-provided IP  
- Screenshot: `pre_ip.png`

### After VPN
- Refreshed the same website  
- New VPN IP and location displayed  
- Screenshot: `vpn_ip.png`

---

## 🔒 4. Encryption & Leak Testing

### DNS Leak Test
- Used **DNSLeakTest.com**
- Result: Only ProtonVPN DNS servers detected  
- **No DNS leak found**  
- Screenshot: `dns_test.png`

### IP Leak Test
- Used **ipleak.net**
- Only VPN IP shown → **secure**

### HTTPS Traffic Verification
- Browsed HTTPS sites → padlock confirmed encryption

---

## 🌍 5. Browsing Behaviour Observed
- Normal websites working fine  
- Slight delay in loading heavy pages  
- No blocked websites  
- Stable browsing experience overall

---

## 🛡 6. VPN Benefits & Limitations

### ✅ Benefits
- Hides real IP address  
- Encrypts all outgoing traffic  
- Protects from Wi-Fi snooping  
- Prevents ISP tracking  
- Can bypass geo-blocks (limited in free plan)

### ⚠ Limitations
- Free VPN servers have slower speeds  
- Limited server locations  
- Some websites block VPN traffic  
- VPN provider can still log metadata  
- Privacy depends on provider trust level

---

## 📌 7. Conclusion
This task provided practical experience in:
- Browser security  
- VPN installation & configuration  
- IP masking verification  
- DNS/IP leak testing  
- Internet privacy analysis  

Successfully completed all required deliverables and gained improved cybersecurity awareness.


---

