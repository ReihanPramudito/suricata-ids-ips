# Suricata IDS/IPS Implementation for Network Threat Detection

## 📖 **Overview**
- 🎯 **Objective:** *Deploy Suricata on Rocky Linux as both IDS and IPS, and secure Apache with OpenSSL-generated SSL/TLS certificates*
- 📝 **Key Steps:**
  - *Installed Suricata via COPR/EPEL, enabled Community-ID, and set up IPS mode*
  - *Created IDS rules to flag SSH on non-standard ports and HTTP anomalies, then switched to “drop” actions for active blocking*
  - *Generated and deployed self-signed SSL/TLS certificates with OpenSSL*
  - *Configured Apache and firewall to enforce HTTPS*
- 📊 **Key Results:**  
  - *100% prevention of tested SSH and HTTP attacks in IPS mode*
  - *Fully enforced HTTPS on Apache, eliminating MITM risk*
- 📚 **Context:** *Simulated enterprise network scenario for end-to-end IDS/IPS deployment and SSL/TLS hardening*

## 🛠️ **Tools & Technologies**
 <img src="https://github.com/ReihanPramudito/ReihanPramudito/blob/main/ImageAssets/suricata.png?raw=true" width="145" alt="Suricata"/>, `Rocky Linux`, `firewall-cmd`, `Apache HTTPD`, `OpenSSL`
