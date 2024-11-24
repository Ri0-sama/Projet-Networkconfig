# Projet-Networkconfig


LEGENDE DES COLABORATEUR DE CE PROJET
RIO-sama ------> SOSSOE Mario
Messco1  ------> MESSANVI Jean-Luc
Adjambo  ------> ADJAMBO Joachim

Pour ce projet, nous avons utiliser Cisco Packet tracer 8.2.2.0400.
Disponibe sur le site officiel de Cisco au lien : https://www.netacad.com/

La configuration des adresses ip s'est faite comme suit : 
DHCP qui donne des ip aux Pc du reseaux dans la plage : 192.168.1 a 192.168.1.4
Le Routeur 1 a une adresse 200.200.200.1/28 
Le routeur 2 a une adresse 200.200.200.2/28

******SSH*******

Nous avons cconfigurer la connexion par SSH sur le routeur 1
Interface du Routeur SSH : G0/1
Password SSH : toto


*****Config des ACL*****
Les machines du reseau en couleur Bleue ne peuvent pas acceeder aux machines des reseaux en rouge sauf celle du ip 192.168.1.11 dont l'adresse a ete fixer statiquement
Les machines du reseau en couleur Jaune peuvent acccerder aux reseaux en ccouleur Rouge


*****Mapage NAT Statique******
C'est la config qui a peermis a la machine 192.168.1.11 a accerder aux reseaux en Rouge




