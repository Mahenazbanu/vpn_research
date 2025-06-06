# VPN Setup and Behavior Analysis Report

**Date:** June 06, 2025  
**VPN Service Used:** ProtonVPN (Free Tier)  
**Conducted By:** Mahenazbanu 

---

## 1. Introduction

A **Virtual Private Network (VPN)** is a technology that creates a secure and encrypted tunnel between a user's device and the internet. VPNs are used to protect online privacy, hide real IP addresses, encrypt data transmission, and bypass geographic restrictions.  
**Objective of this Experiment:**  
To analyze the impact of VPN on internet connectivity, privacy, and security by comparing network behavior before and after connecting to ProtonVPN.

---

## 2. Tools Used

- **VPN Client:** ProtonVPN (Free Tier)
- **Browser:** Firefox
- **Verification Sites:** 
  - https://www.whatismyipaddress.com  
  - https://dnsleaktest.com

---

## 3. VPN Setup Procedure

➤ ProtonVPN:

1. Go to https://protonvpn.com/


2. Click on “Get ProtonVPN Free”


3. Sign up with your email (confirm email).


4. Download the app for your OS (Windows/Linux/macOS/Android).

5. **Verify IP Address & Traffic:** 
   - Used https://www.whatismyipaddress.com to confirm change.
   - Verified encryption via browser lock icon and HTTPS.

---

## 4. Network Behavior: Before VPN Connection

- **IP Address:** `103.xxx.xxx.xxx`
- **DNS Leak Test:** Leaked real ISP DNS
- **Browsing Behavior:** Normal, no encryption beyond HTTPS
- **Traffic Visibility:** ISP could monitor activities

---

## 5. Network Behavior: After VPN Connection

- **New IP Address:** `185.XXX.XXX.XXX` (Location: Romania)
- **DNS Leak Test:** No DNS leaks observed
- **Browsing Encryption:** End-to-end via VPN tunnel
- **Anonymity:** Real IP masked, geolocation changed


---

## 6. Encryption and Privacy Features of VPN Used

- **Protocol Used:** OpenVPN and WireGuard (auto selection)
- **Encryption Level:** AES-256-bit encryption
- **Privacy Policy:** No logs, protected by Swiss privacy laws

---

## 7. Performance Comparison Table

| Parameter           | Before VPN     | After VPN      |
|--------------------|----------------|----------------|
| IP Address          | `103.xxx.xxx.xxx` | `185.XXX.XXX.XXX` |
| Speed (Mbps)        | 12.6 Mbps        | 5.7 Mbps        |
| Encryption Visible? | No             | Yes            |
| DNS Leaks?          | Yes            | No             |

---

## 8. Benefits of Using a VPN

- Preserves **anonymity**
- **Bypasses** content restrictions (e.g., geo-blocked sites)
- Protects data on **public Wi-Fi**
- Hides traffic from ISP and attackers

---

## 9. Limitations & Risks

- May **reduce internet speed**
- **Free tier** has limited server access
- **Trust** in VPN provider is critical
---

## 10. Screenshots and Evidence

- ![Before VPN - IP Address](./before_vpn_ip.png)
- ![After VPN - IP Address](./after_vpn_ip.png)
- ![ProtonVPN Connection Status](./vpn_connected.png)

---

## 11. Conclusion

**Final Observations:**  
VPNs significantly improve privacy and data security by masking IP addresses and encrypting traffic.  
**Should VPNs be used regularly?**  
Yes, especially when handling sensitive data or accessing public networks.  
**Learning Outcome:**  
This experiment deepened understanding of VPN functionality, real-world effects on network behavior, and cybersecurity best practices.
