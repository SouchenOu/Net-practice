# Net-practice
Ce projet a pour but de vous faire découvrir le réseau par des cas pratiques.

-----------------------------------------------------------------------------
👨‍ My solution and basic explanantion on Net_Practice and networking basics:
-----------------------------------------------------------------------------

📫 Comme tout réseau informatique, Internet est une connexion entre de nombreux ordinateurs qui communiquent entre eux. Il est depuis longtemps devenu indispensable de diviser l’immense réseau en plusieurs et différents sous-réseaux. Pour comprendre ce qu’est le subnetting et pour savoir pourquoi il a été introduit et enfin apprendre à calculer un masque de sous-réseau, il est tout d’abord important de clarifier quelques bases sur les réseaux informatiques:

📈 Depuis 1981, Internet fonctionne sur la base du protocole Internet (IP) : un protocole réseau qui régule les circuits de distribution des utilisateurs. Pour envoyer un paquet de données dans un réseau, l’expéditeur doit connaître l’adresse IP du destinataire.

📈 Le Net ID et le Host ID sont cachés dans l’adresse IP. Il est ainsi possible d’identifier le réseau correspondant et son hôte, par exemple un PC ou une imprimante réseau. Sur la base de ces informations, les routeurs peuvent transmettre des paquets de données aux destinataires corrects.

📈 Les ordinateurs ne comprennent que les zéros et les uns et fonctionnent donc dans un système informatique binaire. C’est pourquoi les adresses IP sont ainsi structurées. Le système IPv4 actuellement utilisé est composé de 32 bits, c’est-à-dire 32 zéros ou uns. Pour faciliter la compréhension et pour économiser de l’espace, les adresses IP sont généralement représentées en notations décimales séparées par des points ; c’est la notation décimale à point ou « oudotted decimal notation » : 192.168.88.3.

**Décimal	192	168	88	3
**Binaire	11000000	10101000	01011000	00000011

📈 Ce format fournit un nombre limité d’adresses possibles. Précisément : 232(donc 4.294.967.296) adresses peuvent être attribuées. Cela semble beaucoup, mais ces adresses sont utilisées plus vite que vous le ne pensez. Le subnetting a donc été introduit en 1985.

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





