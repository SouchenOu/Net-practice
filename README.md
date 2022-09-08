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

why using routers and switch:
------------------------------


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

==================================================

📫 Comme tout réseau informatique, Internet est une connexion entre de nombreux ordinateurs qui communiquent entre eux. Il est depuis longtemps devenu indispensable de diviser l’immense réseau en plusieurs et différents sous-réseaux. Pour comprendre ce qu’est le subnetting et pour savoir pourquoi il a été introduit et enfin apprendre à calculer un masque de sous-réseau, il est tout d’abord important de clarifier quelques bases sur les réseaux informatiques:
===================================================
📈 Depuis 1981, Internet fonctionne sur la base du protocole Internet (IP) : un protocole réseau qui régule les circuits de distribution des utilisateurs. Pour envoyer un paquet de données dans un réseau, l’expéditeur doit connaître l’adresse IP du destinataire.

📈 Le Net ID et le Host ID sont cachés dans l’adresse IP. Il est ainsi possible d’identifier le réseau correspondant et son hôte, par exemple un PC ou une imprimante réseau. Sur la base de ces informations, les routeurs peuvent transmettre des paquets de données aux destinataires corrects.

📈 Les ordinateurs ne comprennent que les zéros et les uns et fonctionnent donc dans un système informatique binaire. C’est pourquoi les adresses IP sont ainsi structurées. Le système IPv4 actuellement utilisé est composé de 32 bits, c’est-à-dire 32 zéros ou uns. Pour faciliter la compréhension et pour économiser de l’espace, les adresses IP sont généralement représentées en notations décimales séparées par des points ; c’est la notation décimale à point ou « oudotted decimal notation » : 192.168.88.3.

**Décimal	192	168	88	3
**Binaire	11000000	10101000	01011000	00000011

📈 Ce format fournit un nombre limité d’adresses possibles. Précisément : 232(donc 4.294.967.296) adresses peuvent être attribuées. Cela semble beaucoup, mais ces adresses sont utilisées plus vite que vous le ne pensez. Le subnetting a donc été introduit en 1985.

Un aperçu des différents réseaux informatiques.
------------------------------------------------

📈. *Personal Area Network (PAN)

Pour permettre l’échange de données des appareils modernes comme notamment les smartphones, tablettes, ordinateurs portables ou les ordinateurs de bureau, ces derniers peuvent être connectés à un réseau adapté. Celui-ci peut être relié sous la forme d’un réseau personnel ou PAN (Personnal Area Network), on parle aussi de réseau domestique.

Pour permettre l’échange de données des appareils modernes comme notamment les smartphones, tablettes, ordinateurs portables ou les ordinateurs de bureau, ces derniers peuvent être connectés à un réseau adapté. Celui-ci peut être relié sous la forme d’un réseau personnel ou PAN (Personnal Area Network), on parle aussi de réseau domestique

📈 *Local Area Network (LAN):

Si plusieurs ordinateurs doivent être réunis sur un réseau, cela se fait généralement sous la forme d’un réseau local ou LAN (acronyme de Local Area Network). Un tel réseau peut relier deux ordinateurs d’une maison ou alors plusieurs centaines d’appareils au sein d’une entreprise.

📈 WLAN (wireless local area network):

réseau local sans fil. En France on utilise aussi couramment le terme de WiFi pour désigner un WLAN. Il n’y a pas vraiment de différences entre ces deux termes, WiFi est simplement une marque déposée de protocoles de communication sans fil.

📈 Metropolitan Area Network (MAN)

Un Metropolitan Area Network (MAN) ou réseau métropolitain, est un réseau de télécommunication à large bande qui relie plusieurs LAN géographiquement à proximité. Il s’agit en règle générale de différentes branches d’une société qui sont reliées à un MAN via des lignes loués.

📈 Wide Area Network (WAN):

Alors que les réseaux métropolitains relient des zones qui se trouvent proches les unes des autres dans des zones rurales ou urbaines, les WAN (Wide Area Network) ou réseaux étendus couvrent des vastes zones géographiques à l’échelle d’un pays ou d’un continent par exemple. En principe, le nombre de réseaux locaux ou d’ordinateurs connectés à un réseau étendu est illimité.



Comprendre les principes de base des adresses et sous-réseaux TCP/IP:
--------------------------------------------------------------------

Pour configurer correctement TCP/IP, il est nécessaire de comprendre comment les réseaux TCP/IP sont traités et divisés en réseaux et sous-réseaux.

Le succès du protocole TCP/IP en tant que protocole réseau d’Internet est en grande partie dû à sa capacité à connecter des réseaux de différentes tailles et systèmes de différents types. Ces réseaux sont arbitrairement définis en trois classes principales (et quelques autres) ayant des tailles prédéfinies. Chacun d’eux peut être divisé en sous-réseaux plus petits par les administrateurs système. Un masque de sous-réseau est utilisé pour diviser une adresse IP en deux parties. L’une identifie l’hôte (ordinateur), l’autre le réseau auquel il appartient. Pour mieux comprendre le fonctionnement des adresses IP et des masques de sous-réseau, consultez une adresse IP et voyez comment elle est organisée.


Adresses IP : réseaux et hôtes:
--------------------------------

Une adresse IP est un nombre de 32 bits. Il identifie de manière unique un hôte (ordinateur ou autre appareil, tel qu’une imprimante ou un routeur) sur un réseau TCP/IP.

Les adresses IP sont généralement exprimées au format décimal en pointillés, avec quatre nombres séparés par des points, tels que 192.168.123.132. Pour comprendre comment les masques de sous-réseau sont utilisés pour faire la distinction entre les hôtes, les réseaux et les sous-réseaux, examinez une adresse IP en notation binaire.

Par exemple, l’adresse IP décimale en pointillés 192.168.123.132 est (en notation binaire) le numéro de 32 bits 110000000101000111101110000100. Ce nombre peut être difficile à interpréter, donc divisez-le en quatre parties de huit chiffres binaires.

Ces sections de 8 bits sont appelées octets. L’exemple d’adresse IP devient alors 11000000.10101000.01111011.10000100. Ce nombre est un peu plus logique. Ainsi, pour la plupart des utilisations, convertissez l’adresse binaire au format décimal en pointillés (192.168.123.132). Les nombres décimaux séparés par des points sont les octets convertis de la notation binaire à la notation décimale.

Pour qu’un réseau WAN (Wide Area Network) TCP/IP fonctionne efficacement en tant que collection de réseaux, les routeurs qui passent des paquets de données entre les réseaux ne connaissent pas l’emplacement exact d’un hôte pour lequel un paquet d’informations est destiné. Les routeurs connaissent uniquement le réseau dont l’hôte est membre et utilisent les informations stockées dans le tableau d’itinéraires pour déterminer comment obtenir le paquet vers le réseau de l’hôte de destination. Une fois le paquet remis au réseau de destination, il est remis à l’hôte approprié.

Pour que ce processus fonctionne, une adresse IP comporte deux parties. La première partie d’une adresse IP est utilisée comme adresse réseau, la dernière partie comme adresse hôte. Si vous prenez l’exemple 192.168.123.132 et que vous le divisez en ces deux parties, vous obtenez 192.168.123. = réseau .132 = hôte ou 192.168.123.0 = adresse du réseau. 0.0.0.132 = adresse de l’hôte.

Masque de sous-réseau:
------------------------
Le deuxième élément, requis pour que le protocole TCP/IP fonctionne, est le masque de sous-réseau. Le masque de sous-réseau est utilisé par le protocole TCP/IP pour déterminer si un hôte se trouve sur le sous-réseau local ou sur un réseau distant.

Dans TCP/IP, les parties de l’adresse IP utilisées comme adresses réseau et hôte ne sont pas fixées. Sauf si vous avez plus d’informations, les adresses réseau et hôte ci-dessus ne peuvent pas être déterminées. Ces informations sont fournies dans un autre numéro de 32 bits appelé masque de sous-réseau. Le masque de sous-réseau est 255.255.255.0 dans cet exemple. Il n’est pas évident de savoir ce que signifie ce nombre, sauf si vous savez qu’en notation binaire, 255 est égal à 11111111. Ainsi, le masque de sous-réseau est 11111111.11111111.11111111.00000000.

En alignant l’adresse IP et le masque de sous-réseau, le réseau et des parties hôtes de l’adresse peuvent être séparés :

11000000.10101000.01111011.10000100 - Adresse IP (192.168.123.132)

11111111.11111111.11111111.00000000 - Masque de sous-réseau (255.255.255.0)

Les 24 premiers bits (le nombre de uns dans le masque de sous-réseau) sont identifiés comme lʼadresse réseau. Les 8 derniers bits (le nombre de zéros restants dans le masque de sous-réseau) sont identifiés comme lʼadresse de lʼhôte. Cela vous donne les adresses suivantes :

11000000.10101000.01111011.00000000 - Adresse réseau (192.168.123.0)

00000000.00000000.00000000.10000100 - Adresse de lʼhôte (000.000.000.132)

Vous savez donc maintenant, pour cet exemple utilisant un masque de sous-réseau de 255.255.255.0, que lʼID du réseau est 192.168.123.0 et que lʼadresse de lʼhôte est 0.0.0.132. Lorsqu’un paquet arrive sur le sous-réseau 192.168.123.0 (du sous-réseau local ou d’un réseau distant) et qu’il a une adresse de destination de 192.168.123.132, votre ordinateur le reçoit du réseau et le traite.

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


Mise en sous-réseau:
---------------------

Un réseau TCP/IP de classe A, B ou C peut être encore divisé, ou mis en sous-réseau, par un administrateur système. Cela devient nécessaire lorsque vous conciliez le schéma dʼadressage logique de lʼInternet (le monde abstrait des adresses IP et des sous-réseaux) avec les réseaux physiques utilisés dans le monde réel.

Un administrateur système à qui lʼon attribue un bloc dʼadresses IP peut administrer des réseaux qui ne sont pas organisés de façon à permettre lʼutilisation de ces adresses. Par exemple, vous possédez un réseau étendu avec 150 hôtes sur trois réseaux (dans des villes différentes) qui sont connectés par un routeur TCP/IP. Chacun de ces trois réseaux possède 50 hôtes. On vous attribue le réseau de classe C 192.168.123.0. ( A titre dʼillustration, cette adresse provient en fait dʼune plage qui nʼest pas allouée sur Internet). Cela signifie que vous pouvez utiliser les adresses 192.168.123.1 à 192.168.123.254 pour vos 150 hôtes.

Deux adresses qui ne peuvent pas être utilisées dans votre exemple sont 192.168.123.0 et 192.168.123.255, car les adresses binaires dont la partie hôte est composée de tous les uns et de tous les zéros ne sont pas valides. L’adresse zéro n’est pas valide, car elle est utilisée pour désigner un réseau sans spécifier d’hôte. L’adresse 255 (en notation binaire, une adresse hôte composée de tous les uns) est utilisée pour diffuser un message à tous les hôtes dʼun réseau. N’oubliez pas que la première et la dernière adresse d’un réseau ou d’un sous-réseau ne peuvent pas être attribuées à un hôte individuel.

Vous devriez maintenant être en mesure dʼattribuer des adresses IP à 254 hôtes. Cela fonctionne impeccablement si les 150 ordinateurs sont tous sur un seul réseau. Toutefois, vos 150 ordinateurs se trouvent sur trois réseaux physiques distincts. Au lieu de demander plus de blocs dʼadresses pour chaque réseau, vous divisez votre réseau en sous-réseaux, ce qui vous permet dʼutiliser un bloc dʼadresses sur plusieurs réseaux physiques.

Dans ce cas, vous divisez votre réseau en quatre sous-réseaux à l’aide d’un masque de sous-réseau qui élargit l’adresse réseau et réduit la plage possible d’adresses hôtes. En dʼautres termes, vous « empruntez » certains des bits utilisés pour lʼadresse hôte et les utilisez pour la partie réseau de lʼadresse. Le masque de sous-réseau 255.255.255.192 vous donne quatre réseaux de 62 hôtes chacun. Cela fonctionne, car en notation binaire, 255.255.255.192 est égal à 11111111.11111111.1111111.11000000. Les deux premiers chiffres du dernier octet deviennent des adresses réseau. Vous obtenez donc les réseaux supplémentaires 00000000 (0), 01000000 (64), 10000000 (128) et 11000000 (192). (Certains administrateurs nʼutiliseront que deux des sous-réseaux en employant 255.255.255.192 comme masque de sous-réseau. Pour plus d’informations sur ce sujet, reportez-vous au document RFC 1878). Dans ces quatre réseaux, les six derniers chiffres binaires peuvent être utilisés pour les adresses hôtes.

À l’aide d’un masque de sous-réseau de 255.255.255.192, votre réseau 192.168.123.0 devient alors les quatre réseaux 192.168.123.0, 192.168.123.64, 192.168.123.128 et 192.168.123.192. Ces quatre réseaux auraient comme adresses hôtes valides :

192.168.123.1-62, 192.168.123.65-126, 192.168.123.129-190 et 192.168.123.193-254
Nʼoubliez pas, une fois encore, que les adresses hôtes binaires comportant tous les uns ou tous les zéros ne sont pas valides. Vous ne pouvez donc pas utiliser dʼadresses dont le dernier octet est égal à 0, 63, 64, 127, 128, 191, 192 ou 255.

Vous pouvez voir comment cela fonctionne en examinant deux adresses hôtes, 192.168.123.71 et 192.168.123.133. Si vous avez utilisé le masque de sous-réseau de classe C par défaut de 255.255.255.0, les deux adresses se trouvent sur le réseau 192.168.123.0.

Toutefois, si vous utilisez le masque de sous-réseau de 255.255.255.192, ils se trouvent sur des réseaux différents ; 192.168.123.71 se trouve sur le réseau 192.168.123.64 et 192.168.123.133 se trouve sur le réseau 192.168.123.128.

Levels:
------

📫 level 1:

<img width="2560" alt="Screen Shot 2022-09-08 at 4 48 59 PM" src="https://user-images.githubusercontent.com/87101785/189167641-357d04b4-8cb5-48f7-a69b-ab4371580671.png">

+ In this level, we should put the computers on the same network by respecting the IP adress range.

📫 level 2:

<img width="2560" alt="level2" src="https://user-images.githubusercontent.com/87101785/189173323-9171cc51-31fd-464d-839c-511d00090e1c.png">

level 3:

<img width="2560" alt="level3" src="https://user-images.githubusercontent.com/87101785/189180833-2ba9eb95-8060-49b9-a51e-3461ce3fd2eb.png">

A network switch forwards data packets between devices. Switches send packets directly to devices, rather than sending them to networks like a router does.

level 4:

<img width="2560" alt="level4" src="https://user-images.githubusercontent.com/87101785/189182933-be7c134d-5803-45f6-9c22-9df3c4e117f7.png">

level 5:

<img width="2560" alt="level5" src="https://user-images.githubusercontent.com/87101785/189191377-a5be3815-5c15-4bb5-a6d6-4bd4c625cf1a.png">

level 6 :

<img width="2560" alt="level 6 " src="https://user-images.githubusercontent.com/87101785/189192959-be6e85e3-0946-4ed5-b8e4-fb86856e9f15.png">


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
