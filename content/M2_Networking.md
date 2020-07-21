# The Bits and Bytes of Computer Networking
This module talked about networking technology in more depth

## week 1: TPC/IP layer model
The stack model is a way of dealing with the complexity needed to interconnect the wide range of technologies and devices that form the internet. In the stack model the process of connetion is separated in layer, each one responsable for a single functionality at the time. These layers interface herarhically with one another in such a way that they can be thought as a black box system where, the how of the process made is not needed to be known by the other layers in order for the system to work. This modularity simplifies the design  requierments and makes it more robust, facilitating changes in the implementation. 


There are two main different stack models, the five-layered TCP/IP and the seven-layered OSI model, both are intended to organize the connetion process between computers, the difference is that the OSI model is more detailed in the final stage. Where the TCP/IP model has the application layer the OSI model segment it in three different ones.  

### devices and the physical layer
In order to connect between devices there needs to be some kind of infrastructure that supports this communication. Back in the day there were telegraph lines, as the technology advanced telephone lines emerge, wire connected to each end of the transmission. Despide the improvement phones had a scalability problem  connecting then cellphone antennas phones 

### Data link layer
MAC address



## week 2: The Networking layer
Internet Protocol is intended to organize computers in a logical network IPv4 was originalliy intended to be divide in different classes each one to a specific number of user, however as the numbers grew there needed to be new strategies in order to accomodate the demand. Some of the solutions proposed were: private  not routable IP address, and  Classless Inter-Domain Routing  (CIDR) allowing networking addresing range out of the stablished classes. However this were only temporal solutions and a new standar needed to be created. IPv6 was design to deal with rising number of addresses requiered. It is a 128 bit number divided in two parts first a 64 bit network part followed by a 64.

### ARP (Address Resolution Protocol)

The easiest way to understand what ARP does is thorught an analogy, imagine you want to send a letter to someone, in this case send a letter to Alice. The postal service is the physical layer, the one who made out all the connection infrastructure needed in order send messages, however the infrastructure is not enough you need to know to Alice's address in order to send her the message. What do you do?

Well you can __mail every available address (broadcast)__ a message saying the following:

> I am looking for Alice, if you are Alice please send me back your address if you are not ignore this message

In the real world this doesn't seem a very practical solution but that is how computer find each other out. And this analogy exposess the weaknesses of this system. This strategy works fine in a small town with few addresses but in a big city you'll need to send a huge amount of mail in order to find Alice. Back in the networking world this amount of messages can create a overload in trafic, which becomes worst and worst as the network grows. __Subnetting__ can counteract this problem, it segments big networks into smaller ones reducing the avaliable addresses any computer can broadcast. 

A second problem this system faces is that of __spoofing__, what prevents me from pretending I am Alice responding your message with _"This is Alice here is my address please send the message to me", this is a real issue network security face.  


### routing protocols
Routing tables

Interior Gateway Protocols 

Exterior Gateway Protocols 


NIC: Network Interface Card
MAC Address: Media Access Control



## week 3: The Transport layer
Paradigms of conection or conectionless communication. 
robust and error control mechanism
ackwolegment 

the three way handshake: stablishing a TCP connection


port 
socket: are the aggregate of an IP address and a port 
TPC
UDP

firewalls


## week 4: 
__DNS:__ Domanin Name Service 

__DHCP:__ Dynamic Host Configuration Protocol

__NAT:__ Network Address Translation

fierwalls 

proxy servers

__VPN:__ Virtual Priveta Network creates a secure connection under a insecure network it is used to remotely connect to a  internal network

## week 5: types of connections 
__DSL:__ Digital Subscriber lines
__WLAN__: Wireless LAN 
Channel 
Security


__WAN:__ wide Area Network


## week 6: troubleshooting networking issues
ping
traceroute
