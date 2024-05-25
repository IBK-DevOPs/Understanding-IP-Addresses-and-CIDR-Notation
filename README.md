# Understanding-IP-Addresses-and-CIDR-Notation


### This topic is going to give us clear understanding of IP addresses and CIDR [Classless inter-Domain Routing] 
## Whether as a network administrator, IT professional, or simple interest in network concepts
### We will learn proficiency in learning CIDR notation which allow flexible allocation of IP address ranges.
### We would explore CODR subnet mask and also lean to calculate subnet, and understand how CIDR notation enables efficient address space utilization.
### By the end of this course, we will possess a solid understanding of IP and CIDR notation, enabling us to efficiently manage and design network.
## Introduction to an IP address 
### An IP address is a unique that identifies a device on the internet or a local network. 
### So IP stand for INTERNET PROTOCOL which is the set of rules governing the format of data sent via the internet or local network.
### In nutshell IP addresses are the identifier that allows information to be sent between devices on a network.
### They contain location information and make devices accessible for communication.
## What is an IP Address?
### An IP address is a string of numbers separated by periods. IP addresses are expressed as a set of four numbers - an example of an IP address might be 192.158.1.38. Each number in the set can range from 0 to 255. So, the full IP addressing range goes from 0.0.0.0 to 255.255.255.255.
### IP addresses are not random. They are mathematically produced and allocated by the Internet Assigned Numbers Authority (IANA)   
### Each time anyone registers a domain on the internet, they go through a domain name registrar, who pays a small fee to ICANN to register the domain.

## Subnetting and Subnet Masks
### What is Subnetting?
### Subnetting is the practice of dividing a network into two or smaller networks. It increases routing efficiency, which helps to enhance the security of the network and reduces the size of the broadcast domain.
### IP Subnetting designates high-order bits from the host as part of the network prefix. This method divides a network into smaller subnets.
### IP address start 
## IP Address Aggregator
### IP Address Aggregator is a utility developed to automate minimization process and convert bunch of IPv4 addresses into smallest continuous range(s) possible. IP aggregation is commonly performed by network engineers working with BGP & routers.
### This utility will help webmasters to configure server firewalls, apache .htaccess files, address masks.

## What is Classful Addressing?
### Classful addressing is a network addressing the Internet's architecture from 1981 till Classless Inter-Domain Routing was introduced in 1993. 
### This addressing method divides the IP address into five separate classes based on four address bits.
### Here, classes A, B, C offers addresses for networks of three distinct network sizes. Class D is only used for multicast, and class E reserved exclusively for experimental purposes.



<<<<<<< HEAD
![alt text](<image/IP address class.png>)
=======
![alt text](<image/classful address.png>)
>>>>>>> ddc57c6159076c2d1b5349e775e29bd3e624524d







![alt text](<image/IP address class.png>)


## Class A Network
### This IP address class is used when there are a large number of hosts. In a Class A type of network, the first 8 bits (also called the first octet) identify the network, and the remaining have 24 bits for the host into that network.
## Class B Network
### In a B class IP address, the binary addresses start with 10. In this IP address, the class decimal number that can be between 128 to 191. The number 127 is reserved for loopback, which is used for internal testing on the local machine. The first 16 bits (known as two octets) help you identify the network. The other remaining 16 bits indicate the host within the network.
## Class C Network
### Class C is a type of IP address that is used for the small network. In this class, three octets are used to indent the network. This IP ranges between 192 to 223. In this type of network addressing method, the first two bits are set to be 1, and the third bit is set to O, which makes the first 24 bits of the address them and the remaining bit as the host address. Mostly local area network used Class C IP address to connect with the network.\
## Class D Network
### Class D addresses are only used for multicasting applications. Class Dis never used for regular networking operations. This class addresses the first three bits set to "1" and their fourth bit set to use for "0". Class D
### addresses are 32-bit network addresses. All the values within the range are used to identify multicast groups uniquely.
### Therefore, there is no requirement to extract the host address from the IP address, so Class D does not have any subnet mask. Example for a Class D IP address: 227.21.6.173
### Class E Network
### Class E IP address is defined by including the starting four network address bits as 1, which allows you two to incorporate addresses from 240.0.0.0 to 255.255.255.255. However, E class is reserved, and its usage is never defined. Therefore, many network implementations discard these addresses as undefined or illegal.
## Advanced Topics in IP Addressing
### Advanced topics in TCP/IP networking involve the study of advanced technologies and techniques for managing and optimizing network performance. These may include routing protocols, which are used to exchange information about network destinations between devices on a network; Virtual Private Networks (VPNs), which enable users to securely connect to a private network over the internet; Quality of Service (QoS), which is a set of technologies and techniques that are used to manage and optimize network performance; the Domain Name System (DNS), which is a hierarchical, distributed database that is used to translate human-readable domain names into machine-readable IP addresses; and Network Address Translation (NAT), which is a technique that is used to allow devices on a private network to communicate with devices on a public network.
 
## Routing Protocols Virtual Private Networks (VPNs) Quality of Service (QoS) Domain Name System (DNS) Network Address Translation (NAT)
## Routing Protocols Routing protocols exchange information about network destinations between devices on a network. They are an important component of advanced TCP/IP networking topics, as they play a key role in determining the best path for data to travel from one device to another.
## There are several types of routing protocols, including:
### Distance Vector Routing Protocols: These protocols use a distance metric (such as hop count) to determine the best path to a destination.
### Open Shortest Path First (OSPF) and Intermediate System-to-Intermediate System (IS-IS). Hybrid Routing Protocols: These protocols combine elements of distance vector and link-state protocols.
### Enhanced IGRP (EIGRP) and Border Gateway Protocol (BGP). Path Vector Routing Protocols: These protocols use a path vector (a list of autonomous systems that a route traverses) to determine the best path to a destination.
### Virtual Private Networks (VPNs) A Virtual Private Network (VPN) is a technology that enables users to connect to a private network over the internet securely. It is often used in the context of advanced TCP/IP networking topics to securely extend a private network over a public network, such as the internet.
### There are several types of VPNs, including:
### Remote-Access VPNs: These allow users to connect to a private network remotely, such as their home or office. 
### Site-to-Site VPNs: These VPNs allow organizations to connect multiple sites over a public network, such as the internet, to create a single, private network.
### Mobile VPNs: These VPNs allow users to securely connect to a private network using a laptop or mobile device while on the go.
### Virtual LAN (VLAN) VPNs: These VPNs allow users to create virtual networks within a larger network, segment traffic, and improve security. By using a VPN, organizations can securely connect to a private network from a remote location, connect multiple sites over a public network, or create virtual networks within a larger network. This can help to improve security, enable remote access, and optimize network performance.
### Quality of Service (QoS) Quality of Service (QoS) is a set of technologies and techniques used to manage and optimize network performance. It is often discussed in the context of advanced TCP/IP networking topics to ensure that critical applications and services receive the bandwidth and resources they need to operate effectively.
### Domain Name System (DNS) The Domain Name System (DNS) is a hierarchical, distributed database that is used to translate human-readable domain names (such as  www.example.com) into machine-readable IP addresses (such as 192.168.1.1). It is often discussed in the context of advanced TCP/IP networking topics as a critical component of the internet's infrastructure.
### Network Address Translation (NAT)
 
### Network Address Translation (NAT) is a technique that allows devices on a private network to communicate with devices on a public network, such as the internet. It is often used to allow devices on a local network to access the internet without needing a public IP address.
### There are several benefits to using NAT, including:
### Security: NAT can help to improve security by hiding the IP addresses of devices on the private network from the public network. This can make it more difficult for attackers to target specific devices. Resource
### conservation: NAT can help to conserve resources by allowing multiple devices on a private network to share a single public IP address. This can be useful when a limited number of public IP addresses are available.

