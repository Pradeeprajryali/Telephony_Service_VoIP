# Telephone Service Network Design (VoIP)

Built a telephonic service using VLANs, inter-VLAN routing (Router-on-a-Stick), DHCP
server, SSH, VoIP configurations and Static IPv4 Addressing & Dial peering.

#output

![VOIP](https://github.com/Pradeeprajryali/Telephony_Service_VoIP/assets/144598651/6ec7cea7-bb04-4b16-b91f-f6a8a06f13ea)

The IT Manager emphasized scalability and availability, and hence you are required to provide a complete network infrastructure design and implementation. Turtle Consultancy Limited will be using the following IP address: 192.168.100.0/24 for Data, 172.16.100.0/24 for Voice, and 10.10.10.0/24 between the routers.
Design a networked system to meet the given specifications. Use packet tracer software to design your network.
*Routers- Each department is to have VoIP enabled router with server-side LAN attached to the ICT department router. Note: use Cisco 2811 router.
*Switches- Each department has an access layer switch. Note: use Cisco 2960 switch.
*Connections- Use serial connections between a router and a router, then a straightthrough cable between the router to switch, switch to hosts, phones to PCs.
*Subnets- Each department will be accessing two subnetworks, for example, data and voice subnets. Note: carry out appropriate subnetting.
*Basic settings- Configure basic device settings such as hostnames, console passwords, enable passwords, banner messages, encrypt all passwords, and disable IP domain lookup.
*DHCP Server- For voice (VoIP), use the respective router as the DHCP server while for Data use the DHCP server device at the server-side site.
*VLANs- Each department will be in two VLANS. One for data and another for voice. Note: All IP phones in the network should be in VLAN 100.
*Inter-VLAN Routing- Use router-on-a-stick to enable inter-VLAN routing on the network. Note: create subinterfaces for both data and voice VLANs.
*IP Addressing- All devices in the network are expected to obtain an IP address dynamically from the respective DHCP servers while the devices in the server room are to be allocated IP addresses statically.
*Routing protocol- Use OSPF as the routing protocol to advertise routes on the routers.
*Remote Access- Configure SSH in all the routers for remote login.
*Telephony service- Configure VoIP on the routers and allocate dial numbers in this format for the departments, Finance(1..), HR (2..), Sales (3..), and ICT (4..), (where 1.. can be 101 to 199) and so on.
*Routing for VoIP- Configure dial-peering on the routers to allow IP phones from different routers to communicate.
*inalize- Test Communication, ensure everything configured is working as expected.

Technologies Implemented
> Creating a network topology using Cisco Packet Tracer.
> Hierarchical Network Design.
> Connecting Networking devices with Correct cabling.
> Configuring Basic device settings.
> Creating VLANs and assigning ports VLAN numbers.
> Creating both data and voice VLANs and assigning ports VLAN numbers.
> Subnetting and IP Addressing.
> Configuring Inter-VLAN Routing on the Routers (router-on-a-stick).
> Configuring Dedicated DHCP Server device for Data to provide dynamic IP allocation.
> Configuring Routers as DHCP server for Voice to provide IP Phones dynamic IP allocation.
> Configuring SSH for secure Remote access.
> Configuring OSPF as the routing protocol.
> Configuring VoIP or Telephony service configuration in all routers.
> Configuring Routing for VoIP or Dial peering configuration in all routers.
> Host Device Configurations.
> Test and Verifying Network Communication.
