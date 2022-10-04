---
title: "An Overview Of My Network"
date: 2022-10-02T17:48:35+01:00
---

### ** My Network Infrastructure Breakdown:**

- My network consists of a Ubiquiti EdgeRouter X & a Cisco Catalyst switch.
- Wireguard is the VPN tunneling protocol used to connect external devices to the network.


### **Additional Info**

-----------------
**My Home LAN**

-----------------
- Ubiquiti EdgeRouter X - `erx.zahid.lan`

- Cisco 3560G - `core.zahid.lan`
	- SVIs for VLANs

- Raspberry Pi 4B 8GB - `pi.zahid.lan`
	- Running as a host for Docker containers
	- 120GB M.2 SATA SSD (boot drive) + 8TB HDD
	- Docker Containers Hosted:
		- [Plex Media Server](https://docs.linuxserver.io/images/docker-plex)

