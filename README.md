# GLOBALNET-INTERNATIONAL
![GlobalNet International Network Topology](TOPOLOGY-MAP.png)


1. Executive Summary & Company Profile
GlobalNet International is a rapidly expanding global logistics and supply chain enterprise. The company coordinates freight forwarding, warehousing, and cross-border customs brokerage. To support its massive transactional growth, protect central server resources, and guarantee continuous operational uptime, GlobalNet International requires a modern, highly available, and secure multi-site hybrid architecture.
This project details the implementation of a scalable network architecture connecting the corporate Head Office to two distinct regional facilities (Branch A and Branch B) using standard-compliant segmentation, redundant paths, and structured WAN tunneling.


Technology to be implemented

HSRP (Hot Standby Router Protocol)

LACP EtherChannel (Link Aggregation Control Protocol)

IEEE 802.1Q VLAN Trunking
VLAN Segmentation (VLANs 10, 20, 30, 60, 70, 99, 1)
GRE (Generic Routing Encapsulation) Tunneling
Router-on-a-Stick (ROAS)
	Point-to-Point (P2P) Serial WAN Connectivity
	VLSM (Using 10.10.0.0/16 block)
	DHCP (Dynamic Host Configuration Protocol) Server & Pools
	DHCP Relay Agent (ip helper-address)
	Cisco IP Phone Voice-VLAN Architecture
	DNS (Domain Name System)
	DHCP Snooping
	Dynamic ARP Inspection (DAI)
	Switchport Port Security 
	Access Control Lists (ACLs)
	SSH Version 2 (Secure Shell)
	Cisco IOS Privilege Level 15 Executive Routing
	IP address configuration
	OSPF
	Static routing (default route}
	NAT/PAT
