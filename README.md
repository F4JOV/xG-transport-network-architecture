# xG-transport-network-architecture
This infrastructure represents a exemple of what a private 4G/5G transport network looks like. To make it more simple, it only uses a single OSPF area for the entire dynamic routing. In the real life, it looks like this too but on the transport core network we will find BGP and sometime MPLS when the private xG network is deplyed over an entire city.

This project contains L3 etherchannels on L3 switches and OSPF on all routers and L3 switches. All in area 0, static ip and route on the servers.

Created on Sandbox from PingMyNetwork
