# Net-practice
Ce projet a pour but de vous faire découvrir le réseau par des cas pratiques.

👨‍ My solution and basic explanantion on Net_Practice and networking basics:
-----------------------------------------------------------------------------

📫 Comme tout réseau informatique, Internet est une connexion entre de nombreux ordinateurs qui communiquent entre eux. Il est depuis longtemps devenu indispensable de diviser l’immense réseau en plusieurs et différents sous-réseaux. Pour comprendre ce qu’est le subnetting et pour savoir pourquoi il a été introduit et enfin apprendre à calculer un masque de sous-réseau, il est tout d’abord important de clarifier quelques bases sur les réseaux informatiques:

📈 Depuis 1981, Internet fonctionne sur la base du protocole Internet (IP) : un protocole réseau qui régule les circuits de distribution des utilisateurs. Pour envoyer un paquet de données dans un réseau, l’expéditeur doit connaître l’adresse IP du destinataire.

📈 Le Net ID et le Host ID sont cachés dans l’adresse IP. Il est ainsi possible d’identifier le réseau correspondant et son hôte, par exemple un PC ou une imprimante réseau. Sur la base de ces informations, les routeurs peuvent transmettre des paquets de données aux destinataires corrects.

📈 Les ordinateurs ne comprennent que les zéros et les uns et fonctionnent donc dans un système informatique binaire. C’est pourquoi les adresses IP sont ainsi structurées. Le système IPv4 actuellement utilisé est composé de 32 bits, c’est-à-dire 32 zéros ou uns. Pour faciliter la compréhension et pour économiser de l’espace, les adresses IP sont généralement représentées en notations décimales séparées par des points ; c’est la notation décimale à point ou « oudotted decimal notation » : 192.168.88.3.

**Décimal	192	168	88	3
**Binaire	11000000	10101000	01011000	00000011

📈 Ce format fournit un nombre limité d’adresses possibles. Précisément : 232(donc 4.294.967.296) adresses peuvent être attribuées. Cela semble beaucoup, mais ces adresses sont utilisées plus vite que vous le ne pensez. Le subnetting a donc été introduit en 1985.
