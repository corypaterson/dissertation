###### 23/02/19

## Network Basics
-----

### Clients and Servers

A server will hold information or assets whhich can be requested by clients to use, view or download. This is called a **client-server relationship**.

### IP Addresses

IP Addresses are used to identify the destinations and origins of data flow in a  network.

Composed of: 
- Four numbers
- Ranged between 1 and 254
- Separated by dots
- E.g 173.194.43.7

> IP Addresses can either be public or private. Private addesses will most likely be concealed behind a public address acting as a gateway for network traffic.

### Hubs and Switches

**Network Hub**:

- Network traffic is sent down one cable to the hub and traffic is relayed onto all computers connected to the hub.
- Can be very slow if lots of computers connected

**Switches**:

- Using a switch, the network traffic is only sent to the intended destination.
- Multiple computers can send messages in parallel without interference.
- Switch only knows the address of a connected device, which means the number of possible destinations of network traffic is limited by the number of switch ports.  

### Routers and Firewalls

**Routers**: 
Make decisions about the direction and flow of network traffic, and whether to allow communication of traffic from outside networks.

Three main functions: 
- **Separate and Bridge**:
 - Separating netyworks into sections or, 
 - bridging different networks together
  
- **Assign IPs**:
  - If any new nodes are connected to a network, the router will assign an IP using Dynamic Host Configuration Protocol (DHCP)

- **Firewall and Protect**:
  - Can filter traffic to keep other nwtworks out of private networks.
  - This is software built into a router. 