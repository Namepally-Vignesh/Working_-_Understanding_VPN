## **Task:** 
Identify and Remove Suspicious Browser Extensions + VPN Setup

## 🧰 Tools Used

- ProtonVPN (Free Tier)
- Browser (Chrome)
- https://ipchicken.com
- Windows 10
- Wireshark

## 🔧 VPN Setup Steps

1. Signed up on ProtonVPN.com and created an account.
2. Downloaded and installed ProtonVPN Windows client.
3. Connected to a free server in [Japan].

### Findings
- **Encryption**: AES-256
- **Privacy Features**: No-logs policy, DNS leak protection, kill switch.

## 🌍 IP Address Before and After VPN

| Status             | IP Address       | Location           |
|--------------------|------------------|--------------------|
| Before VPN         |  212.102.21.245  | [HYD, INDIA]       |
| After VPN          |  106.222.233.64  | JAPAN              |


## 🔐 Traffic Encryption Verified

- All visited websites used HTTPS.
- Browser Dev Tools showed secure TLS connections.

## ⚖️ VPN Benefits and Limitations
### ✅ Benefits
- Masks IP address and changes location
- Encrypts all browser and app traffic
- Prevents ISP and public Wi-Fi tracking
- Protects user identity from basic profiling

### ⚠️ Limitations
- Slower speed on free servers
- Doesn’t protect against malware/phishing
- May be blocked by certain websites (Netflix, banking)

## 📸 Screenshots Summary
- `vpn-connected-ip.png`
- `encrypted-traffic.png`
- `vpn-disconnected-ip.png`


## ✅ Conclusion
ProtonVPN effectively encrypted internet traffic, changed IP address, and allowed secure browsing. This exercise demonstrates the value of VPNs in cybersecurity for privacy, encryption, and anonymity.
