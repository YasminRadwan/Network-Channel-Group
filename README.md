# EtherChannel (Channel-Group) Configuration – Cisco Packet Tracer

## Overview
This project demonstrates the configuration of EtherChannel (Port-Channel) on Cisco
switches using Channel-Group. EtherChannel allows multiple physical links to be
aggregated into a single logical link, improving bandwidth and providing redundancy.

The lab covers both static and dynamic EtherChannel protocols (LACP and PAgP) and
highlights verification techniques.

---

## Tools & Technologies
- Cisco Packet Tracer
- Cisco IOS
- EtherChannel / Port-Channel
- LACP (802.3ad) and PAgP
- VLANs and Trunking
- TCP/IP

---

## Configuration Summary
The configuration includes:

- Grouping multiple physical interfaces into a single logical Port-Channel
- Assigning EtherChannel to access or trunk mode
- Configuring dynamic negotiation protocols (LACP / PAgP)
- Verification of Port-Channel status and link aggregation
- Integration with VLANs and inter-switch connections

---

## Key Concepts Covered
- EtherChannel fundamentals and benefits
- Static vs dynamic channel negotiation
- Port-Channel interface configuration
- Redundancy and load balancing
- Interaction with VLANs and trunking

---

## Verification
Use the following commands to verify configurations:

- `show etherchannel summary` – Check Port-Channel group status  
- `show running-config` – Review EtherChannel configuration  
- `show interfaces port-channel` – Verify logical interface  
- `show interfaces trunk` – Ensure trunking works with Port-Channel  
- `ping <destination_ip>` – Test connectivity across aggregated links

---

## Files Included
- `EtherChannel_Lab.pkt` – Packet Tracer file  
- `config.txt` – Full configuration exported from devices  
- `README.md` – This documentation

---

## How to Use
1. Open the `.pkt` file in Cisco Packet Tracer  
2. Review physical interfaces and Port-Channel configuration  
3. Verify protocol used (LACP or PAgP)  
4. Check logical interface status with:
show etherchannel summary
show interfaces port-channel

5. Test connectivity across the aggregated links

---

## Author
**Yasmin Radwan**  
Networking & Security Trainee  
CCNA Certified
