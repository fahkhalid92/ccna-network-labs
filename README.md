# CCNA Mega Lab: Two-Site Campus Network

Three-tier campus network (core, distribution, access) across two offices,
with wireless, voice and internet edge. Built in Cisco Packet Tracer.
Based on Jeremy's IT Lab CCNA Mega Lab; configured and tested by me.

![Topology](CCNA%20MegaLab.png)

## Design
- Core: CSW1, CSW2
- Distribution: DSW-A1/A2 (Office A), DSW-B1/B2 (Office B)
- Access: ASW-A1..A3, ASW-B1..B3
- Wireless: WLC1 with LWAP1/LWAP2
- Voice: IP phones, voice VLANs

## What I configured
- [ ] VLANs and trunking
- [ ] EtherChannel
- [ ] STP
- [ ] Inter-VLAN routing / HSRP
- [ ] OSPF
- [ ] DHCP / DNS
- [ ] NAT / ACLs
- [ ] Wireless (WLC)


## Files
- `CCNA MegaLab.pka`: the lab file (open with Cisco Packet Tracer)
- `CCNA MegaLab.png`: topology screenshot
- `*_running-config.txt`: device running-configs (R1, CSW1, CSW2, DSW-A1/A2, DSW-B1/B2)
