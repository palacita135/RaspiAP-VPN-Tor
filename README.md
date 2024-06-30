Turn your RaspberryPi into a VPN with Tor as Access Point

Any Raspberry Pi within an Ethernet network can be used as a wireless access point, but today we will pump it up with more secure and anonymous internet connection, but first lets learn about the types of Tor and VPN connections:

Tor over VPN
The above setup will only work if the VPN connection is up before running Tor browser. Then Tor browser will connect to tor over VPN and all other applications will simply connect over VPN.
PROS:

1- Hide Tor from your ISP.

2- VPN provider cannot see your traffic.

3- The Tor entry-node cannot see your real IP, it will get the VPN provider IP.

VPN over Tor
This connection setup works within VPN provider support, in this setup your data will be encrypted by the VPN while entering and exiting TOR nodes before it ends up routed to the Internet.
PROS:
1- Your VPN provider cannot see your real IP, only the TOR exit node can.
2- Bypass any website that blocks TOR, as your connection to TOR is hidden by your VPN and the website will get your VPN IP.

learn more about the difference in details here https://airvpn.org/tor/
