# Network Scan Report – Task 1

**Network used:** 10.3.40.0/24  
**Target host:** 10.3.40.195 (my Kali VM)  
**Tool:** Nmap (v7.94)  
**Scan type:** TCP SYN scan (-sS)  
**Purpose:** Discover open ports and services on a local network host.

---

## Steps Followed

1. Checked VM network adapter mode – set to *Bridged Adapter*.
2. Verified IP and gateway using `ip addr` and `ip route`.
3. Ran a host discovery using:
   ```bash
   sudo nmap -sn 10.3.40.0/24 -oN alive_hosts.txt


