## Viktoryia Gidrevich / 10.03.2021

## Executive Summary 
Every week we get more and more knowledge which we can use in our future occupation. In this week we learn how to use the Lucidchart. We learn about data transmission, networking hardware, and network topologies. We tried encryption and cryptography. It is all was very exciting.

## Lucidchart

## Introduction to Networking

### Data Transmission
#### Packet: The fundamental unit of data transmitted over the Internet.  Each packet has the sender’s address, the destination address, a sequence number, and a piece of the overall message to be sent. Different packets in a single message can take a variety of routes to the destination and they can arrive at different times. For this reason the sequence number is used to reassemble the packets in the proper order at the destination.

#### Packet-Switching: A network device that connects multiple hosts together and forwards packets based on their destination within the local network which is commonly known as a Local Area Network (LAN).

#### IP Address: Every device on the Internet (personal computer, a tablet, a smartphone, etc.) is assigned a unique identifying number called an IP (Internet Protocol) address. Originally, the IPv4 (version 4) standard was used. It had a format of four numbers with values ranging from 0 and 255 separated by a period. As the use of the Internet has grown, the number of IP addresses needed has increased to the point where the use of IPv4 addresses will be exhausted. This has led to the new IPv6 standard. The IPv6 standard is formatted as eight groups of four hexadecimal digits. The IPv6 standard has a limit of 3.4×1038 possible addresses.

#### DNS: DNS stands for “domain name server or system.” DNS acts as the directory of websites on the Internet. When a request to access a host with a domain name is given, a DNS server is queried. It returns the IP address of the host requested, allowing for proper routing.

#### Protocol: A protocol is the set of rules that govern how communications take place on a network. For example, File Transfer Protocol (FTP) are the communication rules for transferring files from one host to another. TCP/IP, discussed earlier, is known as a protocol suite since it contains numerous protocols.
These concepts are combined into one chain of events when we send a request to our computer and receive a response. All these are steps of the internal workflow that proceed from the Packet means our computer station and go further into the network.


### Networking Hardware
#### Switch vs. Hub
The purpose of a Hub is to connect all of our network devices together on an internal network. The Hub is considered, not to be intelligent because it does not filter any data or has any intelligence as to where the data is supposed to be sent. 
Switch is very similar to a hub. It is also a device that has multiple ports that accepts Ethernet connections from network devices. The Switch is intelligent. He is learn actual addresses of the devices that are connected to it and it stores these physical addresses. When a data packet is sent to a switch, it is only directed to the intended destination port. 
Hub only detects that a device is physically connected to it.
Switch can detect specific devices that are connected to it.  It keeps a record of the MAC addresses of those devices
Hubs and Switches are used to exchange data within a local area network. Not used to exchange data outside their own network. To exchange data outside their own network, a device needs to be able to read I.P. addresses. 

#### Router vs. Switch and Hub
Routers inspects the data’s IP address and determines if the packet was meant for its own network or if it’s meant for another network.  Routes data from one network to another based on their IP address. The router is the gateway of a network.
Hubs and Switches are used to create networks. Routers are used to connect networks.

### Network Topologies
#### Single point of Failure
If we have one computer or cable is fail in a “Star” network topologies other computers could communicate between each other. For “Bus” and  “Ring” network topologies this rule doesn’t work because are connected to a single cable or backbone.
In a “Mesh” topology, each computer on the network is connected to every other computer on the network. Having so many connections it handles failure very well.

#### Infrastrucutre vs. Wireless Mesh
Infrastructure topology uses a combination of wired and wireless devices. The wireless access point acts like a bridge between the wireless network and the wired network.
Wireless mesh topologies are similar to wired mesh topologies, where devices are interconnected with each other, but with the exception that they are wirelessly interconnected.
I think the wireless mesh because it is cheaper and no extra cabling. No matter which access point that you are connected to, you will have internet access. In a wireless mesh topology mesh, each wireless access point with talk to other wireless access points to create a seamless internet connection for wireless devices to connect to. Even if one or more access points were to fail, it wouldn’t matter, because the other access points will reroute the data. Therefore, a wireless mesh topology is very redundant because the internet connection is spread out over many wireless access points.

### Network Design
For creating my design for the diagram, I use the wireless mesh network topology.  I have a modem that brings in the internet to the building, and I have a switch that has connected to the modem. If computers wanted to access the internet, it would connect to the wireless access point and back to the modern. 

### NSA/CSS
The National Security Agency/Central Security Service (NSA/CSS) leads the U.S. Government in cryptology that encompasses both signals intelligence (SIGINT) insights and cybersecurity products and services and enables computer network operations to gain a decisive advantage for the nation and our allies. Throughout the site, NSA/CSS will be referred to collectively as NSA.
NSA provides foreign signals intelligence (SIGINT) consistent with our authorities to our nation's policy-makers and military forces to defend our country, save lives, and advance U.S. goals and alliances globally.

## Cybersecurity and Encryption

### Information Systems Security

#### Security Triad
The Information Security Triad: Confidentiality, Integrity, Availability (CIA).
Confidentiality- protecting information means you want to want to be able to restrict access to those who are allowed to see it. 
Integrity- the assurance that the information being accessed has not been altered and truly represents what is intended.
Availability- information can be accessed and modified by anyone authorized to do so in an appropriate timeframe.
For Amazon it works next way:
Confidentiality- you can get access using verification by text message. 
Availability- all information and chat service should be available 24/7.
Integrity- all information about your address and bank account should be right.

#### Authentication
Authentication can be accomplished by identifying someone through one or more of three factors:
1.	Something they know,
2.	Something they have, or
3.	Something they are.

#### ACL and RBAC
After authenticating the user, it is to ensure that he can only access the relevant information resources. This is done by using access control. Access control determines which users have the right to read, modify, add and/or delete information. There are several different access control models. The two most common are: Access Control List (ACL) and role-based access control (RBAC).

An information security officer can create an ACL that defines a list of users who have the ability to perform certain actions with an information resource, such as data files. Each user is assigned specific permissions, such as read, write, delete , or add. Only users with such permissions can perform these functions.

Access control lists are easy to understand and maintain, but have several drawbacks. The main disadvantage is that each information resource is managed separately, so if the security administrator wants to add or remove a user from a large set of information resources, it will be quite difficult. And as the number of users and resources increases, ACLs become increasingly difficult to maintain. This has led to an improved access control method called role-based access control or RBAC. In RBAC, instead of granting specific users access rights to an information resource, users are assigned roles, and then access is assigned to these roles. This allows administrators to manage users and roles separately, simplifying administration and, as a result, increasing security.

#### Ciphertext, Public Key and Private Key
Encryption is the process of encoding data when it is transmitted or stored so that only authorized persons can read it. This encoding is performed by software that encodes the plain text that needs to be transmitted (encryption). Then the recipient receives the encrypted text and decodes it (decryption). For this to work, the sender and receiver must agree on the encoding method so that both sides have the same message. Known as symmetric key encryption, both sides use a common encryption key, which allows them to encode and decode each other's messages.
An alternative to symmetric key encryption is public key encryption . When encrypting with a public key, two keys are used: the public key and the private key. To send an encrypted message, you receive a public key, encode the message, and send it. The recipient then uses their private key to decode it. The public key can be provided to anyone who wants to send a message to the recipient. Each user just needs one private key and one public key to protect messages. The private key is required to decrypt the message sent with the public key.

#### Public Key Cryptography
Public key cryptography has become an important means of ensuring confidentiality, in particular through the use of key distribution, when users seeking private communication exchange encryption keys. ... Public key encryption with digital signatures ensures the security and integrity of data from most intruders.

### Cryptography
#### Encryption
The point of Caesar’s cryptography is that you choose a digit, fix it. The number means how many letters ahead the selection of the encrypted word will be. If you choose the number 3 like me, then the letter a in the unencrypted version turns into the letter U. Therefore, the same with each letter you have to write down the encrypted version going back three letters.
“Cryptography is a growing field” = “etarvqitcrja ku c itqykpi hkgnf”

#### Frequency Fingerprint
A typical distribution of letters in English language text. Weak ciphers do not sufficiently mask the distribution, and this might be exploited by a cryptanalyst to read the message.
I agree that it is really works. I tried to type on Russian language using English alphabet and I saw which letters more use than other does.

#### Polyalphabetic Cipher
A polyalphabetic cipher is a set of simple substitution ciphers that are used to encrypt the next plaintext character according to a certain rule. The essence of a polyalphabetic cipher is the cyclic application of several monoalphabetic ciphers to a certain number of letters of the encrypted text.

#### Polyalphabetic Example
“hello professor Kathleen”
Shift word: information
“qsrag csiotgbcx zsgifntb”


#### Brute-Force
In cryptography, a brute-force attack consists of an attacker sending multiple passwords or passphrases with the hope of eventually guessing correctly. The attacker systematically checks all possible passwords and passphrases until the correct one is found.

## Conclusion
During this course, we got a lot of knowledge. Now we start to make the first step for getting any opportunities to try our skills and knowledge in real life. Now begin very responsible period where we create our resume. For me, it is the first step to the IT world. I try to do the best I can with your help and support.

