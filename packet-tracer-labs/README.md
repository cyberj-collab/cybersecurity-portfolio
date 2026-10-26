# Cisco Packet Tracer Labs

Labs completed for Ivy Tech's Cybersecurity & Information Assurance program. Open any `.pkt` file in [Cisco Packet Tracer](https://www.netacad.com/cisco-packet-tracer) (free with a Cisco NetAcad account) to inspect the topology and device configurations.

## Network design

| # | Lab | What I did |
|---|---|---|
| 01 | [MAC Address Table](01-mac-address-table.pkt) | Watched two switches learn MAC addresses as three PCs exchanged traffic, to understand how switches forward frames |
| 02 | [Build a Network](02-build-a-network.pkt) | Built a basic network (router, 2 switches, PCs) on 192.168.0.0/24 |
| 04 | [Subnetting (VLSM)](04-subnetting-vlsm.pkt) | Expanded to 4 routers, 6 switches and 7 PCs. Split 192.168.43.0/24 into /28, /29 and /30 subnets sized to each segment |
| 05 | [VLANs & Router-on-a-Stick](05-vlans-router-on-a-stick.pkt) | Added VLANs, an 802.1Q trunk, and router subinterfaces (dot1Q) to route between VLANs |
| 06 | [RIPv2 Routing](06-ripv2-routing.pkt) | Configured RIPv2 on all 4 routers so every subnet can reach every other subnet (10 PCs total) |

## Security controls

| # | Lab | What I did |
|---|---|---|
| 03 | [Secure Wireless Network](03-secure-wireless-network.pkt) | Set up a Linksys wireless router with a custom SSID and WPA2 encryption, and connected a laptop |
| 07 | [DHCP Snooping](07-dhcp-snooping.pkt) | Enabled DHCP snooping on a 2960 switch and trusted only the uplink port, so rogue DHCP servers on access ports are blocked |
| 08 | [Access Control Lists](08-access-control-lists.pkt) | Applied a standard ACL inbound on a 1941 router to deny one host and permit an authorized one |
| 09 | [SPAN & Syslog](09-span-and-syslog.pkt) | Mirrored traffic from three switch ports with SPAN for packet analysis, and sent router logs to a central syslog server |

## Skills

Cisco IOS CLI · switching and MAC learning · IPv4 subnetting (VLSM) · VLANs and 802.1Q trunking · inter-VLAN routing · RIPv2 · wireless security · DHCP snooping · ACLs · port mirroring (SPAN) · syslog
