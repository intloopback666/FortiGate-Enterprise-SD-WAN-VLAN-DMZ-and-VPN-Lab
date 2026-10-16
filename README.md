# FortiGate-Enterprise-SD-WAN-VLAN-DMZ-and-VPN-Lab
Enterprise FortiGate SD-WAN, VLAN Segmentation, DMZ , SSL-VPN Security Lab

Tasks Completed
Deployed and configured a FortiGate 7.4.1 firewall in EVE-NG.
Configured dual ISP connectivity with WAN1 and WAN2.
Implemented SD-WAN:
WAN1 as the preferred link
WAN2 as the failover link
Internet SLA/health-check monitoring
Created and configured LAN VLANs:
VLAN 100
VLAN 200
VLAN 300
Configured an 802.1Q trunk between the LAN switch and FortiGate.
Configured access ports for endpoints in each VLAN.
Created separate security zones for:
LAN
Management
DMZ
WAN
SSL-VPN users
Configured a Windows Server as:
Active Directory Domain Controller
DNS Server
DHCP Server
Created DHCP scopes for VLANs 100, 200, and 300.
Configured DHCP relay on the FortiGate to forward DHCP requests to the Windows Server.
Configured an internal DNS zone for the domain: corp.lab
Deployed a web server in the DMZ.
Configured internal DNS resolution for the DMZ web server.
Created FortiGate address objects, address groups, and service-based firewall rules.
Implemented enterprise firewall policies:
LAN-to-Internet access using NAT
LAN-to-AD/DNS/DHCP access
LAN-to-DMZ web access over HTTP/HTTPS
DMZ-to-LAN and DMZ-to-management deny rules
Restricted DMZ Internet access for updates
Applied FortiGate security profiles:
Antivirus
IPS
Web Filter
DNS Filter
Application Control
SSL/TLS certificate inspection
Published the DMZ web server securely using:
Virtual IPs (VIP/DNAT)
WAN-to-DMZ firewall policies
HTTP/HTTPS-only exposure
Configured SSL-VPN for remote users:
VPN user and group
SSL-VPN IP pool
Split tunneling
Internal DNS assignment
Restricted VPN-to-internal access policy
Configured ISP-side NAT/port forwarding for external SSL-VPN access in EVE-NG.
Hardened administrative access:
Restricted FortiGate management access to the management network
Used HTTPS/SSH only
Configured trusted administrator hosts
Disabled unnecessary WAN management exposure
Performed validation tests:
DHCP lease assignment
DNS resolution
Internet access
DMZ web-server access
VLAN segmentation
DMZ isolation
SSL-VPN connectivity
WAN1-to-WAN2 SD-WAN failover

Technologies Used:
FortiGate / FortiOS 7.4.1
SD-WAN
SSL-VPN
Cisco Switching
802.1Q VLANs
Windows Server
Active Directory
DNS
DHCP Relay
NAT / PAT
VIP / DNAT
DMZ
IPS
Antivirus
Web Filtering
DNS Filtering
Application Control


