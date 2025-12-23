# Windows Server 2022 – Basic Notes

## Purpose
This Windows Server 2022 VM acts as the **Domain Controller** and **central log source** in the home lab.  
Right now, it is only set up as part of the lab structure.  
All detailed configurations (AD setup, log forwarding, policies, etc.) will be documented later in the mini‑tasks repo.

---

## VM Specs
- **OS:** Windows Server 2022
- **Role:** Domain Controller / Central Logs
- **RAM:** 4 GB
- **CPU:** 4 cores
- **Disk:** 60 GB SSD
- **Network:** NAT (same network as other VMs)

---

## Current Status
- Windows Server 2022 is installed and running.
- No roles or features configured yet.
- Active Directory, DNS, and log forwarding will be added later as separate mini tasks.

---

## Notes
- This VM will eventually manage the domain for the entire lab.
- Windows 10 endpoints will join this domain later.
- Security logs from this server will be forwarded to the SIEM (Ubuntu) in future tasks.
- For now, this file only documents the VM as part of the lab overview.

