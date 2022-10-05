# The Network Layer Notes

`Does your IP address come from your device or the network?`
* IP addresses belong to networks, not the devices attached to the
  networks.

`What relationship do static and dynamic IP addresses have to
clients and servers?`
* In most cases, static IP addresses are reserved for servers and
  network devices, while dynamic IP addresses are reserved for
  clients.

`What are datagrams?`
* A highly structured series of fields that are strictly
  defined. Packets at the network layer, in the IP protocol, a packet is usually revered to as an IP datagram. Primary sections of the IP datagram are the header and the payload.

`What two sections can IP addresses be split into?`
* Network ID and host ID sections
* The first octet in an IP address defines the Network ID and the
  remaining three octets comprise of the host ID.

`What is the address class system?`
* A way of defining how the global IP address space is split up. There
  are three primary types of address classes, Class A,B,C.
  * Class A addresses first octet is the Network ID and the later three
    make up the Host ID
  * Class B address the first two octets are used for Network ID and the
    second two are used for the Host ID
  * Class C addresses use the first three octets are used for the
    Network ID and only the last octet is used for the Host ID

`What is CIDR?`
* Classless Inter-Domain Routing

`What is ARP`?
* Address Resolution Protocol
* A protocol used to discover the hardware address of a node with a
  certain IP address

`What is an ARP table?`
* A list of IP addresses and the MAC addresses associated with them.

`What is subnetting?`
- The process of taking a large network and splitting it up into many
  individual and smaller sub-networks, or subnets

`What is a subnet mask?`
* 32-bit numbers that are normally written out as four octets in
  decimal



