# VPN Setup and Privacy Verification Report  
**Tool Used:** ProtonVPN 
---

## **Objective**  
The goal of this project was to gain hands-on experience with a Virtual Private Network (VPN) by setting it up, connecting to a secure server, and verifying that it successfully masks my IP address, encrypts traffic, and prevents DNS leaks.  

This activity helps in understanding how VPNs enhance online privacy and protect communication from prying eyes, whether they’re hackers on public Wi-Fi or ISPs tracking browsing activity.

---

## **Steps Performed**  

### **1. Launching ProtonVPN and Configuring Privacy Features**  
Since ProtonVPN was already installed on my system, I directly opened the app and logged in.  
Before connecting, I ensured that essential privacy options were enabled:  
- **Kill Switch** — Blocks internet access if VPN disconnects unexpectedly.  
- **DNS Leak Protection** — Ensures all DNS requests are routed through the VPN.  
- **VPN Accelerator** — Improves connection speed (optional).  

This setup ensures that even if the VPN connection drops, my IP and browsing activities remain protected.  

---

### **2. Connecting to a VPN Server**  
I used ProtonVPN’s **Quick Connect** option, which automatically chose the fastest free server available.  
Once connected, the app displayed:  
- **New IP Address** provided by the VPN  
- **Server Location** different from my actual location  
- **Encrypted Connection Status**  

---

### **3. Verifying IP Address Change**  
To confirm the VPN was working, I opened my browser in **Incognito mode** and visited [whatismyipaddress.com](https://whatismyipaddress.com).  
The site showed:  
- **A completely different IP address** from my real one  
- **A different city and country** matching the VPN server location  

This confirmed that my real IP was successfully masked.  

---

### **4. Testing Encryption**  
I visited several HTTPS websites (e.g., Wikipedia) and checked the browser’s padlock icon to confirm secure connections.  
The lock indicated: **“Connection is secure”**, meaning my traffic was encrypted end-to-end.  

---

### **5. DNS Leak Test**  
I went to [dnsleaktest.com](https://dnsleaktest.com) and ran the **Extended Test**.  
The results showed DNS servers belonging to **ProtonVPN**, not my Internet Service Provider (ISP).  

This means all my DNS queries (which reveal what sites I visit) are also routed securely through the VPN — preventing my ISP or attackers from snooping on my browsing history.  

---

## **Conclusion So Far**  
By following these steps, I confirmed that ProtonVPN successfully:  
- Masked my real IP address  
- Encrypted my internet traffic  
- Prevented DNS leaks  

At this stage, the VPN is working as intended, providing a significant privacy boost for online activities.   

---
