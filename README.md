# mon-premier-projet
texte

Technologies
Internet
Introduction, objectifs et contenu
Internet ?
● Ordinateur ?
● Réseau ?
● Protocole ?
● Application ?
Survol historique
● Survol historique
http://fr.wikipedia.org/wiki/Histoire_d%27Internet
○ ARPA - Advanced Research Projects Agency (1962)
○ Email (1965)
○ Réseaux ARPANET (1969)
○ Protocole TCP/IP (1982)
○ GNU project (1983)
○ Linux (1991)
○ Premiers navigateurs: "MOSAIC" (1993), Netscape (1995)...
○ Premiers moteurs de recherche: AltaVista (1995), Yahoo (1995),
Google (1998), ...
○ Napster (1999-2001), Wikipedia (2001), Bittorrent (2001)
○ Skype (2003), Facebook (2004), Twitter (2006)...
○ Tor (2006), Netflix (2007), DropBox (2007)
○ Airbnb (2008), Github (2008), Uber (2009)
○ Bitcoin (2009), Silk Road (2011), OpenBazaar (2016)
Structures organisationnelles
de l'Internet
● Internet Engineering Task Force (IETF): les
normes de protocole Internet
● Internet Corporation for Assigned Names
and Numbers (ICANN): décide des noms de
domaine de base
● World Wide Web Consortium (W3C): les
normes de WEB
Structures organisationnelles
de l'Internet
● W3C
○ créer des standards (recommandations) pour le Web
○ développer des technologies (spécifications, lignes
directrices, logiciel et outils)
○ favoriser l'échange d'information, le commerce,
l'inspiration, la compréhension collective,...
○ Examples: HTML, XHTML, XML, RDF, CSS, ...
● L'innovation est très rapide ...
○ nouvelles technologies à chaque jour
Notions de base
● Un ordinateur et un serveur
● Un système de fichiers
● Un réseau et un sous-réseaux
● L'adresse IP d'un ordinateur et son nom du domaine
● Un service (d'un serveur) et son adresse - numéro de port
● Une adresse TCP/IP, URI/URL
Noms et adresses sur l'Internet
● Adresse IP - un numéro (entier positif) souvent représenté en forme
comme: 74.125.226.33
> whois 74.125.226.33
...
NetRange: 74.125.0.0 - 74.125.255.255
NetName: GOOGLE
Ref: http://whois.arin.net/rest/net/NET-74-125-0-0-1
OrgName: Google Inc.
Address: 1600 Amphitheatre Parkway
City: Mountain View
StateProv: CA
...
● DNS, système de noms de domaine - traduction de nom de domaine en
adresse IP (IPv6):
> host google.com
google.com has address 74.125.226.33
google.com has address 74.125.226.40
...
google.com has IPv6 address 2607:f8b0:400b:801::1007
Adresses IP et noms de
domaine
● Une Adresse IP
○ En détails :
■ codage sur 32 bits, 4 octets - IPv4
■ adresse réseau versus adresse ordinateur
■ classes d'adresse IP
■ Conventions... 127.0.0.1, 10.0.0.1, etc....
○ Comment un message d'un ordinateur arrive vers un
autre ordinateur ?
○ Comment trouver l'adresse d'un ordinateur ?
● Les noms symboliques et la résolution de noms :
○ Les serveurs DNS
Adresses «web»
● URL (Uniform Resource Locator) est une convention
d'identifier (adresser) une ressource du World Wide Web:
document HTML, image, son, ...
○ Exemples:
http://fr.wikipedia.org/
http://fr.wikipedia.org/wiki/Uniform_Resource_Locator
ftp://ftp.rfc-editor.org/in-notes/rfc2396.txt
mailto:Quidam.no-spam@example.com
http://zqktlwi4fecvo6ri.onion
● Syntaxe :
scheme://[username[:password]@](hostname|ip)[:port][/path/][?query][#fragment]
● En pratique :
scheme://[username[:password]@](hostname|ip)[:port]
Architecture client/serveur
● Serveur - un programme qui tourne 24/24 en
attendant des requêtes envoyées par des
clients et y répond.
○ Exemples de serveurs: web (http), e-mail (smtp), ...
● Caractéristiques d'un processus client :
○ il établit la connexion au serveur;
○ lorsque la connexion est acceptée par le serveur, il
communique comme le prévoit le protocole
Socket
●
"Socket" - représente une abstraction fournie par le
système d'exploitation (Windows, Unix, MacOS) d'une
connection logique entre deux programmes
(processus) qui peuvent s'exécuter sous deux machines
différentes.
○ Stream sockets
○ Datagram sockets
●
"Websocket" - permet une communication
bidirectionnelle pour les navigateurs et les serveurs
web.
Objectifs
HTML, CSS, DOM, JavaScript,
HTTP, XML, DTD, XPath, XSLT,
Sécurité sur le WEB,
PHP, Nodejs, express.js
Évaluation
L'examen de mi-session 30 %
L'examen de fin de session 30 %
Les devoirs (2 travaux * 20%) 40 %
