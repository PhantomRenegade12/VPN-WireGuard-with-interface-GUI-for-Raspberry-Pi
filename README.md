Pour que ce script fonctionne convenablement il faut ouvrir le port 51820 de notre box internet.

Le script proposé va nous permettre d'installer un serveur VPN WireGuard dans un Raspbeey Pi.
Nous allons utilisé le language Shell.

Ce script va faire plusieurs chose durant son installation :
_ IP WAN du Rasperry Pi
_ IP LAN du Rasperry Pi
_ Réunir l'IP wan & lan dans un tableau 
_ Va faire un ping sur google.fr afin de tester notre connexion à internet
_ Définit les variables de WireGuard
_ Crée un fichier conf 
_ Mettre à jour le Raspberry Pi
_ Installer Docker
_ Installer PiVPN
_ Installer WireGuard et son interface graphique
