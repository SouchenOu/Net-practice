# Net-practice
Ce projet a pour but de vous faire découvrir le réseau par des cas pratiques.

-----------------------------------------------------------------------------
👨‍ My solution and basic explanantion on Net_Practice and networking basics:
-----------------------------------------------------------------------------

What is Networking?
-------------------

Computer networking enables devices and endpoints to be connected to each other on a local area network (LAN) or to a larger network, such as the internet or a private wide area network (WAN). 

A network is a collection of computers, servers, mainframes, network devices, peripherals, or other devices connected to allow data sharing. An example of a network is the Internet, which connects millions of people all over the world. To the right is an example image of a home network with multiple computers and other network devices all connected.

Network topologies and types of networks:
---------------------------------------

The term network topology describes the relationship of connected devices in terms of a geometric graph. Devices are represented as vertices, and their connections are represented as edges on the graph. It describes how many connections each device has, in what order, and what sort of hierarchy.

Typical network configurations include bus topology, mesh topology, ring topology, star topology, tree topology, and hybrid topology.
<img width="699" alt="network-topologies" src="https://user-images.githubusercontent.com/87101785/189166083-b74fe08d-0b9f-4b7e-8acb-5656100fff74.png">


Types of networking:
--------------------

there are two types of networking: wired networking and wireless networking:
    *wired networking requires the use of a physical medium for transporting data.
    *wireless networking uses radio waves to transport data over the air without any cables.

What's a subnet mask?
--------------------

The subnet mask is used by the TCP/IP protocol to determine whether a host is on the local subnet or on a remote network.

What is TCP/IP?
---------------

TCP/IP was built to help us to determine how a specific computer should be connected to the internet and how data should be transmitted between them, The purpose is to allow communication over large distances.

An IP address is an identifier for a computer or a device on the network, every device has to have an IP address for communication purposes, An IP address consists of 2 parts: a network address and a host address, there are two versions of IP address IPv4 and IPv6:

What is the different between mac address and ip address:
--------------------------------------------------------

1:MAC Address helps in simply identifying the device but IP Address identifies the connection of the device on the network.

2:	MAC Address of computer cannot be changed with time and environment but IP Address modifies with the time and environment.

Key differences between public and private IP addresses
--------------------------------------------------------

The main difference between public and private IP addresses is how far they reach, and what they’re connected to. A public IP address identifies you to the wider internet so that all the information you’re searching for can find you. A private IP address is used within a private network to connect securely to other devices within that same network.

![Public-vs-local-IP-addresses-01](https://user-images.githubusercontent.com/87101785/189178555-71abd5fc-3fdb-4600-a08c-628eb4bb4ad9.png)

Address ranges to be use by private networks are:

Class A: 10.0.0.0 to 10.255.255.255
Class B: 172.16.0.0 to 172.31.255.255
Class C: 192.168.0.0 to 192.168.255.255

The IP address 127.0.0.1 is a special-purpose IPv4 address and is called the localhost or loopback address. All computers use this address as their own, but it doesn't let computers communicate with other devices as a real IP address does.

what is IPV4 and IPV6:
----------------------
*******************

The Internet Protocol (IP) is one of the most important communication protocols in the Internet Protocol Suite (IPS), which is used for routing and addressing packets for networking devices such as computers, laptops and fiber switches across a single network or a series of interconnected networks. There are currently two versions of Internet Protocol: IPv4 (IP version 4) and IPv6 (IP version 6). What do IPv4 and IPv6 mean? Which is faster when we are working or gaming? This article will take you to find the answer.

📫 What Is IPv4?

IPv4 is the fourth version of IP, which establishes the rules for computer networks functioning on the principle of packet exchange. It can uniquely identify devices connected to the network through an addressing system. Whenever a device gets access to the Internet (whether it's a switch, PC, or other devices), it is assigned a unique, numerical IP address such as 192.149.252.76 as shown below. The IPv4 uses a 32-bit address scheme allowing to store 2^32 addresses (4.19 billion addresses). The increasing end-users connected to the Internet leads to the exhaustion of IPv4 addresses. That’s also why the new Internet addressing system, IPv6, is being deployed to fulfill the need for more Internet addresses.

📫 What Is IPv6?

IPv6 (Internet Protocol Version 6) was deployed in 1999 concerning that the demand for IP addresses would exceed the available supply. It allows communication and data transfer to take place over a network. IPv6 is a 128-bit IP address which supports 2^128 Internet addresses in total. The use of IPv6 not only solves the problem of limited network addresses resources but also resolves the barriers for multiple access devices to connect to the Internet. An IPv6 address could be written like this: 3ffe:1900:fe21:4545:0000:0000:0000:0000.

==================================================
What is DHCP and how does it work?
----------------------------------

DHCP is an under-the-covers mechanism that automates the assignment of IP addresses to fixed and mobile hosts that are connected wired or wirelessly.

When a device wants access to a network that’s using DHCP, it sends a request for an IP address that is picked up by a DHCP server. The server responds be delivering an IP address to the device, then monitors the use of the address and takes it back after a specified time or when the device shuts down. The IP address is then returned to the pool of addresses managed by the DHCP server to be reassigned to another device as it seeks access to the network.

==================================================

📫 Comme tout réseau informatique, Internet est une connexion entre de nombreux ordinateurs qui communiquent entre eux. Il est depuis longtemps devenu indispensable de diviser l’immense réseau en plusieurs et différents sous-réseaux. Pour comprendre ce qu’est le subnetting et pour savoir pourquoi il a été introduit et enfin apprendre à calculer un masque de sous-réseau, il est tout d’abord important de clarifier quelques bases sur les réseaux informatiques:
===================================================

Un aperçu des différents réseaux informatiques.
------------------------------------------------

📈. *Personal Area Network (PAN)

Pour permettre l’échange de données des appareils modernes comme notamment les smartphones, tablettes, ordinateurs portables ou les ordinateurs de bureau, ces derniers peuvent être connectés à un réseau adapté. Celui-ci peut être relié sous la forme d’un réseau personnel ou PAN (Personnal Area Network), on parle aussi de réseau domestique.

📈 *Local Area Network (LAN):

Si plusieurs ordinateurs doivent être réunis sur un réseau, cela se fait généralement sous la forme d’un réseau local ou LAN (acronyme de Local Area Network). Un tel réseau peut relier deux ordinateurs d’une maison ou alors plusieurs centaines d’appareils au sein d’une entreprise.

📈 WLAN (wireless local area network):

réseau local sans fil. En France on utilise aussi couramment le terme de WiFi pour désigner un WLAN. Il n’y a pas vraiment de différences entre ces deux termes, WiFi est simplement une marque déposée de protocoles de communication sans fil.

📈 Metropolitan Area Network (MAN)

Un Metropolitan Area Network (MAN) ou réseau métropolitain, est un réseau de télécommunication à large bande qui relie plusieurs LAN géographiquement à proximité. Il s’agit en règle générale de différentes branches d’une société qui sont reliées à un MAN via des lignes loués.

📈 Wide Area Network (WAN):

Alors que les réseaux métropolitains relient des zones qui se trouvent proches les unes des autres dans des zones rurales ou urbaines, les WAN (Wide Area Network) ou réseaux étendus couvrent des vastes zones géographiques à l’échelle d’un pays ou d’un continent par exemple. En principe, le nombre de réseaux locaux ou d’ordinateurs connectés à un réseau étendu est illimité.

Adresses IP : réseaux et hôtes:
--------------------------------

Une adresse IP est un nombre de 32 bits. Il identifie de manière unique un hôte (ordinateur ou autre appareil, tel qu’une imprimante ou un routeur) sur un réseau TCP/IP.

Les adresses IP sont généralement exprimées au format décimal en pointillés, avec quatre nombres séparés par des points, tels que 192.168.123.132. Pour comprendre comment les masques de sous-réseau sont utilisés pour faire la distinction entre les hôtes, les réseaux et les sous-réseaux, examinez une adresse IP en notation binaire.

Masque de sous-réseau:
------------------------
Le deuxième élément, requis pour que le protocole TCP/IP fonctionne, est le masque de sous-réseau. Le masque de sous-réseau est utilisé par le protocole TCP/IP pour déterminer si un hôte se trouve sur le sous-réseau local ou sur un réseau distant.


Classes de réseau:
-------------------

Les classes A, B et C sont les plus courantes. Les classes D et E existent, mais ne sont pas utilisées par les utilisateurs finaux.

Chacune des classes d’adresses possède un masque de sous-réseau par défaut différent. Vous pouvez identifier la classe d’une adresse IP en regardant son

premier octet. Vous trouverez ci-dessous les plages dʼadresses Internet de classe A, B et C, chacune étant accompagnée dʼun exemple dʼadresse :

Les réseaux de classe A utilisent un masque de sous-réseau par défaut de 255.0.0.0 et leur premier octet est compris entre 0 et 127. L’adresse 10.52.36.11 est une adresse de classe A. Son premier octet est 10, qui est une valeur comprise entre 1 et 126 inclus.

Les réseaux de classe B utilisent un masque de sous-réseau par défaut de 255.255.0.0 et leur premier octet est compris entre 128 et 191. L’adresse 172.16.52.63 est une adresse de classe B. Son premier octet est 172, qui est une valeur comprise entre 128 et 191 inclus.

Les réseaux de classe C utilisent un masque de sous-réseau par défaut de 255.255.255.0 et leur premier octet est compris entre 192 et 223. L’adresse 192.168.123.132 est une adresse de classe C. Son premier octet est 192, qui est une valeur comprise entre 192 et 223 inclus.

Dans certains scénarios, les valeurs par défaut du masque de sous-réseau ne correspondent pas aux besoins de l’organisation pour l’une des raisons suivantes :

La topologie physique du réseau
Le nombre de réseaux (ou d’hôtes) ne correspond pas aux restrictions du masque de sous-réseau par défaut.


== How does a computer communicate locally and remotely?

+What different pieces of informations and networking devices will be used to communicate in two different situation localy and remotly:
*physical address.
*ipv4 address.
*subnet mask
*default gateway
*Dns servers

---computer A wants to communicate with computer B and also want to communicate with  c over the internet.

computer B uses the subnet mask to find that the computer c is remote and the computer A is local.

= when computer A know that computer B is local how does the computer A communicate with B (How does the computer B communicate localy):
--------

*computer A ask for Mac address of computer B
(Mac address used for local communication but ip address used for remote communication)

+switch with two devices used for local communication, but with more devices we can use it in a remote communications


<img width="1124" alt="Screen Shot 2022-09-09 at 5 17 56 PM" src="https://user-images.githubusercontent.com/87101785/189395698-77088775-ef23-4bea-adb0-25b9f30a9b07.png">






Levels:
------

📫 level 1:

<img width="1920" alt="level 11" src="https://user-images.githubusercontent.com/87101785/189197548-509ed426-d4c0-4775-80c1-a5b0941ecb1a.png">

+ In this level, we should put the computers on the same network by respecting the IP adress range.

📫 level 2:

<img width="1920" alt="level 22" src="https://user-images.githubusercontent.com/87101785/189197587-29bc4abd-b42d-4963-a39e-c93c52bf4359.png">

level 3:

<img width="1920" alt="level 33" src="https://user-images.githubusercontent.com/87101785/189197617-2871624c-1c74-4f6a-bd72-60def216dc3b.png">

A network switch forwards data packets between devices. Switches send packets directly to devices, rather than sending them to networks like a router does.

level 4:

<img width="1920" alt="level 44" src="https://user-images.githubusercontent.com/87101785/189197633-08504306-fdb1-43d9-853d-4f31faf64779.png">


level 5:

<img width="1920" alt="level 55" src="https://user-images.githubusercontent.com/87101785/189197667-dd36c2e2-fe99-4b1e-89a9-5c544de9f6d9.png">

level 6 :

<img width="1920" alt="level 66" src="https://user-images.githubusercontent.com/87101785/189197700-1f8e4a84-83c0-4fad-998f-05bc8013d0c4.png">

level 7:

<img width="1920" alt="level 77" src="https://user-images.githubusercontent.com/87101785/189197734-a3bda94a-0ff7-428a-a8f0-57fb46438573.png">

level 8:

<img width="1920" alt="level 88" src="https://user-images.githubusercontent.com/87101785/189202387-44dd32cf-323e-4fbc-81ec-91e1fb3dd402.png">



level 9:

<img width="2204" alt="level 99" src="https://user-images.githubusercontent.com/87101785/189334723-682cb447-6e16-47ff-a349-3f320079de18.png">

level 10:


<img width="2204" alt="level 10" src="https://user-images.githubusercontent.com/87101785/189340849-7f336864-920d-416b-8ca4-f3e5a39e52fb.png">

The difference between routers and switch:
-------------------------------------------

Router:

1: The main objective of router is to connect various networks simultaneously.	

2: Router is used by LAN as well as MAN.	

3: Through the router, data is sent in the form of packets.	

4: Router is compatible with NAT.

Switch:

1:While the main objective of switch is to connect various devices simultaneously.

2:While switch is used by only LAN.

3:While through switch data is sent in the form of  frame.

4:While it is not compatible with NAT.


Some ressources:

https://www.linkedin.com/pulse/how-know-two-ip-addresses-same-network-priyanka-kumari/

https://www.youtube.com/watch?v=ecCuyq-Wprc&list=PLSNNzog5eydt_plAtt3k_LYuIXrAS4aDZ&index=7
