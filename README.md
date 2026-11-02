# networkwalks-phase1-kali-lab
Phase 1 cybersecurity lab setup using VirtualBox and Kali Linux
# Networkwalks – Phase 1: Kali Linux Lab Setup

## Project Overview
This project documents the completion of Phase 1 of my cybersecurity internship lab setup with Networkwalks.

The objective was to establish a working Kali Linux virtual machine using Oracle VirtualBox and configure its network connectivity.

## Tools and Technologies
- Oracle VirtualBox
- Kali Linux
- 7-Zip
- VirtualBox NAT Network

## Lab Configuration

| Component | Configuration |
|---|---|
| Virtualisation platform | Oracle VirtualBox |
| Operating system | Kali Linux |
| Network mode | NAT Network |
| Network name | NatNetwork |
| Network subnet | 10.0.0.0/24 |
| Kali IP address | 10.0.0.2/24 |
| Default gateway | 10.0.0.1 |
| DNS server | 8.8.8.8 |

## Tasks Completed
- Installed 7-Zip.
- Installed Oracle VirtualBox.
- Created a NAT Network with the subnet 10.0.0.0/24.
- Downloaded and imported the Kali Linux virtual machine.
- Configured a static IP address for Kali Linux.
- Verified connectivity to the default gateway.
- Tested external network connectivity.
- Verified DNS resolution using google.com.
- Created a VirtualBox snapshot to preserve the lab configuration.

## Network Connectivity Verification

The following tests were successful:

- `ping -c 4 10.0.0.1` – Gateway connectivity.
- `ping -c 4 8.8.8.8` – External network connectivity.
- `ping -c 4 google.com` – DNS resolution and connectivity.

All three tests returned 4 successful replies with 0% packet loss.

## Learning Outcomes
- Gained practical experience configuring a virtual cybersecurity lab.
- Learned to configure static IP addressing in Kali Linux.
- Practised basic network troubleshooting and connectivity verification.
- Learned how to create and manage VirtualBox snapshots.

## Status
**Phase 1 – Lab Setup: Completed**
