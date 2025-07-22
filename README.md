# Denial-of-Service-Attack-Simulation-Mitigation
# Denial-of-Service Attack Simulation & Mitigation

This project demonstrates a controlled Denial-of-Service (DoS) attack simulation in a virtual lab using Kali Linux and Windows 7, applying the Penetration Testing Execution Standard (PTES) methodology.

## 🔍 Project Overview

- **Target:** Windows 7 VM
- **Attacker:** Kali Linux VM
- **Attack Types:** TCP SYN Flood, UDP Flood
- **Tools Used:** hping3, Wireshark, Metasploit, Nmap, Apache
- **Framework:** PTES (Pre-engagement → Intelligence Gathering → Exploitation → Post-exploitation)

## 🧪 Key Features

- Performed SYN flood via `hping3` to exhaust SSH port resources.
- Analyzed impact via Wireshark and CPU usage tracking.
- Created and sent a simulated backdoor using `msfvenom` and phishing.
- Gained remote control using `Meterpreter` in Metasploit.
- Applied mitigations: SYN cookies, rate limiting, IDS/IPS.

## 🛡️ Defense Techniques Tested

- SYN Cookies
- TCP Intercept
- uRPF (Unicast Reverse Path Forwarding)
- AI-based Anomaly Detection
- Web Application Firewalls

## ⚠️ Disclaimer

This project was conducted in a **safe lab environment** for academic purposes only. No real systems or users were harmed. Do **NOT** use these methods on unauthorized systems.

---

## 📷 Screenshots

![DoS Simulation](Demonstration/screenshots/attack_simulation.png)

---

## 📚 References

- PTES: https://www.pentest-standard.org/
- Metasploit Docs: https://docs.metasploit.com/
